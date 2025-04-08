# 김준형 (Jun Hyeong Kim)

## About Me
안녕하세요! 풀스택 개발자 김준형입니다.
백엔드 개발과 클라우드 인프라에 전문성을 가지고 있으며, 현재 [FREAM 프로젝트](https://www.pinjun.xyz/)를 개발 중입니다.

## Technical Skills

### Backend Development
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![JPA](https://img.shields.io/badge/-JPA-007396?style=flat-square&logo=hibernate&logoColor=white)
![Hibernate](https://img.shields.io/badge/-Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/-QueryDSL-4479A1?style=flat-square&logo=java&logoColor=white)
![WebSocket](https://img.shields.io/badge/-WebSocket-010101?style=flat-square&logo=socket.io&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)

### Frontend Development
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Database & Message Queue
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/-Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![H2 Database](https://img.shields.io/badge/-H2_Database-4169E1?style=flat-square&logo=h2-database&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/-Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)

### DevOps & Cloud Services
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-269539?style=flat-square&logo=nginx&logoColor=white)
![Github Actions](https://img.shields.io/badge/-Github_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Let's Encrypt](https://img.shields.io/badge/-Let's_Encrypt-003A70?style=flat-square&logo=let's-encrypt&logoColor=white)

### Development Tools
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/-IntelliJ_IDEA-000000?style=flat-square&logo=intellij-idea&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Gradle](https://img.shields.io/badge/-Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

## Projects

### 1. FREAM Project
**개발 기간:** 2024.12 ~ (진행중)  
**주요 기술:** Spring Boot 3.x, JPA, Hibernate, QueryDSL, MySQL, Redis, ElasticSearch, WebSocket, Kafka, React, Spring Security, JWT, Docker, Nginx, GitHub Actions  
**GitHub:** [Frontend](https://github.com/junhyeong9812/fream-front) | [Backend](https://github.com/junhyeong9812/fream-back)  
**배포 URL:** [www.pinjun.xyz](https://www.pinjun.xyz/)

**서비스:** 기존의 Kream 플랫폼을 분석하고 개선된 중고 거래 서비스를 제공하는 프로젝트

**주요 구현 기능:**
- **검색 최적화:** ElasticSearch의 멀티매치·오타 허용·동의어 기능으로 정교하고 빠른 검색·필터링 구현
- **캐싱 시스템:** Nginx의 Proxy Cache로 상품·스타일 목록을 캐싱하여 DB 부담 감소 및 응답 속도 개선
- **사용자 인증:** JWT와 Redis를 연계한 사용자 인증 및 토큰 관리, OAuth2.0 기반(구글·카카오·네이버) 소셜 로그인 연동
- **결제 시스템:** PortOne API를 통한 결제 및 환불 시스템 구축
- **배송 추적:** 택배사 웹 스크래핑을 통한 배송 상태 확인 자동화
- **입찰 시스템:** 실시간 구매/판매 입찰 시스템 구현
- **로그 처리:** Kafka를 통한 로그 수집으로 백엔드 서버 부하 분산
- **실시간 알림:** WebSocket을 통한 실시간 알림 기능 구현
- **보안 통신:** Let's Encrypt를 활용한 HTTPS 보안 통신 구현
- **컨테이너화:** Docker를 통한 서비스 컨테이너화 및 의존성 관리
- **자동화 배포:** GitHub Actions를 활용한 프론트엔드/백엔드 CI/CD 파이프라인 구축

### 2. 영어학습 도우미 프로젝트
**개발 기간:** 2025.03.12 ~ 2025.03.17  
**주요 기술:** Python 3.7+, Flask 2.0+, OpenAI API (GPT, Whisper), Coqui TTS, PyTorch, HTML5, CSS3, JavaScript  
**GitHub:** [Repository](https://github.com/junhyeong9812/fream-stt-tts)

**서비스:** 음성 인식(STT), 음성 합성(TTS), 언어 학습, 그리고 번역 기능을 제공하는 종합 웹 서비스

**주요 구현 기능:**
- **음성 인식(STT):** 영어 및 일본어 음성을 텍스트로 변환
- **음성 합성(TTS):** 영어 및 일본어 텍스트를 자연스러운 음성으로 변환
- **대화 학습:** 대화 응답과 함께 핵심 단어 추출 및 예시 문장 제공
- **번역 기능:** 한국어, 영어, 일본어 간 텍스트 번역
- **통합 채팅 인터페이스:** 텍스트 및 음성 입력 지원, 대화 기록 관리
- **어휘 학습 지원:** 대화에서 나온 주요 단어와 예문 제공
- **예시 응답 제안:** 학습자가 대화를 이어갈 수 있는 예시 응답 제시

### 3. Auction 프로젝트
**개발 기간:** 2025.01.23 ~ 2025.01.27  
**주요 기술:** Spring Boot 3.x, JPA, QueryDSL, H2 Database, Redis, WebSocket (STOMP, SockJS), Spring Security, JWT, PortOne API, Docker, Nginx  
**GitHub:** [Frontend](https://github.com/junhyeong9812/auction_front) | [Backend](https://github.com/junhyeong9812/auction_back)

**서비스:** 반려동물 경매 시스템을 구현한 프로젝트로, WebSocket과 Redis를 활용한 실시간 경매 진행, 결제 연동, HTTPS 환경 구축

**주요 구현 기능:**
- **경매 시스템:** 반려동물 경매 등록/수정/취소와 실시간 입찰 기능 구현
- **일정 관리:** 경매의 시작/마감 일정을 예약하고 스케줄러로 자동화
- **실시간 입찰:** WebSocket(STOMP + SockJS)을 통한 실시간 입찰 시스템 구현
- **입찰 연장:** 마감 3분 이내 입찰 발생 시 마감시간을 5분 연장하는 동적 마감 로직 구현
- **낙찰 처리:** 마감 시점에 자동으로 최고 입찰자를 낙찰자로 결정하는 로직 구현
- **데이터 관리:** Redis를 활용한 실시간 입찰 데이터 관리로 성능 최적화
- **사용자 인증:** JWT와 Redis 기반 인증/인가 시스템으로 토큰 기반 보안 구현
- **결제 시스템:** PortOne API 연동을 통한 안전한 결제 및 검증 시스템 구축
- **보안 환경:** Nginx와 Certbot을 활용한 HTTPS 환경 설정으로 안전한 통신 구현
- **컨테이너화:** Docker와 Docker Compose를 통한 서비스 배포 및 관리 자동화

### 4. Kream 클론 프로젝트
**개발 기간:** 2024.06 ~ 2024.08  
**주요 기술:** Spring Boot, JPA, React, Flask  
**참여 인력:** 7인  
**GitHub:** [Frontend](https://github.com/dlxodud123/fream_front) | [Backend](https://github.com/junhyeong9812/fream_back)

**서비스:** Kream 웹 사이트 기능을 직접 구현

**주요 구현 기능:**
- **프록시 활용:** 프록시를 통한 프론트와 백엔드 쿠키 관리
- **상태 관리:** 프로바이더 및 컨텍스트를 통한 프론트엔드 로그인 인증 상태 관리
- **결제 시스템:** 구매, 판매 페이지 백엔드 로직 구현 및 PortOne API와 연계한 실제 결제 메커니즘
- **관리자 기능:** 관리자 페이지 프론트엔드 및 백엔드 구현을 통한 운영자들을 위한 사용자 경험 개선
- **데이터 분석:** 사용자 접속 로그 수집 및 해당 로그를 토대로 시각화 그래프로 표현
- **보안 인증:** JWT토큰을 활용한 API 접근 권한 생성
- **클라우드 배포:** AWS를 통한 최종 빌드 배포

### 5. 협업 시스템 프로젝트
**개발 기간:** 2024.04 ~ 2024.04  
**주요 기술:** Node.js, JavaScript, HTML, CSS  
**참여 인력:** 6인  
**GitHub:** [Repository](https://github.com/junhyeong9812/ERP-Project)

**서비스:** Node.js를 통한 ERP 웹 사이트 구현

**주요 구현 기능:**
- **기능 통합:** 페이지 로딩 순서 관리(옵저버 패턴을 통한 로딩 순서 관리)
- **세션 관리:** 회원상태 코드 고도화 및 세션 관리를 통한 실시간 사용자 로그인 상태 관리
- **실시간 통신:** Socket.io를 통한 채팅 시스템 구현
- **데이터베이스 연동:** OracleCloud를 활용한 외부 DB 사용
- **커뮤니티 기능:** 게시판, 로그인 기능 구현
- **클라우드 배포:** 클라우드 시스템을 통한 웹 서버 배포

## Technical Expertise

### Spring Framework 및 백엔드 개발
- **Spring Boot:** 설정 자동화 및 RESTful 웹 애플리케이션 개발
- **Spring Data JPA:** 엔티티 매핑, Repository 인터페이스 활용, ORM 설계
- **Spring Security:** JWT 기반 인증 및 사용자 권한 관리
- **QueryDSL:** 동적 쿼리 생성 및 데이터 검색 최적화
- **JUnit:** 단위 테스트 및 통합 테스트 작성
- **WebSocket:** STOMP, SockJS를 활용한 실시간 경매 시스템, 알림 기능 구현
- **Hibernate:** ORM 프레임워크를 활용한 객체 매핑 및 영속성 관리
- **도메인 주도 설계(DDD):** 복잡한 비즈니스 로직을 도메인 중심으로 설계

### Node.js 및 Python
- **Node.js:**
  - ERP 웹 애플리케이션 개발
  - Socket.io로 구현한 실시간 채팅 기능 설계
- **Python:**
  - Flask: 경량 웹 애플리케이션 및 추천 시스템 구현
  - Pandas, NumPy, Scikit-learn: 데이터 분석 및 머신러닝 모델 개발
  - OpenAI API(GPT, Whisper): 자연어 처리 및 음성 인식 기능 구현
  - Coqui TTS: 텍스트를 음성으로 변환하는 시스템 구현

### 데이터베이스
- **Oracle / SQL Developer:** 데이터베이스 설계, 트랜잭션 처리, PL/SQL 작성
- **MySQL:** 데이터 설계 및 관리
- **Redis:** 사용자 토큰 정보를 저장하고 관리하기 위해 활용
- **ElasticSearch:** 검색 최적화, 멀티매치 검색, 오타 허용, 동의어 기능 구현
- **H2 Database:** 개발 및 테스트 환경에서의 인메모리 데이터베이스 활용

### 서버 및 네트워크
- **Linux:** CentOS, Ubuntu 기본 명령어 사용, DB 및 웹 서버 구성
- **Docker:** 서비스 컨테이너화 및 의존성 관리
- **Nginx:** 프록시 서버 설정, 캐싱 시스템 구현, 로드 밸런싱
- **Certbot:** Let's Encrypt를 활용한 HTTPS 환경 구축
- **Kafka:** 로그 수집 및 백엔드 서버 부하 분산 구현
- **GitHub Actions:** CI/CD 파이프라인 구축 및 자동화 배포

### 외부 API 연동 및 시스템 통합
- **PortOne API:** 결제 및 환불 시스템 구축
- **웹 스크래핑:** 택배사 배송 상태 확인 자동화
- **OAuth 2.0:** 소셜 로그인(구글, 카카오, 네이버) 연동

## GitHub Stats
[![GitHub stats](https://github-readme-stats.vercel.app/api?username=junhyeong9812&show_icons=true&theme=dracula)](https://github.com/junhyeong9812)

## Contact & Links
- Portfolio: [www.pinjun.xyz](https://www.pinjun.xyz/)
- Email: pickjog@naver.com
- GitHub: [@junhyeong9812](https://github.com/junhyeong9812)
