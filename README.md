# 🚀 Porto – Secure REST API with Spring Boot & JWT

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.0-brightgreen?logo=springboot)
![Java](https://img.shields.io/badge/Java-17-blue?logo=java)
![JWT](https://img.shields.io/badge/JWT-Security-orange?logo=jsonwebtokens)
![Database](https://img.shields.io/badge/DB-H2%20InMemory-lightgrey?logo=databricks)
![License](https://img.shields.io/badge/License-MIT-green)
![Build](https://img.shields.io/badge/Build-Passing-success?logo=maven)

> **Porto** is a **Spring Boot 3.2.0** backend project that demonstrates building **secure REST APIs** with **JWT authentication**, **Spring Security**, and **in-memory database (H2)** for fast testing and deployment.

---

## ✨ Key Features

### 🔐 **Authentication & Authorization**
- Secure APIs with **Spring Security**.
- **JWT Token-based Authentication**:
  - Token generation on login
  - Token validation for protected routes
  - Role-based access control.

### 🌐 **RESTful Web API**
- Built using **Spring Boot Starter Web** for lightweight HTTP endpoints.
- Supports **JSON-based communication**.
- **SOAP Web Services** support included for extended integrations.

### 🗄️ **Database & Persistence**
- **Spring Data JPA** for seamless CRUD operations.
- **H2 In-Memory Database** for instant testing (no external setup needed).
- Automatic **schema creation** on application startup.

### ⚡ **Developer Experience**
- **Lombok** reduces boilerplate (getters, setters, constructors).
- **Apache Commons Lang3** provides utilities for strings and objects.
- **jFiglet** adds custom ASCII banners to application startup logs.

### ✅ **Testing Ready**
- **JUnit 5** and **Spring Boot Test** for integration tests.
- **Spring Security Test** for testing secured endpoints.

---

## 🛠️ Tech Stack

| Layer            | Technology                                       |
|-------------------|------------------------------------------------|
| **Language**      | Java 17                                        |
| **Framework**     | Spring Boot 3.2.0                              |
| **Security**      | Spring Security + JWT (JJWT 0.12.5)            |
| **Database**      | H2 (In-memory)                                 |
| **Persistence**   | Spring Data JPA (Hibernate)                    |
| **Utilities**     | Lombok, Apache Commons Lang3, jFiglet          |
| **Build Tool**    | Maven                                          |
| **Testing**       | JUnit 5, Mockito, Spring Security Test         |

---

## ⚙️ Getting Started

### ✅ Prerequisites
- Java 17+
- Maven 3.9+
- (Optional) Postman for API testing

### 🚀 Build & Run

```bash
# Clone the repository
git clone https://github.com/your-username/porto.git
cd porto

# Build the project
mvn clean install

# Run the application
mvn spring-boot:run
