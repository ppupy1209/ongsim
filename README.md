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

## 2026-10-18 보안메일 열기 페이지 직접 추가 (출시 전, noindex)
- securemail/support.html·privacy.html·index.html·icon.png를 choguen 페이지 형식 그대로 직접 작성했다. 홈·sitemap에는 넣지 않았다(출시 후 build_site.py에 항목 추가).
- 개인정보: 기기 안 처리, 메일 안 외부 주소(스타일·글꼴·이미지) 요청, '이 메일 방식 알려주기' 여섯 항목만 Google 설문지로 전송(진단 데이터, 연결·추적 없음), Apple 처리 구입. 시행일 10/18.
- build_site.py로 다시 생성하면 이 폴더는 APPS 목록에 없어 남지만, 재생성 전에 확인한다.

## 2026-10-20 Cutaway Facts Uploader 정책 페이지 직접 추가 (noindex)
- cutaway-uploader/index.html·privacy.html·terms.html·icon.png: TikTok for Developers 앱(개인용 데스크톱 받은편지함 업로드 도구)의 소개·개인정보·약관 URL용. 홈·sitemap에는 넣지 않았다.
- 개인정보: open_id·토큰은 운영자 Mac 파일에만, TikTok API 외 전송·제3자 공유 없음, 토큰 파일 삭제·TikTok 앱 권한 해제로 삭제. 시행일 10/20.
