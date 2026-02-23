# AI-Oriented Engineering Milestones

## Data Indexing & Search Optimization — Elasticsearch

**Problem:** Relational database–based search suffered from poor relevance and high latency, negatively impacting user experience at scale.

**Action:** Migrated critical datasets to Elasticsearch, designing text indexing strategies and user-oriented DSL queries optimized for search relevance and intent.

**Impact:** Reduced query response time by **90%+**, significantly improving UX and search efficiency.

**AI / Knowledge Signal:** Search relevance optimization, text indexing, query modeling, data retrieval performance — foundations for intelligent search systems.

---

## Microservices Architecture — NestJS / TypeScript

**Problem:** User service exhibited high coupling and low maintainability, slowing feature delivery and increasing change risk.

**Action:** Influenced domain separation (controller, service, repository) following Clean Architecture principles and modular design — the same architectural pattern used by NestJS in production applications.

**Impact:** Accelerated delivery speed, reduced code complexity, and lowered regression risk during changes.

**AI / Knowledge Signal:** Domain modeling, separation of concerns, scalable service design — essential for ML-ready and data-driven systems.

---

## REST APIs & Data Mutation Strategy — Node.js / TypeScript

**Problem:** Strict JSON Patch implementation on a relational database introduced excessive complexity and frequent update errors.

**Action:** Designed and implemented a pragmatic adaptation of the JSON Patch protocol aligned with real API usage patterns.

**Impact:** Simplified update operations, reduced error rates, and improved long-term API maintainability.

**AI / Knowledge Signal:** API evolution strategies, data consistency, resilient system design.

---

## Questrade — KYC & AML Compliance Engineering (.NET, Node.js / TypeScript, CI/CD)

**Problem:** Financial KYC and AML compliance workflows experienced recurring deployment failures and low production reliability in a regulated fintech environment.

**Action:** Maintained and refactored compliance-critical Node.js/TypeScript backend services, wrote complex financial database queries for audit and reporting purposes, and redesigned GitLab CI/CD pipelines strengthening validations, automation, and release controls. Monitored system health and security alerts via Datadog.

**Impact:** Reduced deployment failures by **~30%**, increasing reliability of compliance-critical workflows. Every action was observable, every failure recoverable — a non-negotiable standard in regulated financial systems.

**Key Skills:** Node.js, TypeScript, MongoDB, KYC/AML workflows, financial database queries, audit trails, CI/CD, Datadog observability.

**AI / Knowledge Signal:** Regulated systems, observability, automated quality gates — critical for trustworthy AI and compliance pipelines.

---

## Questrade — Microservices Architecture (DDD)

**Problem:** Tightly coupled systems limited extensibility and slowed product evolution.

**Action:** Implemented microservices using DDD principles, SOLID practices, and clear responsibility boundaries across Node.js services.

**Impact:** Delivered extensible, maintainable services prepared for continuous evolution.

**AI / Knowledge Signal:** Domain-driven modeling, service autonomy, scalable architectures.

---

## FullStack Labs — Platform Security & Reliability (GraphQL, Node.js)

**Problem:** High-traffic GraphQL APIs serving 1M+ users were vulnerable to alias-based attacks, threatening platform availability.

**Action:** Implemented GraphQL Armor and schema directives to enforce query complexity and execution limits across Node.js/Express backend services. Built and maintained REST APIs and React interfaces improving user flows and application reliability.

**Impact:** Reduced GraphQL alias attacks by **~90%**, protecting platform availability under heavy load. Implemented automated testing with Jest and CI-friendly workflows reducing regressions across frequent releases.

**Key Skills:** Node.js, Express.js, TypeScript, React.js, GraphQL, Jest, security hardening, high-availability systems.

**AI / Knowledge Signal:** Query complexity control, adversarial patterns, system resilience.

---

## Mercado Pokémon — Payments Platform (Node.js, PostgreSQL, WebSockets)

**Problem:** A volunteer eCommerce platform required a reliable, low-cost payment infrastructure with real-time feedback and zero tolerance for unresolved transactions.

**Action:** Architected and built a full PIX payment integration from scratch using Node.js/Express and PostgreSQL. Leveraged PostgreSQL's native **ACID transactions** to guarantee payment integrity, ensuring every transaction reached a fully resolved and auditable state. Used WebSockets for real-time payment status updates to users. Optimized infrastructure architecture to minimize operational costs while maintaining reliability.

**Impact:** Achieved **$5/month infrastructure cost** while generating **~$2K/month in revenue**. Zero unresolved payment transactions due to ACID-guaranteed flows. Platform's success enabled hiring of **3 junior engineers**. Successfully **mentored 5 junior engineers**, 3 of whom secured their first professional software engineering jobs.

**Key Skills:** Node.js, Express.js, PostgreSQL, ACID transactions, WebSockets, PIX payments, real-time systems, infrastructure cost optimization.

**AI / Knowledge Signal:** Payment state machines, transactional integrity, real-time event-driven flows, financial system reliability.

