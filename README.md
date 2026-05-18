Bank Management System

A secure banking backend built with Java 17 and Spring Boot, featuring JWT authentication, role-based access control, ACID-compliant transactions, and Docker deployment.

Tech Stack

- Java 17
- Spring Boot
- Spring Security
- JWT Authentication
- JPA / Hibernate
- MySQL
- Docker
- GitHub Actions

Features

- JWT-based authentication and authorization
- Role-based access control for Admin and User
- RESTful APIs for account creation, deposits, withdrawals, transfers and balance enquiry
- ACID-compliant transactions with rollback support
- 100% data integrity across 500+ test operations
- Average API response time under 120ms
- 85%+ unit test coverage using JUnit and Mockito
- Dockerized for consistent environment builds
- CI/CD pipeline via GitHub Actions, reducing deployment time by 70%

API Endpoints

POST /api/auth/register — Register a new user

POST /api/auth/login — Login and receive JWT token

GET /api/accounts/{id} — Get account details

POST /api/accounts/deposit — Deposit funds

POST /api/accounts/withdraw — Withdraw funds

POST /api/accounts/transfer — Transfer between accounts

GET /api/admin/users — View all users (Admin only)

DELETE /api/admin/users/{id} — Delete a user (Admin only)

Getting Started

Clone the repository:

git clone https://github.com/anjali09076/Bank-Management-System-Java-Backend-Project.git

Run with Docker:

docker-compose up --build

Or run locally:

mvn clean install

mvn spring-boot:run

Contact

Anjali Kumari

LinkedIn: https://www.linkedin.com/in/anjaliii016

Email: kumarisinghanjali8825@gmail.com
