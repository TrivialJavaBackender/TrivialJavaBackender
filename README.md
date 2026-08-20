<h1 align="center">Pavel Saroka</h1>
<p align="center">Java Backend Engineer · GMT+3 · 5+ years in commercial development</p>

<p align="center">
  <a href="https://www.linkedin.com/in/pavelsaroka/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:pavelsaroka1@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://t.me/shutme_up"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
</p>

---

I build microservices in Java and Kotlin with Spring Boot. Day to day that means designing REST APIs
documented with OpenAPI, wiring services together through Kafka, keeping contracts between services in
Protobuf and making PostgreSQL behave under load with `EXPLAIN ANALYZE` in hand.

Worked in iGaming, B2B subscriptions and enterprise project analytics. Looking for a product team with
real load and end-to-end ownership of a domain.

### What I work with

**Languages**  
![Java](https://img.shields.io/badge/Java%208--21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Frameworks**  
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate%20%2F%20JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![jOOQ](https://img.shields.io/badge/jOOQ-F58220?style=flat-square)
![JUnit 5](https://img.shields.io/badge/JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3E?style=flat-square&logo=docker&logoColor=white)

**Data and messaging**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Protobuf](https://img.shields.io/badge/Protobuf-4285F4?style=flat-square&logoColor=white)

**Platform**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### Selected work

**Backend Engineer at Softnetix**, football event tracking, Kotlin and Java 17, Kafka, jOOQ, CQRS and Event Sourcing.  
Proposed a new notification architecture and refactored the module for it, so a new notification type now
takes hours instead of 3 to 5 days. Covered 50 notification scenarios with regression tests that used to be
run by hand before every release.

**Java Software Engineer at LeverX**, Subscription Billing and a telemetry data warehouse.  
Added weekly billing cycles (1 to 12 weeks) and generalised the cycle model without breaking the API, so the
shortest subscription became a week instead of a month. Reworked a transactional outbox from a single poller
to a sharded worker pool, which let publishing scale horizontally while per-subscription ordering held.
Moved Kafka and Redis configuration into in-house Spring Boot starters with integration tests.

**Java Software Engineer at EPAM**, enterprise analytics for projects, teams and finance.  
Optimised project search by reworking the queries and tuning Elasticsearch, p95 dropped from 10s to 300ms.
Found and fixed a defect behind 60x database growth. Ran a Kafka topic migration across 5 teams with zero
downtime and no message loss.

### Things I build outside work

| Project | About |
| --- | --- |
| [observability-labs](https://github.com/TrivialJavaBackender/observability-labs) | Eight Spring Boot services with a full Grafana, Prometheus, Tempo, Loki and Pyroscope stack. The system ships with no observability at all, so the work is adding the metrics, dashboards and alerts, then replaying 15 incidents against them |
| [pet-project-marketplace](https://github.com/TrivialJavaBackender/pet-project-marketplace) | Kotlin and Spring Boot microservices where one order produces both Kafka facts and RabbitMQ commands, so the difference between the two brokers is visible side by side. Redis cache-aside, Keycloak OIDC, coroutines and a Micronaut service for contrast |
| [Java-Knowledge-Base](https://github.com/TrivialJavaBackender/Java-Knowledge-Base) | Interview Prep, backend preparation across concurrency, system design, infrastructure and Spring. Runnable Kotlin theory, exercises and 110 questions behind a Next.js app with decks and a progress dashboard, [live](https://pavel-learn-app.netlify.app) |
| [sky-rocket-english](https://github.com/TrivialJavaBackender/sky-rocket-english) | English learning app, B2+ to C1, accounts and saved progress, [live](https://sky-rocket-english.netlify.app) |

### Get in touch

<p align="left">
  <a href="mailto:pavelsaroka1@gmail.com"><img src="https://img.shields.io/badge/Email-pavelsaroka1%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://t.me/shutme_up"><img src="https://img.shields.io/badge/Telegram-%40shutme__up-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://www.linkedin.com/in/pavelsaroka/"><img src="https://img.shields.io/badge/LinkedIn-in%2Fpavelsaroka-0A66C2?style=flat-square&logoColor=white" alt="LinkedIn"></a>
</p>
