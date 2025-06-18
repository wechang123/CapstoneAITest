# DanParking Backend

Spring Boot 기반의 주차장 관리 시스템 백엔드 서버입니다.

## 주요 기능
- 사용자 인증 및 계정 관리
- 주차장 정보 조회 및 관리
- 주차 공간 상태 관리
- 즐겨찾기 주차장 관리
- REST API 제공

## 실행 방법

### 1. 개발 환경 설정
- Java 11 이상
- Gradle 7.x

### 2. 데이터베이스 설정
- application.properties에서 데이터베이스 연결 정보 설정
- 기본값으로 H2 데이터베이스가 설정되어 있음

### 3. 실행
```bash
# gradle 빌드
./gradlew build

# 서버 실행
./gradlew bootRun
```

### 4. API 접근
- 기본 포트: 8080
- Swagger UI: http://localhost:8080/swagger-ui.html (설정된 경우)

## 의존성
- Spring Boot 2.7.x
- Spring Security
- Spring Data JPA
- H2 Database
- JWT 인증 