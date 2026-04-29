# Spring Security JWT API

This project demonstrates a **REST API secured with Spring Security and JWT (JSON Web Token)** using Spring Boot.

---

## Overview

The system provides authentication and authorization using **JWT-based security**, allowing secure access to protected endpoints.

Users authenticate using credentials and receive a token, which must be sent in requests to access secured resources.

---

## Technologies

- Java 17+
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- Maven

---

## Features

- User authentication
- JWT token generation
- Token validation
- Protected endpoints
- Role-based access control (if applicable)

---

## Authentication Flow

1. User sends login credentials  
2. Server validates credentials  
3. JWT token is generated  
4. Client stores token  
5. Token is sent in Authorization header  
6. Server validates token for each request  

---

## How to Run

### 1. Clone the project
```bash
git clone https://github.com/joazefrancisco/spring-security-jwt-api
