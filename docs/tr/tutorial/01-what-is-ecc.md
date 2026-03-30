# Bölüm 1: ECC nedir?

## Süre

- **Okuma:** ~25–40 dk · **Pratik:** ~10 dk

## Önkoşul

- Bu depoyu klonladınız veya taradınız; Claude Code / AI agent kavramına aşinasınız.

---

## Tek cümleyle ECC

**Everything Claude Code (ECC)**, **Agent**, **Skill**, **Command** (`/` ile), **Hook**, **Rule** ve **MCP** yapılandırmasını tek pakette sunan, AI kodlama **harness**’ları (Claude Code, Cursor, Codex vb.) üzerinde çalışan mühendislik katmanıdır.

Sürüm ve ölçek: kök [`AGENTS.md`](../../../AGENTS.md).

---

## “Sadece sohbet”ten farkı

| Boyut | Düz sohbet | ECC |
|-------|------------|-----|
| İş akışı | Hafızana kalır | Skill / Command ile adımlar sabitlenir |
| Rol | Tek diyalogda her şey | Farklı **Agent**’lara delege |
| Zamanlama | Sadece mesajda | **Hook** araç öncesi/sonrası, durdurma, sıkıştırma |
| Sınır | Kayma riski | **Rule** + [`CLAUDE.md`](../../../CLAUDE.md) |

Daha akıcı anlatım: [the-shortform-guide.md](../the-shortform-guide.md).

---

## Altı bileşen

| Bileşen | Görev | Konum |
|---------|-------|-------|
| Skill | İsteğe bağlı iş akışı | [`skills/`](../../../skills/) — [SKILL-PLACEMENT-POLICY](../../SKILL-PLACEMENT-POLICY.md) |
| Command | Kullanıcı girişi | [`commands/`](../../../commands/) |
| Agent | Uzman kimlik | [`agents/`](../../../agents/) |
| Hook | Yaşam döngüsü otomasyonu | [`hooks/`](../../../hooks/) |
| Rule | Kalıcı kısıt | [`rules/`](../../../rules/), [`CLAUDE.md`](../../../CLAUDE.md) |
| MCP | Dış araçlar | [`mcp-configs/`](../../../mcp-configs/) |

Ayrıca [`scripts/`](../../../scripts/), [`tests/`](../../../tests/).

---

## Kim faydalanır?

- **Yeni başlayan:** Bölüm 1–3, altı bileşen + yerel test + komut zinciri.  
- **Günlük geliştirici:** 2–4, 6 — gerçek projeye bağlama.  
- **Genişleten / katkı:** 7–8 + [CONTRIBUTING](../CONTRIBUTING.md).

---

## Yaygın hatalar

- “ECC’yi senkronladım” = “Claude Code hazır” sanmak — platform kurulumu ayrı.  
- Her şeyi daha çok Agent ile çözmek — doğru **komut** ve [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) şart.

---

## Okuma listesi

- [../README.md](../README.md) · [README (EN)](../../../README.md)  
- [the-shortform-guide.md](../the-shortform-guide.md)  
- [`CLAUDE.md`](../../../CLAUDE.md) · [`AGENTS.md`](../../../AGENTS.md)

---

## Sonraki bölüm

Kökte testleri çalıştırarak **ECC kaynak doğrulaması**.
