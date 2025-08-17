📌 RESTful Web Services (Spring Boot)
📖 Overview

A Spring Boot REST API project that manages Users and their Posts.
It demonstrates REST principles, HATEOAS, Spring Data JPA, and Spring Security.

🎯 Features

CRUD APIs for Users and Posts

One-to-Many relation (User → Posts)

Basic Authentication with Spring Security

H2 In-Memory DB for storage

HATEOAS links in responses

▶️ Run
mvn spring-boot:run


API Root → http://localhost:8080

H2 Console → http://localhost:8080/h2-console

🔐 Security

All endpoints are secured with Basic Auth.
Example:

curl -u admin:admin http://localhost:8080/users

🌐 API Endpoints
Users

GET /users → All users

GET /users/{id} → User by ID

POST /users → Create user

DELETE /users/{id} → Delete user

Posts

GET /posts → All posts

GET /posts/{id} → Post by ID

POST /posts → Create post

DELETE /posts/{id} → Delete post

📂 Structure
user/      → Entities & Controllers
jpa/       → Repositories
security/  → Auth config


✅ Motivation: Learn Spring Boot REST API development, database integration, and security.
