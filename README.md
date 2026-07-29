# WORK MOBILE — Landing Page

모빗 주식회사의 기업용 회선 관리 서비스 **WORK MOBILE** 랜딩페이지 버전 아카이브.

## 구조

```
/
├── index.html        ← 버전 셀렉터 (다크 허브)
├── v1/index.html     ← 챌린저스(biz-challengers.com) 스타일
├── v2/index.html     ← 챌린저스 톤 정제 (672px 컬럼)
└── v3/index.html     ← 뮤즈바이(museby.co.kr) 데이터 드리븐 SaaS 스타일
```

## 버전 비교

| | v1 | v2 | v3 |
|---|---|---|---|
| 레퍼런스 | biz-challengers.com | biz-challengers.com | museby.co.kr |
| 톤 | 다크 필 + 블루 | 화이트 + 블루 | 화이트 + 그린 |
| 히어로 | 텍스트 중심 | 인터랙티브 BG | 실시간 카운터 + 대시보드 |
| 핵심 패턴 | 원페이지 + 리드폼 | 고객 목소리 + 가치제안 | 5-STEP 탭 + 3-tier 플랜 |
| 인터랙션 | 스크롤 리빌 | 스크롤 리빌 + FAQ | 탭 전환 + 검색 + 카운터 |

## 실행

정적 HTML이라 아무 서거나 열면 됩니다:

```bash
cd work-mobile
python3 -m http.server 8080
# http://localhost:8080
```

## 라이선스

© 2026 Mobit Inc. All rights reserved.
