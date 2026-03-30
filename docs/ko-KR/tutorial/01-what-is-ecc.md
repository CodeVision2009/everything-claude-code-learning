# 제1편: ECC란?

## 소요 시간

- 읽기 ~25–40분 · 실습 ~10분

## 전제

- 이 저장소를 클론하거나 둘러봄 · Claude Code 등 AI 코딩 도구에 익숙함

---

## 한 줄 요약

**Everything Claude Code(ECC)**는 **Agent·Skill·Command(`/`)·Hook·Rule·MCP** 설정을 묶어 AI 코딩 **harness**(Claude Code, Cursor, Codex 등) 위에서 **재사용 가능한 워크플로**로 일하게 해 주는 엔지니어링 레이어입니다.

버전·규모: 루트 [`AGENTS.md`](../../../AGENTS.md).

---

## “채팅만” 할 때와 비교

| 측면 | 단발 프롬프트 | ECC |
|------|---------------|-----|
| 워크플로 | 기억에 의존 | Skill/Command로 고정 |
| 역할 분담 | 한 대화에 전부 | 서로 다른 **Agent**에 위임 |
| 타이밍 | 메시지 때만 | **Hook**이 도구 전후·중단·압축 등에서 실행 |
| 경계 | 이탈 쉬움 | **Rule** + [`CLAUDE.md`](../../../CLAUDE.md) |
| 외부 도구 | 말로만 | **MCP**로 구조화 |

감 잡기: [**영문** 요약 가이드](../../../the-shortform-guide.md).

---

## 여섯 구성 요소

| 요소 | 역할 | 위치 |
|------|------|------|
| Skill | 선택적 워크플로 | [`skills/`](../../../skills/) · [SKILL-PLACEMENT-POLICY](../../SKILL-PLACEMENT-POLICY.md) |
| Command | 사용자 진입점 | [`commands/`](../../../commands/) |
| Agent | 전문 페르소나 | [`agents/`](../../../agents/) |
| Hook | 생명주기 자동화 | [`hooks/`](../../../hooks/) |
| Rule | 항상 켜진 제약 | [`rules/`](../../../rules/), [`CLAUDE.md`](../../../CLAUDE.md) |
| MCP | 외부 연동 | [`mcp-configs/`](../../../mcp-configs/) |

[`scripts/`](../../../scripts/), [`tests/`](../../../tests/) 참고.

---

## 누구에게

- **입문:** 1–3편으로 개념·테스트·커맨드 체인  
- **일상 개발:** 2,3,4,6 — 실제 프로젝트 연결  
- **확장/기여:** 7–8 + [CONTRIBUTING](../CONTRIBUTING.md)

---

## 흔한 실수

- ECC 동기화 = Claude Code 설치 완료로 착각  
- Agent만 늘리기 — 올바른 **커맨드**와 [COMMAND-AGENT-MAP](../../COMMAND-AGENT-MAP.md) 필요

---

## 더 읽기

- [../README.md](../README.md) · [**영문** Shorthand](../../../the-shortform-guide.md)  
- [`CLAUDE.md`](../../../CLAUDE.md) · [`AGENTS.md`](../../../AGENTS.md)

---

## 다음 편

루트에서 테스트 실행 — **ECC 소스 자체 검증**
