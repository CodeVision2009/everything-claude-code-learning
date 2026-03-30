# ECC Öğretici Serisi (Türkçe)

**Everything Claude Code (ECC)** için kademeli öğretici. Ayrıntılar bağlantılarla depodaki otoriter belgelere bırakılır; Shorthand/Longform/Security rehberleriyle tekrar önlenir.

**Kaynak:** `docs/zh-CN/tutorial/` (Çince); senkron **2026-03-30**.

## Meta

| Öğe | Açıklama |
|-----|----------|
| ECC sürümü | 1.9.0 — kök [`AGENTS.md`](../../../AGENTS.md) |
| İlk yayın tarihi | 2026-03-30 |
| Süre (tahmini) | Okuma 3–6 saat; uygulama 3–5 saat |

## Okuma sırası

| Bölüm | Dosya | Konu |
|-------|-------|------|
| 1 | [01-what-is-ecc.md](./01-what-is-ecc.md) | ECC nedir, altı bileşen |
| 2 | [02-install-and-verify.md](./02-install-and-verify.md) | Kurulum ve doğrulama |
| 3 | [03-commands-and-daily-workflow.md](./03-commands-and-daily-workflow.md) | Komutlar ve günlük akış |
| 4 | [04-hooks-and-rules.md](./04-hooks-and-rules.md) | Hooks ve Rules |
| 5 | [05-advanced-topics-index.md](./05-advanced-topics-index.md) | İleri konular (longform’a işaret) |
| 6 | [06-security-and-harnesses.md](./06-security-and-harnesses.md) | Güvenlik ve harness’ler |
| 7 | [07-extending-with-skills.md](./07-extending-with-skills.md) | Skill ile genişletme |
| 8 | [08-appendix-cheatsheet.md](./08-appendix-cheatsheet.md) | Ek ve hızlı referans |

## Laboratuvarlar

| Lab | Bölüm | Özet |
|-----|-------|------|
| A | 2 | `node tests/run-all.js` kökte |
| B | 3 | Sandbox’ta komut zinciri + [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) |
| C | 4 | `hooks/` altında bir JSON oku |
| D | 4 | Rule vs Skill |
| E | 7 | Yerel Skill oluştur |

## Otoriter bağlantılar

- Komut ↔ Agent/Skill: [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)
- Proje özeti: [../README.md](../README.md) (bu locale)
- Kısa rehber: [the-shortform-guide.md](../the-shortform-guide.md)
- Uzun rehber: [the-longform-guide.md](../the-longform-guide.md)
- Güvenlik: [the-security-guide.md](../the-security-guide.md)
- Sorun giderme: [../TROUBLESHOOTING.md](../TROUBLESHOOTING.md) · kök [TROUBLESHOOTING.md](../../../TROUBLESHOOTING.md)
- Skill: [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md), [SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md)
- Katkı: [../CONTRIBUTING.md](../CONTRIBUTING.md)

## Bakım

- Büyük sürümlerde `AGENTS.md` ve bu sayfadaki tarihi güncelleyin. Komut eşlemesi için tek kaynak: **COMMAND-AGENT-MAP**.
