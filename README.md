# MSA_eureka_server

**msa-architecture-eureka-server**는 마이크로서비스 아키텍처(Microservices Architecture)에서 서비스 등록 및 검색을 관리하기 위한 Spring Cloud Eureka 서버입니다.

## 주요 기능

- 서비스 등록 및 검색
- 분산 환경에서의 서비스 디스커버리
- Spring Cloud Eureka 기반의 서비스 레지스트리 구현

## 기술 스택

- **언어**: Java
- **프레임워크**: Spring Boot, Spring Cloud Netflix Eureka

## 설치 및 실행

1. 저장소를 클론합니다:
   ```bash
   git clone https://github.com/kyungje/MSA_eureka_server.git
   ```
2. 프로젝트 디렉토리로 이동합니다:
   ```bash
   cd MSA_eureka_server
   ```
3. 필요한 의존성을 설치하고 애플리케이션을 실행합니다:
   ```bash
   ./mvnw spring-boot:run
   ```

## 사용 방법

1. 클라이언트 애플리케이션에서 Eureka 서버를 설정합니다.
   - `application.yml` 또는 `bootstrap.yml` 파일에서 Eureka 서버 URL을 추가합니다.
2. Eureka 대시보드를 통해 서비스 상태를 확인할 수 있습니다.
   - 기본적으로 [http://localhost:8761](http://localhost:8761)에서 대시보드에 접근할 수 있습니다.

## 기여

기여를 환영합니다! 이 프로젝트에 기여하려면 다음 단계를 따라주세요:

1. 이 저장소를 포크합니다.
2. 새로운 브랜치를 생성합니다:
   ```bash
   git checkout -b feature/새로운기능
   ```
3. 변경사항을 커밋합니다:
   ```bash
   git commit -m "추가: 새로운 기능 설명"
   ```
4. 브랜치를 푸시합니다:
   ```bash
   git push origin feature/새로운기능
   ```
5. Pull Request를 생성합니다.

## 라이센스

이 프로젝트는 MIT 라이센스를 따릅니다. 세부사항은 [LICENSE](LICENSE) 파일을 참조하세요.

## 참고 자료

- [Spring Cloud Eureka 공식 문서](https://spring.io/projects/spring-cloud-netflix)
- [마이크로서비스 아키텍처 개요](https://martinfowler.com/articles/microservices.html)
```
