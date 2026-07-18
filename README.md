# 손찬양 | Java/Spring Backend Engineer

Java와 Spring으로 기업용 플랫폼 API를 개발·운영하며 데이터 모델 설계, 운영 안정성 개선과 테스트를 담당해 왔습니다.

[이력서 PDF](https://github.com/cyson21/portfolio-hub/releases/download/latest/resume.pdf) · [웹 포트폴리오](https://cyson21.github.io/) · [통합 포트폴리오 PDF](https://github.com/cyson21/portfolio-hub/releases/download/latest/portfolio-complete.pdf)

## 대표 프로젝트

| 프로젝트 | 해결한 문제 | 핵심 구현 |
|---|---|---|
| [StockRush](https://github.com/cyson21/stockrush) | 결제 실패, 이벤트 중복과 Kafka 중단 뒤에도 주문·재고·결제 상태가 모순 없이 끝나도록 처리 | [Saga, Transactional Outbox, 소비자 중복 처리 방지](https://cyson21.github.io/projects/stockrush/) |
| [Member Event Consistency](https://github.com/cyson21/member-event-consistency) | 동시 요청으로 생길 수 있는 중복 보상, 초과 쿠폰과 음수 포인트를 저장 단계에서 차단 | [PostgreSQL 제약·행 잠금, 선택형 Redis 잠금과 RabbitMQ 처리](https://cyson21.github.io/projects/member-event-consistency/) |
| [CDC Data Platform](https://github.com/cyson21/cdc-data-platform) | DB 변경을 다시 받아도 중복 반영하지 않고 적재 실패 원인과 재처리 상태를 추적 | [원천 위치 기반 이벤트 ID, 처리 장부, 실패 재처리](https://cyson21.github.io/projects/cdc-data-platform/) |

## 다른 프로젝트

| 프로젝트 | 해결한 문제와 구현 |
|---|---|
| [AI Gateway](https://github.com/cyson21/ai-gateway) | 여러 애플리케이션의 조직 인증, 사용량 제한, 캐시와 모델 장애 복구 정책을 한곳에서 적용 |
| [Enterprise Policy RAG](https://github.com/cyson21/enterprise-policy-rag) | 권한 없는 문서를 검색 단계에서 제외하고 근거가 없으면 답변 생성을 중단 |
| [Fashion Personalization Platform](https://github.com/cyson21/fashion-personalization-platform) | 행동 이벤트를 한 번만 프로필에 반영하고 상품 조건을 근거로 추천 순위 생성 |

## 기술 초점

Java · Spring Boot · PostgreSQL · Kafka · Redis · RabbitMQ · Testcontainers

Transactional Outbox · 멱등 처리 · 동시성 제어 · 장애 복구 · CDC · 데이터 계보

[전체 저장소와 프로젝트 자료](https://github.com/cyson21/portfolio-hub)
