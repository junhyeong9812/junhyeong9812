# Hi, I'm Junhyeong

> 매일 작게라도 개선과 실험을 멈추지 않으며, 구조와 원리를 깊이 이해해 더 나은 설계를 추구하는 개발자를 지향합니다.

이 저장소는 제가 진행한 **배포·테스트 가능한 서비스 수준의 프로젝트**와
**프레임워크·서버 구조 실험, 성능 최적화, 인프라 설계 프로젝트**를 한눈에 볼 수 있도록 정리한 페이지입니다.

---

## 대표 프로젝트

### 1. [Fream Backend](https://github.com/junhyeong9812/fream-back)

Spring Boot 기반 확장 가능한 웹 서비스 인프라 구축 프로젝트
**주요 특징**

* Spring Boot 3.x + Java 17 + JPA/QueryDSL
* AWS 기반 인프라 (EC2, Route53, Docker)
* Redis 캐싱, Elasticsearch 검색, Kafka 이벤트 처리
* GitHub Actions 기반 CI/CD + Blue-Green 무중단 배포
* WebSocket 기반 실시간 알림

🔗 **Frontend:** [Fream Frontend](https://github.com/junhyeong9812/fream-front)

---

### 2. [StackNote Backend](https://github.com/junhyeong9812/stackknote-back) & [Frontend](https://github.com/junhyeong9812/stackknote-front)

노션 스타일의 문서·포트폴리오 관리 플랫폼
**주요 특징**

* Backend: Spring Boot + MySQL + Redis
* Frontend: Next.js 15 + React 19 + TailwindCSS 4
* BlockNote/Tiptap 기반 블록 에디터
* 실시간 협업 (Yjs + WebSocket)
* 공개/비공개 페이지, 댓글, 태그, 검색 시스템

---

## 프레임워크 & 서버 아키텍처 실험

### 3. [Winter](https://github.com/junhyeong9812/winter)

Spring MVC 구조를 직접 구현한 경량 웹 프레임워크
**주요 특징**

* DispatcherServlet, HandlerMapping, ViewResolver 직접 구현
* 어노테이션 기반 컨트롤러, ModelAndView, 예외 처리기
* 학습 단계별 문서화 & 브랜치 관리
* MVC → IoC/DI → AOP → Security → Integration 순서로 확장

---

### 4. [JavaServerArchitectures](https://github.com/junhyeong9812/JavaServerArchitectures)

순수 Java로 구현한 3가지 HTTP 서버 아키텍처 비교
**구현 아키텍처**

* Thread-per-Request (전통적 스레드 모델)
* Hybrid Async (스레드 재활용 비동기 처리)
* EventLoop (논블로킹 단일 루프)

**학습 포인트**

* HTTP 파서 & 라우팅 직접 구현
* 동시성 모델별 성능 벤치마크
* Netty, Node.js, Spring WebFlux 구조 이해 기반 마련

---

## 학습·실험 프로젝트

* **ORM 실험**: JPA vs QueryDSL 성능 비교, DB 인덱스 튜닝
* **검색 엔진 최적화**: Elasticsearch 형태소 분석기 & FastAPI 통합 실험
* **인프라 실험**: Nginx Reverse Proxy, Redis TTL 관리, Kafka 로그 처리
* **프레임워크 원리 학습**: DI 컨테이너, 애너테이션 파서, 요청 파라미터 바인딩 구현
* **성능 최적화 실험**: 캐시 계층 설계, DB 샤딩, 비동기 메시징 구조

---

## Contact

* GitHub: [junhyeong9812](https://github.com/junhyeong9812)
* Email: [pickjog@naver.com](mailto:pickjog@naver.com)
