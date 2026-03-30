# ECC 繁體中文教學系列

漸進式介紹 **Everything Claude Code（ECC）**。正文以連結指向倉庫權威文件，避免與簡明／長文／安全專章重複堆疊。

**正文來源與同步：** 以 [`docs/zh-CN/tutorial/`](../zh-CN/tutorial/) 簡體中文版為準；上次對齊 **2026-03-30**。深內容若僅有簡體，連結會標註（簡體中文）。

## 元資訊

| 項 | 說明 |
|----|------|
| 對應 ECC 版本 | 1.9.0（以根目錄 [`AGENTS.md`](../../../AGENTS.md) 為準） |
| 教學正文初版日期 | 2026-03-30 |
| 建議總投入 | 閱讀約 3～6 小時；動手約 3～5 小時 |

## 閱讀順序

| 篇 | 檔案 | 主題 |
|----|------|------|
| 1 | [01-what-is-ecc.md](./01-what-is-ecc.md) | ECC 是什麼、六類構件與目錄 |
| 2 | [02-install-and-verify.md](./02-install-and-verify.md) | 安裝與第一次驗證（含儲存庫測試） |
| 3 | [03-commands-and-daily-workflow.md](./03-commands-and-daily-workflow.md) | 命令與日常工作流 |
| 4 | [04-hooks-and-rules.md](./04-hooks-and-rules.md) | Hooks 與 Rules |
| 5 | [05-advanced-topics-index.md](./05-advanced-topics-index.md) | 進階主題導讀（連長文） |
| 6 | [06-security-and-harnesses.md](./06-security-and-harnesses.md) | 安全與多 harness |
| 7 | [07-extending-with-skills.md](./07-extending-with-skills.md) | 用 Skill 擴展 ECC |
| 8 | [08-appendix-cheatsheet.md](./08-appendix-cheatsheet.md) | 附錄與速查 |

## 實驗一覽

| 實驗 | 篇 | 內容摘要 |
|------|-----|----------|
| A | 2 | 在儲存庫根執行 `node tests/run-all.js` |
| B | 3 | 沙箱中跑命令鏈並對照 [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) |
| C | 4 | 閱讀 `hooks/` 下一則 Hook 設定 |
| D | 4 | 對比 Rule（或 `CLAUDE.md`）與 Skill |
| E | 7 | 依策略新增一則本機 Skill |

## 權威索引

- 命令 ↔ Agent/Skill：[COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)
- 專案說明（繁體本頁）：[../README.md](../README.md) · [簡體總覽](../../README.zh-CN.md)
- 簡明指南（簡體）：[the-shortform-guide.md](../zh-CN/the-shortform-guide.md) · [English（根目錄）](../../../the-shortform-guide.md)
- 長文： [the-longform-guide.md](../zh-CN/the-longform-guide.md) · [English](../../../the-longform-guide.md)
- 安全： [the-security-guide.md](../zh-CN/the-security-guide.md) · [English](../../../the-security-guide.md)
- 排除問題：根目錄 [`TROUBLESHOOTING.md`](../../../TROUBLESHOOTING.md)（英文）· [簡體場景](../../zh-CN/TROUBLESHOOTING.md)
- Skill：[SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md)、[SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md)
- 貢獻：[../CONTRIBUTING.md](../CONTRIBUTING.md)（繁體若有）或 [`CONTRIBUTING.md`](../../../CONTRIBUTING.md)

## 維護說明

- ECC 大版本發布後：核對 `AGENTS.md` 版本號、更新本頁日期、檢查連結。
- 命令與 Agent 對應以 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) 為準。
