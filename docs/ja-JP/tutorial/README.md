# ECC チュートリアルシリーズ（日本語）

**Everything Claude Code（ECC）**の段階的ガイド。詳細はリポジトリの権威ある文書へリンクします。

**原文（簡体字）:** `docs/zh-CN/tutorial/` · 同期 **2026-03-30**  
**英語ガイド:** リポジトリルートの `the-*-guide.md` を参照（本 README のリンク参照）。

## メタ情報

| 項目 | 内容 |
|------|------|
| ECC バージョン | 1.9.0 — ルート [`AGENTS.md`](../../../AGENTS.md) |
| 初版日 | 2026-03-30 |
| 想定時間 | 読書 3〜6時間 · 実践 3〜5時間 |

## 読む順番

| 章 | ファイル | テーマ |
|----|----------|--------|
| 1 | [01-what-is-ecc.md](./01-what-is-ecc.md) | ECC とは・6コンポーネント |
| 2 | [02-install-and-verify.md](./02-install-and-verify.md) | インストールと検証 |
| 3 | [03-commands-and-daily-workflow.md](./03-commands-and-daily-workflow.md) | コマンドと日常フロー |
| 4 | [04-hooks-and-rules.md](./04-hooks-and-rules.md) | Hooks と Rules |
| 5 | [05-advanced-topics-index.md](./05-advanced-topics-index.md) | 上級トピック案内 |
| 6 | [06-security-and-harnesses.md](./06-security-and-harnesses.md) | セキュリティと harness |
| 7 | [07-extending-with-skills.md](./07-extending-with-skills.md) | Skill で拡張 |
| 8 | [08-appendix-cheatsheet.md](./08-appendix-cheatsheet.md) | 付録・早見表 |

## ラボ

| ラボ | 章 | 概要 |
|------|-----|------|
| A | 2 | ルートで `node tests/run-all.js` |
| B | 3 | サンドボックスでコマンド連鎖 + [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) |
| C | 4 | `hooks/` の JSON を読む |
| D | 4 | Rule vs Skill |
| E | 7 | ローカル Skill |

## 権威リンク

- コマンド ↔ Agent/Skill: [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- プロジェクト紹介: [../README.md](../README.md) · [README（英語・ルート）](../../../README.md)  
- **英語** 簡潔ガイド: [the-shortform-guide.md](../../../the-shortform-guide.md)  
- **英語** 長編: [the-longform-guide.md](../../../the-longform-guide.md)  
- **英語** セキュリティ: [the-security-guide.md](../../../the-security-guide.md)  
- トラブルシュート: [TROUBLESHOOTING（ルート）](../../../TROUBLESHOOTING.md) · [簡体字シナリオ](../../zh-CN/TROUBLESHOOTING.md)（任意）  
- Skill: [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md), [SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md)  
- コントリビューション: [../CONTRIBUTING.md](../CONTRIBUTING.md)

## メンテナンス

- メジャーリリース時は `AGENTS.md` と本ページの日付を更新。コマンド対応は **COMMAND-AGENT-MAP** が唯一のソース。
