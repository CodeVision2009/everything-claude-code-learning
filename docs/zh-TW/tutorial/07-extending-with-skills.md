# 第 7 篇：用 Skill 擴展 ECC

## 本篇要花多久

- **閱讀**：約 40～60 分鐘  
- **動手**：約 60～90 分鐘

## 學前需備

- [第 6 篇](./06-security-and-harnesses.md)。  
- 瀏覽 [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md)。

---

## 為什麼寫 Skill

**Skill** 把**何時用、分幾步**固化成檔，讓你、同事與 **Agent** 對齊。  
**Command** 是捷徑入口；**Skill** 是可被多處引用的工作流本體；**Agent** 常讀 Skill 當手冊。

---

## 放在哪裡

以 [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md) 為準。

| 層級 | 用途 |
|------|------|
| 上游 [`skills/`](../../../skills/) | ECC 策展；進主倉走 PR。 |
| 使用者目錄（如 `~/.claude/skills/`） | 個人習慣。 |
| 團隊約定路徑 | 與專案綁定。 |

**路徑錯 = 永遠載入不到**。

---

## 最小 Skill

對齊 [SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md)：**何時使用**、**如何做**、**示例**、（可選）**反例**。

---

## 實驗 E：本機 Skill

1. 依放置策略選目錄。  
2. 新建例如 **`pre-commit-smoke.md`**：標題、何時使用、可複製步驟。  
3. 刷新 harness，確認模型能讀到。  
4. **驗收**：無真實金鑰；結構完整。

---

## 貢獻者：Skill／Command／Agent

新 Command 須同步 [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md)。新 Agent 見 [CONTRIBUTING](../../../CONTRIBUTING.md)。

---

## 貢獻上游

1. [CONTRIBUTING](../../../CONTRIBUTING.md)  
2. `node tests/run-all.js`（或子集）  
3. PR 說明場景與是否更新地圖

---

## 常見坑

一份 skill 包一切；內部 URL 貼到公開 fork。

---

## 延伸閱讀

- [Skill 放置](../../SKILL-PLACEMENT-POLICY.md)、[開發指南](../../SKILL-DEVELOPMENT-GUIDE.md)  
- [地圖](../../COMMAND-AGENT-MAP.md)、[CONTRIBUTING](../../../CONTRIBUTING.md)

---

## 下一篇預告

術語表、目錄樹、維護清單。
