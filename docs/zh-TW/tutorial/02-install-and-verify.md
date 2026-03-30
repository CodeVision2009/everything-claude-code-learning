# 第 2 篇：安裝與第一次驗證

## 本篇要花多久

- **閱讀**：約 20～35 分鐘  
- **動手**：約 30～60 分鐘（依你是否第一次設定 harness 而定）

## 學前需備

- 已讀 [第 1 篇](./01-what-is-ecc.md)。  
- 本機已安裝 **Node.js**。  
- 想清楚你的 **主 harness**：Claude Code、Cursor、OpenCode、Codex 等之一。

---

## 安裝路徑總覽（文件優先順序）

1. **各 harness 官方文件** — 安裝客戶端、登入、權限。  
2. **本儲存庫** [README.zh-CN.md](../../../README.zh-CN.md) 或 [根 README](../../../README.md) — ECC 如何接入。  
3. **`plugins/`** — 多工具鏈差異說明。

原則：**ECC 提供能力與約定，不負責替你裝作業系統或 IDE。**

---

## 依主 harness 理解差異

| Harness（範例） | 你需自行核對 |
|-----------------|-------------|
| Claude Code | 與 `.claude`、外掛市集相關說明；本系列**主參考**。 |
| Cursor | `.cursor` 規則、MCP 掛載方式可能不同。 |
| Codex／OpenCode | 可能更依賴 `AGENTS.md`、`opencode.json` 等。 |

**Hook** 與部分斜線命令在非主 harness 上可能**不等價**。請查 [根目錄 TROUBLESHOOTING](../../../TROUBLESHOOTING.md) 或 [簡體場景](../../zh-CN/TROUBLESHOOTING.md)。

---

## 實驗 A：儲存庫自檢

1. 在終端機進入本儲存庫**根目錄**。  
2. 執行：

```bash
node tests/run-all.js
```

3. （可選）例如：`node tests/lib/utils.test.js`

**驗收**：退出碼 0、測試通過。這是 **ECC 自己的迴歸測試**，不代表你的業務專案已設定好 ECC。

---

## 排除問題入口

- [**TROUBLESHOOTING.md**](../../../TROUBLESHOOTING.md)（根目錄，英文）  
- [**zh-CN 場景化**](../../zh-CN/TROUBLESHOOTING.md)（簡體）

---

## 常見坑

- **Node 未裝**：先解決環境。  
- **在子目錄跑測試**：請在根目錄執行。

---

## 延伸閱讀

- [README.zh-CN.md](../../../README.zh-CN.md)、[`CLAUDE.md`](../../../CLAUDE.md)  
- [TROUBLESHOOTING（英文）](../../../TROUBLESHOOTING.md)

---

## 下一篇預告

用 `/plan`、`/tdd`、`/code-review` 串一條最小工作流，並查 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)。
