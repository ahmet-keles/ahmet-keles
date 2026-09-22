# Ahmet Keles

Computer Science student focused on backend engineering and distributed systems, building event-driven services in Java and Spring Boot.

## About

I'm a Computer Science student at The University of Texas at Dallas, graduating Fall 2027 and pursuing Summer 2027 software engineering internships. My primary interests are backend engineering and distributed systems, with a secondary interest in applied AI and retrieval systems. I enjoy building practical software projects focused on reliability, scalability, and real-world engineering problems.

## Featured Projects

### [Event-Driven Commerce](https://github.com/ahmet-keles/event-driven-commerce) — completed, v1.0.0

Event-driven commerce backend built with Java, Spring Boot, Kafka, and PostgreSQL. Three independent services coordinate orders, inventory, and payments while handling duplicate events, failures, and concurrent processing through reliability patterns such as transactional outbox, idempotency, saga compensation, retries, and optimistic locking. Verified with 345 automated tests.

### [NovaSearch](https://github.com/ahmet-keles/novasearch) — in progress

Hybrid search service built with Python, FastAPI, PostgreSQL, and pgvector. Keyword full-text search and vector similarity search run over the same database and are combined with Reciprocal Rank Fusion, behind a Redis response cache whose invalidation epoch lives in PostgreSQL so it commits atomically with writes. Embeddings sit behind a provider interface; the shipped implementation is a deterministic hashing baseline rather than a trained model.

### [Distributed Job Scheduler](https://github.com/ahmet-keles/distributed-job-scheduler) — in progress

Distributed job scheduler built with Java, Spring Boot, and PostgreSQL. Competing worker instances claim due jobs with `SELECT … FOR UPDATE SKIP LOCKED` — no broker or coordination service — and leases with heartbeats let any instance recover a crashed worker's jobs. Supports delayed and prioritized jobs, recurring UTC cron schedules, bounded exponential-backoff retries, and immutable per-attempt history under at-least-once execution. Verified with 75 automated tests.

### [Distributed Object Storage](https://github.com/ahmet-keles/distributed-object-storage) — in progress

Distributed object storage built with Java, Spring Boot, and PostgreSQL. A coordinator splits objects into fixed-size chunks, replicates each chunk across two storage nodes, and verifies every byte with SHA-256 end to end, so any single node can be lost without making an object unreadable. A background repair worker rebuilds missing replicas from a checksum-verified surviving copy, making a later second node loss survivable; end-to-end tests stop real node containers to prove it.

## Technologies

- **Languages:** Java, Python, C++, C#, JavaScript, SQL
- **Backend:** Spring Boot, FastAPI, Apache Kafka, REST APIs
- **Data:** PostgreSQL, pgvector, Redis, Flyway
- **Infrastructure:** Docker, Docker Compose, Testcontainers, GitHub Actions, AWS, Linux, Git

## Connect

- **GitHub:** [github.com/ahmet-keles](https://github.com/ahmet-keles)
- **LinkedIn:** [linkedin.com/in/ahmet-keles-91b33b228](https://www.linkedin.com/in/ahmet-keles-91b33b228/)
- **Portfolio:** [ahmet-keles.github.io](https://ahmet-keles.github.io)
