# 기본 개념

### 1. 백엔드 개발이란?
- 사용자와 직접상호 작용하지 않는 서버측면을 다루는 기술을 말하는 것으로 데이터베이스, 네트워크, API등을 포함한 기능들을 담당한다.

### 2. RESTful API란?
- #### Representational State Transfer: 웹 서비스의 아키텍쳐 스타일 중 하나이다.
    > 1. **Client-Server Architecture** : 클라이언트와 서버는 독립적 일 것
    > 2. **Stateless : 
    > 3. **Cacheable
    > 4. **Uniform Interface
    > 5. **Layered System
    > 6. **Code on Demand (optional)
- #### 예시코드
    > - GET '/users'
    > - POST '/users'
    > - GET '/users/{id}'
    > - PUT '/users/{id}'
    > - DELETE '/users/{id}'

### 3. HTTP 요청 메서드의 차이점
- **GET**: 서버로부터 정보를 조회하는 데 사용합니다.
- **POST**: 서버로 데이터를 전송해 리소스를 생성하는 데 사용합니다.
- **PUT**: 서버의 리소스를 업데이트할 때 사용합니다.
- **DELETE**: 서버의 리소스를 삭제할 때 사용합니다.

### 4. 데이터베이스와 DBMS의 차이
- **데이터베이스**: 데이터를 저장하는 구조화된 공간입니다.
- **DBMS (Database Management System)**: 데이터베이스의 데이터를 관리, 조작할 수 있는 시스템입니다.

### 5. SQL과 NoSQL의 차이점
- **SQL**: 관계형 데이터베이스에서 사용하는 구조화된 쿼리 언어입니다.
- **NoSQL**: 비관계형 데이터베이스에서 사용되며, 유연한 스키마를 가지고 있습니다.

### 6. CRUD 연산
- **Create**: 데이터 생성
- **Read**: 데이터 조회
- **Update**: 데이터 수정
- **Delete**: 데이터 삭제
<br><br><br><br>

# 데이터베이스

### 1. 인덱스의 역할
- 인덱스는 데이터베이스에서 데이터 검색 속도를 향상시키기 위해 사용됩니다.

### 2. JOIN 연산의 종류
- **Inner Join**: 두 테이블의 교집합을 반환합니다.
- **Outer Join**: 한 테이블의 모든 데이터와 다른 테이블의 일치하는 데이터를 반환합니다.

### 3. 트랜잭션과 ACID 속성
- **트랜잭션**: 데이터베이스의 안전한 작업을 보장하기 위한 작업 단위입니다.
- **ACID**: Atomicity, Consistency, Isolation, Durability의 약자로, 트랜잭션의 안전을 보장합니다.

### 4. 데이터베이스 정규화
- 데이터 중복을 최소화하고 데이터 무결성을 유지하기 위해 데이터베이스를 구조화하는 과정입니다.
<br><br><br><br>

# 서버와 네트워크

### 1. 서버와 클라이언트의 차이점
- **클라이언트**: 서비스를 요청하는 주체입니다.
- **서버**: 서비스를 제공하는 주체입니다.

### 2. 웹 서버와 애플리케이션 서버의 차이
- **웹 서버**: 정적 컨텐츠를 처리합니다.
- **애플리케이션 서버**: 동적 컨텐츠를 처리합니다.

### 3. 로드 밸런싱
- 서버에 들어오는 요청을 균등하게 분배하여 처리하는 기술입니다.

### 4. CORS (Cross-Origin Resource Sharing)
- 다른 도메인 간의 자원 공유를 가능하게 하는 보안 메커니즘입니다.
<br><br><br><br>

# 개발 및 배포

### 1. CI/CD
- **CI (Continuous Integration)**: 지속적인 통합을 의미합니다.
- **CD (Continuous Deployment)**: 지속적인 배포를 의미합니다.

### 2. Docker
- 컨테이너 기술을 사용하여 애플리케이션을 패키징하고 배포하는 오픈소스 플랫폼입니다.

### 3. 웹 애플리케이션 배포 과정
- 코드 작성 후 빌드, 테스트를 거쳐 프로덕션 서버에 배포하는 일련의 과정을 의미합니다.

### 4. JWT (Json Web Token)
- 서버와 클라이언트 간 인증에 사용되는 토큰 기반의 인증 방식입니다.
<br><br><br><br>

# 성능 및 보안

### 1. 서버 성능 최적화 방법
- 로드 밸런싱, 캐싱, 자원 할당 조정 등을 통해 서버 성능을 최적화할 수 있습니다.

### 2. 웹 애플리케이션 보안 강화
- XSS, SQL Injection 등의 공격을 방지하기 위해 다양한 보안 조치를 적용할 수 있습니다.
