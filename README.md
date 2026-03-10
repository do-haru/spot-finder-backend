# 실행 가이드

## 환경 요구사항

- Java 21
- Gradle
- Spring Boot 3.5.11
- PostgreSQL

## 실행 방법

```bash
git clone https://github.com/do-haru/spot-finder-backend.git
cd spot-finder-backend
./gradlew bootRun
```

서버 실행 후 브라우저에서 접속

```
http://localhost:8080
```

Windows 환경에서는 다음 명령어를 사용할 수 있습니다.

```bash
gradlew.bat bootRun
```

## 디렉토리 구조

```
spot-finder-backend
├─ src
│  ├─ main
│  │  ├─ java
│  │  │  └─ com
│  │  │     └─ doharu
│  │  │        └─ spotfinder
│  │  │           └─ SpotFinderApplication.java
│  │  └─ resources
│  │     └─ application.properties
│  └─ test
│
├─ build.gradle
├─ settings.gradle
├─ gradlew
├─ gradlew.bat
└─ README.md
```

디렉토리 설명

- src : 애플리케이션의 소스 코드
- main : 실제 애플리케이션 코드
- test : 테스트 코드
- resources : 설정 파일 및 리소스 파일
- build.gradle : Gradle 빌드 설정 파일