# 강지형

운영 중 반복되는 문제의 원인을 찾고, 데이터 정합성과 안정성이 중요한 백엔드 시스템을 설계해 온 Backend Engineer입니다.

결제와 구독, 포인트 원장, 인증, 행사 트래픽, AI 콘텐츠 생성처럼 실패했을 때 사용자가 바로 불편을 겪는 영역을 주로 맡았습니다. 기술 자체보다 먼저 실패 케이스와 운영 기준을 정의하고, 출시 후에도 설명 가능한 구조를 만드는 데 집중합니다.

## 주로 다룬 문제

- 결제와 구독: 빌링키, 정기 결제, 재시도, 환불, 요금제 권한 적용
- 데이터 정합성: append-only 원장, 멱등성, 트랜잭션 경계, 감사 가능한 이력
- 인증과 성능: JWT 전환, refresh token rotation, 공통 요청 경로의 불필요한 I/O 제거
- 트래픽과 운영: Redis 랭킹, 분산락, 부하테스트, 행사 장애 대응
- AI 제품화: 게임 생성 오케스트레이션, 이미지/BGM 생성, 크레딧 처리, 사용 로그 기록

## 대표 성과

- 약 1.5개월 안에 스튜디오 구독 결제와 요금제 적용 기능을 운영 환경에 출시했습니다.
- 월 최대 5.6만 건의 포인트 이벤트를 append-only 원장 모델로 처리했습니다.
- 공통 인증 경로에서 Redis/DB 조회를 제거해 주요 요청의 평균 응답 시간을 약 200-300ms 단축했습니다.
- 약 3천 명 규모 오프라인 행사에서 랭킹 조회 병목을 RDB에서 Redis Sorted Set으로 전환해 장애를 복구했습니다.
- 운영 백업 기준 74개 채널에서 전체 게임 102개가 생성된 AI 게임 생성 기능을 구현했습니다.

## 기술 스택

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![C Sharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_Service_Bus-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

## 포트폴리오 주제

| 주제 | 핵심 역량 | 설명 |
| --- | --- | --- |
| 스튜디오 요금제 | 결제, 구독, 권한 | 빌링키, 재시도 정책, Outbox, 예약 메시지 |
| 포인트 원장 | 정합성, 감사 이력 | 유료/무료 포인트 분리, append-only 이벤트, 환불 추적 |
| 트레저 행사 | Redis, 트래픽, 장애 대응 | 랭킹 구조 전환, 보상 수량 제어, 분산락 |
| 인증 개선 | 성능, 호환성 | JWT access token, refresh token rotation, 레거시 토큰 공존 |
| AI 게임 생성 | AI 오케스트레이션, 비동기 처리 | Bedrock, 이미지/BGM 생성, 크레딧, 운영 사용 로그 |

## 지금 하는 일

- 운영 경험을 백엔드 케이스 스터디로 정리하고 있습니다.
- 결제, 원장, 동시성 제어를 주제로 공개 샘플 프로젝트를 만들고 있습니다.
- 백엔드 포지션 지원을 위한 포트폴리오와 이력서를 다듬고 있습니다.

