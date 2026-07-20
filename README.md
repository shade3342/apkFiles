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
| `stocksignal-debug.apk` | debug | 5단계 초정밀 레짐-스위칭 — 홈 상단에 '시장 국면 · OO장'(강세/횡보/반등/하락/폭락) 뱃지 신설(백엔드 market_regime.stage 실시간 구독) |
