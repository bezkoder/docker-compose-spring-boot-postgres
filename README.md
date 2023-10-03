# Docker Compose Spring Boot and Postgres example

## Run the System
We can easily run the whole with only a single command:
```bash
docker compose up
```

Docker will pull the PostgreSQL and Spring Boot images (if our machine does not have it before).

The services can be run on the background with command:
```bash
docker compose up -d
```

## Stop the System
Stopping all the running containers is also simple with a single command:
```bash
docker compose down
```

If you need to stop and remove all containers, networks, and all images used by any service in <em>docker-compose.yml</em> file, use the command:
```bash
docker compose down --rmi all
```

For more detail, please visit:
> [Docker Compose Spring Boot and Postgres](https://www.bezkoder.com/docker-compose-spring-boot-postgres/)

Related Posts:
> [Spring Boot + PostgreSQL: CRUD Rest API example](https://www.bezkoder.com/spring-boot-postgresql-example/)

> [Spring Boot R2DBC + PostgreSQL example](https://www.bezkoder.com/spring-boot-r2dbc-postgresql/)

> [Spring Boot Validate Request Body](https://www.bezkoder.com/spring-boot-validate-request-body/)

> [Spring Boot and Swagger 3 example](https://www.bezkoder.com/spring-boot-swagger-3/)

> [Spring Boot Redis Cache example](https://www.bezkoder.com/spring-boot-redis-cache-example/)

> [Spring Boot File upload example](https://www.bezkoder.com/spring-boot-file-upload/)

> [Exception handling: @RestControllerAdvice example in Spring Boot](https://www.bezkoder.com/spring-boot-restcontrolleradvice/)

> [Spring Boot Repository Unit Test with @DataJpaTest](https://www.bezkoder.com/spring-boot-unit-test-jpa-repo-datajpatest/)

> [Spring Boot Rest Controller Unit Test with @WebMvcTest](https://www.bezkoder.com/spring-boot-webmvctest/)

Security:
> [Secure Spring Boot App with Spring Security & JWT Authentication (PostgreSQL)](https://www.bezkoder.com/spring-boot-security-postgresql-jwt-authentication/)
