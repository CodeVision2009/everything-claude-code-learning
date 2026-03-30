# Bölüm 4: Hooks ve Rules

## Süre

- ~35–50 dk okuma · ~30–45 dk pratik

## Önkoşul

- [Bölüm 3](./03-commands-and-daily-workflow.md) · JSON okuyabilme.

---

## Hook nedir?

Belirli **yaşam döngüsü** veya **araç çağrısı** anlarında çalışan otomasyon. Sizin yazdığınız `/komut` ile aynı değil.

Özet tablo ([the-shortform-guide](../the-shortform-guide.md) ile uyumlu):

| Olay | Kısa örnek |
|------|------------|
| PreToolUse | Bash çalışmadan önce uyarı |
| PostToolUse | Sonrası format / log |
| UserPromptSubmit | Mesaj gönderildiğinde |
| Stop | Yanıt bittiğinde özet |
| PreCompact | Bağlam sıkıştırmadan önce |
| Notification | İzin / bildirim |

---

## Laboratuvar C

1. [`hooks/`](../../../hooks/) içinde bir `.json` açın.  
2. **matcher** bulun.  
3. **hooks** dizisindeki eylemleri bulun.  
4. Tek cümle: ne zaman, ne amaçla?

[`hooks/README.md`](../../../hooks/README.md)

---

## Rules

[`rules/`](../../../rules/) ve [`CLAUDE.md`](../../../CLAUDE.md) — **sürekli** kısıtlar.  
**Skill** — **isteğe bağlı** el kitabı.

---

## Karşılaştırma (Lab D)

- Bir **Rule** veya `CLAUDE.md` parçası — 2–4 cümle.  
- Bir **Skill** — 2–4 cümle.  
- **Kalıcı vs istek üzerine** özetini tek cümleyle yazın.

---

## Yaygın hatalar

- Hook hiç tetiklenmiyor — harness desteği, dar matcher.  
- İş kurallarını hook’a tıkmak — mantık koda ve teste.

---

## Okuma listesi

- [the-shortform-guide.md](../the-shortform-guide.md)  
- [`CLAUDE.md`](../../../CLAUDE.md) · [hooks/README](../../../hooks/README.md)  
- [TROUBLESHOOTING](../TROUBLESHOOTING.md)

---

## Sonraki

[the-longform-guide.md](../the-longform-guide.md) — doğrulama, eval, öğrenme, `/orchestrate`.
