# 第 6 篇：安全與多 harness

## 本篇要花多久

- **閱讀**：約 35～50 分鐘  
- **動手**：可選（只讀 `mcp-configs/` 範例，**勿**提交真實金鑰）

## 學前需備

- [第 5 篇](./05-advanced-topics-index.md)。

---

## 三條安全底線

1. **金鑰**：永不寫入儲存庫、教學或截圖；用環境變數或祕密管理。  
2. **敏感變更仍須人工 gates**：認證、付款、個資等，ECC **不能替代**你的安全審查。  
3. **「裝了 ECC」≠「已通過安全稽核」**。

---

## 安全專章怎麼讀

[安全指南（簡體）](../../zh-CN/the-security-guide.md) 或 [英文](../../../the-security-guide.md)。不在此複製 CVE。  
[`rules/`](../../../rules/) 安全條目為 **Rule 層**；**security-review** skill 為按需深潛。

---

## MCP 與外向資料

[`mcp-configs/`](../../../mcp-configs/) — 教學只用**占位符**（如 `YOUR_API_KEY`）。遵**最小權限**。

---

## `/security-scan`（若啟用）

見 [地圖](../../COMMAND-AGENT-MAP.md)：`/security-scan`、AgentShield。依賴與環境須就緒。

---

## 多 harness（與安全相關）

| 注意 | 說明 |
|------|------|
| 規則注入 | 各 IDE 注入 `rules/` 方式可能不同；敏感限制須逐端驗證。 |
| Hook | 遷移 harness 須重測。 |
| MCP | UI 設定與 `mcp-configs/` 可能並存；避免矛盾權限。 |

---

## 常見坑

把外掛掃描當滲透替代品；在 Issue 貼 API Key。

---

## 延伸閱讀

- [安全（簡體）](../../zh-CN/the-security-guide.md)、[英文](../../../the-security-guide.md)  
- [地圖](../../COMMAND-AGENT-MAP.md)  
- [`security-review/SKILL.md`](../../../.agents/skills/security-review/SKILL.md)

---

## 下一篇預告

最小 Skill、實驗 E。
