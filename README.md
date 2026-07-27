# 손찬양 | Java/Spring Backend Engineer

Java·Spring 기반 기업용 플랫폼 API를 개발하고 운영해 왔습니다. 요구사항 분석부터 데이터 모델과 비즈니스 로직 설계, 테스트, 운영 안정성 개선까지 담당합니다.

분산 상태 변경, 동시 요청의 데이터 정합성, 접근 제어, 이벤트 전달과 재처리 문제를 구현과 테스트 근거로 설명합니다.

[웹 포트폴리오](https://cyson21.github.io/) · [프로젝트 HTML](https://cyson21.github.io/projects/) · [이력서 PDF](https://github.com/cyson21/portfolio-hub/releases/download/latest/resume.pdf)

## 대표 프로젝트

| 프로젝트 | 다룬 문제와 구현 |
|---|---|
| [StockRush](https://github.com/cyson21/stockrush) · [HTML](https://cyson21.github.io/projects/stockrush/) | Saga와 Transactional Outbox로 주문·재고·결제의 부분 실패와 중복 처리를 제어 |
| [Member Event Consistency](https://github.com/cyson21/member-event-consistency) · [HTML](https://cyson21.github.io/projects/member-event-consistency/) | PostgreSQL 제약·행 잠금과 선택형 Redis/RabbitMQ 방식으로 동시 요청의 업무 불변식 보호 |
| [Enterprise Policy RAG](https://github.com/cyson21/enterprise-policy-rag) · [HTML](https://cyson21.github.io/projects/enterprise-policy-rag/) | 검색 전 권한 필터와 인용 범위 검사로 비인가 문서와 무근거 답변 차단 |
| [AI Gateway](https://github.com/cyson21/ai-gateway) · [HTML](https://cyson21.github.io/projects/ai-gateway/) | 여러 애플리케이션의 인증·사용량·캐시·라우팅·장애 복구 정책을 공통 경계에 적용 |
| [CDC Data Platform](https://github.com/cyson21/cdc-data-platform) · [HTML](https://cyson21.github.io/projects/cdc-data-platform/) | Debezium 변경 이벤트의 중복 적재를 막고 실패 뒤 원천 위치와 재처리 상태 추적 |
| [Fashion Personalization Platform](https://github.com/cyson21/fashion-personalization-platform) · [HTML](https://cyson21.github.io/projects/fashion-personalization-platform/) | 행동 이벤트의 중복·재시도를 격리하고 상품 조건을 근거로 추천 순위 생성 |

## 기술 초점

Java · Spring Boot · PostgreSQL · Kafka · Redis · RabbitMQ · Testcontainers

Transactional Outbox · 멱등 처리 · 동시성 제어 · 장애 복구 · CDC · 데이터 계보

[전체 프로젝트 HTML](https://cyson21.github.io/projects/) · [공개 자료 허브](https://github.com/cyson21/portfolio-hub)
