## Spring Data JPA - Query creation

https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.query-methods.query-creation


1. PostgreSQL / MySQL / H2 / MariaDB / SQL Server ...
2. JDBC
3. Hibernate (ORM)
4. Spring Data JPA <-- Estamos aquí


--- Arquitectura capas:

POSTMAN --> REST Repositorio
POSTMAN --> Controlador --> Repositorio --> Base de datos (PostgreSQL)
POSTMAN --> Controlador --> Servicio --> Repositorio --> Base de datos (PostgreSQL)




Angular (Navegador) --> Controlador (+ Seguridad JWT) --> Servicio --> Repositorio --> Base de datos
(Frontend: Vercel) --> (Backend: Heroku)

