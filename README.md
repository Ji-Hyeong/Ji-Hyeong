# 강지형 | Backend Engineer

Kotlin/Spring Boot와 C#/.NET으로 결제·구독, 인증, AI 콘텐츠 생성, 포인트·광고 보상, 오프라인 행사 시스템을 개발해 왔습니다.

운영 중 생기는 장애와 데이터 불일치를 원인부터 확인하고, 테스트와 모니터링이 가능한 구조로 고치는 일을 중요하게 생각합니다.

[포트폴리오](https://calico-dolomite-4bc.notion.site/Backend-Engineer-3b133406e7178119a485c71ba17edb8d) · [이메일](mailto:wlgud30@gmail.com)

## 실무에서 다룬 문제

- 수기로 관리하던 유료 이용을 채널 요금제와 정기결제 기능으로 전환했습니다.
- 약 3천 명이 참여한 오프라인 행사에서 랭킹 장애를 Redis Sorted Set으로 전환해 약 30분 안에 복구했습니다.
- 난수 토큰 인증을 JWT와 Refresh Token Rotation 방식으로 바꿔 대부분의 API 응답 시간을 150~250ms 줄였습니다.
- AI 게임 생성 과정의 장시간 외부 호출, 데이터 저장 순서와 실패 시 크레딧 취소를 비동기 작업으로 처리했습니다.

실무 프로젝트의 구조와 결과는 [포트폴리오](https://calico-dolomite-4bc.notion.site/Backend-Engineer-3b133406e7178119a485c71ba17edb8d)에 정리했습니다.

## 공개 저장소

| 저장소 | 내용 |
| --- | --- |
| [backend-study](https://github.com/Ji-Hyeong/backend-study) | 트랜잭션, 외부 결제, Outbox/Inbox, 동시성, 캐시, JWT/OIDC를 작은 애플리케이션과 테스트로 재현한 저장소 |
| [clean-architecture-study](https://github.com/Ji-Hyeong/clean-architecture-study) | Kotlin 멀티 모듈에서 도메인·애플리케이션·인프라·API 의존성을 분리한 학습 프로젝트 |
| [my-blog](https://github.com/Ji-Hyeong/my-blog) | 이력과 기술 기록을 제공하는 React/Vite 기반 개인 사이트 |

## 사용 기술

- **Backend** Kotlin, Java, C#, Spring Boot, .NET
- **Data** PostgreSQL, MSSQL, MySQL, Redis, JPA, QueryDSL
- **Platform** AWS, Azure, Azure Service Bus, Docker, Kafka, Quartz
- **Testing** JUnit 5, Kotest, Testcontainers, WireMock