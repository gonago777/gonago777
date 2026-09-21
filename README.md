# Backend Developer

Java와 Spring Boot를 중심으로 백엔드 개발을 학습하고 프로젝트를 구현하고 있습니다.  
REST API, 인증/인가, DB 연동, 외부 API 및 AI 서버 연동처럼 서비스의 흐름을 연결하는 백엔드 개발에 관심이 있습니다.

## Main Projects

### RanDi — RFP 제안서 지원 시스템
조달 공고 분석부터 유사 RFP 검색, PPT 생성, 발표 스크립트 생성까지 이어지는 서비스입니다.

- **Backend:** Java 17, Spring Boot 3.5.9, Spring Security, Spring Data JPA
- **Database / Auth:** MySQL, Redis, JWT
- **Integration:** Spring Boot ↔ FastAPI 연동
- **주요 구조:** Controller → Service → FastApiClient
- **주요 흐름:** 공고 분석 → 유사 RFP 검색 → PPT 생성 → 발표 스크립트 생성

Repositories:
- [Backend](https://github.com/Bigproject-09/backend)
- [Frontend](https://github.com/Bigproject-09/frontend)
- [AI / Modeling](https://github.com/Bigproject-09/modeling)

### KT Library Website
React 기반 도서 관리 웹 클라이언트입니다.

- React 19, Vite, Axios, React Router
- 회원가입 / 로그인 / 세션 확인
- 도서 조회·등록·수정·삭제
- 댓글, 좋아요, 찜 기능
- AI 표지 생성 API 연동
- AWS CodeBuild용 `buildspec.yml` 구성

Repository:
- [kt_library-website-repo](https://github.com/gonago777/kt_library-website-repo)

## Tech Stack

**Backend**  
Java · Spring Boot · Spring Security · Spring Data JPA · REST API

**Database / Auth**  
MySQL · Redis · JWT

**Frontend**  
React · JavaScript · Vite · Axios

**AI / Integration**  
FastAPI · Python · External API Integration

**Infra / Tools**  
AWS · Git · GitHub · Gradle · Postman

## What I Focus On

- 계층을 분리한 백엔드 구조 설계
- 프론트엔드와 AI 서버 사이의 API 흐름 연결
- 인증/인가와 데이터 저장 흐름 구현
- 외부 서비스 장애와 API 오류를 고려한 연동 구조 개선
