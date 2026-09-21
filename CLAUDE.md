# KWS 복지 가이드 — 프로젝트 전용 규칙

> 문서 저장·GitHub 연동 등 공통 규칙은 전역 CLAUDE.md 적용

## 프로젝트 정보

- **서비스**: KWS 복지 가이드 (사회복지 서비스 안내 공개 포털)
- **포털 주소**: https://kwsdeveloper.github.io/kws-portal-web/
- **GitHub 저장소**: https://github.com/kwsDeveloper/kws-portal-web
- **로컬 경로**: C:\ClaudeProjects\kws-portal-web\
- **운영 목적**: 구글 애드센스 승인 목표 공개 사이트

## 기술 구성

- **호스팅**: GitHub Pages (main 브랜치 자동 배포)
- **백엔드**: 없음 (순수 HTML/CSS/JS)
- **디자인 기반**: kws-portal 디자인 시스템 (CSS 변수·다크모드)

## 페이지 구성

- `index.html` — 홈 (히어로·서비스 카드·신청 절차·정보 박스)
- `welfare-types.html` — 복지 서비스 6종 탭 상세
- `how-to-apply.html` — 신청 방법 + FAQ
- `news.html` — 복지 소식
- `about.html` — 사이트 소개
- `privacy.html` — 개인정보처리방침
- `contact.html` — 문의하기

## 코드 수정 규칙

- HTML 수정 후 반드시 `git push`까지 완료
- 애드센스 코드는 `<head>` 안에 삽입 (각 페이지 공통)
- 콘텐츠는 실제 복지 정보를 기반으로 한 원본 내용 유지
- 외부 JS 라이브러리 추가 금지 (순수 HTML 유지)
