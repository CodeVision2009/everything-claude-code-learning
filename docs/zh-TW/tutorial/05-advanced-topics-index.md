# 第 5 篇：進階主題導讀

## 本篇要花多久

- **閱讀**：約 25～40 分鐘  
- **動手**：可選

## 學前需備

- [第 4 篇](./04-hooks-and-rules.md)。  
- 會查 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)。

---

## 為什麼單獨一篇「導讀」

**Token、記憶、平行工作樹、評測** 等篇幅大，若全寫進本系列會與 [長文（簡體）](../../zh-CN/the-longform-guide.md)／[英文長文](../../../the-longform-guide.md) **重複且易過期**。

本篇三件事：何時離開教程讀長文；場景→入口表；**評測工作流 ≠ 業務單元測試**。

---

## 場景 → 推薦入口

| 你想解決… | 建議第一步 |
|-----------|------------|
| 省 token、會話記憶、平行 | 讀 [長文（簡體）](../../zh-CN/the-longform-guide.md) 或 [英文](../../../the-longform-guide.md) |
| 驗證／閘門 | 地圖中 `/checkpoint`、`/verify`、**verification-loop** |
| harness／工作流評測 | `/eval`、**eval-harness**；[`eval-harness/SKILL.md`](../../../.agents/skills/eval-harness/SKILL.md) |
| 持續學習 | `/learn` 系、**continuous-learning**（見地圖） |
| 多 Agent 編排 | `/orchestrate`；[`orchestrate.md`](../../../commands/orchestrate.md) |
| 託管迴圈 | `/loop-start`（**loop-operator**） |

**增刪以 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) 為準。**

---

## 與命令地圖的配合

勿在團隊另維護分叉大表；以地圖為**唯一事實來源**。

---

## 可選動手：乾跑

在**非關鍵分支**試 `/verify` 或 `/eval`，只觀察輸出階段。

---

## 常見坑

未讀長文就改壓縮／評測 hook；把 eval 通過當產品無 bug。

---

## 延伸閱讀

- [長文（簡體）](../../zh-CN/the-longform-guide.md)、[英文](../../../the-longform-guide.md)  
- [地圖](../../COMMAND-AGENT-MAP.md)、[`orchestrate.md`](../../../commands/orchestrate.md)

---

## 下一篇預告

三條安全底線、MCP、harness 差異。
