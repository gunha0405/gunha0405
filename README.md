# Oh Gunha

## 👋 About Me

개발을 통해 문제를 해결하고 구조를 만들어가는 과정에 매력을 느껴,꾸준히 배우고 실전에 적용해가고 있는 백엔드 개발자입니다.

- 🏕️ **KH정보교육원 공공데이터 융합 자바개발자 양성과정** 수료 (2024.04 ~ 2024.10)
- 🏕️ **한화시스템 BEYOND SW캠프 12기** 수료 (2024.11 ~ 2025.05)

---

## 🧩 핵심 역량
- **문제 해결 중심 개발자**: 기술적 난관을 해결하고 성능을 개선할 때 가장 큰 동기를 느낍니다.

- **성장에 몰입하는 태도**: 새로운 기술 습득에 적극적이며, 학습한 내용을 프로젝트에 빠르게 적용합니다.

- **구조적 설계 지향**: 단순 구현을 넘어 예외 처리, 응답 구조, 배포 자동화 등 서비스 완성도를 중시합니다.


## 🛠️ Tech Stack

### Programming Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=flat&logo=gnu-bash&logoColor=white)

### Data & Database
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

### Infrastructure & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)

### Frameworks & Tools
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)

---

## 🗂️ Projects

### 🔹 Tech-Up (사용자 기반 맞춤형 쇼핑몰 플랫폼)

- **커뮤니티 기능 구현**
  - 게시글/댓글 CRUD, 좋아요, 게시글 정렬(최신순/좋아요순/댓글순), 키워드 검색
  - S3 연동 이미지 업로드 (다중 첨부파일 포함)

- **알림 기능 (이벤트 기반 처리)**
  - Kafka 기반 실시간 알림 처리  
    - 로그인한 사용자가 ‘찜한 제품’이 할인/품절/재입고 시, Kafka 메시지를 통해 알림 전송
  - Spring Scheduler 기반 크론 작업 구현  
    - 매월 쿠폰 발급 알림, 주문 완료 알림 등 정기 메시지 발송 처리

- **선착순 쿠폰 발급 시스템**
  - Redis Lua 스크립트로 동시성 제어 구현 → 중복 발급 및 재고 초과 방지
  - 대기열 UX 반영을 통해 발급 실패/대기 상태도 사용자에게 실시간 피드백

- **CI/CD 및 배포 환경**
  - Jenkins 기반 CI/CD 파이프라인 구축 → 테스트 및 자동 배포 자동화
  - Kubernetes 환경에서 서비스 배포 → 학습용 클러스터에서 Blue/Green 배포 적용
👉 [GitHub Repo](https://github.com/beyond-sw-camp/be12-fin-404Found-Tech-Up-BE)
---
### 🔹 EduLink | 부트캠프 학습 관리 시스템 (미니 프로젝트)

기존 HRD-Net의 한계를 보완하고, 커리큘럼 관리와 학습 성과 분석 기능을 강화한 부트캠프 전용 학습 관리 플랫폼입니다.

- 게시글 작성/수정/삭제/조회, 사용자별 목록 조회 기능 구현  
- 게시판 타입 및 페이지네이션 적용한 리스트 API 설계  
- 이미지 업로드/삭제 시 S3 연동 및 Pre-Signed URL 기반 처리  
- 전역 예외 처리(`@RestControllerAdvice`), 공통 응답 구조(BaseResponse) 설계 및 적용  
- 팀 내 공통 아키텍처 적용을 위한 예외/응답 설계 주도  
👉 [GitHub Repo](https://github.com/beyond-sw-camp/be12-3rd-404Error-EduLink)

---

### 🔸 기타 학습 프로젝트

- **TravelNote**  
  - 사용자 일정 공유, 패키지 여행 예약, 커뮤니티 기능을 포함한 통합 여행 플랫폼  
  - 이메일 인증, JWT 로그인, 소셜 로그인, 사용자 초대 및 프로필 수정 등 회원 기능 중심 API 구현  
  👉 [GitHub Repo](https://github.com/gunha0405/Project_TravelNote)

- **Minit**  
  - SNS형 피드 서비스 구조 구현: 피드 작성, 댓글, 좋아요, 저장, 신고 기능 포함  
  - 신고 누적 시 자동 숨김 처리, 사용자 상태 기반 데이터 구성  
  👉 [GitHub Repo](https://github.com/gunha0405/Minit)

---

## 📫 Contact

- Email: dhrjsgk0405@gmail.com
- Blog: [velog.io/@gunha](https://velog.io/@gunha)  
