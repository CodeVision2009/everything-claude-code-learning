# 第6章: セキュリティと harness

## 所要 — 35〜50分

## 前提 — [第5章](./05-advanced-topics-index.md)

---

## 三本柱

1. **秘密**をリポ・チュートリアル・スクショに書かない。  
2. 認証・決済・PII — ECC は**人間の承認・セキュリティプロセス**に代わらない。  
3. **ECC 導入 ≠ 監査合格。**

---

## セキュリティ専章

[**英語** the-security-guide](../../../the-security-guide.md). CVE の列挙はしない。  
[`rules/`](../../../rules/) · **security-review** skill。

---

## MCP

[`mcp-configs/`](../../../mcp-configs/) — **プレースホルダーのみ**。**最小権限。**

---

## `/security-scan`

[MAP](../../COMMAND-AGENT-MAP.md) — 依存がなければ失敗しうる。

---

## 複数 harness

ルール注入・Hook・MCP は IDE ごとに異なる — **各端で**敏感な禁止を検証。

---

## 参照 — [security EN](../../../the-security-guide.md) · [MAP](../../COMMAND-AGENT-MAP.md) · [security-review SKILL](../../../.agents/skills/security-review/SKILL.md)

---

## 次章 — 最小 Skill · ラボ E
