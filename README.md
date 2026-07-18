# 손찬양 | Java/Spring Backend Engineer

Java와 Spring으로 기업용 플랫폼 API를 개발·운영하며 데이터 모델 설계, 운영 안정성 개선과 테스트를 담당해 왔습니다.

[이력서 PDF](https://github.com/cyson21/portfolio-hub/releases/download/latest/resume.pdf) · [웹 포트폴리오](https://cyson21.github.io/) · [통합 포트폴리오 PDF](https://github.com/cyson21/portfolio-hub/releases/download/latest/portfolio-complete.pdf)

## 대표 프로젝트

| 프로젝트 | 해결한 문제 | 검증 시나리오 |
|---|---|---|
| [StockRush](https://github.com/cyson21/stockrush) | 주문·재고·결제 분리 뒤 부분 실패를 Saga와 Transactional Outbox로 수렴 | [동일 SKU 동시 주문, 중복 요청, Kafka 중단 후 Outbox 복구](https://cyson21.github.io/projects/stockrush/) |
| [Member Event Consistency](https://github.com/cyson21/member-event-consistency) | 최초 보상·쿠폰·포인트 요청 경합을 PostgreSQL 제약과 선택형 Redis/RabbitMQ 제어로 차단 | [회원당 1회 지급, 캠페인 수량, 음수 잔액 불변식](https://cyson21.github.io/projects/member-event-consistency/) |
| [CDC Data Platform](https://github.com/cyson21/cdc-data-platform) | DB 변경 재전달을 원천 위치 기반 이벤트 ID와 처리 장부로 식별하고 재처리 상태를 추적 | [생성·수정·삭제 캡처, 중복 처리, 적재 실패 재처리](https://cyson21.github.io/projects/cdc-data-platform/) |

## 다른 프로젝트

| 프로젝트 | 검증 주제 |
|---|---|
| [AI Gateway](https://github.com/cyson21/ai-gateway) | 조직 인증, 사용량 제한, 2단계 캐시, 모델 선택과 장애 복구 |
| [Enterprise Policy RAG](https://github.com/cyson21/enterprise-policy-rag) | 검색 전 권한 필터, 근거 없는 답변 거절, 출처와 회귀 평가 |
| [Fashion Personalization Platform](https://github.com/cyson21/fashion-personalization-platform) | 메모리 이벤트 중복 방지, 규칙 기반 추천 순위, 배치 스냅샷 |

## 기술 초점

Java · Spring Boot · PostgreSQL · Kafka · Redis · RabbitMQ · Testcontainers

Transactional Outbox · 멱등 처리 · 동시성 제어 · 장애 복구 · CDC · 데이터 계보

[전체 저장소와 프로젝트 자료](https://github.com/cyson21/portfolio-hub)
