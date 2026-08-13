# data/ — 구조화 데이터

iOS 앱을 만들 때 쓸 시드 데이터입니다. 마크다운 문서가 원본이고, 여기는 파생물입니다.

## phrases.json

| 필드 | 설명 |
| --- | --- |
| `id` | `p001` 형식 |
| `scene` | `core` `izakaya` `react` `help` `golf` `shop` `move` `safe` `read` |
| `section` | 원본 문서의 섹션명 |
| `mode` | `say` = 소리 내어 말함 / `read` = 눈으로 알아보기만 함 |
| `ko_reading` | **한글 읽기** — 앱에서 가장 크게 보여줄 값 |
| `ja` | 일본어 원문 — 상대에게 화면으로 보여줄 값 |
| `ko_meaning` | 한국어 뜻 |
| `priority` | 0~3. 높을수록 자주 씀 |

## 현재 범위

`web/index.html` 의 현장 카드에서 추출했습니다. **가이드 문서(`guides/`) 전체 문장은 아직 포함돼 있지 않습니다.**
앱 작업을 시작하면 가이드 표에서 추가 추출하세요.

## 재생성

```bash
# web/index.html 의 DATA 배열 → data/phrases.json
# 추출 스크립트는 커밋에 남아 있지 않습니다. 표 형식이 일정하므로 재작성이 쉽습니다.
```