---

## Luiza Labs — Quality, CI/CD & Observability (Node.js)

### Automated Testing

**Problem:** Low test coverage caused frequent regressions and production bugs.

**Action:** Designed and implemented unit and integration test strategies in Node.js, establishing a sustainable test foundation.

**Impact:** Increased test coverage to **~80%** and reduced production bugs by **~30%**.

**AI / Knowledge Signal:** Test-driven reliability, signal quality for automated systems.

---

### Fraud Prevention — Python Service

**Problem:** Manual review processes failed to scale against fraudulent product registrations in a high-traffic marketplace.

**Action:** Designed and implemented a **Python-based rule-driven service** to automatically block fraudulent listings using pre-configured business rules — an early application of automated decision systems in a financial-adjacent context.

**Impact:** Reduced manual review workload and prevented invalid listings at scale.

**AI / Knowledge Signal:** Rule-based decision systems, automated classification, fraud prevention pipelines.

---

### Event-Driven Microservices — Kafka & Redis

**Problem:** High-volume logistics and e-commerce systems required stable, low-latency inter-service communication and efficient data retrieval under sustained load.

**Action:** Stabilized systems using **Kafka** for event-driven microservices and **Redis** for caching, improving reliability and reducing service latency across the platform.

**Impact:** Improved platform reliability and reduced service latency for a high-traffic e-commerce environment.

**Key Skills:** Kafka, Redis, event-driven architecture, microservices, Node.js, caching strategies.

**AI / Knowledge Signal:** Async messaging patterns, distributed system reliability, queue-based workload management.

---

### CI/CD & Continuous Delivery

**Problem:** Delivery process limited release frequency and stability.

**Action:** Implemented GitLab CI/CD pipelines for automated build, testing, and deployment.

**Impact:** Enabled **~13 stable releases per week**, accelerating business value delivery.

**AI / Knowledge Signal:** Automation, deployment intelligence, fast feedback loops.

---

### Observability & Security

**Problem:** Inconsistent error handling hindered monitoring and incident response.

**Action:** Built a centralized Express ErrorHandler standardizing logs and exception handling across Node.js services.

**Impact:** Improved monitoring and implemented security alerts in Datadog.

**AI / Knowledge Signal:** Observability, anomaly detection readiness, operational intelligence.

---

## Database Experience — Relational & Non-Relational

**Relational:**
- **PostgreSQL** — production payments platform with ACID transaction guarantees for PIX payment integrity
- **MySQL / SQL** — complex financial and compliance queries, index design, query optimization at Cedro Technologies

**Non-Relational:**
- **MongoDB** — KYC/AML data storage at Questrade, leveraging document flexibility for varying compliance data shapes
- **Elasticsearch** — text indexing, DSL query design, 90%+ query response time improvement
- **Redis** — caching layer in high-traffic microservices at Luiza Labs, reducing latency under sustained load

**Philosophy:** Relational databases when data integrity and transactional guarantees are non-negotiable. Non-relational when flexibility and horizontal scale are the priority.

---

## Backend Software Engineer (Remote) — Luiza Labs | Brazil

**Sept 2020 – June 2021**

Stabilized high-volume logistics and e-commerce systems using **Kafka** for event-driven microservices and **Redis** for caching, improving reliability and reducing service latency.

Ensured application quality and security through automated testing and static analysis with **ESLint** and **SonarQube**, identifying vulnerabilities, code smells, and technical risks early.

Influenced technical direction by promoting test-oriented development and safe deployment practices, resulting in more predictable and stable releases.

---

## Senior Mobile Software Engineer — Social Bank | Brazil

**Jun 2019 – Sept 2020**

Led the development of a **Smart POS application** for gas stations, delivering a scalable white-label product ready for customization.

Drove adoption of open-source platforms and code reuse, reducing project costs by **~50%** without compromising quality or security.

---

## Junior Full Stack Engineer — Cedro Technologies

**May 2014 – Oct 2018**

Promoted from intern to Junior Engineer within **6 months**, recognized for rapid technical growth and consistent delivery.

Developed applications and APIs using **C#, JavaScript, Java, and Swift**, contributing across multiple system layers.

Improved application performance through SQL optimization, index creation, and elimination of inefficient subqueries.

---

## Education

**Federal University of Uberlândia (UFU)**
Authored an academic article on **Neural Networks learning the concept of influence in the game of Go**, detailing the evolution of an intelligent agent solving a complex strategic environment.

**AI / Knowledge Signal:** Reinforcement learning concepts, neural networks, game intelligence.

---

## Mentorship & Team Growth — Mercado Pokémon Experience

**Successfully mentored 3 of 5 junior engineers to secure their first professional software engineering jobs**, providing hands-on guidance in backend fundamentals, real-world project delivery, and code review best practices, while fostering their confidence and career readiness.

Platform's success also supported the hiring of **three junior engineers**, enabling team and product scale.