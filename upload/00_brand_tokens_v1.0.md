# 코인턱보트 (CoinTugboat) — 브랜드 디자인 토큰 v1.0

작성: 2026-05-07
운영사: CREATIVE BASECAMP (사업자번호 211-08-65517)

---

## 브랜드 한 줄
> 관측은 객관, 판단은 본인.
> 업비트 KRW 250종목을 5분마다 관측하는 한국형 시장 레이더.

매수·매도 추천이 아닌 **7-Layer 근거 기반 관측 도구**.
한국 가상자산 이용자 보호법(2024-07-19) 준수, 17세+ 권장.

---

## 컬러 팔레트

| 역할 | HEX | 용도 |
|---|---|---|
| Background (Dark Charcoal) | `#07080d` | 메인 배경, App theme_color |
| Sage / Mint (Primary Accent) | `#6FCFA8` | 관측 활성, 조건 충족, Solution 강조 |
| Cyan (Info Accent) | `#38BDF8` | 정보·링크·중립 상태 |
| Coral (Warning Accent) | `#E57F6E` | 주의 구간, 해제 임박, CTA 보조 |
| Text Primary | `#F8FAFC` | 본문 글자 |
| Text Muted | `#94A3B8` | 보조 텍스트 |
| Divider | `#1E293B` | 카드/섹션 구분선 |

**금지:** 사이버펑크 네온, 형광 옐로우/마젠타, 게임 HUD 컬러, 빨간색 단독 사용(시그널 오인)

---

## 타이포그래피

- **Family**: Pretendard Variable (한국어 산세리프, CDN 로드)
- **Weights**: Bold(700) 헤드라인 / SemiBold(600) 서브 / Regular(400) 본문
- **Heading**: 32~56px, line-height 1.2, letter-spacing -0.02em
- **Body**: 14~18px, line-height 1.6
- **Numeric**: tabular-nums (시세·비율·점수)

---

## 레이아웃·스페이싱

- **Grid**: 4px 베이스 단위 (4·8·12·16·24·32·48·64)
- **Border Radius**: 8px(작은 칩) / 16px(카드) / 24px(모달)
- **Shadow**: 미니멀 (`0 4px 12px rgba(0,0,0,0.4)` 다크 환경 한정)
- **Container Max**: 모바일 430px / 태블릿 768px / 데스크톱 1280px

---

## 핵심 컴포넌트

### 1) 관측 상태 배지 (Status Badge)
- 조건 충족 / 관측 활성 / 중립 / 주의 구간 / 관측 해제
- ✅ 안전 표현 / ❌ "강세 신호", "매수 신호" 사용 금지

### 2) 7-Layer 카드 (Layer Card)
1. 가격 (VWAP·EMA·피보나치)
2. 거래량 (거래대금·시간대 정규화)
3. 추세 (RSI·MACD·StochRSI 멀티TF)
4. 구조 (SMC·BOS·CHoCH·FVG)
5. 수급 (호가벽·순시장가·테이커)
6. 매크로 (BTC 도미넌스·F&G·매크로 레짐)
7. 리스크 (펀딩비·OI·롱숏 비율)

각 카드: 아이콘 + 레이블 + 상태바 + 짧은 근거 1줄

### 3) 해제 조건 박스 (Invalidation Box)
- "관측 해제 조건" 라벨
- 가격/볼륨/시간 조건 1~3개
- 다음 체크포인트 시각

### 4) Pro 페이월 (Paywall)
- 가격: ₩3,300 / 월
- 7일 무료 체험 (자동 결제 안내 명시)
- ❌ "수익 보장", "트레이딩 시작" 표현 금지
- ✅ "더 정밀한 관측", "관심종목 30개 + 변화로그 24h/7d"

### 5) 면책 다이얼로그 (Disclaimer Modal)
- "본 서비스는 투자 자문이 아닙니다"
- 동의 체크박스 + "동의하고 시작" 단일 버튼 (거부 버튼 X)
- 한국 자본시장법 + Apple/Google 가이드 준수

---

## 톤 & 매너 (카피)

✅ **권장**:
관측 / 관측 후보 / 조건 충족 / 해제 조건 / 시장 변화 / 근거 / 상태 변화 / 레이더 / 객관적 기준 / 판단은 본인

❌ **금지** (컴플라이언스 grep):
매수 / 매도 / 진입 / 익절 / 손절 / 수익 보장 / 승률 / 적중률 / 매수 추천 / 매수 신호 / 강력 매수 / 자동매매 / 따라 사세요 / 무조건 상승 / 급등 확정 / 시그널 / 리딩 / 단타

---

## 참고 자산 (이 폴더에 동봉)
- `01_logo_cointugboat_1024.png` — iOS App Icon (1024×1024)
- `02_store_icon_android_512.png` — Google Play Store Icon (512×512)
- `03_screenshot_5장_명세.md` — App Store 스크린샷 5장 카피·화면 명세
- `04_랜딩페이지_기획서.md` — thecreativebasecamp.com/cointugboat/ 랜딩 기획서
- `05_logo_CBC_parent.png` — CREATIVE BASECAMP 모회사 로고
