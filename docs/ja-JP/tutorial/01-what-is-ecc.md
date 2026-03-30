# 第1章: ECC とは

## 所要時間 — 読み 25〜40分 · 演習 ~10分

## 前提 — リポジトリ閲覧済み · Claude Code 等の前提知識

---

## 一文で

**Everything Claude Code（ECC）**は **Agent・Skill・Command（`/`）・Hook・Rule・MCP** を束ね、Claude Code / Cursor / Codex などの **harness** 上で再利用可能なフローを提供する設定層です。

規模はルート [`AGENTS.md`](../../../AGENTS.md) を参照。

---

## 「チャットだけ」との違い

| 軸 | 単発プロンプト | ECC |
|----|----------------|-----|
| フロー | 記憶頼み | Skill/Command で固定 |
| 分業 | 一つの会話ですべて | **Agent** に委譲 |
| タイミング | メッセージ時のみ | **Hook** がツール前後・停止・圧縮等で動く |
| 境界 | ブレやすい | **Rule** + [`CLAUDE.md`](../../../CLAUDE.md) |
| 外部 | 口頭のみ | **MCP** で構造化 |

体感: [**英語** Shorthand](../../../the-shortform-guide.md).

---

## 6つの構成要素

| 要素 | 役割 | 場所 |
|------|------|------|
| Skill | オンデマンド手順 | [`skills/`](../../../skills/) · [PLACEMENT](../../SKILL-PLACEMENT-POLICY.md) |
| Command | ユーザー入口 | [`commands/`](../../../commands/) |
| Agent | 専門役 | [`agents/`](../../../agents/) |
| Hook | ライフサイクル自動化 | [`hooks/`](../../../hooks/) |
| Rule | 常時制約 | [`rules/`](../../../rules/) · [`CLAUDE.md`](../../../CLAUDE.md) |
| MCP | 外部連携 | [`mcp-configs/`](../../../mcp-configs/) |

[`scripts/`](../../../scripts/) · [`tests/`](../../../tests/)

---

## 読者

- **初心者:** 1〜3章で用語・テスト・コマンド連鎖  
- **日常:** 2,3,4,6 で実プロ接続  
- **拡張:** 7〜8 + [CONTRIBUTING](../CONTRIBUTING.md)

---

## 落とし穴

- ECC 同期＝Claude Code 完了と誤解  
- Agent 乱発 — 正しい **コマンド** と [MAP](../../COMMAND-AGENT-MAP.md) が必要

---

## 参照

- [../README.md](../README.md) · [Shorthand EN](../../../the-shortform-guide.md) · [`CLAUDE.md`](../../../CLAUDE.md) · [`AGENTS.md`](../../../AGENTS.md)

---

## 次章

ルートでテスト — **ECC ソースの健全性**
