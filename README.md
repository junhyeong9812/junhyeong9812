## 김준형 | Backend Developer

> "이건 진짜일까?", "그렇다면 한계는 어디일까?"
>
> 이 두 가지 질문에서 시작해 매일 조금씩 코드를 쓰며 성장하고 있습니다.
> LLM을 활용한 개발이 일상이 된 지금, 더 나은 방향을 판단하고 제시하려면
> 기본기와 다양한 케이스에 대한 이해가 오히려 더 중요하다고 생각합니다.

---

### 🔬 실험 — 기술적 통념을 직접 검증합니다

| 프로젝트 | 핵심 질문 | 결론 |
|---------|---------|------|
| [Sync-Async Lab](https://github.com/junhyeong9812/sync-async-lab) | async가 정말 빠른가? | 고부하에서만 유의미. 실서비스에서는 DB 커넥션 풀이 진짜 병목 |
| [Distributed Log Pipeline](https://github.com/junhyeong9812/distributed-log-pipeline) | RDB의 한계는 어디까지인가? | 1억 건 이상 집계에서 HDFS+Spark가 우위 |
| [Proto Bench](https://github.com/junhyeong9812/proto-bench) | 직렬화 포맷 간 실제 성능 차이는? | (진행중) |

### 🏛️ 아키텍처 비교 — 같은 설계를 다른 프레임워크로 구현합니다

| 프로젝트 | 핵심 질문 |
|---------|---------|
| [Spring Architecture](https://github.com/junhyeong9812/spring-architecture) | Hexagonal + Modulith가 Spring에서 어떻게 구현되는가? |
| [FastAPI Architecture](https://github.com/junhyeong9812/fastapi-architecture) | 같은 설계를 FastAPI로 옮기면 뭐가 바뀌고 뭐가 남는가? |

> 동일한 도메인(주문→결제→배송)을 두 프레임워크로 나란히 구현하며,
> 프레임워크에 종속되지 않는 설계와 각 생태계의 관용적 차이를 직접 비교합니다.

### 📦 오픈소스 — 다른 개발자가 쓸 수 있는 도구를 만듭니다

| 프로젝트 | 설명 |
|---------|------|
| [Streamix](https://github.com/junhyeong9812/streamix) | Spring Boot Starter 기반 미디어 스트리밍 라이브러리. Hexagonal Architecture, Maven Central 배포 |

### 🧱 매일 쌓는 기본기

| 리포 | 내용 |
|-----|------|
| [data-structure](https://github.com/junhyeong9812/data-structure) | 자료구조를 매일 테스트 케이스와 함께 직접 구현 |
| [di-ioc](https://github.com/junhyeong9812/di-ioc) | DI/IoC 컨테이너를 밑바닥부터 구현하며 원리 이해 |

### 🛠️ Tech Stack

**Backend:** Java, Spring Boot, Python, FastAPI
**Data:** PostgreSQL, Elasticsearch, Redis, Kafka
**Infra:** Docker, Kubernetes(k3s), AWS

---

📫 pickjog@naver.com
