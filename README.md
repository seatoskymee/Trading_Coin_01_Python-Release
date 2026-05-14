# RSP Bitcoin Auto Trader

빗썸(Bithumb) 현물 자동매매 PC 프로그램 — Windows 64bit

## ⬇ 다운로드

[![최신 버전 다운로드](https://img.shields.io/github/v/release/seatoskymee/Trading_Coin_01_Python-Release?label=최신버전&style=for-the-badge)](https://github.com/seatoskymee/Trading_Coin_01_Python-Release/releases/latest/download/RSPBitcoin_latest.exe)

**고정 다운로드 URL (버전이 바뀌어도 URL 불변)**
```
https://github.com/seatoskymee/Trading_Coin_01_Python-Release/releases/latest/download/RSPBitcoin_latest.exe
```

## 실행 방법

1. `RSPBitcoin_latest.exe` 다운로드
2. 같은 폴더에 `config.json` 생성
   - paper 모드는 API 키 없이도 동작
   - 예시 설정: [config.example.json](https://github.com/seatoskymee/Trading_Coin_01_Python-Release/releases/latest)
3. EXE 실행

## 주요 기능

| 기능 | 설명 |
|------|------|
| 전략 프리셋 | 변동성 돌파 / 볼린저 / MACD / ATR 등 10가지 |
| 멀티 심볼 | BTC, ETH, XRP 등 동시 거래 |
| 실시간 차트 | 가격·RSI·BB%B·MACD·ATR 자동 스케일 |
| 워밍업 로드 | 거래 시작 시 최근 5분 1분봉 데이터 선로드 |
| 리스크 관리 | 일일 손실 한도 · 연속 손실 차단 · 트레일링 스톱 |
| EOD 자동 청산 | KST 23:55 기준 미포지션 자동 종료 |
| 알림 | Telegram / Slack 선택 알림 (opt-in) |
| Paper 모드 | API 키 없이 모의 거래 지원 |

## ⚠ 경고

> **일일 5~10% 수익 목표는 매우 위험합니다.**
> 반드시 **paper 모드** + 백테스트 + 워크포워드 검증 후 소액으로 시작하세요.
> 투자 손실에 대한 책임은 전적으로 사용자 본인에게 있습니다.

## 버전 이력

| 버전 | 내용 |
|------|------|
| v1.0.0 | 최초 릴리스 |
