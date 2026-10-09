# 손찬양 | Java/Spring 백엔드 개발자

2021년부터 백엔드 개발·운영을 담당해 왔습니다. 이엠캐스트에서 B2B 교육 플랫폼 API 개발, 데이터 처리와 운영 개선을 담당하고 있습니다.

운영하면서 가장 오래 붙잡고 있던 문제는 대부분 "데이터가 왜 이렇게 됐지?"였습니다. 동시에 들어온 요청, 중간에 실패한 처리, 두 번 도착한 이벤트 같은 것들이요. 그래서 개인 프로젝트도 그런 상황을 일부러 만들어 보고, 그때 데이터가 어떻게 남는지 테스트로 확인하는 쪽으로 진행했습니다.

[실무 경력](https://cyson21.github.io/experience/) · [이력서 PDF · 핵심 기여 요약](https://cyson21.github.io/downloads/resume.pdf) · [경력기술서 PDF · 담당 범위와 주요 기여](https://cyson21.github.io/downloads/career-description.pdf) · [포트폴리오 HTML · 실무 사례와 개인 구현 상세](https://cyson21.github.io/portfolio/index.html)

## 개인 프로젝트

| 프로젝트 | 내용 |
|---|---|
| [StockRush](https://github.com/cyson21/stockrush) | 주문, 재고, 결제가 나뉜 쇼핑몰 백엔드. 결제가 실패하거나 Kafka가 멈춰도 주문이 어중간한 상태로 남지 않게 Saga와 Outbox로 처리 |
| [Member Event Consistency](https://github.com/cyson21/member-event-consistency) | 쿠폰 수량, 포인트 잔액처럼 동시 요청에 약한 데이터를 PostgreSQL 잠금, Redis, RabbitMQ로 각각 막아 보고 비교 |
| [Enterprise Policy RAG](https://github.com/cyson21/enterprise-policy-rag) | 사내 문서 검색 RAG. 볼 권한이 없는 문서는 검색 단계에서부터 빼고, 근거 문서 없이 답하지 않게 제한 |
| [AI Gateway](https://github.com/cyson21/ai-gateway) | 여러 서비스가 LLM을 호출할 때 인증, 사용량 제한, 캐시, 장애 시 다른 모델로 넘기는 처리를 한곳에 모은 게이트웨이 |
| [CDC Data Platform](https://github.com/cyson21/cdc-data-platform) | Debezium으로 받은 변경 이벤트를 중복 없이 쌓고, 실패하면 어디서부터 다시 돌릴지 추적하는 프로토타입 |

## 주로 쓰는 기술

Java, Spring Boot, JPA/QueryDSL, MySQL, PostgreSQL, Kafka, Redis, RabbitMQ, Docker, AWS, Testcontainers

## 자료 안내 경로

이 프로필은 [웹 포트폴리오](https://cyson21.github.io/)와 [공개 자료 안내](https://github.com/cyson21/portfolio-hub), 위 개인 프로젝트의 구현 저장소를 연결합니다. 최신 이력서·경력기술서는 웹사이트의 다운로드 경로를 사용합니다. 구현 설명이나 경력 문안이 바뀌면 웹사이트와 이 프로필의 요약·링크를 함께 확인합니다.
