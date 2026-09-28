# NeoAmico · 대우ACC 홍보 웹사이트

대우ACC(주식회사 대우컴프레셔)의 프리미엄 공기 케어 브랜드 **NeoAmico**를 소개하는 정적 홍보 웹사이트입니다.

- 순수 HTML/CSS/JS로 제작 (빌드 과정 불필요)
- 반응형 디자인 (모바일 / 태블릿 / 데스크톱)
- 회사 소개, 핵심 기술(저온제습·UV-C 살균·광촉매 탈취), 제품 라인업, 설치 사례, 인증·특허, 문의 섹션 구성

## 로컬 실행

별도 빌드 없이 정적 파일이므로 아무 정적 서버로 열면 됩니다.

```bash
python -m http.server 5500
# http://localhost:5500 접속
```

## 배포

Vercel에 GitHub 저장소를 연동하면 별도 설정 없이 정적 사이트로 자동 배포됩니다.
(Framework Preset: **Other / Static**, Build Command 없음, Output Directory: `./`)

## 폴더 구조

```
neoamico-site/
├── index.html      # 전체 페이지 콘텐츠
├── styles.css      # 스타일 (네이비 & 레드 브랜드 컬러)
├── script.js       # 스크롤 인터랙션, 모바일 메뉴
├── images/         # 제품/설치 사례 이미지
└── README.md
```

## 콘텐츠 출처

회사 소개, 제품 스펙, 인증, 설치 사례 데이터는 대우컴프레셔에서 제공한 회사소개서·제품소개서·설치사례 자료를 기반으로 작성했습니다.
