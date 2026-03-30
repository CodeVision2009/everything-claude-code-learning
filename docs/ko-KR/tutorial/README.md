# ECC 튜토리얼 시리즈 (한국어)

**Everything Claude Code(ECC)**를 단계적으로 익히는 가이드입니다. 자세한 내용은 저장소의 권위 문서로 링크합니다.

**원문(간체):** `docs/zh-CN/tutorial/` · 동기화 **2026-03-30**  
**영문 가이드:** 저장소 루트 및 아래 링크 참조.

## 메타

| 항목 | 내용 |
|------|------|
| ECC 버전 | 1.9.0 — 루트 [`AGENTS.md`](../../../AGENTS.md) 기준 |
| 초판 날짜 | 2026-03-30 |
| 예상 시간 | 읽기 3~6시간 · 실습 3~5시간 |

## 읽는 순서

| 편 | 파일 | 주제 |
|----|------|------|
| 1 | [01-what-is-ecc.md](./01-what-is-ecc.md) | ECC란, 여섯 구성 요소 |
| 2 | [02-install-and-verify.md](./02-install-and-verify.md) | 설치 및 검증 |
| 3 | [03-commands-and-daily-workflow.md](./03-commands-and-daily-workflow.md) | 커맨드와 일상 워크플로 |
| 4 | [04-hooks-and-rules.md](./04-hooks-and-rules.md) | Hooks와 Rules |
| 5 | [05-advanced-topics-index.md](./05-advanced-topics-index.md) | 고급 주제 안내 |
| 6 | [06-security-and-harnesses.md](./06-security-and-harnesses.md) | 보안과 harness |
| 7 | [07-extending-with-skills.md](./07-extending-with-skills.md) | Skill로 확장 |
| 8 | [08-appendix-cheatsheet.md](./08-appendix-cheatsheet.md) | 부록·치트시트 |

## 실험

| 실험 | 편 | 요약 |
|------|-----|------|
| A | 2 | 루트에서 `node tests/run-all.js` |
| B | 3 | 샌드박스에서 커맨드 체인 + [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) |
| C | 4 | `hooks/` JSON 읽기 |
| D | 4 | Rule vs Skill |
| E | 7 | 로컬 Skill 작성 |

## 권위 링크

- 커맨드 ↔ Agent/Skill: [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md)  
- 프로젝트 소개: [../README.md](../README.md) · 루트 [README(영문)](../../../README.md)  
- **영문** 요약 가이드: [the-shortform-guide.md](../../../the-shortform-guide.md)  
- **영문** 장문: [the-longform-guide.md](../../../the-longform-guide.md)  
- **영문** 보안: [the-security-guide.md](../../../the-security-guide.md)  
- 간체 시나리오: [zh-CN TROUBLESHOOTING](../../zh-CN/TROUBLESHOOTING.md) (선택)  
- 문제 해결(루트): [TROUBLESHOOTING.md](../../../TROUBLESHOOTING.md)  
- Skill: [SKILL-PLACEMENT-POLICY.md](../../SKILL-PLACEMENT-POLICY.md), [SKILL-DEVELOPMENT-GUIDE.md](../../SKILL-DEVELOPMENT-GUIDE.md)  
- 기여: [../CONTRIBUTING.md](../CONTRIBUTING.md)

## 유지보수

- 대규모 릴리스 시 `AGENTS.md`와 본 페이지 날짜 갱신. 커맨드 매핑은 **COMMAND-AGENT-MAP** 단일 소스.
