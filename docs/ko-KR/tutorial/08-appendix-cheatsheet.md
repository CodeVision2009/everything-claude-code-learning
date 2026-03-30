# 제8편: 부록·치트시트

## 소요 시간

- ~15–25분

## 용어

| 구성 | 한 줄 | 디렉터리 |
|------|-------|----------|
| Skill | 선택 워크플로 | `skills/` |
| Command | `/` 명령 | `commands/` |
| Agent | 전문 역할 | `agents/` |
| Hook | 자동화 | `hooks/` |
| Rule | 상시 제약 | `rules/`, `CLAUDE.md` |
| MCP | 외부 연동 | `mcp-configs/` |

```
agents/  commands/  hooks/  mcp-configs/  rules/  skills/  scripts/  tests/
```

[`CLAUDE.md`](../../../CLAUDE.md) · [`AGENTS.md`](../../../AGENTS.md)

---

## 예시 커맨드 (전체 아님)

전체: [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md).

| 커맨드 | Agent |
|--------|-------|
| `/plan` | planner |
| `/tdd` | tdd-guide |
| `/code-review` | code-reviewer |
| `/build-fix` | build-error-resolver |
| `/orchestrate` | 다중 agent |

---

## 유지 체크리스트

- [ ] 대형 릴리스: [README](./README.md) 버전·날짜  
- [ ] 링크 점검  
- [ ] 커맨드 이름 변경 시 **먼저 맵**  
- [ ] 깊은 내용은 [longform (EN)](../../../the-longform-guide.md)

---

## 목차

| # | 링크 |
|---|------|
| 1–7 | [README](./README.md) 표 참고 |
| 8 | 본 페이지 |

---

## 더 읽기

- [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) · [CONTRIBUTING](../CONTRIBUTING.md)

**시리즈 끝.** PR 환영.
