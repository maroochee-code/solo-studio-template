# solo-studio-template

Claude Code로 1인 개발할 때 쓰는 프로젝트 시작 세트와 세팅 스킬.

- Claude Code 본체가 **개발 총괄**을 맡고, 필요할 때 실무 에이전트를 "고용"한다.
- 규모(S/M/L)와 단계(프로토타입 → 본설계 → 구현 → 베타 → 라이브 → 동결)에 따라 대응 방식이 바뀐다.
- 사용자는 기획·사업·개발 총괄을 겸하는 최종 결재자.

## 구성
| 위치 | 내용 |
|---|---|
| `template/` | 프로젝트에 복사되는 파일 전체. 안내서는 `template/docs/STUDIO-GUIDE.md` |
| `skills/studio-setup/` | 세팅 스킬: 새 프로젝트 / 기존 프로젝트 적용 / 규모 올리기 / 템플릿 업데이트 반영 |

## 스킬 설치 (Claude Code)
`skills/studio-setup` 폴더를 `%USERPROFILE%\.claude\skills\studio-setup` 으로 복사한다.
이후 프로젝트 폴더에서 "스튜디오 세팅해줘" 또는 "/studio-setup".

## 템플릿 고치기
1. `template/` 수정
2. `template/.studio-template-version` 버전 올리기
3. 커밋 메시지에 무엇이 왜 바뀌었는지 적기
4. GitHub Desktop에서 Push

진행 중인 프로젝트는 스킬의 "템플릿 업데이트 반영"으로 바뀐 규칙만 골라 받는다.
