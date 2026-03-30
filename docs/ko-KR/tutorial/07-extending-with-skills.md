# 제7편: Skill로 ECC 확장

## 소요 시간

- 읽기 ~40–60분 · 실습 ~60–90분

## 전제

- [제6편](./06-security-and-harnesses.md) · [SKILL-PLACEMENT-POLICY](../../SKILL-PLACEMENT-POLICY.md)

---

## 왜 Skill?

반복 규칙을 대화 한 번에만 두지 말고 **파일**로 고정합니다.  
**Command** = 바로가기 · **Skill** = 본문 · **Agent**가 읽는 매뉴얼.

---

## 어디에?

[SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md) 단일 기준.

| 단 | 용도 |
|----|------|
| [`skills/`](../../../skills/) | ECC 큐레이션 · 메인 PR |
| `~/.claude/skills/` | 개인 |
| 팀 경로 | 프로젝트 |

**경로 틀림 = 로드 안 됨.**

---

## 최소 Skill

[SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md) — **언제**, **방법**, **예**, (선택) **한계**.

---

## 실험 E

1. 정책에 맞는 디렉터리.  
2. 예: `pre-commit-smoke.md` — 제목·언제·단계.  
3. harness 새로고침 후 로드 확인.  
4. **성공:** 실제 비밀 없음 · 구조 완전.

---

## 기여

새 Command → [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) · [CONTRIBUTING](../CONTRIBUTING.md) · `node tests/run-all.js`.

---

## 더 읽기

- [SKILL-PLACEMENT-POLICY](../../SKILL-PLACEMENT-POLICY.md) · [SKILL-DEVELOPMENT-GUIDE](../../SKILL-DEVELOPMENT-GUIDE.md) · [맵](../../COMMAND-AGENT-MAP.md)

---

## 다음

부록·유지보수
