# 👋 About Me
**문제의 본질을 찾을 때까지 멈추지 않는 개발자, 박신영입니다!**

---

## 🏅 Competitions & Experiences

### 🏆 수상 및 활동
- **2025.11** SSAFY 자율프로젝트 부울경 우수상 (3등)
  - ┗ AI 기반 GitHub 개인 맞춤형 멘토링 플랫폼 개발
- **2025.09** SSAFY 빅데이터 특화 프로젝트 부울경 우수상 (2등)
  - ┗ KNN 알고리즘 기반 와인 추천 챗봇 서비스 개발
- **2025.08** SSAFY 웹기술 프로젝트 부울경 우수상 (3등)
  - ┗ 1:1 영상통화 팬사인회 플랫폼 개발
 
---

### 📚 자격증
- **2025** SQL 개발자(SQLD) 취득
- **2025** 데이터분석 준전문가(ADsP) 취득
- **2024** 컴퓨터활용능력 1급
- **2022** 정보처리기사 취득
- **2025** TOEIC Speaking IH

---

### 🎓 학력 및 교육
- **2025.01 ~ 2025.12** SSAFY 삼성 청년 SW 아카데미 13기 수료
- **2018.03 ~ 2024.02** 경상국립대학교 조경학과 학사 졸업
  - ┗ 2021 영남지역 조경학과 연합 졸업작품전 영남지회장상 수상
  - ┗ 제12회 대한민국 도시숲 설계 공모대전 우수상 수상
  - ┗ 제17회 한국농촌계획대전 특선 수상
 
---

### 📖 활동
- **CS 북스터디** '한 권으로 읽는 컴퓨터 구조와 프로그래밍' (주 1회, 세미나 형식)

---

## 🛠 Tech Stack

### Languages
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### Backend & API
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-0078D4?style=flat-square&logo=spring&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

### Database / Cache
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00ADD8?style=flat-square&logo=meta&logoColor=white)

