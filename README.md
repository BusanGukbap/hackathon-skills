# Hackathon Skills

기존에 사용하던 스킬 중 짧은 개발 과제에 유용한 네 가지를 모았습니다. 각 스킬은 `skills/<이름>/SKILL.md`에 있습니다.

| 스킬 | 용도 |
| --- | --- |
| `prompt-contracts` | 목표, 제약, 출력 형식, 실패 조건 정리 |
| `systematic-debugging` | 오류 재현, 원인 추적, 수정과 검증 |
| `test-driven-development` | 핵심 동작을 테스트로 검증 |
| `verification-before-completion` | 완료 및 제출 전 실행 결과 확인 |

## 사용법

허용된 개발 환경에서 이 저장소를 내려받은 뒤, Codex에 필요한 스킬의 `SKILL.md` 파일을 읽고 적용하라고 요청합니다. 예: `skills/systematic-debugging/SKILL.md를 읽고 오류 원인을 조사해줘`. 에이전트가 저장소 내 `skills/`를 자동 검색하는지는 실행 환경에 따라 다릅니다.

## 대회 사용 시 확인 사항

- 대회 운영 안내와 최신 공지가 우선합니다. 공개 저장소 사용 조건과 공개 유지 기간을 지킵니다.
- 문제, 작업물, 제출 파일을 외부로 전송하거나 Git push 하지 않습니다.
- 시험 중에는 제공된 Codex를 사용하고, Computer Use 및 후속 서술형 AI 사용 제한을 따릅니다.
- 각 스킬의 추가 단계와 도구 사용이 시험 환경 및 대회 규칙에 맞는지 확인합니다. 모든 워크플로를 수행할 필요는 없습니다.

## 출처 및 라이선스

- `systematic-debugging`, `test-driven-development`, `verification-before-completion`: [obra/superpowers](https://github.com/obra/superpowers), MIT License. 라이선스 전문은 [LICENSE-SUPERPOWERS](LICENSE-SUPERPOWERS)를 참조하세요. 원본은 로컬에 설치된 Superpowers 7.0.1입니다.
- `prompt-contracts`: 사용자의 로컬 스킬에서 가져왔습니다. 독립적인 오픈소스 라이선스는 확인되지 않아 별도 라이선스를 부여하지 않았습니다.

React와 웹 UI 관련 스킬은 [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills)의 공개 원본을 참고하세요.
