# 제2편: 설치와 첫 검증

## 소요 시간

- 읽기 ~20–35분 · 실습 ~30–60분

## 전제

- [제1편](./01-what-is-ecc.md) · **Node.js** · 사용할 **harness** 결정

---

## 문서 우선순위

1. harness 공식 문서  
2. 본 저장소 [README](../README.md) / 루트 [README(영문)](../../../README.md)  
3. `plugins/`

ECC는 OS/IDE를 설치하지 않습니다.

---

## Harness 차이

| Harness | 메모 |
|---------|------|
| Claude Code | 주 참조(`.claude` 등) |
| Cursor | `.cursor`, MCP UI 상이 |
| Codex/OpenCode | `AGENTS.md`, `opencode.json` 등 |

**Hook**·일부 `/` 커맨드는 동작이 다를 수 있음. [TROUBLESHOOTING(루트)](../../../TROUBLESHOOTING.md) · [간체](../../zh-CN/TROUBLESHOOTING.md).

---

## 실험 A

저장소 **루트**에서:

```bash
node tests/run-all.js
```

선택: `node tests/lib/utils.test.js`

**성공 기준:** exit 0 — **ECC 자체 회귀 테스트**이며, 업무 프로젝트 설정과 동치 아님.

---

## 문제 해결

- [../../../TROUBLESHOOTING.md](../../../TROUBLESHOOTING.md)  
- [../../zh-CN/TROUBLESHOOTING.md](../../zh-CN/TROUBLESHOOTING.md) (간체)

---

## 더 읽기

- [`CLAUDE.md`](../../../CLAUDE.md)

---

## 다음

`/plan`, `/tdd`, `/code-review` + [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md)
