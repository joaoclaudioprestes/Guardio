# 🛡️ Guardio

**Guardio** é um projeto backend para um sistema de autenticação com Spring Boot, usando JWT, Spring Security e H2 em memória. Ideal para aplicações fullstack com Angular, React ou qualquer cliente que consuma APIs REST seguras.

---

## 🚀 Tecnologias

- Java 17
- Spring Boot
- Spring Security
- Spring Web
- Spring Data JPA
- H2 Database
- JWT (Auth0)
- Lombok

---

## 🔐 Endpoints de Autenticação

* `POST /auth/register`
  Cria um novo usuário e retorna um token JWT.

* `POST /auth/login`
  Autentica usuário e retorna um token JWT.

> Todos os demais endpoints exigem autenticação com header:
> `Authorization: Bearer <token>`

---

## 🧩 Estrutura de Pacotes

```
com.jprestes.guardio
│
├── controller
├── domain.entity.user
├── dto
├── infra.security
├── repositories
└── service
```

---

## 📌 Sobre

Este projeto é parte de estudos e desenvolvimento de aplicações seguras com autenticação JWT.
Backend desacoplado e pronto para integração com qualquer frontend.