### AI/ML
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Upstage](https://img.shields.io/badge/Upstage-FF6B35?style=flat-square&logo=artificial-intelligence&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=flat-square&logo=databricks&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-306998?style=flat-square&logo=python&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Frontend & Other
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

---

## 📂 Portfolio
👉 [박신영 포트폴리오 바로가기](https://shin-yeong-portfolio.notion.site/2b889e209a1e807aafe8f)

---

## 🧩 Projects

### 🤖 AI 기반 GitHub 개인 맞춤형 멘토링 플랫폼 (Coditor)

> 개발자의 하루를 자동으로 성장 기록으로 바꾸는 AI 기반 GitHub 개인 맞춤형 멘토링 플랫폼입니다.  
> GitHub 활동 데이터를 수집·분석하여 기술 스택, 코딩 습관, 숙련도를 자동으로 평가하고,  
> TIL, TSL, 포트폴리오를 자동 생성하며 LangGraph 멀티 에이전트 아키텍처를 활용한 맞춤형 챗봇을 제공합니다.

**기간**: 2025.10.10 ~ 2025.11.20 (6주) | **역할**: 백엔드 개발

**핵심 기여**:
- RabbitMQ 메시지 큐 도입으로 회원가입 응답 지연 문제 해결 (비동기 처리 아키텍처)
- GitHub REST API → GraphQL 전환으로 API 호출 N+1 → 1로 최적화
- DB 제약조건 + 예외 재시도 로직으로 Lock 없는 동시성 제어 구현
- n8n 기반 자동 코드 리뷰 파이프라인 구축 (Gemini 2.5 Flash 활용)

**Tech**: `Spring Boot` `JPA` `QueryDSL` `ElasticSearch` `FastAPI` `LangChain` `LangGraph` `OpenAI` `RabbitMQ` `MySQL` `Redis` `Docker` `Jenkins`

👉 [GitHub](https://github.com/ParkShinyeong/coditor)

---

### 🎤 1:1 영상통화 팬사인회 플랫폼 (muse:eume)

> KPOP 아티스트와 팬들을 위한 1:1 영상통화 서비스입니다.  
> 팬들이 대기실 → 아티스트 1 → 아티스트 2 → ... → 아티스트 N 순으로 자동 이동하며,  
> 실시간 동시 촬영 및 웃음 탐지 자동 사진 촬영 기능을 제공하고, 포토북으로 영상과 사진을 다시 볼 수 있습니다.

**기간**: 2025.07.14 ~ 2025.08.25 (6주) | **역할**: 백엔드 개발

**핵심 기여**:
- 3-Plane 아키텍처 설계로 폐쇄 루프 기반 매칭 시스템 구축 (Controller/Execution/Feedback)
- OpenVidu 서버 통신 시 발생한 Deadlock 완전 해결 (책임 분리 원칙 + 락 최소화)
- SSE 연결 불안정 문제 해결 (Zustand 전역 상태 관리 도입)
- 녹화 파일 단계별 처리 전략으로 세션 전환 지연 제거

**Tech**: `Spring Boot` `MySQL` `Redis` `OpenVidu` `AWS S3` `Docker` `Jenkins` `React.js` `TypeScript`

👉 [GitHub](https://github.com/muse-eum) | [시연 영상](https://www.youtube.com/watch?v=2Omm0dsWzg4)

---

### 🍷 사용자 맞춤형 와인 추천 챗봇 (Wind up)

> 사용자의 상황, 분위기, 맛 등의 자연어 입력에서 키워드를 추출해 와인을 추천하는 챗봇 서비스입니다.  
> KNN 알고리즘과 OpenAI를 활용해 사용자 자연어의 의미와 분위기를 모두 반영한 와인 추천을 제공하며,  
> 추천 와인과 어울리는 음식 페어링 정보도 함께 확인할 수 있습니다.

**기간**: 2025.08.25 ~ 2025.09.29 (6주) | **역할**: 백엔드 개발

**핵심 기여**:
- KNN 추천 알고리즘 성능 20배 향상 (평균 유사도 0.02 → 0.45, 자기 추천 정확도 98%)
- LLM 기반 3단계 의도 분류 시스템 구현 (와인 추천 / 일상 대화 / 조건 검색)
- 가격/도수 필터링 단계 분리로 조건 반영 정확도 개선
- Spring Boot ↔ FastAPI 마이크로서비스 아키텍처 설계

**Tech**: `Spring Boot` `MySQL` `Redis` `FastAPI` `OpenAI` `FAISS` `KNN` `Docker` `Jenkins` `Vue.js`

👉 [GitHub](https://github.com/wind-kimchijjim/wind-up)

---

### 🗺️ 다국어 비자 안내 AI 챗봇 (naVISAtion)

> 복잡한 한국 비자 및 체류 관련 정보를 외국인들이 쉽게 이해할 수 있도록 돕는 RAG 기반 AI 챗봇 서비스입니다.  
> 하이코리아 매뉴얼(.hwp) 공식 문서를 기반으로 5개 국어 지원 챗봇을 구축하였으며,  
> DeepL API를 활용한 다국어 파이프라인과 RAGAS 지표를 활용한 답변 정확도 검증을 구현했습니다.

**기간**: 2025.06.30 ~ 2025.07.04 (1주) | **역할**: AI 개발

**핵심 기여**:
- RAG 파이프라인 구축 (Solar Pro & Embedding + FAISS 벡터 스토어)
- 표 데이터 Markdown 변환 + 2단계 청킹 전략으로 의미 연속성 확보
- RAGAS 기반 정량 평가로 정확도 대폭 개선 (Precision 0.57→0.83, Recall 0.89→1.00)
- DeepL API 활용 다국어 파이프라인 구현 (5개 국어 지원)

**Tech**: `Python` `FastAPI` `LangChain` `FAISS` `Upstage Solar Pro` `RAGAS` `DeepL API` `PDFMiner` `pdfplumber`

👉 [GitHub](https://github.com/oyaa52/navisation)

---

## 📫 Contact

- **Email**: syngh503@gmail.com
- **GitHub**: [@ParkShinyeong](https://github.com/ParkShinyeong)

---

<div align="center">
  
**더 나은 질문을 던지고, 더 깊은 답을 찾겠습니다.**

</div>
