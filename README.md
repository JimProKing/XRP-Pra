# XRPL Korea Toolkit 🇰🇷

XRPL(XRP Ledger)에 쉽게 연결해서 아래와 같은 작업들을 할 수 있는 멀티 기능 Node.js 라이브러리 & 예제 리포지터리입니다.

### 지원하는 주요 기능
- 계정 정보 및 XRP 잔고 조회
- XRP 송금 (기본 결제)
- 토큰(issued currency) 송금
- 트러스트라인(TrustLine) 생성/수정/삭제
- DEX 오퍼(OfferCreate) 생성 및 취소
- NFT 민팅 (NFTokenMint), 수락, 판매 오퍼 (NFTokenCreateOffer)
- 거래 서명 및 직렬화 (오프라인 서명 지원)
- WebSocket 및 REST API 둘 다 지원
- Testnet / Devnet / Mainnet 자동 전환

## 빠른 시작 (5분 안에 실행해보기)

### 1. 설치
```bash
git clone https://github.com/당신아이디/xrpl-korea-toolkit.git
cd xrpl-korea-toolkit
npm install