# 第4章: Hooks と Rules

## 所要 — 読み 35〜50分 · 演習 30〜45分

## 前提 — [第3章](./03-commands-and-daily-workflow.md) · JSON

---

## Hook

**ライフサイクル**や**ツール呼び出し**の前後で走る自動化。手入力の `/` とは別。

| イベント | 一言 |
|----------|------|
| PreToolUse | 実行直前 |
| PostToolUse | 実行直後 |
| UserPromptSubmit | プロンプト送信時 |
| Stop | 応答終了 |
| PreCompact | 圧縮前 |
| Notification | 権限・通知 |

詳名: [**英語** Shorthand](../../../the-shortform-guide.md).

---

## ラボ C

[`hooks/`](../../../hooks/) の `.json` 一つ · **matcher** · アクション · 目的を一文で。

[`hooks/README.md`](../../../hooks/README.md)

---

## Rules

[`rules/`](../../../rules/) + [`CLAUDE.md`](../../../CLAUDE.md) — **常時**。**Skill** — **オンデマンド**。

---

## ラボ D

Rule/`CLAUDE.md` 例と Skill 例をそれぞれ 2〜4文 · **常駐 vs オンデマンド** を一文。

---

## 参照 — [Shorthand EN](../../../the-shortform-guide.md) · [`CLAUDE.md`](../../../CLAUDE.md)

---

## 次章 — [Longform EN](../../../the-longform-guide.md) へ誘導
