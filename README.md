# 🔐 Spring Security In-Memory Authentication Example

This is a simple Spring Boot project demonstrating **In-Memory Authentication** using **Spring Security**.

## ✅ Features

- In-memory user authentication
- Secured REST endpoint: `/health`
- HTTP Basic Authentication
- Custom users defined in Java config
- Built with Spring Boot 3.5.0 and Java 21

---

## 👥 In-Memory Users

The following users are configured in `SecurityConfig.java`:

| Username | Password | Role  |
|----------|----------|-------|
| user1    | user1    | USER  |
| user2    | user2    | USER  |

> Passwords are stored using `{noop}` for plain text (not secure for production).

---


