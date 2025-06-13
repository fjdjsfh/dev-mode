# 💸 깐부대출 (Gganbu Loan)

**친구와 함께하는 신뢰 기반 P2P & 풀 대출 플랫폼**

블록체인 기술을 활용하여 친구 간 대출 요청/승인 및 대출 풀 참여를 투명하고 안전하게 지원하는 서비스입니다. Hyperledger Fabric을 기반으로 한 체인코드와 React + Supabase 기반의 웹 프론트엔드로 구성되어 있습니다.
![wqed](https://github.com/user-attachments/assets/885e4998-37f2-4012-b21b-3b685c9e8905)
---![기능및기대효과](https://github.com/user-attachments/assets/f02de78f-f32b-45f8-95a6-995688eef72e)



## 📸 데모 화면
![메인/대시보드](https://github.com/user-attachments/assets/f7a9c744-4468-4ca7-a995-e4f1ec192aee)

![대출풀](https://github.com/user-attachments/assets/698ffd0e-7427-47a6-83a2-ab79b5513fca)

![개인대출신청](https://github.com/user-attachments/assets/3d91593d-d7f8-4378-8c88-026146b49a25)
![계약서](https://github.com/user-attachments/assets/d116b752-58e2-4c6d-9532-25a10ccbecb4)
![자금현황](https://github.com/user-attachments/assets/3ef7b00c-d221-40d1-88c1-a4fdb9a59ee3)
![친구목록](https://github.com/user-attachments/assets/c484c6b3-67d1-41e4-9bc9-f9a932772bb2)


---

## 🚀 주요 기능

### 🤝 친구 간 대출 (P2P Loan)
- 친구에게 대출 요청 및 승인/거절 기능
- 대출 계약 체결 및 상환 처리
- 체인코드 기반의 투명한 상태 관리 (`pending`, `active`, `repaid`)
- 대차계약서 자동 작성

### 🏦 대출 풀 (Lending Pool)
- 대출 풀 생성 및 초기 입금
- 최소 예치금 조건을 만족한 사용자가 참여 가능
- 풀 기간 종료 후 이자 자동 분배(예정)

### 친구 추가
- 이메일 기반 친구 요청/수락 시스템
- 친구에게만 P2P 대출 가능

### 💰 자금 현황
- 대출 거래 내역 조회 (대출/차입, 금액, 이자율 등)
- 상대방 이름, 시작일, 상태(상환 완료/활성/연체) 필터링 및 정렬


---
## ERD
![erd](https://github.com/user-attachments/assets/8f958014-6555-45cf-b3c7-eb905639cf68)

---
## 플로우차트
https://www.figma.com/board/pbjlCrPRjafskegZByRp8N/%EA%B9%90%EB%B6%80%EB%8C%80%EC%B6%9C-%ED%94%8C%EB%A1%9C%EC%9A%B0%EC%B0%A8%ED%8A%B8?node-id=0-1&p=f&t=fAOdAxLmp7jvVeLX-0

---
## ⚙️ 기술 스택

| 분류 | 기술 |
|------|------|
| 프론트엔드 | React, Tailwind CSS |
| 백엔드 | Node.js (Express)|
| 블록체인 | Hyperledger Fabric, Fabric SDK |
| DB | Supabase |
| 배포 | (로컬/테스트용) |

---

## 🧩 pdf
[결과보고서_5팀_블록체인을-활용한-깐부대출_.pdf](https://github.com/user-attachments/files/20720699/_5._.-.-._.pdf)




