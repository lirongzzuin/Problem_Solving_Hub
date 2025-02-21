# 🏆 Problem Solving Hub

## 📌 프로젝트 개요
**Problem Solving Hub**는 개발자들이 **알고리즘 문제 풀이, CS 개념 정리, 기술 블로그 작성** 등을 통해 학습하고 공유할 수 있는 플랫폼입니다.  
IT 기업의 코딩 테스트를 준비하는 개발자들에게 **효율적인 문제 풀이 및 학습 경험**을 제공합니다.  

이 프로젝트는 **MSA(Microservices Architecture), Kafka, Redis** 등 최신 기술을 활용하여 **확장성과 성능을 고려한 구조**로 개발됩니다.  
또한, **React를 활용한 프론트엔드 경험을 쌓고자 하는 목표**도 포함되어 있습니다.  

---

## 🎯 프로젝트 목표
✅ **개발자의 학습을 돕는 효율적인 플랫폼 구축**  
✅ **MSA 기반 아키텍처 설계 및 운영 경험 습득**  
✅ **Kafka, Redis 등의 최신 기술을 활용한 실무 경험 쌓기**  
✅ **React를 이용한 프론트엔드 개발 경험 추가**  
✅ **실제 IT 기업에서 요구하는 기술 스택을 적용하여 포트폴리오 구축**  

---

## 🛠️ 기술 스택 (Tech Stack)
| 분야 | 기술 |
|------|------|
| **Frontend** | React.js, TypeScript, TailwindCSS |
| **Backend** | Spring Boot, Spring Cloud (MSA) |
| **API Gateway** | Spring Cloud Gateway |
| **Database** | MySQL, Redis (캐싱) |
| **Message Queue** | Kafka (비동기 이벤트 처리) |
| **Authentication** | JWT (JSON Web Token) |
| **DevOps & Infra** | Docker, Kubernetes, AWS |
| **CI/CD** | GitHub Actions, ArgoCD |

---

## 🚀 주요 기능 (Key Features)
| 기능 | 설명 |
|------|------|
| 📝 **문제 풀이 공유** | 백준, 프로그래머스, LeetCode 문제 풀이 기록 & 공유 |
| 📖 **CS 학습 노트** | 운영체제, 네트워크, 데이터베이스 등 정리 |
| ✍️ **기술 블로그** | 개발 공부 기록, 면접 후기 작성 |
| 💬 **실시간 토론** | 댓글 및 채팅 기능으로 문제 풀이 & CS 개념 토론 |
| 🏆 **랭킹 시스템** | 유저 활동에 따라 포인트 & 배지 지급 |
| 🎯 **문제 추천 기능** | AI(ML 모델) 기반으로 문제 추천 (추후 확장 가능) |

---

```
📂 폴더 구조 (Directory Structure)

📂 problem_solving_hub/
├── 📁 backend/ # 백엔드 서비스 (Spring Boot 기반 MSA)
│ ├── 📁 user-service/ # 사용자 관리 서비스
│ ├── 📁 problem-service/ # 문제 풀이 관련 서비스
│ ├── 📁 blog-service/ # 기술 블로그 서비스
│ ├── 📁 ranking-service/ # 랭킹 시스템 서비스
│ ├── 📁 api-gateway/ # API Gateway (Spring Cloud Gateway)
│ ├── 📁 common/ # 공통 모듈
├── 📁 frontend/ # 프론트엔드 (React + TypeScript)
│ ├── 📁 src/
│ ├── 📁 components/
│ ├── 📁 pages/
│ ├── 📁 hooks/
├── 📁 infra/ # 인프라 구성 (Docker, Kubernetes)
│ ├── 📄 docker-compose.yml
│ ├── 📄 k8s-deployment.yaml
├── 📁 docs/ # 문서 및 API 명세
│ ├── 📄 API_SPEC.md
│ ├── 📄 SYSTEM_ARCH.md
├── 📄 README.md # 프로젝트 소개 문서
```

---

## 🏗️ 개발 로드맵 (Development Roadmap)
### **🔹 1️⃣ MVP (최소 기능 제품) - 1개월**
🔥 **목표: 기본적인 문제 풀이 공유 기능 구현**  
- [ ] **Backend:** `Spring Boot + MySQL` 기반 CRUD API 구현  
- [ ] **Frontend:** `React + TailwindCSS`로 UI 기본 화면 제작  
- [ ] **유저 인증 시스템** → JWT 기반 로그인 구현  
- [ ] **문제 풀이 업로드 기능** → REST API 개발  
- [ ] **Docker 컨테이너화** → `docker-compose`로 환경 구축  

### **🔹 2️⃣ 확장 (2~3개월)**
🔥 **목표: MSA로 분리 & Kafka 도입하여 확장성 고려**  
- [ ] **Backend MSA 전환** → `Spring Cloud`를 활용한 API Gateway 구축  
- [ ] **Kafka 적용** → 비동기 이벤트 처리 (예: 문제 추천 기능, 랭킹 시스템)  
- [ ] **Redis 캐싱 도입** → 빠른 조회 성능 개선  
- [ ] **프론트엔드 개선** → React 상태 관리 (Recoil/Zustand 활용)  
- [ ] **CI/CD 구축** → GitHub Actions + ArgoCD로 자동 배포  

### **🔹 3️⃣ 추가 기능 (3~6개월)**
🔥 **목표: 실제 서비스처럼 운영 가능하도록 기능 확장**  
- [ ] **실시간 채팅 (WebSocket) 추가**  
- [ ] **AI 기반 문제 추천 기능 (ML 모델 활용 가능)**  
- [ ] **Kubernetes 기반 클러스터링 & 배포 최적화**  

---

## 📜 API 명세 (API Documentation)
📌 API 문서는 [`docs/API_SPEC.md`](docs/API_SPEC.md)에서 확인할 수 있습니다.  
📌 시스템 아키텍처 설계는 [`docs/SYSTEM_ARCH.md`](docs/SYSTEM_ARCH.md)에서 확인할 수 있습니다.  

---

## 🛠️ 개발 환경 설정 (Setup)
### **1️⃣ 백엔드 실행**
```
bash
cd backend/
docker-compose up -d

```
### 2️⃣ 프론트엔드 실행
```
cd frontend/
npm install
npm start
```
## 📌 협업 및 기여 방법 (Contributing)
1. 레포지토리 클론 → git clone https://github.com/lirongzzuin/problem_solving_hub.git
2. Feature Branch 생성 → git checkout -b feature-branch
3. 개발 & 커밋 → git commit -m "새로운 기능 추가"
4. PR 요청 → main 브랜치로 Pull Request 제출


---

## **💡 최종 정리**
1️⃣ **MSA, Kafka, Redis 등 IT 기업에서 선호하는 기술을 적극 활용하는 프로젝트**  
2️⃣ **백엔드(Spring Boot) + 프론트엔드(React)까지 경험을 쌓을 수 있는 프로젝트**  
3️⃣ **확장 가능성을 고려한 로드맵 제공 → 기업이 관심을 가질만한 포트폴리오 프로젝트**  

