# Série de tutorial ECC (português BR)

Tutorial gradual para **Everything Claude Code (ECC)**. Detalhes apontam para os documentos canônicos do repositório.

**Fonte (chinês simplificado):** `docs/zh-CN/tutorial/` · sincronizado em **2026-03-30**  
**Guias em inglês:** raiz do repositório (`the-*-guide.md`), conforme links abaixo.

## Meta

| Item | Conteúdo |
|------|----------|
| Versão ECC | 1.9.0 — ver [`AGENTS.md`](../../../AGENTS.md) na raiz |
| Data da primeira versão | 2026-03-30 |
| Tempo estimado | Leitura 3–6 h · prática 3–5 h |

## Ordem de leitura

| Parte | Arquivo | Tema |
|-------|---------|------|
| 1 | [01-what-is-ecc.md](./01-what-is-ecc.md) | O que é o ECC, seis componentes |
| 2 | [02-install-and-verify.md](./02-install-and-verify.md) | Instalação e verificação |
| 3 | [03-commands-and-daily-workflow.md](./03-commands-and-daily-workflow.md) | Comandos e fluxo diário |
| 4 | [04-hooks-and-rules.md](./04-hooks-and-rules.md) | Hooks e Rules |
| 5 | [05-advanced-topics-index.md](./05-advanced-topics-index.md) | Tópicos avançados (índice) |
| 6 | [06-security-and-harnesses.md](./06-security-and-harnesses.md) | Segurança e harnesses |
| 7 | [07-extending-with-skills.md](./07-extending-with-skills.md) | Estender com Skill |
| 8 | [08-appendix-cheatsheet.md](./08-appendix-cheatsheet.md) | Apêndice |

## Laboratórios

| Lab | Parte | Resumo |
|-----|-------|--------|
| A | 2 | `node tests/run-all.js` na raiz |
| B | 3 | Cadeia de comandos em sandbox + [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) |
| C | 4 | Ler um JSON em `hooks/` |
| D | 4 | Rule vs Skill |
| E | 7 | Skill local |

## Links canônicos

- Comando ↔ Agente/Skill: [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- Visão do projeto: [../README.md](../README.md) · [README em inglês (raiz)](../../../README.md)  
- **Inglês** guia curto: [the-shortform-guide.md](../../../the-shortform-guide.md)  
- **Inglês** longo: [the-longform-guide.md](../../../the-longform-guide.md)  
- **Inglês** segurança: [the-security-guide.md](../../../the-security-guide.md)  
- Solução de problemas: [TROUBLESHOOTING na raiz](../../../TROUBLESHOOTING.md) · [zh-CN](../../zh-CN/TROUBLESHOOTING.md) (opcional)  
- Skill: [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md), [SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md)  
- Contribuir: [../CONTRIBUTING.md](../CONTRIBUTING.md)

## Manutenção

- Após releases grandes: alinhar `AGENTS.md` e a data desta página. A **COMMAND-AGENT-MAP** é a única fonte para mapeamento de comandos.
