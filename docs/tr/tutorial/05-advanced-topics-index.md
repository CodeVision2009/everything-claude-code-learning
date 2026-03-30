# Bölüm 5: İleri konular — rehber

## Süre

- Okuma ~25–40 dk

## Önkoşul

- [Bölüm 4](./04-hooks-and-rules.md) · [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md)

---

## Neden ayrı bir bölüm?

**Token, bellek, parallel worktree, eval, sürekli öğrenme** — [the-longform-guide.md](../the-longform-guide.md) boyutunda ve sık güncellenir. Bu seride yinelenmeyi önlemek için yalnızca **yönlendirme** yapıyoruz.

**Eval iş akışı ≠ ürün birim testleri.**

---

## Senaryo → giriş

| İhtiyaç | İlk adım |
|---------|-----------|
| Token, oturum belleği, paralel | [the-longform-guide.md](../the-longform-guide.md) |
| Doğrulama / kapı | `/checkpoint`, `/verify`, **verification-loop** |
| Harness / iş akışı değerlendirme | `/eval`, **eval-harness** — [SKILL](../../../.agents/skills/eval-harness/SKILL.md) |
| Oturumdan öğrenme | `/learn` ailesi, **continuous-learning** |
| Çoklu agent sırası | `/orchestrate` — [orchestrate.md](../../../commands/orchestrate.md) |
| Yönetilen döngü | `/loop-start`, **loop-operator** |

Güncel liste: [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md).

---

## Harita ile çalışma

Ekip içinde ikinci bir komut tablosu tutmayın; **tek kaynak harita**.

---

## İsteğe bağlı: kuru çalıştırma

`/verify` veya `/eval` — kritik olmayan dalda çıktıyı gözlemleyin.

---

## Yaygın hatalar

- Longform’u okumadan sıkıştırma / eval hook’larını değiştirmek.  
- Eval geçtiği = üründe hata yok sanmak.

---

## Okuma listesi

- [the-longform-guide.md](../the-longform-guide.md)  
- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- [orchestrate.md](../../../commands/orchestrate.md)

---

## Sonraki

Güvenlik, MCP, çoklu harness.
