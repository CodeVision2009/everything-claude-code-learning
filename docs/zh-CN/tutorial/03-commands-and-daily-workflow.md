# 第 3 篇：命令与日常工作流

## 本篇要花多久

- **阅读**：约 30～45 分钟  
- **动手**：约 45～90 分钟（建议单独空目录或玩具项目）

## 学前需备

- [第 2 篇](./02-install-and-verify.md) 中的环境已可用或你已知排错路径。  
- 打开并收藏 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) — 本系列**唯一权威的命令 ↔ Agent/Skill 对照表**；正文只举少量例子，**不复制全表**。

---

## Command、Skill、Agent 的关系

- **斜杠命令**（`/plan`、`/tdd` …）是你**主动输入**的入口；其背后会触发某条提示模板、脚本说明或委派某个 **Agent**。  
- **Skill** 多是「怎么做」的成文工作流：可被命令引用，也可在对话中被技能检索拉起。  
- **Agent** 是带边界身份的执行者（如专门做规划的 planner、专门推 TDD 的 tdd-guide）。

**谁说了算？** 以仓库内的 **[COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)** 为准。升级 ECC 后若映射有变，优先信地图，不要死记本页示例。

---

## 推荐的「第一天」命令链

下面是一条对**功能开发**常见的心智路径（示意，非唯一真理）：

1. **`/plan`** — 请 **planner** 帮你把需求拆成阶段、依赖与风险；按 [plan 命令说明](../../../commands/plan.md) 的约定，**在得到你明确确认前不应直接大改代码**。  
2. **`/tdd`** — 请 **tdd-guide** 走「测试先行 → 再实现」的节奏（具体以 harness 中实际执行为准）。  
3. **实现与本地验证** — 仍由你与主会话完成；Agent 是助手不是自动机器人。  
4. **`/code-review`** — 请 **code-reviewer** 做质量与可维护性方面的第二意见。

请现在在地图中自行核对：上述三条命令的主 Agent 是否分别为 **planner、tdd-guide、code-reviewer**（若你的 ECC 版本有调整，以地图为准）。

更轻松的「技能与命令」叙事见 [简明指南](../the-shortform-guide.md)。

---

## 实验 B：沙箱项目

1. 准备一个**小仓库**（或空目录 init git），避免误伤生产代码。  
2. 在你的 harness 中**至少执行两步**：例如先 `/plan`（描述一个极小的功能），再 `/tdd`（或实现后的 `/code-review`）。若环境暂不支持某条命令，在笔记中诚实记录「受限原因」。  
3. 打开 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)，为**你用过的每条命令**写下对应表中的 **Primary agent(s)** 名称。  
4. **验收**：你能**查表得出**答案，而不是凭印象猜；并理解 **命令不是「一键完成」**，仍需你的判断与上下文。

---

## 打造你的「个人常用命令卡」（≤8 条）

建议从你的栈出发增加 1～2 条，其余留给通用项。示例（**请用地图替换/补充真实映射**）：

| 我的场景 | 命令 | 地图里对应的主要 Agent |
|----------|------|------------------------|
| 大改前先想清 | `/plan` | planner |
| 新功能 / 修 bug 推测试先行 | `/tdd` | tdd-guide |
| 合并或提交前过一遍 | `/code-review` | code-reviewer |
| Go 项目额外评审 | `/go-review` | go-reviewer |
| 构建挂了 | `/build-fix` | build-error-resolver |
| E2E | `/e2e` | e2e-runner |

把表裁剪到 **不超过 8 行**，贴在笔记或团队 Wiki；每月对照 release 与地图看是否需更新。

---

## 常见坑

- **把 `/plan` 当成自动写代码**：plan 的设计是 **先计划、等你确认** 再动代码；见 `commands/plan.md`。  
- **地图与博客文章不一致**：永远以仓库里的 **[COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)** 为准。

---

## 延伸阅读

- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- [the-shortform-guide.md](../the-shortform-guide.md)  
- [`commands/plan.md`](../../../commands/plan.md)  

---

## 下一篇预告

Hooks 在何时触发、Rules 如何长驻；动手读一条 Hook JSON，并对比 Rule 与 Skill。
