### 김동선 · Dongsun Kim

**웹·앱 화면부터 API·DB·인프라까지 직접 개발하고 운영하는 풀스택 개발자입니다.**

스마트시티 관제 대시보드(React)로 시작해, 이후 3년간 외주로 웹·앱 서비스를 출시하고 운영했습니다.
화면에서 보이는 문제를 네트워크·DB까지 따라가 원인을 찾습니다.

`TypeScript` `React` `Next.js` `React Native` `Capacitor` · `Node.js` `Express` `Prisma` `PostgreSQL` `Redis` · `AWS` `Cloudflare`

---

#### 해 온 일

| | | |
| --- | --- | --- |
| **숏캐시** | 앱테크 리워드 앱(고객사 외주) · 2023.12 인수 후 7개 저장소를 1인으로 개발·운영 · Android 누적 설치 5만 | [Google Play](https://play.google.com/store/apps/details?id=com.pluscash) · [App Store](https://apps.apple.com/kr/app/id6474850803) |
| **오퍼월** | 숏캐시 연계 리워드 미션 플랫폼 · 버즈빌 등 광고 네트워크 연동 | |
| **밥알** | 식품 큐레이션 하이브리드 앱(Next.js + Capacitor) · 외주 1인 개발 | [bab-r.com](https://bab-r.com) |
| **KoK** | 강사·전문가 매칭 플랫폼 · 결제·본인인증·푸시 · 외주 1인 개발 | [kok-it.com](https://kok-it.com) |

#### 최근에 한 일

- 배포 직후 API 평균 응답이 **12ms → 160ms**(일부 60초)로 느려진 장애에서, DB CPU는 정상이었지만
  커넥션 풀 대기를 따라가 원인 쿼리를 찾고 Redis 캐시·중복 요청 제거로 **7~9ms**로 되돌렸습니다
- 오퍼월 API 요청의 31%가 CORS preflight인 원인(GET에도 붙던 Content-Type)을 찾아
  하루 **40,668건 → 2,265건**으로 줄였습니다
- 리전 간 **월 6.8TB** 전송을 역추적해 gzip 임계값 설정 오류를 바로잡고 응답 크기를 **70~90%** 줄였습니다
- WKWebView에서 키보드가 열린 채 링크를 누르면 스와이프 뒤로가기가 화면을 건너뛰는 버그를
  시뮬레이터에서 재현하고 WebKit 디버그 프록시로 원인을 찾아 고쳤습니다
- D1 읽기 복제를 공개 조회에만 적용해 해외 경유 쿼리 중앙값을 **약 590ms → 214ms**로 줄였습니다

📮 le12352@gmail.com
