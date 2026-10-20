# 🛒 E-Commerce REST API

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)

A REST API for a mini e-commerce platform, built with **Java 21** and **Spring Boot**.

> 🚧 **Status: foundation in place, actively being built.** The project skeleton (Spring Boot app, Maven wrapper, JPA/Validation/WebMVC stack, PostgreSQL driver) is set up — business endpoints are landing next.

## 🛠️ Stack

- **Java 21** · **Spring Boot 4.x**
- **Spring Data JPA** — persistence layer
- **Spring Validation** — request validation
- **PostgreSQL** — database (runtime driver)
- **Maven** — build tool (wrapper included)

## 🚀 Getting started

**Prerequisites:** Java 21+, PostgreSQL

```bash
git clone https://github.com/medreda091/ecommerce-api.git
cd ecommerce-api

# Configure the datasource in src/main/resources/application.properties,
# then run:
./mvnw spring-boot:run
```

The API starts on http://localhost:8080.

## 📌 Roadmap

- [ ] Product & category resources (CRUD)
- [ ] Orders and cart management
- [ ] Authentication & authorization (JWT)
- [ ] Global error handling & API documentation (OpenAPI)

## 👤 Author

**Reda Ait Smouguen** — Master 1 Computer Science @ Université Claude Bernard Lyon 1

- GitHub: [@medreda091](https://github.com/medreda091)
- LinkedIn: [reda-ait-smouguen](https://www.linkedin.com/in/reda-ait-smouguen-4b7b79200)
