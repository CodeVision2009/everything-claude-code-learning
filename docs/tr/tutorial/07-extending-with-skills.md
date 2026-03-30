# Bölüm 7: Skill ile ECC’yi genişletmek

## Süre

- Okuma ~40–60 dk · Pratik ~60–90 dk

## Önkoşul

- [Bölüm 6](./06-security-and-harnesses.md) · [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md)

---

## Neden Skill?

“Her zaman önce test yaz” demeyi tek diyalogda unutursunuz. **Skill** bunu dosyada sabitler.  
**Command** kısayol · **Skill** iş akışı gövdesi · **Agent** sıklıkla Skill’i okur.

---

## Nereye?

[SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md) — tek otorite.

| Seviye | Amaç |
|--------|------|
| [`skills/`](../../../skills/) | ECC kürasyonu; ana depoya PR |
| `~/.claude/skills/` | Kişisel |
| Takım yolu | Projeye özel |

**Yanlış yol = hiç yüklenmez.**

---

## Minimum Skill

[SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md): **Ne zaman**, **Nasıl**, **Örnek**, (isteğe bağlı) **Kısıt**.

---

## Laboratuvar E

1. Politikaya göre dizin seçin.  
2. Örn. **`pre-commit-smoke.md`**: başlık, ne zaman, adımlar.  
3. Harness’i yenileyin; modelin okuduğunu doğrulayın.  
4. **Kabul:** Gerçek anahtar yok; yapı tamam.

---

## Katkı

- Yeni Command → [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md)  
- Yeni Agent → [CONTRIBUTING](../CONTRIBUTING.md)

Ana depoya skill: [CONTRIBUTING](../CONTRIBUTING.md), `node tests/run-all.js`, PR açıklaması.

---

## Yaygın hatalar

- Tek skill’e her şeyi doldurmak.  
- İç URL’leri public fork’a yapıştırmak.

---

## Okuma listesi

- [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md)  
- [SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md)  
- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) · [CONTRIBUTING](../CONTRIBUTING.md)

---

## Sonraki

Ek ve bakım listesi.
