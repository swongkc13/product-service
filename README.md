# 📦 Product-Service

A minimal Spring Boot microservice created as part of a 30-Day Full-Stack Java to DevOps roadmap. This service will eventually integrate into a microservice architecture alongside other services like `hello-service`, using Spring Cloud components and containerization with Docker.

---

## 🚀 Overview

This microservice is responsible for handling product-related operations. It is part of a larger system where each microservice has a single responsibility and communicates via HTTP or service discovery.

---

## ✅ Features

- Java 17 + Spring Boot 3.5.3
- Clean REST API endpoint (`/products`)
- Environment-based config (`application-local.properties`)
- PostgreSQL integration via Docker Compose
- Profile switching (`local`)
- Maven-based build and dependency management
- Runs independently on port `8081`

---

## 🧪 API Endpoints

### GET `/products`

Returns a test response to verify the service is running.

```bash
curl http://localhost:8081/products