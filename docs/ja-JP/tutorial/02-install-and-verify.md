# 第2章: インストールと初回検証

## 所要 — 読み 20〜35分 · 実践 30〜60分

## 前提 — [第1章](./01-what-is-ecc.md) · **Node.js** · メイン **harness**

---

## 文書の優先順位

1. 各 harness 公式  
2. [../README.md](../README.md) / [ルート README](../../../README.md)  
3. `plugins/`

ECC は OS/IDE をインストールしません。

---

## Harness 差

| Harness | メモ |
|---------|------|
| Claude Code | 主参照 |
| Cursor | `.cursor` · MCP UI が異なる場合 |
| Codex/OpenCode | `AGENTS.md` 等 |

**Hook** と `/` コマンドは同等でないことがあります。[TROUBLESHOOTING](../../../TROUBLESHOOTING.md) · [簡体](../../zh-CN/TROUBLESHOOTING.md).

---

## ラボ A

リポジトリ **ルート**:

```bash
node tests/run-all.js
```

任意: `node tests/lib/utils.test.js`

**合格:** exit 0 — ECC **自身**の回帰テスト（ビジネスプロジェクト設定とは別）。

---

## 次章

`/plan` · `/tdd` · `/code-review` と [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md)
