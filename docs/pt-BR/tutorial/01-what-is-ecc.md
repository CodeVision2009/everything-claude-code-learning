# Parte 1: O que é o ECC?

## Tempo — leitura ~25–40 min · prática ~10 min

## Pré-requisitos — clone ou navegação no repositório · noções de Claude Code / assistente de código

---

## Em uma frase

**Everything Claude Code (ECC)** empacota **Agent**, **Skill**, **Command** (`/`), **Hook**, **Rule** e **MCP** como camada de engenharia sobre harnesses de IA (Claude Code, Cursor, Codex, etc.) para **fluxos reutilizáveis**.

Escala e versão: [`AGENTS.md`](../../../AGENTS.md) na raiz.

---

## Comparado a “só conversar”

| Dimensão | Prompt único | ECC |
|----------|--------------|-----|
| Fluxo | Memória | Skill/Command fixam passos |
| Papéis | Um chat faz tudo | **Agents** especializados |
| Momento | Só quando você manda | **Hooks** em eventos de ferramenta / parada / compactação |
| Limite | Deriva fácil | **Rules** + [`CLAUDE.md`](../../../CLAUDE.md) |
| Externo | Só texto | **MCP** estruturado |

Visão rápida: [**inglês** shorthand](../../../the-shortform-guide.md).

---

## Seis componentes

| Componente | Papel | Pasta |
|------------|-------|-------|
| Skill | Fluxo sob demanda | [`skills/`](../../../skills/) — [PLACEMENT](../../SKILL-PLACEMENT-POLICY.md) |
| Command | Entrada do usuário | [`commands/`](../../../commands/) |
| Agent | Persona | [`agents/`](../../../agents/) |
| Hook | Automação de ciclo de vida | [`hooks/`](../../../hooks/) |
| Rule | Restrição permanente | [`rules/`](../../../rules/), [`CLAUDE.md`](../../../CLAUDE.md) |
| MCP | Integração externa | [`mcp-configs/`](../../../mcp-configs/) |

Também [`scripts/`](../../../scripts/), [`tests/`](../../../tests/).

---

## Quem se beneficia

- **Iniciante:** partes 1–3 — conceito, teste local, cadeia de comandos.  
- **Dia a dia:** 2, 3, 4, 6 — projeto real.  
- **Extensão:** 7–8 + [CONTRIBUTING](../CONTRIBUTING.md).

---

## Armadilhas

- Achar que sincronizar ECC = instalar Claude Code por completo.  
- Multiplicar Agents sem saber **qual comando** usar — ver [MAP](../../COMMAND-AGENT-MAP.md).

---

## Leitura adicional

- [../README.md](../README.md) · [shorthand EN](../../../the-shortform-guide.md) · [`CLAUDE.md`](../../../CLAUDE.md) · [`AGENTS.md`](../../../AGENTS.md)

---

## Próxima parte

Testes na raiz — **sanidade do código-fonte ECC**
