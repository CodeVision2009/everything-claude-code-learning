# 第 8 篇：附录与速查

## 本篇要花多久

- **阅读**：约 15～25 分钟（可当辞典跳着读）

## 学前需备

- 可选：已读 [第 1～7 篇](./README.md) 中你关心的篇目。

---

## 术语速查

| 构件 | 一句话 | 典型目录 |
|------|--------|----------|
| Skill | 按需工作流与领域知识 | [`skills/`](../../../skills/) + 个人/团队路径（见放置策略） |
| Command | 斜杠命令入口 | [`commands/`](../../../commands/) |
| Agent | 可委派的专才身份 | [`agents/`](../../../agents/) |
| Hook | 生命周期/工具事件自动化 | [`hooks/`](../../../hooks/) |
| Rule | 长驻约束 | [`rules/`](../../../rules/) + [`CLAUDE.md`](../../../CLAUDE.md) |
| MCP | 外向工具配置形态 | [`mcp-configs/`](../../../mcp-configs/) |

---

## 仓库目录树（精简）

```
agents/       # 子代理定义
commands/     # 斜杠命令
hooks/        # 钩子 JSON 等
mcp-configs/  # MCP 示例与配置
rules/        # 规则 Markdown
skills/       # 策展技能
scripts/      # 钩子等用到的 Node 脚本
tests/        # 本仓库测试
```

根目录 [`CLAUDE.md`](../../../CLAUDE.md)、[`AGENTS.md`](../../../AGENTS.md) 描述**在本仓工作时**助手应遵守的全局行为与 Agent 表。

---

## 高频命令示例（非完整表）

**完整映射见 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)。**

| 命令 | 主要 Agent / 备注 |
|------|-------------------|
| `/plan` | planner |
| `/tdd` | tdd-guide |
| `/code-review` | code-reviewer |
| `/build-fix` | build-error-resolver |
| `/orchestrate` | 多 Agent 编排（见 `commands/orchestrate.md`） |

栈相关命令（Go/Python/Java…）同样在地图中 —— **不要背本表**。

---

## 系列维护清单（维护者用）

- [ ] ECC 大版本：更新 [tutorial README](./README.md) 的版本号与日期。  
- [ ] 跑链接检查或手动点开本系列「延伸阅读」。  
- [ ] 若命令重命名：**先改** [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)，再改教程示例行。  
- [ ] 不与 [the-longform-guide.md](../the-longform-guide.md) 争长文篇幅 —— 深内容留在专章。

---

## 全系列索引

| 篇 | 链接 |
|----|------|
| 1 | [ECC 是什么](./01-what-is-ecc.md) |
| 2 | [安装与验证](./02-install-and-verify.md) |
| 3 | [命令与工作流](./03-commands-and-daily-workflow.md) |
| 4 | [Hooks 与 Rules](./04-hooks-and-rules.md) |
| 5 | [进阶导读](./05-advanced-topics-index.md) |
| 6 | [安全与 harness](./06-security-and-harnesses.md) |
| 7 | [扩展 Skill](./07-extending-with-skills.md) |
| 8 | 本文 |

---

## 延伸阅读

- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- [README.zh-CN.md](../../../README.zh-CN.md)  
- [CONTRIBUTING.md](../../../CONTRIBUTING.md)  

**系列完结。** 欢迎通过 PR 改进措辞与过时代码路径。
