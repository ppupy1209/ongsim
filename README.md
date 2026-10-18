# ONGSIM

Support and privacy pages for ONGSIM apps: https://ppupy1209.github.io/ongsim/

- Static GitHub Pages site. No analytics, cookies, trackers, external scripts or remote fonts.
- Pages under each app folder: `support.html`, `privacy.html` (Brieflume also `terms.html`).
- Apps not yet on the App Store have pages marked `noindex` and are not listed on the home page.
- Contact: ppupy1200@gmail.com

## 2026-10-14 f8f9133 개인정보 처리방침 직접 수정 (1.2.0 기능)
- owedone/privacy.html(직접 입력 환율·PDF/CSV·구입 범위), packstead/privacy.html(동행자 이름·출발 전 로컬 알림·구입 범위), shift-rail/privacy.html(저장한 교대 패턴)을 게시본에서 직접 고쳤다.
- build_site.py로 다시 생성하면 이 수정이 사라지므로, 재생성 전에 같은 문구를 원본 쪽에 반영하거나 이 커밋의 diff를 다시 적용한다.

## 2026-10-15 초근장부 페이지 직접 수정 (무료 + 선택형 이용권)
- choguen/support.html(무료와 이용권 절, 복원 방법, 업무지침 10/1 개정 반영 표기), choguen/privacy.html(Apple 처리 구입 항목, 위젯 공유 정보에 이용권 여부, 시행일 10/15)을 게시본에서 직접 고쳤다. noindex 유지.
- build_site.py로 다시 생성하면 이 수정이 사라지므로, 재생성 전에 같은 문구를 원본 쪽에 반영하거나 이 커밋의 diff를 다시 적용한다.

## 2026-10-18 owedone/support.html 직접 수정 (1.2.0 여러 통화)
- '여러 통화를 한 원장에 쓸 수 있나요?' KO/EN 답을 1.2.0(직접 입력 환율로 환산, 두 번째 통화 저장은 이용권) 기준으로 고치고 owedone-support의 여러 통화 안내로 연결했다.
- build_site.py로 다시 생성하면 이 수정이 사라지므로, 재생성 전에 같은 문구를 원본 쪽에 반영하거나 이 커밋의 diff를 다시 적용한다.
