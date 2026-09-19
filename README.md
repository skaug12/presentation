# 발표 아카이브

이슬기가 진행한 발표 자료 모음입니다. 목록: <https://skaug12.github.io/presentation/>

## 정본은 여기가 아닙니다

배포용 HTML 만 둡니다. 덱은 옵시디언 `Memo` 보관함의 소스를 고치고 다시 생성합니다.
덱이 아닌 문서(FAQ)는 `Memo` 가 아니라 `hfk-workspace` 에 소스가 있습니다.

| 문서 | 정본 | 고치는 법 |
|---|---|---|
| 새 덱 (26여름 5회차~) | `Memo/3 콘텐츠/발표/AI부사수/{시즌}-{회차}-{트랙}.md` | 소스 수정 후 `make_deck.py` 재생성 |
| 과거 덱 | 배포된 HTML | `Memo/…/AI부사수/_content/<덱>.md` 수정 후 `deck_content.py inject` |
| FAQ (`faq-ai-assistant.html`) | `~/hfk-workspace/note/AI부사수/AI부사수_FAQ.md` | 재생성 스크립트 없음. .md 와 HTML 을 손으로 같이 고침 |

색인: `Memo/3 콘텐츠/발표/_발표목록.md` (FAQ 는 이 색인에 없습니다)

FAQ 는 2026-04-11 에 만든 뒤 8월 갱신분이 HTML 에만 들어가 정본이 13개 섹션에서 멈춰 있었습니다.
2026-09-18 에 배포 HTML(22개 섹션) 기준으로 .md 를 다시 맞췄습니다. 다음부터는 .md 를 먼저 고쳐주세요.

## HFK 배포본과의 관계

AI부사수 덱과 FAQ · 트렌드는 멤버에게 `thehfk.github.io/hfk-ai-bss/` 주소로
공유돼 있습니다. 그 주소들은 이 아카이브로 넘겨주는 리다이렉트로 살려둡니다.
멤버용 진입 목록(시즌 페이지 · 회차별 기록)은 계속 `thehfk/hfk-ai-bss` 가 맡습니다.

## 목록 구성

`all.html` 은 네 갈래입니다.

| 섹션 | 내용 |
|---|---|
| AI부사수 | 26여름 주말 · 26여름 주중 · 26봄 · 모바일 버전 |
| FAQ | `faq-ai-assistant.html` |
| 트렌드 | `trends.html` |
| 그 외 발표자료 | 워크숍 · 외부 강연 · 오리엔테이션 |
