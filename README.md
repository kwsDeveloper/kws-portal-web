# KWS 복지 가이드

대한사회복지회(KWS)가 제공하는 **사회복지 서비스 안내 공개 포털**입니다.  
구글 애드센스 승인을 목표로 운영되는 공개 사이트입니다.

## 사이트 주소

> GitHub Pages 활성화 후: `https://kwsdeveloper.github.io/kws-portal-web/`

## 페이지 구성

| 파일 | URL | 내용 |
|---|---|---|
| `index.html` | / | 홈 — 서비스 카드·신청 절차 |
| `welfare-types.html` | /welfare-types.html | 복지 서비스 유형 상세 (탭) |
| `how-to-apply.html` | /how-to-apply.html | 신청 방법 단계별 안내 + FAQ |
| `news.html` | /news.html | 복지 소식 (최신 정책 변경) |
| `about.html` | /about.html | 사이트 소개 |
| `privacy.html` | /privacy.html | 개인정보처리방침 |
| `contact.html` | /contact.html | 문의하기 |

## 다른 PC에서 가져오기

```bash
git clone https://github.com/kwsDeveloper/kws-portal-web.git
cd kws-portal-web
```

## 로컬 수정 후 배포

```powershell
git add .
git commit -m "변경 내용 설명"
git push
```

→ push 즉시 GitHub Pages에 반영됩니다 (약 1~2분 소요).

## 기술 구성

- **호스팅**: GitHub Pages (main 브랜치 자동 배포)
- **백엔드**: 없음 (순수 HTML/CSS/JS)
- **폰트**: Google Fonts (Noto Sans KR)
- **디자인**: kws-portal 디자인 시스템 기반
