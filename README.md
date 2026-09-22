# Ahmet Keles

Computer Science student focused on backend engineering and distributed systems, building event-driven services in Java and Spring Boot.

## About

I'm a Computer Science student at The University of Texas at Dallas, graduating Fall 2027 and pursuing Summer 2027 software engineering internships. My primary interests are backend engineering and distributed systems, with a secondary interest in applied AI and retrieval systems. I enjoy building practical software projects focused on reliability, scalability, and real-world engineering problems.

## Featured Projects

### [Event-Driven Commerce](https://github.com/ahmet-keles/event-driven-commerce) — completed, v1.0.0

Event-driven commerce backend built with Java, Spring Boot, Kafka, and PostgreSQL. Three independent services coordinate orders, inventory, and payments while handling duplicate events, failures, and concurrent processing through reliability patterns such as transactional outbox, idempotency, saga compensation, retries, and optimistic locking. Verified with 345 automated tests. Read the [case study](https://ahmet-keles.github.io/projects/event-driven-commerce/): the decisions, the bugs found along the way, and what I would change.

### [NovaSearch](https://github.com/ahmet-keles/novasearch) — in progress

Hybrid search engine: PostgreSQL full-text and pgvector semantic retrieval behind one FastAPI service, fused with Reciprocal Rank Fusion. Milestone 1 is done; model-backed embeddings are next.

### [Distributed Job Scheduler](https://github.com/ahmet-keles/distributed-job-scheduler) — in progress

Background-job platform where competing workers coordinate through PostgreSQL row locks alone: `SKIP LOCKED` claims, leases, heartbeats, crash recovery, and fenced attempt history. Milestone 1 is done.

### [Distributed Object Storage](https://github.com/ahmet-keles/distributed-object-storage) — in progress

Objects split into chunks, replicated to two of three storage nodes, SHA-256-verified end to end, and readable through a node failure. Milestone 1 is done; repair and re-replication are next.

## Technologies

- **Languages:** Java, Python, C++, C#, JavaScript, SQL
- **Backend:** Spring Boot, Apache Kafka, REST APIs
- **Data:** PostgreSQL, Redis, Flyway
- **Infrastructure:** Docker, Docker Compose, Testcontainers, GitHub Actions, AWS, Linux, Git

## Writing

Notes from the projects above, at [ahmet-keles.github.io/writing](https://ahmet-keles.github.io/writing/) ([RSS](https://ahmet-keles.github.io/feed.xml)):

- [A transactional outbox that survives two replicas](https://ahmet-keles.github.io/writing/transactional-outbox-spring-boot/)
- [Idempotent Kafka consumers: the claim goes inside the transaction](https://ahmet-keles.github.io/writing/idempotent-kafka-consumers/)
- [Drawing wrap-around Karnaugh map loops on a canvas](https://ahmet-keles.github.io/writing/karnaugh-map-loops-canvas/)

## Connect

- **GitHub:** [github.com/ahmet-keles](https://github.com/ahmet-keles)
- **LinkedIn:** [linkedin.com/in/ahmet-keles-91b33b228](https://www.linkedin.com/in/ahmet-keles-91b33b228/)
- **Portfolio:** [ahmet-keles.github.io](https://ahmet-keles.github.io) · [what I am doing now](https://ahmet-keles.github.io/now/)
