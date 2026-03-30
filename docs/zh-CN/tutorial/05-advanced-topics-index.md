# 第 5 篇：进阶主题导读

## 本篇要花多久

- **阅读**：约 25～40 分钟  
- **动手**：可选（浏览一条命令的帮助输出或 dry-run）

## 学前需备

- [第 4 篇](./04-hooks-and-rules.md)。  
- 会查 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) 的表格结构。

---

## 为什么需要单独一篇「导读」

**Token 优化、会话记忆、并行工作树、评测与持续学习** 等主题篇幅大、与 harness 版本耦合紧。若全部写进本系列，会与 [the-longform-guide.md](../the-longform-guide.md) **重复且更快过期**。

本篇只做三件事：

1. 告诉你 **什么时候该离开教程、去读长文**；  
2. 用一张 **场景 → 入口** 表指路到命令与技能名（细节以地图与 skill 正文为准）；  
3. 强调 **评测类工作流 ≠ 业务单元测试** —— 前者评的是「AI 干活方式是否达标」，后者评的是你的领域逻辑。

---

## 场景 → 推荐入口

下列命令与技能名来自当前仓库习惯；**增删以 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) 为准**。

| 你想解决… | 建议第一步 |
|-----------|------------|
| 理解如何省 token、怎样做会话级记忆与并行 | 读 [the-longform-guide.md](../the-longform-guide.md) 对应章节 |
| 验证 / 闸门式检查 | 地图中的 `/checkpoint`、`/verify` 与 **verification-loop** 技能 |
| 对 harness 或工作流做正式化评测 | `/eval` 与 **eval-harness**；实现细节见 [`../../../.agents/skills/eval-harness/SKILL.md`](../../../.agents/skills/eval-harness/SKILL.md) |
| 从会话里沉淀可复用习惯（Instinct 等） | `/learn` 系列命令与 **continuous-learning** / **continuous-learning-v2**（见地图） |
| 多 Agent 顺序编排 | `/orchestrate`；长流程与工作树脚本见 `commands/orchestrate.md` |
| 托管的循环执行 | `/loop-start`（**loop-operator**），需配置停止条件与安全档 |

读完上表仍不确定时：**先打开长文目录**，再回来用地图查「这条命令到底绑了哪个 skill」。

---

## 与命令地图的配合方式

- **不要**在团队内部另维护一张「命令 ↔ Agent」大表与上游分叉。  
- **要**把 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) 当作 **唯一事实来源**；本系列只教你怎么 **用它做决策**。

---

## 可选动手：干跑

若你的环境允许，任选 **`/verify` 或 `/eval`** 在一次**非关键分支**上执行，只观察：输出了哪些阶段、是否引用某个 skill 文件。**不必**强求通过；目的是熟悉「评测类命令长什么样」。

---

## 常见坑

- **没读长文就更改压缩或评测钩子** —— 容易与现有 profile（如 `ECC_HOOK_PROFILE`）预期冲突；先读原文再改。  
- **把 eval harness 的通过当成产品无 bug** —— 业务测试仍要由项目测试金字塔覆盖。

---

## 延伸阅读

- [the-longform-guide.md](../the-longform-guide.md)  
- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- [`commands/orchestrate.md`](../../../commands/orchestrate.md)  

---

## 下一篇预告

三条安全底线、MCP 形态与多 harness 差异；明确 **工具与安全流程不能互相替代**。
