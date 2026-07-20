# StockSignal APK

시그널 트레이딩(StockSignal) 디버그 빌드 APK 배포용 리포지토리.

## 설치 방법 (실제 폰)

1. 아래 파일을 폰에서 다운로드
   - [`stocksignal-debug.apk`](stocksignal-debug.apk)
2. 폰 설정에서 **출처를 알 수 없는 앱 설치 허용** (Chrome/파일 앱 등)
3. 다운로드한 APK 를 눌러 설치

> ⚠️ **디버그 빌드**입니다. 디버그 서명 키로 서명돼 있어 테스트용입니다.
> 스토어 배포용이 아닙니다.

## 파일

| 파일 | 빌드 | 비고 |
|---|---|---|
| `stocksignal-debug.apk` | debug | 어드민 유저관리 '익명' 오표시 근본 수정 — 구글 연결 직후·앱 진입 시 authProvider·email 을 users 문서에 재동기화(서버측 Auth→users 백필 스케줄 병행). 이 APK로 앱을 한 번만 열면 연결 계정이 어드민에 이메일로 정상 표시됨. (직전 '5단계 레짐-스위칭 시장 국면 뱃지' 기능 포함) |
