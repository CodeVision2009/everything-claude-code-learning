# 第3章: コマンドと日常ワークフロー

## 所要 — 読み 30〜45分 · 演習 45〜90分

## 前提 — [第2章](./02-install-and-verify.md) · [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md)

---

## Command / Skill / Agent

**`/` コマンド**は能動的入力。**Skill** は手順文書。**Agent** は `planner` 等の役。

唯一の正: **[COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)**。

---

## 推奨チェーン

1. **`/plan`** — **planner** — [`plan.md`](../../../commands/plan.md): **明示承認なしに**大規模変更しない。  
2. **`/tdd`** — **tdd-guide**  
3. 実装 — あなた + メインセッション  
4. **`/code-review`** — **code-reviewer**

[Shorthand EN](../../../the-shortform-guide.md)

---

## ラボ B

小リポまたは `git init` · 最低2ステップ（例 `/plan` → `/tdd`）· マップに **Primary agent(s)** を記す · 答えは **表から**。

---

## 個人カード（≤8）

| 場面 | コマンド | Agent（マップ確認） |
|------|----------|---------------------|
| 計画 | `/plan` | planner |
| TDD | `/tdd` | tdd-guide |
| レビュー | `/code-review` | code-reviewer |
| Go | `/go-review` | go-reviewer |
| ビルド | `/build-fix` | build-error-resolver |
| E2E | `/e2e` | e2e-runner |

---

## 落とし穴

`/plan`＝自動コーディングではない · ブログより **マップ**

---

## 参照 — [MAP](../../COMMAND-AGENT-MAP.md) · [plan](../../../commands/plan.md)

---

## 次章 — Hook · Rule vs Skill
