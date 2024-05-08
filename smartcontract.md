---
description: Smart Contact
---

# 스마트컨트랙트

CPESO 스마트컨트랙트는 이더리움 기반의 ERC-20 네트워크에서 동작하도록 설계 되었습니다.&#x20;

이더리움 2.0으로 업그레이드 되면서 합의 알고리즘이 PoW에서 PoS로 변경 되었습니다. 칸쿤 업그레이드로 느린속도와 높은 가스비(수수료)의 문제가 해결 되었습니다. 또한, 자체 메인넷 완료 이후는 보다 저렴하고 빠른 속도로 처리가 가능해 질 것입니다.

스테이블 서비스가 가능해짐에 따라 법정화폐 인 Peso 와 디지털 자산인 CPESO의 환 페깅(exchange paging)이 가능 해졌습니다.

CPESO의 유동성을 막기 위해서 중앙화 금융서비스(CEX)와 CPESO의 보안성, 그리고 안정성을 보장하기 위하여 탈중앙화 금융 서비스(DEX) 를 결합하였습니다.

Ethereum Test net

* 스마트 컨트랙트 주소 : [0x1739Ebc150c50302120b93876cED09276DB82d4E](https://sepolia.etherscan.io/token/0x1739Ebc150c50302120b93876cED09276DB82d4E)
* 스마트 컨트랙트 코드 : [https://github.com/CPESO/smartcontracts/tree/draft](https://github.com/CPESO/smartcontracts/tree/draft)



Ethereum Main net

* 스마트 컨트랙트 주소 :&#x20;
* 스마트 컨트랙트 코드 : [https://github.com/CPESO/smartcontracts/tree/main](https://github.com/CPESO/smartcontracts/tree/main)

주요기능

| 함수명            | 기능          |
| -------------- | ----------- |
| approve()      | 승인          |
| allowance()    | 허용량 확인      |
| transfer()     | 토큰 전송       |
| transferFrom() | 토큰 전송 및 교환  |
| balanceOf()    | 계정 잔액       |
| name()         | 토큰 이름       |
| symbol()       | 토큰 심볼       |
| totalSupply()  | 토큰 발행 전체 개수 |
