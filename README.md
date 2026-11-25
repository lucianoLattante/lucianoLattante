# Hi, I'm Luciano Lattante

Backend Software Engineer based in Santa Fe, Argentina, with 4+ years of professional experience.

I work with Java and Spring Boot, building and maintaining backend services and REST APIs. My current work at Mercado Libre includes purchase-order processing and MySQL query and schema optimization.

[LinkedIn](https://linkedin.com/in/luciano-lattante) · [GitHub](https://github.com/lucianoLattante) · [Email](mailto:lattanteluciano@gmail.com) · [Portfolio](https://lucianolattante.github.io/portfolio-web/en/)

## Professional experience

| Company | Period | Focus |
| --- | --- | --- |
| Mercado Libre | May 2023–present | Java 17/21/25, Spring Boot, order-processing microservices, MySQL |
| Experta / ASAP Consulting | Oct 2022–Apr 2023 | Personal finance backend; Java 11, Quarkus, Node.js, AWS, DynamoDB, PostgreSQL |
| Aufiero Informática | May–Aug 2022 | Java 8, Groovy, Grails and SQL |
| Casimiro Zbikoski | Dec 2021–Feb 2022 | Full-stack development with Java, Spring Framework and SQL Server |

## Featured personal projects

**[CommerceFlow — commerce processing backend](https://github.com/lucianoLattante/commerceflow)**  
Original Java 21 / Spring Boot modular monolith with MySQL, Kafka and Redis. The local functional MVP includes transactional stock reservations, scoped idempotency, outbox/inbox processing, simulated payments, audited ADMIN recovery and role/catalog administration.

CI passed **128 unit tests and 160 integration tests** and exercised order flows over HTTP in Docker Compose. A reproducible MySQL experiment on **50,000 synthetic deliveries** compares offset and cursor pagination under committed state changes and measures the candidate index's write cost. [CI](https://github.com/lucianoLattante/commerceflow/actions/runs/45541230478) · [Experiment](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/CONTENTION.md)

[Architecture](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/ARCHITECTURE.md) · [Decisions and case study](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/CASE_STUDY.md) · [Local demo (Spanish)](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/LOCAL_TESTING.es.md) · [Simulated payment walkthrough (Spanish)](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/LOCAL_TESTING.es.md#7-pagar-y-consultar-la-evidencia)

This is personal portfolio work, separate from employer systems. Payments are synthetic; no production deployment or capacity benchmark is claimed.

**[LedgerCore — simulated transfers](https://github.com/lucianoLattante/ledgercore)**  
Java 21 and Spring Boot API backed by PostgreSQL, with immutable postings, idempotency, compensating reversals, and account reconciliation. Integration tests run the API with a restricted database role while a separate login applies Flyway migrations. [CI](https://github.com/lucianoLattante/ledgercore/actions/runs/45541202715) · [Database roles](https://github.com/lucianoLattante/ledgercore/blob/afe6f05b5dce9c22b15b6226c06ae92b3a60daba/docs/DATABASE_ROLES.md) · [Design decision](https://github.com/lucianoLattante/ledgercore/blob/afe6f05b5dce9c22b15b6226c06ae92b3a60daba/docs/adr-001-transfer-journal.md)

**[KnowledgeAI — private document retrieval](https://github.com/lucianoLattante/knowledgeai)**  
Java 21 API using Spring AI and pgvector. Ranking is scoped to the authenticated tenant and owner, and the offline provider returns cited excerpts. The PostgreSQL suite covers citation isolation, abstention, and competing uploads for the last slot in a configurable per-owner document limit. [CI](https://github.com/lucianoLattante/knowledgeai/actions/runs/45620226691) · [Retrieval evaluation](https://github.com/lucianoLattante/knowledgeai/blob/046993307578b52b4dcba5f61f9362d7951e9a82/docs/RETRIEVAL_EVALUATION.md)

**[Portfolio website](https://lucianolattante.github.io/portfolio-web/en/)**  
Bilingual portfolio and downloadable résumé, with links to source and test evidence. [Repository](https://github.com/lucianoLattante/portfolio-web) · [Main branch verification](https://github.com/lucianoLattante/portfolio-web/actions/runs/45453650710) · [Deployment](https://github.com/lucianoLattante/portfolio-web/actions/runs/45454762853).

## Selected collaborative work

**[Somos Más — NGO REST API](https://github.com/lucianoLattante/OT167-Java-server)**  
Educational team project developed during Alkemy's Java acceleration program. The repository includes authentication, role-based rules, content management, DTOs, Swagger documentation and JUnit/Mockito test sources. It is a legacy learning project being reviewed for reproducibility and security.

My recorded contributions include [Swagger schemas](https://github.com/lucianoLattante/OT167-Java-server/commit/eaa51ebf9ac0adf8fdab1c10afb44c171dadbe99). Team attribution remains in the repository.

**[Recruitment application](https://github.com/lucianoLattante/Reclutamiento)**  
Collaborative Java/Spring MVC application for employer and candidate profiles. Preserved as an earlier team project.

Recent OT167 maintenance includes documentation, authentication and ownership checks, and stricter demo startup and image upload validation. [Documentation](https://github.com/lucianoLattante/OT167-Java-server/pull/1) · [Authentication and ownership](https://github.com/lucianoLattante/OT167-Java-server/pull/2) · [Demo and uploads](https://github.com/lucianoLattante/OT167-Java-server/pull/3)

## Technical focus

- Professional backend work: Java, Spring Boot, Spring Framework, Quarkus, Node.js and REST APIs.
- Data experience: MySQL, PostgreSQL, SQL Server and DynamoDB.
- Engineering interests: domain modeling, transactional consistency, distributed systems and reliable asynchronous processing.
- Demonstrated in personal projects: Kafka, Redis, transactional outbox/inbox, Testcontainers, Docker Compose and GitHub Actions.
- Development workflow: JUnit, Mockito, Git and AI-assisted development with Codex, Claude Code and Windsurf.

[Español](README.es.md)
