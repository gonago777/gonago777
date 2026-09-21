# Backend Developer

Java와 Spring Boot를 중심으로 **REST API, 인증/인가, 데이터 저장, 외부 API 및 AI 서버 연동**을 구현해왔습니다.  
기능 구현에 그치지 않고, **Controller → Service → Client**처럼 역할을 분리하고 서비스 간 데이터 흐름을 명확하게 만드는 백엔드 구조에 관심이 있습니다.

---

## Main Projects

### RanDi — RFP 제안서 지원 시스템

조달 공고 분석부터 유사 RFP 검색, PPT 생성, 발표 스크립트 생성까지 이어지는 서비스입니다.

```text
React
  ↓
Spring Boot
  ↓
FastAPI
  ↓
MySQL / Redis
```

**Backend**
- Java 17, Spring Boot 3.5.9
- Spring Security, Spring Data JPA
- MySQL, Redis, JWT
- Spring Boot ↔ FastAPI 연동
- Controller → Service → FastApiClient 구조 분리
- Redis 기반 이메일 인증
- JWT Logout Blacklist 처리
- 외부 API 연동 및 WebClient 오류 처리

**Service Flow**
1. 공고 분석
2. 유사 RFP 검색
3. PPT 생성
4. 발표 스크립트 생성

**Repositories**
- [Backend](https://github.com/Bigproject-09/backend)
- [Frontend](https://github.com/Bigproject-09/frontend)
- [AI / Modeling](https://github.com/Bigproject-09/modeling)

---

### KT Library Website

React 기반 도서 관리 웹 클라이언트로, 백엔드 REST API와 연동하여 도서 및 사용자 기능을 제공합니다.

**Tech**
- React 19
- Vite
- Axios
- React Router
- MUI / Emotion

**Features**
- 회원가입 / 로그인 / 로그아웃 / 세션 확인
- 도서 조회 · 등록 · 수정 · 삭제
- 댓글 · 좋아요 · 찜
- AI 표지 생성 API 연동
- AWS CodeBuild용 `buildspec.yml` 구성

**Repository**
- [kt_library-website-repo](https://github.com/gonago777/kt_library-website-repo)

---

## Tech Stack

### Backend
Java · Spring Boot · Spring Security · Spring Data JPA · REST API

### Database / Auth
MySQL · Redis · JWT

### Integration
FastAPI · WebClient · Axios · External API

### Frontend
React · JavaScript · Vite

### Infra / Tools
AWS CodeBuild · Git · GitHub · Gradle · Postman

---

## Development Focus

- 역할을 분리한 백엔드 계층 구조
- 인증/인가와 사용자 상태 관리
- DB와 Redis를 활용한 데이터 관리
- 프론트엔드 · 백엔드 · AI 서버 간 API 연동
- 외부 API 오류와 서버 간 통신 실패를 고려한 예외 처리
- 실제 동작 흐름을 추적하기 쉬운 코드 구조
