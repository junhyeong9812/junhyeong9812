## 김준형 | Backend Developer

> **다양한 기능과 이론을 추상화 수준에서 빠르게 익히고, 필요한 순간에는 딥다이브로 동작 원리까지 파고드는 개발자입니다.**  
> "이건 어떻게 동작하는가"라는 질문으로 직접 구현하고 실험하며 문제를 개선하고 해결합니다.  
> 필요한 도구는 가져와 공부하고 그 원리를 탐구해 사용하며, 쓰임에 비해 너무 크다면 직접 만듭니다.

---

## 🌐 오픈소스 기여

프레임워크 소스를 코드 레벨로 분석·문서화하는 과정([react-ko-docs](https://github.com/junhyeong9812/react-ko-docs) · [spring-framework-ko-docs](https://github.com/junhyeong9812/spring-framework-ko-docs) · [spring-security-ko-docs](https://github.com/junhyeong9812/spring-security-ko-docs))에서 발견한 정확성(correctness) 문제를 업스트림에 제안합니다. 각 PR은 실패하는 재현 테스트(red) → 수정 통과(green)로 검증합니다.

<ul>
  <li>
    <a href="https://github.com/react/react">react/react</a> — React ·
    <a href="https://github.com/react/react/pulls?q=is%3Apr+author%3Ajunhyeong9812">PR 목록</a> ·
  </li>
  <li>
    <a href="https://github.com/elastic/elasticsearch">elastic/elasticsearch</a> — Elasticsearch ·
    <a href="https://github.com/elastic/elasticsearch/pulls?q=is%3Apr+author%3Ajunhyeong9812">PR 목록</a> ·
  </li>
  <li>
    <a href="https://github.com/spring-projects/spring-security">spring-projects/spring-security</a> — Spring Security ·
    <a href="https://github.com/spring-projects/spring-security/pulls?q=is%3Apr+author%3Ajunhyeong9812">PR 목록</a> ·
  </li>
  <li>
    <a href="https://github.com/spring-projects/spring-framework">spring-projects/spring-framework</a> — Spring Framework ·
    <a href="https://github.com/spring-projects/spring-framework/pulls?q=is%3Apr+author%3Ajunhyeong9812">PR 목록</a> ·
  </li>
</ul>

---

## 📂 Project History

각 프로젝트는 하나의 질문에서 시작했습니다. 카테고리별로 정리한 전체 기록입니다.

### 🛠 라이브러리 · 도구

직접 만들어 배포·사용 중인 것들

| 프로젝트 | 설명 |
|---|---|
| [streamix](https://github.com/junhyeong9812/streamix) | 파일 업로드 서버 라이브러리 (Maven 배포) |
| [streamix-example](https://github.com/junhyeong9812/streamix-example) | streamix를 사용한 파일 서비스 예제 |
| [elastic-query-builder](https://github.com/junhyeong9812/elastic-query-builder) | Java용 Elasticsearch 쿼리 빌더 |
| [python-elastic-query-builder](https://github.com/junhyeong9812/python-elastic-query-builder) | Python Elasticsearch 쿼리 빌더 (PyPI 배포) |
| [perf-pilot](https://github.com/junhyeong9812/perf-pilot) | Web Vitals·네트워크·FPS·메모리·React 리렌더·CSS 검사를 실시간 측정하는 크롬 익스텐션 (MV3) |
| [claude-code-harness](https://github.com/junhyeong9812/claude-code-harness) | Claude Code 작업 하네스 — 정의→계획→개발→검증→기록 파이프라인 규칙·훅·템플릿 |

### 🔍 내부 동작 해부 — "이건 어떻게 동작하는가?"

프레임워크·미들웨어의 내부를 직접 구현하거나 흐름을 추적한 프로젝트

| 프로젝트 | 설명 |
|---|---|
| [winter](https://github.com/junhyeong9812/winter) | Spring MVC 구조를 직접 구현하는 경량 웹 프레임워크 — DispatcherServlet·HandlerMapping·ViewResolver 단계별 구현 |
| [JavaServerArchitectures](https://github.com/junhyeong9812/JavaServerArchitectures) | 순수 자바로 구현하는 3가지 HTTP 서버 아키텍처 비교 |
| [db-engine-lab](https://github.com/junhyeong9812/db-engine-lab) | DB 내부 구조(저장·인덱스·트랜잭션)를 Kotlin/JVM으로 직접 구현 |
| [xunit](https://github.com/junhyeong9812/xunit) | 언어별 xUnit 테스트 프레임워크 직접 구현 (Rust 외) |
| [orm](https://github.com/junhyeong9812/orm) | JPA·MyBatis·QueryDSL 비교 분석 + 5개 DB Docker 실습 — 데이터 접근 기술 벤치마크 |
| [springflow](https://github.com/junhyeong9812/springflow) | Spring Boot 자동 설정을 걷어내고 MVC 요청 처리 흐름을 수동 구성으로 추적 |
| [fastapi-flow](https://github.com/junhyeong9812/fastapi-flow) | FastAPI의 요청 흐름·미들웨어·예외 처리를 Spring MVC 구조에 대응시켜 실험 |
| [di-ioc](https://github.com/junhyeong9812/di-ioc) | DI/IoC는 왜 필요한가 — 컨테이너 동작 원리 학습 |
| [python-di-container](https://github.com/junhyeong9812/python-di-container) | 파이썬 의존성 주입 컨테이너 동작 구조화 |
| [spring-architecture](https://github.com/junhyeong9812/spring-architecture) | 스프링 아키텍처 내부 구조 학습 |
| [fastapi-architecture](https://github.com/junhyeong9812/fastapi-architecture) | FastAPI 아키텍처 철학 학습 |
| [code-storage-server](https://github.com/junhyeong9812/code-storage-server) | Rust로 Git을 무의존 재구현한 독립 VCS — 자체 CLI(`cts`)·서버·JWT 인증/협업자 인가·push 빌드 자동 트리거 (헥사고날 4크레이트) |
| [ide](https://github.com/junhyeong9812/ide) | Java & Python IDE는 어떻게 만들어지는가 |
| [process_thread](https://github.com/junhyeong9812/process_thread) | 프로세스·스레드의 생명주기·동기화·스케줄링을 Java로 구현하고 관찰 |
| [Gatekeeper](https://github.com/junhyeong9812/Gatekeeper) | IAM(인증·인가) 핵심 메커니즘 직접 구현 — **진행예정** (설계 문서 단계) |
| [Reverse-ETL](https://github.com/junhyeong9812/Reverse-ETL) | DW→운영 시스템 역ETL 파이프라인 직접 구현 (Java 25 / Spring Boot 4.0) — **진행예정** (설계 문서 단계) |
| [Cluster-Simulator](https://github.com/junhyeong9812/Cluster-Simulator) | 한 대의 PC에서 클러스터링 핵심 원리(Fan-out/Fan-in) 실험 — **진행예정** (설계 문서 단계) |

### ⚗️ 실험 · 벤치마크

가설을 세우고 직접 돌려서 확인한 것들

| 프로젝트 | 설명 |
|---|---|
| [sync-async-lab](https://github.com/junhyeong9812/sync-async-lab) | 동기 vs 비동기 통신 가설 실험 |
| [redis-atomicity-lab](https://github.com/junhyeong9812/redis-atomicity-lab) | Redis Lua 스크립트를 통한 원자성 보장 실험 |
| [acid-Lab-](https://github.com/junhyeong9812/acid-Lab-) | 트랜잭션 ACID 속성 실험 — **진행중** |
| [spring-cache-lab](https://github.com/junhyeong9812/spring-cache-lab) | Spring 캐시 동작 실험 |
| [proto-bench](https://github.com/junhyeong9812/proto-bench) | gRPC vs HTTP 비교 분석 (Kotlin) |
| [spring-performance-benchmark](https://github.com/junhyeong9812/spring-performance-benchmark) | Spring MVC vs WebFlux 부하 테스트 |
| [Network-Timeout-Experiment](https://github.com/junhyeong9812/Network-Timeout-Experiment) | 네트워크 타임아웃 동작 실험 |
| [thread-scheduler-test](https://github.com/junhyeong9812/thread-scheduler-test) | Manual Thread+Sleep vs ScheduledExecutorService 비교 |
| [mongo-es-search-benchmark](https://github.com/junhyeong9812/mongo-es-search-benchmark) | MongoDB vs Elasticsearch 검색 성능 벤치마크 |
| [distributed-log-pipeline](https://github.com/junhyeong9812/distributed-log-pipeline) | 분산처리 vs 단일 DB 처리 벤치마크 |
| [overload](https://github.com/junhyeong9812/overload) | 자바 부하 테스트용 웹사이트 |
| [react-next](https://github.com/junhyeong9812/react-next) | React vs Next.js 차이점 비교 |
| [sorting-and-graph](https://github.com/junhyeong9812/sorting-and-graph) | 정렬·그래프 알고리즘 구현 및 비교 |

### 🏗 도메인 · 서비스 구현

설계부터 구현까지 — 실서비스 형태의 프로젝트

| 프로젝트 | 설명 |
|---|---|
| [erp](https://github.com/junhyeong9812/erp) | Java Spring & TypeScript 물류 도메인 ERP |
| [fream-back](https://github.com/junhyeong9812/fream-back) | KREAM 스타일 리셀 커머스 백엔드 — Kafka CQRS·ES(Nori)·결정적 암호화·CI/CD 운영. 2026 Spring Modulith 리팩토링(경계 강제·FK→ID/이벤트 디커플링·trade 매칭+CAS) 진행 중 |
| [VulnScope](https://github.com/junhyeong9812/VulnScope) | 자동 모의해킹·취약점 점검 SaaS — 학습용이지만 실서비스 표준으로 진행 |
| [Hybrid-Event-Driven-Architecture](https://github.com/junhyeong9812/Hybrid-Event-Driven-Architecture) | 모듈러 모놀리스 기반 하이브리드 이벤트 드리븐 아키텍처 |
| [hexapass](https://github.com/junhyeong9812/hexapass) | 구독형 멤버십·예약 도메인을 순수 자바 OOP로 설계 — SOLID·패턴·헥사고날·TDD |
| [transfer-money](https://github.com/junhyeong9812/transfer-money) | Go로 구현한 송금 시스템 |
| [payroll-calculator](https://github.com/junhyeong9812/payroll-calculator) | 자동 급여 계산 시스템 |
| [intelligence-collection](https://github.com/junhyeong9812/intelligence-collection) | 역사 데이터·세계 뉴스 수집 파이프라인 서버 |
| [orchestration-data-pipeline](https://github.com/junhyeong9812/orchestration-data-pipeline) | 데이터 수집 파이프라인 오케스트레이션 설계 |
| [unit-monitoring](https://github.com/junhyeong9812/unit-monitoring) | 모니터링 시스템 간편 구축 |
| [study-site](https://github.com/junhyeong9812/study-site) | 1,524개 학습 항목을 실시간 편집·실행하는 인터랙티브 코드 플레이그라운드 |
| [chatbot](https://github.com/junhyeong9812/chatbot) | Spring AI 챗봇 |
| [ExceptionRadar](https://github.com/junhyeong9812/ExceptionRadar) | 스레드·프로세스 경계에서 사라지는 예외 추적·모니터링 — **진행예정** |

### 🏢 팀 프로젝트

#### [Tickatch](https://github.com/Tickatch) — 티켓 예매 플랫폼 MSA

2025.12 · 1개월 · 5명 · **인증 / 공통 라이브러리 / 상품 도메인 / 프론트엔드 담당**, 서비스 간 이벤트·API 흐름 문서화 및 테스트 시나리오 조율  
`Spring Boot` `Spring Cloud` `Kafka` `RabbitMQ` `PostgreSQL` `Redis` `Docker` `NGINX` `Next.js`

- Gateway 독립 JWT RS256 검증과 JWKS 캐싱으로 매 요청 Auth 호출 제거
- HTTP·Feign·MQ·Scheduler traceId 자동 전파 라이브러리를 Maven Central에 배포
- 좌석 동시성 4방안을 비교하고 도메인 특성에 맞춰 비관적 락 채택
- 운영 코드와 분리된 부하/정합성 검증 환경 구축 — 초당 150 RPS·최대 대기 10만 명 시나리오에서 대기열 안정성 검증
- Docker Compose·NGINX·Let's Encrypt 기반 자가 서버 호스팅 구성

직접 구현한 리포: [auth-service](https://github.com/Tickatch/auth-service) · [user-service](https://github.com/Tickatch/user-service) · [common-lib](https://github.com/Tickatch/common-lib) · [product-service](https://github.com/Tickatch/product-service) · [tickatch_web](https://github.com/Tickatch/tickatch_web) · [test-service](https://github.com/Tickatch/test-service) · [infrastructure](https://github.com/Tickatch/infrastructure)

#### [EarlyExpress](https://github.com/EarlyExpress) — 물류 플랫폼 MSA · 프로젝트 리딩

2025.11 · 1개월 · 4명 · **요구사항 명세 / 도메인 경계 정의 / 서비스 분담·API 계약 조율 / Saga Orchestrator 구현**  
`Spring Boot` `Spring Cloud` `Kafka` `Keycloak` `OpenFeign` `PostgreSQL`

- Order Service 중심 Saga Orchestrator로 7단계 분산 트랜잭션 흐름 제어
- Step History 영속화로 진행/실패/보상 경로 추적 — 장애 분석 시간 10분 → 1분
- 보상 트랜잭션 처리 순서를 재정립해 장애 시 히스토리 소실 문제 차단
- HubSegment 기반 다중 구간 배송 모델로 전국 허브 복합 경로 처리
- Kafka 이벤트 기반으로 Order와 Track의 책임 경계 및 배송 상태 Source of Truth 정리

직접 구현한 리포: [order-service](https://github.com/EarlyExpress/order-service) · [track-service](https://github.com/EarlyExpress/track-service) · [delivery-service](https://github.com/EarlyExpress/delivery-service) · [hub-delivery-service](https://github.com/EarlyExpress/hub-delivery-service) · [product-service](https://github.com/EarlyExpress/product-service) · [inventory-service](https://github.com/EarlyExpress/inventory-service) · [early-express-frontend](https://github.com/EarlyExpress/early-express-frontend)

### 📚 자료구조 · CS · 기록

| 프로젝트 | 설명 |
|---|---|
| [data-structure](https://github.com/junhyeong9812/data-structure) | 자료구조와 시야 확장하기 |
| [data-structure-application](https://github.com/junhyeong9812/data-structure-application) | 30가지 실무 시나리오를 자료구조로 해결 — POP/OOP 병행 (Java 21) |
| [data-structure-advanced](https://github.com/junhyeong9812/data-structure-advanced) | 30가지 복합 실무 시나리오 — POP/OOP 병행 (Java 21) |
| [computer_science](https://github.com/junhyeong9812/computer_science) | 컴퓨터 과학 정리 |
| [dev-reference](https://github.com/junhyeong9812/dev-reference) | 6개 언어 1,524개 코드에 한국어 줄 단위 주석을 단 학습 레퍼런스 |
| [dev-questions](https://github.com/junhyeong9812/dev-questions) | 개발하며 스스로에게 던지는 질문 모음 — 7개 순환 질문 + 18개 체크리스트 |
| [study-history](https://github.com/junhyeong9812/study-history) | 프로젝트를 진행하며 공부한 내용 기록 |
| [java-spring-history](https://github.com/junhyeong9812/java-spring-history) | 자바·스프링 히스토리 정리 |
| [tidy-first-example](https://github.com/junhyeong9812/tidy-first-example) | 『Tidy First?』의 기법들을 예제로 구현 |
| [analyze-open-code-review-analyze](https://github.com/junhyeong9812/analyze-open-code-review-analyze) | Alibaba open-code-review 분석·요약 문서 |
| [keycloak-analyze](https://github.com/junhyeong9812/keycloak-analyze) | Keycloak 26.6.2 공식 가이드 78편 한국어 1:1 완역 — 서버 설정·앱 보안·관측성·HA 전 문서 |
| [spring-framework-ko-docs](https://github.com/junhyeong9812/spring-framework-ko-docs) | Spring Framework 7.1 소스 22모듈을 "책처럼 읽으며" 내부 구조를 코드 레벨로 풀어쓴 한글 해설서 (why→what→how + ASCII 구조도) |
| [spring-security-ko-docs](https://github.com/junhyeong9812/spring-security-ko-docs) | Spring Security 7.1 소스 22모듈(인증·인가·OAuth2·SAML2·WebAuthn) 한글 해설서 — spring-framework-ko-docs 자매편 |
