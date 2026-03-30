# Bölüm 8: Ek ve hızlı referans

## Süre

- ~15–25 dk

## Önkoşul

- İsteğe bağlı: [Bölüm 1–7](./README.md).

---

## Terimler

| Bileşen | Özet | Dizin |
|---------|------|-------|
| Skill | İsteğe bağlı iş akışı | [`skills/`](../../../skills/) |
| Command | `/` komutu | [`commands/`](../../../commands/) |
| Agent | Uzman kimlik | [`agents/`](../../../agents/) |
| Hook | Yaşam döngüsü otomasyonu | [`hooks/`](../../../hooks/) |
| Rule | Kalıcı kısıt | [`rules/`](../../../rules/), `CLAUDE.md` |
| MCP | Dış araç yapılandırması | [`mcp-configs/`](../../../mcp-configs/) |

---

## Dizin özeti

```
agents/  commands/  hooks/  mcp-configs/  rules/  skills/  scripts/  tests/
```

[`CLAUDE.md`](../../../CLAUDE.md), [`AGENTS.md`](../../../AGENTS.md) — bu depoda çalışma kuralları.

---

## Örnek komutlar (tam tablo değil)

**Tam eşleme:** [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md).

| Komut | Agent |
|-------|-------|
| `/plan` | planner |
| `/tdd` | tdd-guide |
| `/code-review` | code-reviewer |
| `/build-fix` | build-error-resolver |
| `/orchestrate` | Çoklu agent |

---

## Bakım kontrol listesi

- [ ] Büyük sürüm: [tutorial README](./README.md) sürüm/tarih  
- [ ] Bağlantı kontrolü  
- [ ] Komut yeniden adlandırma: önce harita  
- [ ] Derin içerik [longform](../the-longform-guide.md)’da kalmalı

---

## Seri indeksi

| # | Bağlantı |
|---|----------|
| 1 | [ECC nedir](./01-what-is-ecc.md) |
| 2 | [Kurulum](./02-install-and-verify.md) |
| 3 | [Komutlar](./03-commands-and-daily-workflow.md) |
| 4 | [Hooks & Rules](./04-hooks-and-rules.md) |
| 5 | [İleri konular](./05-advanced-topics-index.md) |
| 6 | [Güvenlik](./06-security-and-harnesses.md) |
| 7 | [Skill](./07-extending-with-skills.md) |
| 8 | Bu sayfa |

---

## Okuma listesi

- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- [README (EN)](../../../README.md) · [CONTRIBUTING](../CONTRIBUTING.md)

**Seri tamamlandı.** Katkılar PR ile.
