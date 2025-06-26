
# 🗄️ Databases

This repository consolidates the most relevant concepts of **Database Systems**, focusing on both theoretical foundations and practical implementations. It integrates secure design principles, backend interaction, and vulnerability testing — all essential skills for cloud infrastructure and enterprise systems.

---

## 📁 Repository Structure

```bash
databases/
├── theory/             # 📚 Notes on database concepts and architecture
│   ├── normalization.md
│   ├── relational_algebra.md
│   ├── dbms_internals.md
│   ├── indexing_storage.md
│   ├── transactions.md
│   └── sql_injection.md
│
├── practice/           # 💻 SQL queries and JDBC/Spring Boot integration
│   ├── sql_queries/
│   ├── jdbc_examples/
│   └── springboot_orm/
│
├── projects/           # 🚧 Projects ranging from basic CRUD to secure systems
│   ├── student-records-db/
│   ├── library-api-jdbc/
│   ├── bookstore-springboot/
│   └── injection-lab/
│
└── README.md
```

---

## 🎯 Objectives

- Master the design and structure of robust, normalized databases
- Understand DBMS internals, indexing, and transaction control
- Explore secure practices to mitigate vulnerabilities like SQL injection
- Connect and manipulate databases using **JDBC** and **Spring Boot**

---

## 📚 Theory Coverage

Inside `/theory` you'll find:
- 🔹 Entity-Relationship modeling and relational schema design
- 🔹 Normal forms: 1NF, 2NF, 3NF, BCNF
- 🔹 Relational algebra and constraints
- 🔹 Indexing methods and data storage layers
- 🔹 Transaction properties: ACID, isolation levels
- 🔹 How SQL injection works and how to prevent it

---

## 💻 Practice Programs

The `/practice` folder includes:
- Handwritten SQL for selection, joins, subqueries, grouping
- JDBC snippets using vanilla Java to query and update DBs
- Spring Boot examples using ORM (e.g. JPA, Hibernate)

---

## 🚀 Projects

The `/projects` folder includes:
- 📌 `student-records-db`: simple CRUD system in raw SQL
- 📌 `library-api-jdbc`: full-stack Java app using JDBC
- 📌 `bookstore-springboot`: backend with RESTful API and secure access
- 📌 `injection-lab`: flawed DB setup to explore SQL injection and defenses

Each project includes:
- `README.md` with architecture and setup steps
- Schema definition files
- Test cases or sample datasets

---

## 🛠️ Technologies Used

- `SQL` (PostgreSQL or MySQL)
- `Java` + `JDBC` or `Spring Boot`
- `Hibernate`, `JPA`
- `Docker` (optional for DB containerization)

---

## 📎 Notes

This repository emphasizes how data integrity, efficiency, and **security** come together in cloud applications. Special attention is paid to practical risks (e.g. SQLi) and enterprise-ready design patterns.

---
