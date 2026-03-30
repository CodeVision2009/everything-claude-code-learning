# Bölüm 2: Kurulum ve ilk doğrulama

## Süre

- Okuma ~20–35 dk · Pratik ~30–60 dk

## Önkoşul

- [Bölüm 1](./01-what-is-ecc.md) · **Node.js** · Ana **harness**’inizi seçin.

---

## Belge önceliği

1. Resmi harness dokümantasyonu  
2. Bu depo [README (EN)](../../../README.md) / diğer locale README  
3. `plugins/` alt dizinleri

ECC, OS veya IDE kurmaz.

---

## Harness farkları

| Harness | Not |
|---------|-----|
| Claude Code | Genelde ana referans (`.claude`, market) |
| Cursor | `.cursor`, MCP UI farklı olabilir |
| Codex / OpenCode | `AGENTS.md`, `opencode.json` vb. |

**Hook** ve bazı `/` komutları birebir olmayabilir. Bakınız [../TROUBLESHOOTING.md](../TROUBLESHOOTING.md) ve [kök](../../../TROUBLESHOOTING.md).

---

## Laboratuvar A: Depo testleri

Depo **kökünde**:

```bash
node tests/run-all.js
```

İsteğe bağlı: `node tests/lib/utils.test.js`

**Kabul:** Çıkış kodu 0. Bu, **ECC’nin kendi regresyon testleri**dir; ürün projenizin ECC ile yapılandırıldığı anlamına gelmez.

---

## Sorun giderme

- [../TROUBLESHOOTING.md](../TROUBLESHOOTING.md) (TR)  
- [Kök TROUBLESHOOTING](../../../TROUBLESHOOTING.md)

---

## Yaygın hatalar

- Node yok veya yanlış dizin.  
- Tüm hook’ların Cursor’da aynen çalışacağını varsaymak.

---

## Okuma listesi

- [`CLAUDE.md`](../../../CLAUDE.md) (Running Tests)  
- [TROUBLESHOOTING](../TROUBLESHOOTING.md)

---

## Sonraki

`/plan`, `/tdd`, `/code-review` ve [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md).
