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

[GitHub Actions](https://github.com/lucianoLattante/commerceflow/actions/runs/45044196595) aprobó **128 pruebas unitarias y 160 de integración** con MySQL, Kafka y Redis. El flujo levanta la aplicación con Docker Compose y prueba el pago simulado por HTTP.

[Arquitectura](https://github.com/lucianoLattante/commerceflow/blob/950b4c98f677847c48ec575ff3e2cd22ced22603/docs/ARCHITECTURE.md) · [Caso de estudio](https://github.com/lucianoLattante/commerceflow/blob/950b4c98f677847c48ec575ff3e2cd22ced22603/docs/CASE_STUDY.md) · [Probar en local con Swagger](https://github.com/lucianoLattante/commerceflow/blob/950b4c98f677847c48ec575ff3e2cd22ced22603/docs/LOCAL_TESTING.es.md) · [Ejemplo de pago simulado](https://github.com/lucianoLattante/commerceflow/blob/950b4c98f677847c48ec575ff3e2cd22ced22603/docs/LOCAL_TESTING.es.md#7-pagar-y-consultar-la-evidencia)

Es código personal de portfolio, separado del trabajo para el empleador. Los pagos son simulados; no se afirma despliegue productivo ni capacidad medida.

**[LedgerCore — transferencias simuladas](https://github.com/lucianoLattante/ledgercore)**  
API Java 21 y Spring Boot con PostgreSQL, asientos inmutables, idempotencia y reversos compensatorios. El [CI de main](https://github.com/lucianoLattante/ledgercore/actions/runs/45241679509) verificó débitos concurrentes y rollback con Testcontainers. [Decisión de diseño](https://github.com/lucianoLattante/ledgercore/blob/c6e26ff281e4bb80c72b25d10ba6ac2af74998d1/docs/adr-001-transfer-journal.md).

**[KnowledgeAI — búsqueda documental privada](https://github.com/lucianoLattante/knowledgeai)**  
API Java 21 con Spring AI y pgvector. Aplica aislamiento por organización y propietario antes del ranking. El proveedor local devuelve extractos con citas. [CI de main](https://github.com/lucianoLattante/knowledgeai/actions/runs/45246199593) · [Decisión de diseño](https://github.com/lucianoLattante/knowledgeai/blob/2bd50a4bd8819921ba3b45d06395abbc91ca2831/docs/adr-001-local-retrieval.md).

**[Portfolio web](https://lucianolattante.github.io/portfolio-web/)**  
Portfolio bilingüe con CV descargable y referencias a código y pruebas. [Repositorio](https://github.com/lucianoLattante/portfolio-web) · [Verificación en main](https://github.com/lucianoLattante/portfolio-web/actions/runs/45421372027) · [Despliegue](https://github.com/lucianoLattante/portfolio-web/actions/runs/45432175655).

## Proyectos colaborativos

**[Somos Más — API para una ONG](https://github.com/lucianoLattante/OT167-Java-server)**  
Proyecto educativo en equipo del programa de aceleración Java de Alkemy. Incluye autenticación, reglas por rol, gestión de contenido, DTOs, documentación Swagger y fuentes de tests JUnit/Mockito. El proyecto recibió mantenimiento de documentación y seguridad; sigue siendo un proyecto educativo histórico con limitaciones documentadas.

Mi contribución registrada incluye [esquemas Swagger](https://github.com/lucianoLattante/OT167-Java-server/commit/eaa51ebf9ac0adf8fdab1c10afb44c171dadbe99). Se preserva la autoría del equipo.

**[Aplicación de reclutamiento](https://github.com/lucianoLattante/Reclutamiento)**  
Proyecto colaborativo anterior con Java/Spring MVC, perfiles de empleadores y candidatos. Se conserva como evidencia de aprendizaje.

Mantenimiento reciente de OT167: [documentación](https://github.com/lucianoLattante/OT167-Java-server/pull/1) y [autenticación y control de propietario](https://github.com/lucianoLattante/OT167-Java-server/pull/2). Estos cambios de mantenimiento ya fueron integrados.

## Enfoque técnico

- Experiencia laboral: Java, Spring Boot, Spring Framework, Quarkus, Node.js, APIs REST, MySQL, PostgreSQL, SQL Server y DynamoDB.
- Intereses de ingeniería: modelado de dominio, consistencia transaccional, sistemas distribuidos y procesamiento asíncrono confiable.
- Demostrado en proyectos personales: Kafka, Redis, outbox/inbox, Testcontainers, Docker Compose y GitHub Actions.
- Flujo de desarrollo: JUnit, Mockito, Git y herramientas de asistencia como Codex, Claude Code y Windsurf.

[English](README.md)
