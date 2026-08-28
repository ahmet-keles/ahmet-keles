# Ahmet Keles

Computer Science student focused on backend engineering and distributed systems, building event-driven services in Java and Spring Boot.

## About

I'm a Computer Science student at The University of Texas at Dallas (expected graduation Fall 2027), looking for Summer 2027 software engineering internships in backend and distributed systems, with a secondary interest in applied AI and retrieval-augmented generation. I like building systems the production way — sagas with compensation, transactional outboxes, idempotent consumers — and proving they work with real integration tests.

## Featured Projects

### [Event-Driven Commerce](https://github.com/ahmet-keles/event-driven-commerce) — completed, v1.0.0

Event-driven microservices platform in Java 21 and Spring Boot: order, inventory, and payment services coordinated over Apache Kafka, each with its own PostgreSQL database. Implements a saga with compensation (declined payments release reserved stock), transactional outbox publishing safe for multiple replicas, durable consumer-side event deduplication, and retry/backoff with dead-letter topics. Verified by per-service Testcontainers suites and a cross-service end-to-end suite in GitHub Actions; runs locally with Docker Compose.

### [NovaSearch](https://github.com/ahmet-keles/novasearch) — in progress

Distributed full-text search engine.

### [Distributed Job Scheduler](https://github.com/ahmet-keles/distributed-job-scheduler) — in progress

Distributed job scheduling and workflow engine.

### [Distributed Object Storage](https://github.com/ahmet-keles/distributed-object-storage) — in progress

Distributed object storage system.

## Technologies

- **Languages:** Java, Python, C++, C#, JavaScript, SQL
- **Backend:** Spring Boot, Apache Kafka, REST APIs
- **Data:** PostgreSQL, Redis, Flyway
- **Infrastructure:** Docker, Docker Compose, Testcontainers, GitHub Actions, AWS, Linux, Git

## Connect

- **GitHub:** [github.com/ahmet-keles](https://github.com/ahmet-keles)
- **LinkedIn:** [linkedin.com/in/ahmet-keles-91b33b228](https://www.linkedin.com/in/ahmet-keles-91b33b228/)
- **Portfolio:** [ahmet-keles.github.io](https://ahmet-keles.github.io)
