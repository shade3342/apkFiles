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
| `stocksignal-debug.apk` | debug | **DB 무손실 마이그레이션** — 앱 업데이트 시 시그널 홈 알림·성과검증·설정이 사라지던 문제 근본 수정(과거 Room `fallbackToDestructiveMigration` 이 버전업마다 전 테이블 삭제 → 무손실 마이그레이션으로 전환). **이 APK부터는 다음 업데이트에서 기존 알림/이력이 보존**됩니다. (직전 빌드 UX 7종 포함 — 성과검증 타임라인 Bottom Sheet·카드↔딥링크 UI 통일·프리셋 백테스트 하이브리드·내전략 정렬/수정·기간 필터) |
