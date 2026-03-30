# 第 4 篇：Hooks 與 Rules

## 本篇要花多久

- **閱讀**：約 35～50 分鐘  
- **動手**：約 30～45 分鐘

## 學前需備

- [第 3 篇](./03-commands-and-daily-workflow.md)。  
- 能閱讀 **JSON**；會在編輯器中開啟 `hooks/` 下檔案。

---

## Hook 是什麼

**Hook** 在特定**生命週期事件**或**工具呼叫前後**自動執行。與你主動輸入 `/xxx` **不同**。

類型與 [簡明指南（簡體）勾子一節](../../zh-CN/the-shortform-guide.md) 對齊：

| 時機 | 一句場景 |
|------|----------|
| PreToolUse | 某工具將執行前 — 風險提示。 |
| PostToolUse | 執行完畢後 — 輸出格式化、日誌。 |
| UserPromptSubmit | 你送出使用者訊息時。 |
| Stop | 本輪助手回覆結束時 — 摘要。 |
| PreCompact | 上下文壓縮前。 |
| Notification | 權限／通知（依 harness）。 |

---

## 實驗 C：閱讀一則 Hook

1. 開啟 [`hooks/`](../../../hooks/)，選一個 `.json`。  
2. 找 **matcher**。  
3. 找 **hooks** 陣列中的 **command** 等。  
4. 用**一句話**寫出這則 hook 的目的。

可選：[`hooks/README.md`](../../../hooks/README.md)

---

## Rules 與長駐約束

**Rule** 多在 [`rules/`](../../../rules/)，與 [`CLAUDE.md`](../../../CLAUDE.md) 構成長駐邊界。

- **Rule／CLAUDE.md**：偏 **Always-on**。  
- **Skill**：偏 **按需**。

---

## 實驗 D：Rule 與 Skill 對比

1. 在 [`rules/`](../../../rules/) 或 `CLAUDE.md` 舉一例：寫 2～4 句。  
2. 在 [`skills/`](../../../skills/) 舉一例：寫 2～4 句。  
3. **驗收**：一句話總結「長駐 vs 按需」。

---

## 常見坑

- Hook 不觸發：harness 是否支援、matcher 是否過窄。  
- 複雜商業規則塞進 Hook：宜簡短；重邏輯放程式與測試。

---

## 延伸閱讀

- [簡明指南（簡體）](../../zh-CN/the-shortform-guide.md)  
- [`CLAUDE.md`](../../../CLAUDE.md)、[`hooks/README.md`](../../../hooks/README.md)  
- [TROUBLESHOOTING（英文）](../../../TROUBLESHOOTING.md)

---

## 下一篇預告

深入 [長文（簡體）](../../zh-CN/the-longform-guide.md) 或 [英文長文](../../../the-longform-guide.md)；驗證／評測／編排命令只做場景索引。
