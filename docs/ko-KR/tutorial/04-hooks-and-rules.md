# 제4편: Hooks와 Rules

## 소요 시간

- ~35–50분 · 실습 ~30–45분

## 전제

- [제3편](./03-commands-and-daily-workflow.md) · JSON

---

## Hook

특정 **생명주기**·**도구 호출** 시점에 실행되는 자동화. 직접 치는 `/` 명령과 다릅니다.

| 이벤트 | 한 줄 |
|--------|-------|
| PreToolUse | Bash 등 실행 직전 |
| PostToolUse | 실행 직후 |
| UserPromptSubmit | 메시지 제출 시 |
| Stop | 한 라운드 응답 종료 |
| PreCompact | 컨텍스트 압축 전 |
| Notification | 권한·알림 |

자세한 이름: [**영문** Shorthand](../../../the-shortform-guide.md).

---

## 실험 C

1. [`hooks/`](../../../hooks/) 에서 `.json` 하나.  
2. **matcher** · **hooks** 배열의 동작.  
3. 한 문장으로 목적 서술.

[`hooks/README.md`](../../../hooks/README.md)

---

## Rules

[`rules/`](../../../rules/) + [`CLAUDE.md`](../../../CLAUDE.md) — **항상** 적용.  
**Skill** — **필요할 때** 펼침.

---

## 실험 D

Rule/`CLAUDE.md` 한 예 + Skill 한 예 · 각 2–4문장 · **상주 vs 온디맨드** 한 줄 요약.

---

## 흔한 실수

- Hook이 안 뜸 — harness 지원·좁은 matcher  
- 비즈니스 규칙 전부 Hook에

---

## 더 읽기

- [영문 Shorthand](../../../the-shortform-guide.md) · [`CLAUDE.md`](../../../CLAUDE.md) · [TROUBLESHOOTING](../../../TROUBLESHOOTING.md)

---

## 다음

[영문 Longform](../../../the-longform-guide.md) — 검증·eval·학습·`/orchestrate`
