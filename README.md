# 📋 Focus Planner
### Task Management System

> **4th Semester Project I** &nbsp;|&nbsp; BCA &nbsp;|&nbsp; Deadline: 3 Months &nbsp;|&nbsp; Date: June 11, 2025

---

## 🗂️ Table of Contents

- [Project Overview](#-project-overview)
- [Tech Stack](#-tech-stack)
- [Dependencies](#-dependencies)
- [Summary](#-summary)

---

## 📌 Project Overview

| Field | Details |
|-------|---------|
| **Project Name** | Focus Planner |
| **Type** | Task Management System |
| **Course** | 4th Semester Project I (BCA) |
| **Date** | June 11, 2025 |
| **Deadline** | 3 Months |
| **Status** | 🚧 In Development |

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| **Frontend** | HTML, CSS, JavaScript | User Interface & Interaction |
| **Backend** | Java / Spring Boot | REST API & Business Logic |
| **Database** | PostgreSQL | Data Persistence |
| **Security** | Spring Security + BCrypt | Authentication & Authorization |
| **ORM** | Spring Data JPA / Hibernate | Database Management |
| **Validation** | Bean Validation API | Input Validation |
| **Dev Tools** | Lombok + Spring DevTools | Developer Productivity |

---

## 📦 Dependencies

This project uses the following Spring Boot dependencies to simplify development, improve security, and provide efficient database management.

---

### 1. 🔐 Spring Security
**Purpose:** Authentication and Authorization

Secures the application by providing authentication and access control mechanisms. Protects REST APIs, encrypts passwords using BCrypt, and manages user login and authorization.

**Features:**
- User Authentication
- User Authorization
- Password Encryption (BCrypt)
- API Security
- JWT Integration Support

---

### 2. 🌐 Spring Web
**Purpose:** REST API Development

Provides the necessary tools for building web applications and RESTful APIs. Enables HTTP-based communication between the frontend and backend with an embedded Tomcat server.

**Features:**
- REST API Development
- Request Mapping
- JSON Data Handling
- Embedded Tomcat Server

---

### 3. 🗄️ Spring Data JPA
**Purpose:** Database Management

Simplifies database operations using the repository pattern. Uses Hibernate as the default ORM framework, reducing boilerplate database code significantly.

**Features:**
- CRUD Operations
- Object Relational Mapping (ORM)
- Repository Pattern
- Database Query Support

---

### 4. 🐘 PostgreSQL Driver
**Purpose:** Database Connectivity

Establishes a connection between the Spring Boot application and the PostgreSQL database, enabling all database operations through JDBC.

**Features:**
- PostgreSQL Database Connection
- JDBC Support
- Efficient Data Communication

---

### 5. ✅ Validation
**Purpose:** Data Validation

Ensures incoming user data meets predefined rules before being processed or stored in the database, maintaining data integrity.

**Features:**
- Input Validation
- Constraint Checking
- Error Handling
- Data Integrity

**Example:**
```java
@NotBlank
private String description;
```

---

### 6. ⚡ Lombok
**Purpose:** Reduce Boilerplate Code

Automatically generates common Java methods (getters, setters, constructors, builders) during compilation, resulting in cleaner and more maintainable code.

**Features:**
- Automatic Getter/Setter Generation
- Constructor Generation
- Builder Pattern Support
- Cleaner Codebase

**Example:**
```java
@Getter
@Setter
@NoArgsConstructor
@AllArgsConstructor
public class Task {
}
```

---

### 7. 🔄 Spring Boot DevTools
**Purpose:** Development Productivity

Improves the development experience with automatic application restart on code changes and live reload support, speeding up the development cycle.

**Features:**
- Automatic Restart
- Live Reload Support
- Faster Development Cycle
- Development-Time Configuration

---

## 📊 Summary

| Dependency | Purpose |
|------------|---------|
| **Spring Security** | Authentication and Authorization |
| **Spring Web** | REST API Development |
| **Spring Data JPA** | Database Operations |
| **PostgreSQL Driver** | PostgreSQL Connectivity |
| **Validation** | Input Validation |
| **Lombok** | Reduce Boilerplate Code |
| **Spring Boot DevTools** | Faster Development Experience |

---

<div align="center">
  <sub>Focus Planner &nbsp;|&nbsp; Task Management System &nbsp;|&nbsp; BCA 4th Semester Project I</sub>
</div>
