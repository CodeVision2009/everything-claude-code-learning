# 第 3 篇：命令與日常工作流

## 本篇要花多久

- **閱讀**：約 30～45 分鐘  
- **動手**：約 45～90 分鐘（建議獨立空目錄或玩具專案）

## 學前需備

- [第 2 篇](./02-install-and-verify.md)。  
- 開啟 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)。

---

## Command、Skill、Agent 的關係

- **斜線命令**（`/plan`、`/tdd` …）是你**主動輸入**的入口。  
- **Skill** 多是成文工作流。  
- **Agent** 是帶邊界身份的執行者。

**誰說了算？** 以 **[COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)** 為準。

---

## 推薦的「第一天」命令鏈

1. **`/plan`** — **planner**；依 [`plan.md`](../../../commands/plan.md)，**在你明確確認前不應大改程式碼**。  
2. **`/tdd`** — **tdd-guide**。  
3. **實作與本機驗證** — 仍由你與主會話完成。  
4. **`/code-review`** — **code-reviewer**。

請在對照表核對 **planner、tdd-guide、code-reviewer**（若有版本差異以地圖為準）。

「技能與命令」敘事另見 [簡明指南（簡體）](../../zh-CN/the-shortform-guide.md)。

---

## 實驗 B：沙箱專案

1. 準備**小儲存庫**（或空目錄 `git init`）。  
2. 在 harness 中至少執行兩步：例如 `/plan` 再 `/tdd`（或之後的 `/code-review`）。  
3. 開啟 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)，為用過的命令寫下 **Primary agent(s)**。  
4. **驗收**：能**查表**回答；理解命令不是一鍵完成。

---

## 「個人常用命令卡」（≤8 條）

| 場景 | 命令 | 主要 Agent（請以地圖為準） |
|------|------|---------------------------|
| 大改前先想清 | `/plan` | planner |
| 新功能／修 bug | `/tdd` | tdd-guide |
| 提交前 | `/code-review` | code-reviewer |
| Go 專案 | `/go-review` | go-reviewer |
| 建置失敗 | `/build-fix` | build-error-resolver |
| E2E | `/e2e` | e2e-runner |

---

## 常見坑

- **把 `/plan` 當自動寫程式**：須先計畫並等你確認。  
- **地圖與部落格不一致**：以倉庫 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) 為準。

---

## 延伸閱讀

- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- [簡明指南（簡體）](../../zh-CN/the-shortform-guide.md)  
- [`commands/plan.md`](../../../commands/plan.md)

---

## 下一篇預告

Hooks 何時觸發、Rules 如何長駐；讀一則 Hook JSON 並對比 Rule 與 Skill。
