# Hola, soy Luciano Lattante

Backend Software Engineer en Santa Fe, Argentina, con más de cuatro años de experiencia profesional. Trabajo principalmente con Java y Spring Boot, APIs REST y servicios backend. En Mercado Libre desarrollo y mantengo microservicios de procesamiento de órdenes y optimizo consultas y esquemas MySQL.

[LinkedIn](https://linkedin.com/in/luciano-lattante) | [GitHub](https://github.com/lucianoLattante) | [Correo](mailto:lattanteluciano@gmail.com) | [Portfolio](https://lucianolattante.github.io/portfolio-web/)

## Experiencia profesional

| Empresa | Período | Enfoque |
| --- | --- | --- |
| Mercado Libre | Mayo de 2023–actualidad | Java 17/21/25, Spring Boot, microservicios de órdenes y MySQL |
| Experta / ASAP Consulting | Octubre de 2022–abril de 2023 | Backend de finanzas personales; Java 11, Quarkus, Node.js, AWS, DynamoDB y PostgreSQL |
| Aufiero Informática | Mayo–agosto de 2022 | Java 8, Groovy, Grails y SQL |
| Casimiro Zbikoski | Diciembre de 2021–febrero de 2022 | Desarrollo full stack con Java, Spring Framework y SQL Server |

## Proyectos personales destacados

**[CommerceFlow — backend de procesamiento de e-commerce](https://github.com/lucianoLattante/commerceflow)**  
Monolito modular original con Java 21, Spring Boot, MySQL, Kafka y Redis. Su MVP local funcional incluye reservas transaccionales de stock, idempotencia por usuario, outbox/inbox, pagos simulados, recuperación ADMIN auditada y administración de usuarios/productos.

CI aprobó **128 pruebas unitarias y 160 de integración** y ejecutó flujos de pedidos por HTTP en Docker Compose. Un experimento reproducible en MySQL con **50.000 entregas sintéticas** compara la paginación por offset y por cursor cuando cambian los estados confirmados y mide el costo de escritura del índice candidato. [CI](https://github.com/lucianoLattante/commerceflow/actions/runs/45541230478) · [Experimento](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/CONTENTION.md)

[Arquitectura](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/ARCHITECTURE.md) · [Caso de estudio](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/CASE_STUDY.md) · [Probar en local con Swagger](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/LOCAL_TESTING.es.md) · [Ejemplo de pago simulado](https://github.com/lucianoLattante/commerceflow/blob/cc82414bbcd5063e281d7e0e8baac4e9157ca70d/docs/LOCAL_TESTING.es.md#7-pagar-y-consultar-la-evidencia)

Es código personal de portfolio, separado del trabajo para el empleador. Los pagos son simulados; no se afirma despliegue productivo ni capacidad medida.

**[LedgerCore — transferencias simuladas](https://github.com/lucianoLattante/ledgercore)**  
API Java 21 y Spring Boot con PostgreSQL, asientos inmutables, idempotencia, reversos compensatorios y reconciliación por cuenta. Las pruebas de integración ejecutan la API con un usuario de base de datos restringido y aplican las migraciones Flyway con otro usuario. [CI](https://github.com/lucianoLattante/ledgercore/actions/runs/45541202715) · [Roles de base de datos](https://github.com/lucianoLattante/ledgercore/blob/afe6f05b5dce9c22b15b6226c06ae92b3a60daba/docs/DATABASE_ROLES.md) · [Decisión de diseño](https://github.com/lucianoLattante/ledgercore/blob/afe6f05b5dce9c22b15b6226c06ae92b3a60daba/docs/adr-001-transfer-journal.md)

**[KnowledgeAI — búsqueda documental privada](https://github.com/lucianoLattante/knowledgeai)**  
API Java 21 con Spring AI y pgvector. La búsqueda ordena solo documentos de la organización y propietario autenticados, y el proveedor local devuelve extractos con citas. La suite de PostgreSQL verifica el aislamiento de las citas, la abstención y dos cargas que compiten por el último cupo de un límite configurable por propietario. [CI](https://github.com/lucianoLattante/knowledgeai/actions/runs/45620226691) · [Evaluación de recuperación](https://github.com/lucianoLattante/knowledgeai/blob/046993307578b52b4dcba5f61f9362d7951e9a82/docs/RETRIEVAL_EVALUATION.md)

**[Portfolio web](https://lucianolattante.github.io/portfolio-web/)**  
Portfolio bilingüe con CV descargable y referencias a código y pruebas. [Repositorio](https://github.com/lucianoLattante/portfolio-web) · [Verificación en main](https://github.com/lucianoLattante/portfolio-web/actions/runs/45453650710) · [Despliegue](https://github.com/lucianoLattante/portfolio-web/actions/runs/45454762853).

## Proyectos colaborativos

**[Somos Más — API para una ONG](https://github.com/lucianoLattante/OT167-Java-server)**  
Proyecto educativo en equipo del programa de aceleración Java de Alkemy. Incluye autenticación, reglas por rol, gestión de contenido, DTOs, documentación Swagger y fuentes de tests JUnit/Mockito. El proyecto recibió mantenimiento de documentación y seguridad; sigue siendo un proyecto educativo histórico con limitaciones documentadas.

Mi contribución registrada incluye [esquemas Swagger](https://github.com/lucianoLattante/OT167-Java-server/commit/eaa51ebf9ac0adf8fdab1c10afb44c171dadbe99). Se preserva la autoría del equipo.

**[Aplicación de reclutamiento](https://github.com/lucianoLattante/Reclutamiento)**  
Proyecto colaborativo anterior con Java/Spring MVC, perfiles de empleadores y candidatos. Se conserva como evidencia de aprendizaje.

El mantenimiento reciente de OT167 incluye documentación, controles de autenticación y propietario, y validaciones de arranque de la demo y de carga de imágenes. [Documentación](https://github.com/lucianoLattante/OT167-Java-server/pull/1) · [Autenticación y propietario](https://github.com/lucianoLattante/OT167-Java-server/pull/2) · [Demo y cargas](https://github.com/lucianoLattante/OT167-Java-server/pull/3)

## Enfoque técnico

- Experiencia laboral: Java, Spring Boot, Spring Framework, Quarkus, Node.js, APIs REST, MySQL, PostgreSQL, SQL Server y DynamoDB.
- Intereses de ingeniería: modelado de dominio, consistencia transaccional, sistemas distribuidos y procesamiento asíncrono confiable.
- Demostrado en proyectos personales: Kafka, Redis, outbox/inbox, Testcontainers, Docker Compose y GitHub Actions.
- Flujo de desarrollo: JUnit, Mockito, Git y herramientas de asistencia como Codex, Claude Code y Windsurf.

[English](README.md)
