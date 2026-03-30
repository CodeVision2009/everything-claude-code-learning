# 제3편: 커맨드와 일상 워크플로

## 소요 시간

- 읽기 ~30–45분 · 실습 ~45–90분

## 전제

- [제2편](./02-install-and-verify.md) · [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)

---

## Command, Skill, Agent

- **`/plan`**, **`/tdd`** 등은 **당신이 누르는** 진입점입니다.  
- **Skill** — 프로시저 문서.  
- **Agent** — `planner`, `tdd-guide` 같은 역할.

단일 출처: **[COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)**.

---

## 추천 첫 체인

1. **`/plan`** — **planner** — [`plan.md`](../../../commands/plan.md): **명시적 확인 전** 대규모 코드 변경 금지.  
2. **`/tdd`** — **tdd-guide**  
3. 구현 — 본인 + 메인 세션  
4. **`/code-review`** — **code-reviewer**

맵에서 직접 확인하세요.

Skill/Command 감: [**영문**](../../../the-shortform-guide.md).

---

## 실험 B

1. 작은 저장소 또는 `git init`.  
2. 최소 두 단계: 예) `/plan` 후 `/tdd` 또는 `/code-review`.  
3. [맵](../../COMMAND-AGENT-MAP.md)에 **Primary agent(s)** 기록.  
4. **성공:** 표에서 답을 찾음 · 커맨드는 만능 버튼이 아님.

---

## 개인 커맨드 카드 (≤8)

| 시나리오 | 커맨드 | Agent(맵 확인) |
|----------|--------|----------------|
| 계획 | `/plan` | planner |
| TDD | `/tdd` | tdd-guide |
| 리뷰 | `/code-review` | code-reviewer |
| Go | `/go-review` | go-reviewer |
| 빌드 | `/build-fix` | build-error-resolver |
| E2E | `/e2e` | e2e-runner |

---

## 흔한 실수

- `/plan` = 자동 코딩  
- 블로그 vs 저장소 맵 — **항상 맵**

---

## 더 읽기

- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) · [plan.md](../../../commands/plan.md)

---

## 다음

Hook, Rule vs Skill
