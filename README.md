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

[GitHub Actions](https://github.com/lucianoLattante/commerceflow/actions/runs/45044196595) passed **128 unit tests and 160 integration tests** with MySQL, Kafka and Redis. The workflow starts the application with Docker Compose and exercises the simulated payment over HTTP.

[Architecture](https://github.com/lucianoLattante/commerceflow/blob/950b4c98f677847c48ec575ff3e2cd22ced22603/docs/ARCHITECTURE.md) · [Decisions and case study](https://github.com/lucianoLattante/commerceflow/blob/950b4c98f677847c48ec575ff3e2cd22ced22603/docs/CASE_STUDY.md) · [Local demo (Spanish)](https://github.com/lucianoLattante/commerceflow/blob/950b4c98f677847c48ec575ff3e2cd22ced22603/docs/LOCAL_TESTING.es.md) · [Simulated payment walkthrough (Spanish)](https://github.com/lucianoLattante/commerceflow/blob/950b4c98f677847c48ec575ff3e2cd22ced22603/docs/LOCAL_TESTING.es.md#7-pagar-y-consultar-la-evidencia)

This is personal portfolio work, separate from employer systems. Payments are synthetic; no production deployment or capacity benchmark is claimed.

**[LedgerCore — simulated transfers](https://github.com/lucianoLattante/ledgercore)**  
Java 21 and Spring Boot API backed by PostgreSQL, with immutable postings, idempotency, and compensating reversals. The [main branch run](https://github.com/lucianoLattante/ledgercore/actions/runs/45241679509) verifies concurrent debits and rollback using Testcontainers. [Design decision](https://github.com/lucianoLattante/ledgercore/blob/c6e26ff281e4bb80c72b25d10ba6ac2af74998d1/docs/adr-001-transfer-journal.md).

**[KnowledgeAI — private document retrieval](https://github.com/lucianoLattante/knowledgeai)**  
Java 21 API using Spring AI and pgvector. Search scopes document candidates by tenant and owner before ranking. The local provider returns cited excerpts. [Main branch run](https://github.com/lucianoLattante/knowledgeai/actions/runs/45246199593) · [Design decision](https://github.com/lucianoLattante/knowledgeai/blob/2bd50a4bd8819921ba3b45d06395abbc91ca2831/docs/adr-001-local-retrieval.md).

**[Portfolio website](https://lucianolattante.github.io/portfolio-web/en/)**  
Bilingual portfolio and downloadable résumé, with links to source and test evidence. [Repository](https://github.com/lucianoLattante/portfolio-web) · [Main branch verification](https://github.com/lucianoLattante/portfolio-web/actions/runs/45421372027) · [Deployment](https://github.com/lucianoLattante/portfolio-web/actions/runs/45432175655).

## Selected collaborative work

**[Somos Más — NGO REST API](https://github.com/lucianoLattante/OT167-Java-server)**  
Educational team project developed during Alkemy's Java acceleration program. The repository includes authentication, role-based rules, content management, DTOs, Swagger documentation and JUnit/Mockito test sources. It is a legacy learning project being reviewed for reproducibility and security.

My recorded contributions include [Swagger schemas](https://github.com/lucianoLattante/OT167-Java-server/commit/eaa51ebf9ac0adf8fdab1c10afb44c171dadbe99). Team attribution remains in the repository.

**[Recruitment application](https://github.com/lucianoLattante/Reclutamiento)**  
Collaborative Java/Spring MVC application for employer and candidate profiles. Preserved as an earlier team project.

Recent OT167 maintenance: [documentation](https://github.com/lucianoLattante/OT167-Java-server/pull/1) and [authentication/ownership hardening](https://github.com/lucianoLattante/OT167-Java-server/pull/2). These maintenance pull requests have been merged.

## Technical focus

- Professional backend work: Java, Spring Boot, Spring Framework, Quarkus, Node.js and REST APIs.
- Data experience: MySQL, PostgreSQL, SQL Server and DynamoDB.
- Engineering interests: domain modeling, transactional consistency, distributed systems and reliable asynchronous processing.
- Demonstrated in personal projects: Kafka, Redis, transactional outbox/inbox, Testcontainers, Docker Compose and GitHub Actions.
- Development workflow: JUnit, Mockito, Git and AI-assisted development with Codex, Claude Code and Windsurf.

[Español](README.es.md)
