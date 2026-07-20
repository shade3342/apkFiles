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
| `stocksignal-debug.apk` | debug | 이메일(구글) 인증 사용자가 어드민 유저관리에 '익명'으로 표시되던 버그 수정(연결 후·앱 진입 시 authProvider·email 을 users 문서에 재동기화) |
