# my-skills

오수 전용 Claude 스킬 모음. claude.ai 플러그인 마켓플레이스로 등록해서 사용.

## 등록 방법
사용자 지정 → 플러그인 → 추가 → 마켓플레이스 추가 → 저장소에서 추가 → `깃허브아이디/my-skills` 입력

## 포함된 스킬
| 플러그인 | 용도 | 출처 |
|---|---|---|
| unslop | AI 티 나는 UI 진단·개선 | [heydamir/unslop](https://github.com/heydamir/unslop) (CC BY 4.0, Damir Sokolovsky) |

## 스킬 추가하는 법
1. `plugins/` 아래에 새 폴더 생성 (예: `plugins/새스킬/`)
2. 그 안에 `.claude-plugin/plugin.json`, `skills/새스킬/SKILL.md` 배치 (unslop 폴더 구조 그대로 복사해서 수정)
3. `.claude-plugin/marketplace.json`의 `plugins` 목록에 한 줄 추가
4. 커밋·푸시 후 claude.ai 플러그인 화면에서 업데이트

## 외부 스킬 업데이트
원본 레포가 바뀌면 `plugins/unslop/skills/unslop` 폴더를 새 버전으로 교체하고 `version` 숫자 올리기.
