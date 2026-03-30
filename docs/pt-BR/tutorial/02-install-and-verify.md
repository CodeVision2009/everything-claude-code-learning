# Parte 2: Instalação e primeira verificação

## Tempo — leitura ~20–35 min · prática ~30–60 min

## Pré-requisitos — [Parte 1](./01-what-is-ecc.md) · **Node.js** · escolha do **harness** principal

---

## Prioridade de documentação

1. Docs oficiais do harness  
2. README deste repositório [../README.md](../README.md) / [raiz EN](../../../README.md)  
3. `plugins/`

O ECC não instala SO nem IDE.

---

## Diferenças de harness

| Harness | Nota |
|---------|------|
| Claude Code | Referência principal |
| Cursor | `.cursor`, MCP na UI pode variar |
| Codex/OpenCode | `AGENTS.md`, `opencode.json`, etc. |

**Hooks** e alguns comandos `/` podem não ser equivalentes. [TROUBLESHOOTING raiz](../../../TROUBLESHOOTING.md) · [zh-CN](../../zh-CN/TROUBLESHOOTING.md).

---

## Laboratório A

Na **raiz** do repositório:

```bash
node tests/run-all.js
```

Opcional: `node tests/lib/utils.test.js`

**Critério:** código de saída 0 — regressão **do próprio ECC**, não do seu app.

---

## Próxima — `/plan`, `/tdd`, `/code-review` e [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md)
