# 지갑부터 만들어라

3개의 독립 블록체인 생태계를 솔로로 설계·구축·운영 중입니다.

---

## EverChain Ecosystem · [ever-chain.xyz](https://ever-chain.xyz)

| 체인 | 기반 | 특징 | 링크 |
|---|---|---|---|
| **BitEver (BEC)** | Bitcoin Core v30.2 | PoW, 포크블록 #478,558 | [탐색기](https://bitever.ever-chain.xyz) |
| **EtherEver (ETE)** | Core-Geth (PoW) | 포크블록 #1,919,999, London HF | [탐색기](https://etherever.ever-chain.xyz) |
| **SolaEver (SLE)** | Agave / Solana v4.0 | Tower BFT, 400ms slot | [탐색기](https://solaever.ever-chain.xyz) |

각 체인마다 **노드 + 탐색기 + 지갑 → 풀스택 인프라**를 직접 구축했습니다.

---

## 직접 건드린 것들

- **C++** — Bitcoin Core chainparams, magic bytes 수정  
- **Rust** — Solana validator u128 overflow 버그 패치 (`runtime/src/inflation_rewards`)  
- **Go** — Core-Geth fork, Nethermind 모드 활성화  
- **Python** — custom `proxy.py` (Esplora API 번역), `bootstrap.dat` 생성 스크립트  
- **TypeScript** — Next.js Solana Explorer fork  
- **Elixir** — BlockScout fork, SSL/WebSocket 수정  
- **React Native** — MetaMask Mobile fork (iOS + Android, EtherEver 전용)  
- **Python/Qt** — Electrum fork (Windows + Android)

모든 레포는 **GitHub Actions CI 통과 + 실제 Ubuntu 빌드·운영 확인** 기준으로만 올립니다.

---

## 최근 완료 작업 (260423)

- SolaEver 전용 안드로이드 지갑 구현 완료(네이티브 코인 전송, SPL 토큰 전송, 뷰 트랜잭션 확인)

---

## 현재 진행 중

- EtherEver (L1)의 전용 L2 Layer 구축중

---

[![Discord](https://img.shields.io/badge/Discord-지만쫌-5865F2?logo=discord)](https://discord.com/invite/dfSF58pzZB)
[![YouTube](https://img.shields.io/badge/YouTube-지만쫌-FF0000?logo=youtube)](http://www.youtube.com/@지만쫌)
