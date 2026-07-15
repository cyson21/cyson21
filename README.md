# 손찬양 | Java/Spring Backend Engineer

분산된 상태가 어긋나는 조건을 먼저 정의하고, 복구 경로와 데이터 흐름을 코드와 재현 가능한 테스트로 확인합니다.

[이력서 PDF](https://github.com/cyson21/portfolio-hub/releases/download/latest/resume.pdf) · [웹 포트폴리오](https://cyson21.github.io/) · [통합 포트폴리오 PDF](https://github.com/cyson21/portfolio-hub/releases/download/latest/portfolio-complete.pdf)

## 대표 프로젝트

| 프로젝트 | 해결한 문제 | 검증 시나리오 |
|---|---|---|
| [StockRush](https://github.com/cyson21/stockrush) | 주문·재고·결제 분리 뒤 부분 실패를 Saga와 Transactional Outbox로 수렴 | [동일 SKU 동시 주문, 중복 요청, Kafka 중단 후 Outbox 복구](https://cyson21.github.io/projects/stockrush/) |
| [Member Event Consistency](https://github.com/cyson21/member-event-consistency) | 최초 보상·쿠폰·포인트 요청 경합을 PostgreSQL 제약과 선택형 Redis/RabbitMQ 제어로 차단 | [회원당 1회 지급, 캠페인 수량, 음수 잔액 불변식](https://cyson21.github.io/projects/member-event-consistency/) |
| [CDC Data Platform](https://github.com/cyson21/cdc-data-platform) | DB 변경 재전달을 source metadata event id와 ledger로 식별하고 replay 상태를 추적 | [create/update/delete 캡처, 중복 ingest, sink failure replay](https://cyson21.github.io/projects/cdc-data-platform/) |

## 다른 프로젝트

| 프로젝트 | 검증 주제 |
|---|---|
| [AI Gateway](https://github.com/cyson21/ai-gateway) | tenant 인증, quota, 2단계 cache, routing, provider fallback |
| [Enterprise Policy RAG](https://github.com/cyson21/enterprise-policy-rag) | 권한 선필터 검색, 근거 없는 답변 거절, citation과 회귀 평가 |
| [Fashion Personalization Platform](https://github.com/cyson21/fashion-personalization-platform) | in-memory 이벤트 멱등성, 결정론적 ranking, batch snapshot |

## 기술 초점

Java · Spring Boot · PostgreSQL · Kafka · Redis · RabbitMQ · Testcontainers

Transactional Outbox · idempotency · concurrency control · failure recovery · CDC · data lineage

[전체 저장소와 프로젝트 자료](https://github.com/cyson21/portfolio-hub)
