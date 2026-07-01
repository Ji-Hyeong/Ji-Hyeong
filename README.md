# Kang Ji Hyeong

Backend Engineer focused on reliability, data consistency, and product-facing systems.

I have worked on payment and subscription flows, point ledgers, authentication, event traffic, and AI content generation. I care about defining the failure cases first, then building a structure that can be operated and explained after launch.

## What I Work On

- Payment and subscription systems: billing keys, recurring payments, retries, refunds, and entitlement application
- Data consistency: append-only ledgers, idempotency, transactional boundaries, and audit trails
- Authentication and performance: JWT migration, refresh token rotation, and removing unnecessary I/O from common request paths
- Traffic and operations: Redis-based ranking, distributed locks, load testing, and incident recovery
- AI product features: game generation orchestration, image and BGM generation, credit handling, and usage logging

## Selected Impact

- Launched a studio subscription and pricing-plan system in about 1.5 months.
- Processed up to 56K monthly point events through an append-only ledger model.
- Improved common authenticated API latency by about 200-300ms by removing Redis and DB lookups from the access-token path.
- Recovered an offline event ranking incident for about 3K participants by moving ranking reads from RDB queries to Redis Sorted Set.
- Operated AI game generation used by 74 channels, with 102 full-game generations recorded in production backup data.

## Tech Stack

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![C Sharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_Service_Bus-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

## Portfolio Projects

| Project | Focus | Notes |
| --- | --- | --- |
| Studio Subscription | Payment, recurring billing, entitlement | Billing key, retry policy, outbox, scheduled messages |
| Point Ledger | Data consistency, audit trail | Paid/free point separation, append-only events, refund traceability |
| Treasure Event | Redis, traffic, incident response | Ranking migration, reward quantity control, distributed lock |
| Auth Migration | Performance, compatibility | JWT access token, refresh token rotation, legacy-token coexistence |
| AI Game Generation | AI orchestration, async processing | Bedrock, image/BGM generation, credits, production usage logs |

## Current Focus

- Writing backend case studies from production experience
- Building public sample projects around payment, ledgers, and concurrency
- Improving portfolio material for backend engineering roles

