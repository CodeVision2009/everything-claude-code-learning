# Parte 3: Comandos e fluxo de trabalho diário

## Tempo — ~30–45 min leitura · ~45–90 min prática

## Pré-requisitos — [Parte 2](./02-install-and-verify.md) · [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)

---

## Relação Command / Skill / Agent

Comandos **`/`** são entradas **ativas**. **Skills** são procedimentos escritos. **Agents** (`planner`, `tdd-guide`, …) executam papéis.

Fonte única: **[COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)**.

---

## Cadeia sugerida no primeiro dia

1. **`/plan`** — **planner** — [`plan.md`](../../../commands/plan.md): sem **sua confirmação explícita**, não alterar código em massa.  
2. **`/tdd`** — **tdd-guide**  
3. Implementação — você + sessão principal  
4. **`/code-review`** — **code-reviewer**

Confira sempre o mapa.

[Shorthand EN](../../../the-shortform-guide.md)

---

## Laboratório B

Repositório pequeno ou `git init` · pelo menos dois passos · registrar **Primary agent(s)** no mapa · respostas devem vir da **tabela**, não da memória.

---

## Cartão pessoal (≤8 linhas)

| Cenário | Comando | Agent (mapa) |
|---------|---------|----------------|
| Planejar | `/plan` | planner |
| TDD | `/tdd` | tdd-guide |
| Revisão | `/code-review` | code-reviewer |
| Go | `/go-review` | go-reviewer |
| Build | `/build-fix` | build-error-resolver |
| E2E | `/e2e` | e2e-runner |

---

## Armadilhas — `/plan` não é autopilot · blogs vs **mapa do repo**

---

## Leitura — [MAP](../../COMMAND-AGENT-MAP.md) · [plan](../../../commands/plan.md)

---

## Próxima — Hooks e Rules
