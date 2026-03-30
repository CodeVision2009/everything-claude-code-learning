# ECC 中文教程系列

面向 **Everything Claude Code（ECC）** 的渐进式教程。正文按篇展开，细节以链接指向仓库权威文档，避免与简明/长文/安全专章重复堆叠。

## 元信息

| 项 | 说明 |
|----|------|
| 对应 ECC 版本 | 1.9.0（以根目录 [`AGENTS.md`](../../../AGENTS.md) 为准） |
| 教程正文初版日期 | 2026-03-30 |
| 建议总投入 | 阅读约 3～6 小时；动手约 3～5 小时 |

## 阅读顺序

| 篇 | 文件 | 主题 |
|----|------|------|
| 1 | [01-what-is-ecc.md](./01-what-is-ecc.md) | ECC 是什么、六类构件与目录 |
| 2 | [02-install-and-verify.md](./02-install-and-verify.md) | 安装与第一次验证（含仓库测试） |
| 3 | [03-commands-and-daily-workflow.md](./03-commands-and-daily-workflow.md) | 命令与日常工作流 |
| 4 | [04-hooks-and-rules.md](./04-hooks-and-rules.md) | Hooks 与 Rules |
| 5 | [05-advanced-topics-index.md](./05-advanced-topics-index.md) | 进阶主题导读（链长文） |
| 6 | [06-security-and-harnesses.md](./06-security-and-harnesses.md) | 安全与多 harness |
| 7 | [07-extending-with-skills.md](./07-extending-with-skills.md) | 用 Skill 扩展 ECC |
| 8 | [08-appendix-cheatsheet.md](./08-appendix-cheatsheet.md) | 附录与速查 |

## 实验一览（对应篇目）

| 实验 | 篇 | 内容摘要 |
|------|-----|----------|
| A | 2 | 在仓库根运行 `node tests/run-all.js` |
| B | 3 | 沙箱中跑命令链并对照 [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) |
| C | 4 | 阅读 `hooks/` 下一条 Hook 配置 |
| D | 4 | 对比 Rule（或 `CLAUDE.md`）与 Skill |
| E | 7 | 按策略新建一则本地 Skill |

## 权威索引

- 命令 ↔ Agent/Skill：[COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)
- 项目说明（中文）：[README.zh-CN.md](../../../README.zh-CN.md)
- 简明指南：[the-shortform-guide.md](../the-shortform-guide.md)
- 长文（Token、记忆等）：[the-longform-guide.md](../the-longform-guide.md)
- 安全：[the-security-guide.md](../the-security-guide.md)
- 排错：根目录 [`TROUBLESHOOTING.md`](../../../TROUBLESHOOTING.md) 与 [TROUBLESHOOTING.md](../TROUBLESHOOTING.md)
- Skill：[SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md)、[SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md)
- 贡献：[CONTRIBUTING.md](../../../CONTRIBUTING.md)

## 其他语言版本（与简体同步结构）

| 语言 | 入口 |
|------|------|
| 繁體中文 | [zh-TW/tutorial/README.md](../../zh-TW/tutorial/README.md) |
| 한국어 | [ko-KR/tutorial/README.md](../../ko-KR/tutorial/README.md) |
| 日本語 | [ja-JP/tutorial/README.md](../../ja-JP/tutorial/README.md) |
| Türkçe | [tr/tutorial/README.md](../../tr/tutorial/README.md) |
| Português (BR) | [pt-BR/tutorial/README.md](../../pt-BR/tutorial/README.md) |

## 维护说明

- ECC 大版本发布后：核对 `AGENTS.md` 版本号、更新本页日期、检查上述链接是否仍有效；各译本 `tutorial/README.md` 一并更新 **source synced** 日期。
- 命令与 Agent 对应关系 **以后台 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) 为准**，教程正文只保留示例与指针。
