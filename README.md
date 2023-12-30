# 게시판 구현하기

이 프로젝트는 간단한 게시판 API를 구현한 것으로, 사용자가 게시글을 생성, 조회, 수정, 삭제할 수 있는 기능을 제공합니다. Spring Boot와 JPA, QueryDSL을 이용하여 RESTful API를 구현하였으며, 데이터베이스로는 H2를 사용합니다.

## 기능

- **게시글 생성**: 사용자는 새로운 게시글을 생성할 수 있습니다.
- **게시글 조회**: 사용자는 모든 게시글 목록을 조회하거나 특정 게시글을 상세 조회할 수 있습니다.
- **게시글 수정**: 사용자는 자신의 게시글을 수정할 수 있습니다.
- **게시글 삭제**: 사용자는 자신의 게시글을 삭제할 수 있습니다.

## 기술 스택

- **Spring Boot**: 애플리케이션의 주요 프레임워크로 사용됩니다.
- **JPA(Hibernate)**: 객체 관계 매핑(ORM)을 위해 사용됩니다.
- **QueryDSL**: 복잡한 쿼리 및 동적 쿼리를 타입 안전하게 구성하기 위해 사용됩니다.
- **H2 Database**: 인메모리 데이터베이스로, 개발 및 테스트 용도로 사용됩니다.
- **Maven**: 의존성 관리 및 빌드 도구로 사용됩니다.
- **Lombok**: 반복되는 코드(예: getter, setter)를 줄이기 위해 사용됩니다.

## 시작하기

### 필수 조건

- JDK 1.8 이상
- Maven

### 실행 방법

1. **저장소 복제**: 
   ```sh
   git clone https://github.com/JamieJai/Project_BoardApi_Jamie.git
   ```

2. **애플리케이션 실행**: 
   ```sh
   cd Project_BoardApi_Jamie
   mvn spring-boot:run
   ```

## REST API

- **게시글 생성**: `POST /api/boards`
- **게시글 전체 조회**: `GET /api/boards`
- **게시글 상세 조회**: `GET /api/boards/{id}`
- **게시글 수정**: `PUT /api/boards/{id}`
- **게시글 삭제**: `DELETE /api/boards/{id}`

## 개발자

- Jamie Jai - [GitHub](https://github.com/JamieJai)
