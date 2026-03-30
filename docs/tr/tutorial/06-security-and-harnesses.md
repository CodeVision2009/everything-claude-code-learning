# Bölüm 6: Güvenlik ve harness’ler

## Süre

- ~35–50 dk okuma

## Önkoşul

- [Bölüm 5](./05-advanced-topics-index.md)

---

## Üç güvenlik ilkesi

1. **Sırlar** depoya, öğreticilere veya ekrana yazılmaz.  
2. **Kimlik doğrulama, ödeme, KVKK** yolları — ECC kod üretir ama **insan onayı ve güvenlik süreci** yerine geçmez.  
3. **ECC kurulu** ≠ **güvenlik denetiminden geçti.**

---

## Güvenlik rehberi

[the-security-guide.md](../the-security-guide.md). CVE listesi burada çoğaltılmaz.  
[`rules/`](../../../rules/) güvenlik maddeleri; **security-review** skill derinlemesine.

---

## MCP

[`mcp-configs/`](../../../mcp-configs/) — örneklerde yalnızca **yer tutucu** (`YOUR_API_KEY`). **En az yetki.**

---

## `/security-scan`

[Harita](../../COMMAND-AGENT-MAP.md): AgentShield / security-scan. Bağımlılıklar eksikse başarısız veya boş çalışabilir.

---

## Harness ve güvenlik

| Konu | Not |
|------|-----|
| Kural enjeksiyonu | IDE’ler `rules/` farklı uygular — hassas yasağı her uçta test edin. |
| Hook | Harness değişince yeniden test. |
| MCP | UI + `mcp-configs/` çakışmasın. |

---

## Yaygın hatalar

- Eklenti taramasını pentest sanmak.  
- Issue’ya API anahtarı yapıştırmak.

---

## Okuma listesi

- [the-security-guide.md](../the-security-guide.md)  
- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- [security-review SKILL](../../../.agents/skills/security-review/SKILL.md)

---

## Sonraki

Minimum Skill, Lab E.
