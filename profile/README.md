# P-Project8 – PetFit 🐶👗

<img width="830" height="553" alt="스크린샷 2025-12-12 오전 10 24 54" src="https://github.com/user-attachments/assets/0b8744e7-93ad-4b8c-86ac-3a086b5f60c2" />

**PetFit**은 반려인이 올린 **반려견 사진과 쇼핑몰 상품 이미지를 AI로 스타일링**하여,
강아지에게 어울리는 모습을 미리 확인하고 **찜·장바구니·구매까지 한 번에 이어지는** 반려견 패션 쇼핑 서비스입니다.

---

## 🔗 Repositories

* **Backend**: [PetFit-BE](https://github.com/P-Project8/PetFit-BE)
* **Frontend**: [PetFit-Front](https://github.com/P-Project8/PetFit-Front)

---

## 🧩 Key Features

* 반려견 사진 업로드 + 상품 선택 → **AI 스타일링 이미지 생성 (Gemini)**
* 상품 찜, 장바구니, 주문 내역, 리뷰 작성 등 기본 쇼핑 기능
* 이메일 인증 / 로그인, JWT + Redis 블랙리스트 기반 인증 인가
* PostgreSQL + Redis + S3 기반 데이터/이미지 관리

---

## 🏛 Architecture

* **Frontend**: React, TypeScript, Vite, Zustand, TailwindCSS, Vercel
* **Backend**: Spring Boot, JPA, Spring Security, Redis, PostgreSQL (AWS RDS), S3
* **Infra**: Docker, AWS EC2, GitHub Actions + CodeDeploy

---

## ⚙️ Getting Started

각 레포의 README에서 자세한 실행 방법을 확인하실 수 있습니다.

1. Backend: `PetFit-BE` README 참고
2. Frontend: `PetFit-Front` README 참고

---

문의나 피드백은 Issues로 남겨 주세요 🙌
