# Bölüm 3: Komutlar ve günlük iş akışı

## Süre

- Okuma ~30–45 dk · Pratik ~45–90 dk

## Önkoşul

- [Bölüm 2](./02-install-and-verify.md) · [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)

---

## Command, Skill, Agent

- **`/plan`**, **`/tdd`** — sizin **aktif** girişiniz.  
- **Skill** — yazılı iş akışı.  
- **Agent** — görev kimliği (ör. `planner`, `tdd-guide`).

Tek doğruluk kaynağı: **[COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)**.

---

## Önerilen ilk zincir

1. **`/plan`** — **planner** — [`plan.md`](../../../commands/plan.md): **Açık onayınız olmadan** büyük kod değişikliği yapmamalı.  
2. **`/tdd`** — **tdd-guide**  
3. Uygulama — siz + ana oturum  
4. **`/code-review`** — **code-reviewer**

Haritada `planner`, `tdd-guide`, `code-reviewer` doğrulayın.

[the-shortform-guide.md](../the-shortform-guide.md) — Skill / Command anlatımı.

---

## Laboratuvar B: Sandbox

1. Küçük bir repo veya `git init`.  
2. En az iki adım: örn. `/plan` sonra `/tdd` veya `/code-review`.  
3. Kullandığınız her komut için haritada **Primary agent(s)** yazın.  
4. **Kabul:** Cevap **tablodan**; komut “tek tık sihir” değil.

---

## Kişisel komut kartı (≤8)

| Senaryo | Komut | Agent (haritadan) |
|---------|-------|-------------------|
| Plan | `/plan` | planner |
| TDD | `/tdd` | tdd-guide |
| İnceleme | `/code-review` | code-reviewer |
| Go | `/go-review` | go-reviewer |
| Derleme | `/build-fix` | build-error-resolver |
| E2E | `/e2e` | e2e-runner |

---

## Yaygın hatalar

- `/plan` = otomatik kod sanmak.  
- Blog ile depo haritası çelişirse — **her zaman harita**.

---

## Okuma listesi

- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- [commands/plan.md](../../../commands/plan.md)

---

## Sonraki

Hook zamanlaması, Rule vs Skill.
