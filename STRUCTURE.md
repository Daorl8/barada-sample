# STRUCTURE · barada-sample (v0.3 · 사진 중심 갤러리형)

```
barada-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인 · 모바일 메뉴 · 리빌 · 앵커 스크롤)
├─ wrangler.toml              name = barada-sample → barada-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ bd-pretendard.woff2        한글 · 본문 (Pretendard 300–600, 쓰는 글자만)
├─ bd-outfit.woff2            영문 라벨 (Outfit 400–600, 라틴)
├─ bd-mark.webp               헤더 로고 "brd."
├─ bd-logo.webp               전체 로고 검정(푸터)
├─ bd-hero.webp               히어로 (화면 가득)
├─ bd-photo-01 ~ 12.webp      포트폴리오 갤러리 (원래 비율 · 2단)
├─ favicon.png · og-barada.jpg
├─ img/                       다올 제공 원본 85장 (배포 제외 · 인물 사진 포함)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(+ `#m-nav`) → 히어로(전체 폭 사진) → `#about`(흰 · 한 단락) → `#works`(흰 · 갤러리 + 사례 목록 · 블로그 링크) → `#process`(흰 · 진행 8단계 + 신청 시기) → `#contact`(옅은 크림 · 상담 + 주소 · 영업 + 지도) → 한 줄 푸터 + 모바일 `.quick`.

## 연락 채널
무료 상담 예약(구글 폼 · 헤더 · 히어로 · 상담 · 하단 바) · 카카오톡 오픈채팅(상담 · 하단 바) · 전화 010-3421-3532 · 블로그 · 네이버 플레이스 1365790485(길찾기).

## 그리드
모든 그리드 칸 `minmax(0, …)`(LESSONS §27). 오시는 길 R-1.

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). Outfit은 영문에만.
