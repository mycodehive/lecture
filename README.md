# lecture

Fullstack 관련 자료
  - https://gamma.app/docs/-joxxaf8wg6nhth8

## 학습방향
<br>
기술 스택 (React + FastAPI + PostgreSQL)을 기반으로 학습할 수 있는 체계적이고 효율적인 커리큘럼을 다음과 같이 스터디합니다.

* * *

## 📌 **학습 목표**

- 프론트엔드에서 React로 사용자 인터페이스를 구성하고 API 통신 처리
- 백엔드에서 FastAPI로 RESTful API를 개발하고 관리
- PostgreSQL을 이용한 데이터베이스 모델링 및 연동
- 전체 서비스의 구조 설계 및 운영 방법 숙지 (배포, 관리 포함)

* * *

## ✅ **추천 학습 커리큘럼 (약 8주 과정 기준)**

아래와 같이 구성하면 기술별 기초부터 심화까지 빠르게 습득할 수 있습니다.

* * *

### 🚩 **Week 1-2: Front-End 기초 (React + TypeScript)**

1. **JavaScript & ES6 기초 복습 (필요 시)**
    - 기본 문법, 함수형 프로그래밍, 비동기 처리(Promise, async/await)

2. **React 기본 개념**
    - JSX, 컴포넌트 개념 (함수형 컴포넌트)
    - props, state 관리(useState, useEffect, useRef 등)
    - React Router로 화면 전환 처리

3. **TypeScript 소개 및 적용**
    - TypeScript 기초 및 타입 개념 (interface, type, generics)
    - React 프로젝트에 TypeScript 적용 방법

4. **REST API 연동 (axios 또는 fetch)**
    - 백엔드 API를 호출하고 데이터 처리하는 방법 학습

**학습 자료 추천:**

- [React 공식문서](https://react.dev/)
- [TypeScript 공식 문서](https://www.typescriptlang.org/)
- React Tutorial (FreeCodeCamp)

* * *

### 🚩 **Week 3-4: Back-End 기초 (FastAPI + Python)**

1. **Python 기초 복습 (필요 시)**
    - 비동기 프로그래밍(async/await), 타입 힌트

2. **FastAPI 기본 개념**
    - FastAPI 프로젝트 환경 설정 (venv, requirements.txt)
    - 기본 API 작성법(GET, POST, PUT, DELETE)
    - Pydantic을 이용한 데이터 유효성 검증 및 스키마 작성

3. **FastAPI와 데이터베이스 연동(SQLAlchemy)**
    - ORM 개념 및 CRUD 작업 처리
    - 비동기 DB 처리(asyncpg, SQLAlchemy-async)

4. **Swagger(OpenAPI)를 이용한 자동 API 문서화**

**학습 자료 추천:**

- FastAPI 공식문서
- FastAPI Tutorial - 공식문서 튜토리얼
- SQLAlchemy 공식 문서

* * *

### 🚩 **Week 5: PostgreSQL 기초 및 심화**

1. **PostgreSQL 설치 및 환경 구성**
    - 로컬 환경에서 DB 생성 및 관리 (pgAdmin 또는 DBeaver)

2. **SQL 기초 학습**
    - 기본 쿼리(SELECT, INSERT, UPDATE, DELETE), JOIN 연산 이해

3. **고급 기능**
    - JSONB, 부분 인덱스, 트랜잭션, 인덱스 최적화 방법 등

4. **FastAPI와 PostgreSQL 통합 실습**
    - 데이터 모델링 실습 (관계형 모델 설계)

**학습 자료 추천:**

- [PostgreSQL 공식문서](https://www.postgresql.org/docs/)
- PostgreSQL 튜토리얼 (TutorialsPoint)

* * *

### 🚩 **Week 6: Front-End & Back-End 통합 실습**

1. **FastAPI-React 전체 구조 연결 실습**
    - 실제 앱의 구조처럼 API 연동 및 통합 프로젝트 제작

2. **JWT 기반 인증 처리**
    - 로그인/회원가입 구현 및 관리 방법 학습

3. **API 에러처리 및 예외처리**
    - 예외 처리 로직 작성 및 상태 코드 관리 방법

**추천 실습 프로젝트:**

- Todo 리스트 앱 (CRUD, 인증, DB 활용 실습에 좋음)
- 간단한 게시판 앱 제작

* * *

### 🚩 **Week 7: 배포 및 CI/CD 환경 구성**

1. **AWS Lightsail 기반 환경 설정**
    - 서버 설정 (Ubuntu 서버 환경 구축)
    - Nginx 리버스 프록시 설정 및 HTTPS 적용 (Certbot)

2. **Docker와 GitHub Actions를 이용한 CI/CD**
    - Docker 컨테이너 제작
    - GitHub Actions로 자동 배포 처리 실습

3. **환경 변수 관리 및 보안 고려**

**학습 자료 추천:**

- Docker 공식문서
- [GitHub Actions 공식문서](https://docs.github.com/ko/actions)

* * *

### 🚩 **Week 8: 심화 및 최적화**

1. **성능 모니터링 및 최적화**
    - 백엔드 API 성능 최적화 (비동기 처리, 캐싱)
    - 프론트엔드 최적화 (코드 스플리팅, 캐싱 전략 등)

2. **테스트 코드 작성**
    - React 테스트(Jest, React Testing Library)
    - FastAPI 테스트 (Pytest)

3. **확장성 및 아키텍처 설계 실습**
    - REST API 설계의 고급 주제 (리소스 구조, 에러 처리)

* * *

## 🔧 **최종 목표 (학습 후 성과물)**

- React + FastAPI + PostgreSQL을 활용한 풀스택 앱 제작
- JWT 인증과 RESTful API 구현 및 배포 경험
- Docker 및 GitHub Actions를 이용한 CI/CD 경험

* * *

## 📌 **학습 체크리스트**

| 주차  | 주요 목표 |
| --- | --- |
| 1~2주 | React, TypeScript 기초 및 API 연결 실습 |
| 3~4주 | FastAPI 기초 및 DB 연동 실습 |
| 5주  | PostgreSQL 기초 및 데이터 모델링 |
| 6주  | 프론트-백엔드 통합 앱 구현 (CRUD+인증) |
| 7주  | AWS 배포 및 Docker, CI/CD 구성 |
| 8주  | 성능 최적화 및 테스트 코드 작성 |
