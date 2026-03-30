# 제5편: 고급 주제 안내

## 소요 시간

- ~25–40분

## 전제

- [제4편](./04-hooks-and-rules.md) · [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md)

---

## 왜 별도 편인가

토큰·메모리·병렬 worktree·eval 등은 [**영문** Longform](../../../the-longform-guide.md) 규모이고 자주 바뀝니다. 여기서는 **색인**만 합니다.

**Eval 워크플로 ≠ 제품 단위 테스트.**

---

## 시나리오 → 입구

| 목표 | 첫 단계 |
|------|---------|
| 토큰·세션·병렬 | [longform (EN)](../../../the-longform-guide.md) |
| 게이트 검증 | `/checkpoint`, `/verify`, **verification-loop** |
| harness 평가 | `/eval`, **eval-harness** · [SKILL](../../../.agents/skills/eval-harness/SKILL.md) |
| 학습 습관 | `/learn`, **continuous-learning** |
| 다중 agent | `/orchestrate` · [orchestrate.md](../../../commands/orchestrate.md) |
| 루프 | `/loop-start`, **loop-operator** |

최신: [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md).

---

## 맵 활용

팀만의 대형 커맨드 표를 만들지 말고 **공식 맵**만 유지.

---

## 선택: 드라이런

`/verify` 또는 `/eval` — 중요하지 않은 브랜치에서 출력만 관찰.

---

## 더 읽기

- [longform (EN)](../../../the-longform-guide.md) · [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) · [orchestrate](../../../commands/orchestrate.md)

---

## 다음

보안·MCP·harness
