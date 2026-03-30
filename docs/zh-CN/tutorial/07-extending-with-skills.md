# 第 7 篇：用 Skill 扩展 ECC

## 本篇要花多久

- **阅读**：约 40～60 分钟  
- **动手**：约 60～90 分钟

## 学前需备

- [第 6 篇](./06-security-and-harnesses.md)。  
- 浏览过 [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md) 的目录约定摘要（本篇会再收紧为可执行 checklist）。

---

## 为什么要写 Skill

单次对话里口授「我们团队永远先写测试」会在三周后遗忘。**Skill** 把 **何时采用、分几步、有哪些反例** 固化成文件，让 **你、同事与 Agent** 在同一套剧本上对齐。

与 **Command** 的差别可以记：**Command 是快捷入口**，**Skill 是成文的、可被多处引用的工作流本体**。与 **Agent** 的差别：**Agent 是执行身份**，**Skill 常是它读的手册**。

---

## 放在哪里（权威来源）

**一切以 [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md) 为准。** 概念上你会遇到三层：

| 层级 | 典型用途 |
|------|----------|
| 上游 [`skills/`](../../../skills/) | ECC 策展的通用技能；想进主仓走 PR。 |
| 用户目录（如 `~/.claude/skills/`） | 个人习惯、不与项目绑定时。 |
| 团队项目内约定路径 | 与仓库绑定的规范；路径由团队文档声明，并对照放置策略核对。 |

**路径错 = 永远不会被加载**。写完 skill 后务必在真实 harness 里开一局短对话验证「能被检索或引用」。

---

## 最小 Skill 长什么样

与 [SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md) 对齐时，新手可只保证四块：

1. **何时使用** —— 两到三个触发场景。  
2. **如何做** —— numbered 步骤，每步一句话以上。  
3. **示例** —— 一个最短正例（可伪代码/命令）。  
4. **反例或边界** —— 可选，但团队 skill 强烈建议有。

复杂 skill 可做成目录 + `SKILL.md`；**不要**把整本设计文档粘进一个文件——改链到内部 Wiki。

---

## 实验 E：新增一则本地 Skill

1. 根据 [放置策略](../../SKILL-PLACEMENT-POLICY.md) 选定目录（个人或团队）。  
2. 新建 Markdown（或按指南要求命名），例如 **`pre-commit-smoke.md`**，内容包含：  
   - 标题  
   - 「何时使用」：提交前自测三步（安装依赖 / 单测 / 类型检查 —— 按你栈改）  
   - 「步骤」：可复制清单  
3. 重启或刷新 harness（按工具要求），发一条消息明确 **@该 skill 名称** 或依赖自动检索，确认模型**能读到**文件摘要或小标题。  
4. **验收**：路径合规；结构含「何时 / 步骤 / 示例」；无 **真实密钥**；能被当前环境发现。

---

## Skill、Command、Agent 的协作（给贡献者）

- **新 Command** 若固定绑定某 workflow，应在实现与 [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) 里**同步登记**。  
- **新 Agent** 属于更大块变更：阅读 [CONTRIBUTING.md](../../../CONTRIBUTING.md) 与现有 agent 的 frontmatter 惯例。

---

## 贡献上游 ECC

如果你希望 skill **进入本仓库**：

1. 读 [CONTRIBUTING.md](../../../CONTRIBUTING.md) 的格式与提交约定。  
2. 本地跑通至少与改动相关的测试（`node tests/run-all.js` 或子集）。  
3. PR 描述写清：适用场景、与现有 skill 是否重复、是否需要地图更新。

---

## 常见坑

- **一份 skill 包一切** —— 难以维护；按场景拆。  
- **复制粘贴内部 URL 到公开 fork** —— 泄密；区分公开与私有仓。

---

## 延伸阅读

- [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md)  
- [SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md)  
- [CONTRIBUTING.md](../../../CONTRIBUTING.md)  
- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  

---

## 下一篇预告

术语表、精简目录树、示例命令行与 **系列维护清单**。
