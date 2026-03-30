# Parte 6: Segurança e harnesses

## Tempo — ~35–50 min

## Pré-requisitos — [Parte 5](./05-advanced-topics-index.md)

---

## Três linhas de base

1. **Segredos** nunca no repositório, tutorial ou captura de tela.  
2. Auth, pagamento, PII — o ECC ajuda, mas **não substitui** revisão humana e aprovação.  
3. **ECC instalado ≠ auditoria de segurança feita.**

---

## Guia de segurança

[**Inglês:** the-security-guide](../../../the-security-guide.md). Sem lista CVE aqui.  
[`rules/`](../../../rules/) — camada Rule; skill **security-review** para aprofundar.

---

## MCP

[`mcp-configs/`](../../../mcp-configs/) — apenas **placeholders** em exemplos. **Privilégio mínimo.**

---

## `/security-scan`

[MAP](../../COMMAND-AGENT-MAP.md) — AgentShield; pode falhar sem dependências.

---

## Vários harnesses

Injeção de regras, hooks e MCP na UI variam — valide restrições sensíveis em **cada** ferramenta.

---

## Leitura — [security EN](../../../the-security-guide.md) · [MAP](../../COMMAND-AGENT-MAP.md) · [security-review SKILL](../../../.agents/skills/security-review/SKILL.md)

---

## Próxima — Skill mínima · Lab E
