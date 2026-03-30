# 第 8 篇：附錄與速查

## 本篇要花多久

- **閱讀**：約 15～25 分鐘

## 學前需備

- 可選：[第 1～7 篇](./README.md)。

---

## 術語速查

| 構件 | 一句話 | 目錄 |
|------|--------|------|
| Skill | 按需工作流 | [`skills/`](../../../skills/) + 放置策略 |
| Command | 斜線命令 | [`commands/`](../../../commands/) |
| Agent | 可委派專才 | [`agents/`](../../../agents/) |
| Hook | 生命週期自動化 | [`hooks/`](../../../hooks/) |
| Rule | 長駐約束 | [`rules/`](../../../rules/)、`CLAUDE.md` |
| MCP | 外向工具設定 | [`mcp-configs/`](../../../mcp-configs/) |

---

## 儲存庫目錄樹（精簡）

```
agents/  commands/  hooks/  mcp-configs/  rules/  skills/  scripts/  tests/
```

根目錄 [`CLAUDE.md`](../../../CLAUDE.md)、[`AGENTS.md`](../../../AGENTS.md) 描述在本倉工作時的全域行為。

---

## 高頻命令示例（非完整）

**完整表：** [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)。

| 命令 | 主要 Agent |
|------|------------|
| `/plan` | planner |
| `/tdd` | tdd-guide |
| `/code-review` | code-reviewer |
| `/build-fix` | build-error-resolver |
| `/orchestrate` | 多 Agent 編排 |

---

## 系列維護清單

- [ ] 大版本：更新 [tutorial README](./README.md) 版本與日期。  
- [ ] 檢查連結。  
- [ ] 命令更名：先改地圖再改教學。  
- [ ] 深內容留在 [長文（簡體）](../../zh-CN/the-longform-guide.md)／[英文](../../../the-longform-guide.md)。

---

## 全系列索引

| 篇 | 連結 |
|----|------|
| 1 | [ECC 是什麼](./01-what-is-ecc.md) |
| 2 | [安裝與驗證](./02-install-and-verify.md) |
| 3 | [命令與工作流](./03-commands-and-daily-workflow.md) |
| 4 | [Hooks 與 Rules](./04-hooks-and-rules.md) |
| 5 | [進階導讀](./05-advanced-topics-index.md) |
| 6 | [安全與 harness](./06-security-and-harnesses.md) |
| 7 | [擴展 Skill](./07-extending-with-skills.md) |
| 8 | 本文 |

---

## 延伸閱讀

- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- [README.zh-CN.md](../../../README.zh-CN.md)、[CONTRIBUTING](../../../CONTRIBUTING.md)

**系列完結。** 歡迎 PR。

</think>


<｜tool▁calls▁begin｜><｜tool▁call▁begin｜>
StrReplace