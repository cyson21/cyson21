# 손찬양 | Java/Spring Backend Engineer

Java·Spring 기반 기업용 플랫폼 API를 개발하고 운영해 왔습니다. 요구사항 분석부터 데이터 모델·비즈니스 로직 설계, 테스트와 운영 안정성 개선까지 담당합니다.

[이력서 PDF](https://github.com/cyson21/portfolio-hub/releases/download/latest/resume.pdf) · [웹 포트폴리오](https://cyson21.github.io/) · [프로젝트 HTML](https://cyson21.github.io/projects/)

## 대표 프로젝트

| 프로젝트 | 문제 조건 | 핵심 구현 |
|---|---|---|
| [StockRush](https://github.com/cyson21/stockrush) | 주문·재고·결제가 서로 다른 속도로 처리되고 일부 단계가 실패하는 상황 | [Saga, Transactional Outbox, 소비자 중복 처리 방지](https://cyson21.github.io/projects/stockrush/) |
| [Enterprise Policy RAG](https://github.com/cyson21/enterprise-policy-rag) | 비인가 문서가 모델 입력에 포함되거나 근거 없이 답변하는 상황 | [검색 전 권한 필터, 무근거 답변 거절과 인용 범위 검사](https://cyson21.github.io/projects/enterprise-policy-rag/) |
| [Member Event Consistency](https://github.com/cyson21/member-event-consistency) | 동시 요청으로 중복 보상, 쿠폰 초과 발급과 음수 잔액이 생기는 상황 | [PostgreSQL 제약·행 잠금, 선택형 Redis 잠금과 RabbitMQ 처리](https://cyson21.github.io/projects/member-event-consistency/) |

## 다른 프로젝트

| 프로젝트 | 다룬 조건과 구현 |
|---|---|
| [AI Gateway](https://github.com/cyson21/ai-gateway) · [웹 상세](https://cyson21.github.io/projects/ai-gateway/) | 여러 애플리케이션의 인증·사용량·캐시·장애 복구 정책을 공통 경계에 적용 |
| [CDC Data Platform](https://github.com/cyson21/cdc-data-platform) · [웹 상세](https://cyson21.github.io/projects/cdc-data-platform/) | 재전달된 DB 변경을 식별하고 적재 실패 뒤의 원천 위치와 처리 상태를 추적 |
| [Fashion Personalization Platform](https://github.com/cyson21/fashion-personalization-platform) · [웹 상세](https://cyson21.github.io/projects/fashion-personalization-platform/) | 행동 이벤트의 중복·재시도 범위를 분리하고 상품 조건을 근거로 추천 순위 생성 |

## 기술 초점

Java · Spring Boot · PostgreSQL · Kafka · Redis · RabbitMQ · Testcontainers

Transactional Outbox · 멱등 처리 · 동시성 제어 · 장애 복구 · CDC · 데이터 계보

[전체 저장소와 프로젝트 자료](https://github.com/cyson21/portfolio-hub)
