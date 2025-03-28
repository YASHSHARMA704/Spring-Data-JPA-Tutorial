# 🚀 Spring Data JPA Tutorial with Spring Boot 🌱

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.3-green?style=flat-square&logo=springboot) ![Hibernate](https://img.shields.io/badge/Hibernate-5.6.10-blue?style=flat-square&logo=hibernate) ![MySQL](https://img.shields.io/badge/MySQL-8.0-orange?style=flat-square&logo=mysql) ![Java](https://img.shields.io/badge/Java-17-red?style=flat-square&logo=java)

---

## 📖 Overview
This repository provides a **comprehensive tutorial** on **Spring Data JPA** using **Spring Boot**. It covers fundamental to advanced concepts, helping developers integrate relational databases seamlessly.

### 🌟 Features
✔️ Spring Boot & JPA Integration  
✔️ CRUD Operations  
✔️ JPA Relationships (One-To-One, One-To-Many, Many-To-Many)  
✔️ Query Methods, JPQL & Native Queries  
✔️ Paging & Sorting  
✔️ Transaction Management  
✔️ Embedded Entities & Cascade Types  

---

## 📚 Table of Contents
- [📖 Overview](#-overview)
- [🌟 Features](#-features)
- [⚙️ Technologies Used](#-technologies-used)
- [🚀 Getting Started](#-getting-started)
- [📌 Usage](#-usage)
- [📚 Topics Covered](#-topics-covered)

---

## ⚙️ Technologies Used
- **Spring Boot** 🌱
- **Spring Data JPA** 🗄️
- **Hibernate** 🏗️
- **MySQL / H2 / PostgreSQL** (Configurable) 🗃️
- **Lombok** 🏷️
- **Maven** 📦

---

## 🚀 Getting Started
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YASHSHARMA704/Spring-Data-JPA-Tutorial.git
cd Spring-Data-JPA-Tutorial
```
### 2️⃣ Configure Database
Modify `application.properties` to set up your database:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/yourdb
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```
### 3️⃣ Build & Run
```bash
mvn spring-boot:run
```

---

## 📌 Usage
- Test APIs using **Postman** or **cURL**
- Sample API Endpoints:
  - `GET /api/employees` → Fetch all employees 👥
  - `POST /api/employees` → Add a new employee 📝
  - `PUT /api/employees/{id}` → Update employee details 🔄
  - `DELETE /api/employees/{id}` → Remove an employee ❌

---

## 📚 Topics Covered
| Topic | Description |
|------------------------------------------------|-----------------------------|
| **Intro** | Introduction to the tutorial |
| **What is Spring Data JPA?** | Overview of Spring Data JPA |
| **Connecting Spring Boot App with DB** | Setting up database connectivity |
| **Mapping Entities with DB** | Defining entity classes |
| **Different JPA Annotations** | Explanation of JPA annotations |
| **Understanding Repositories and Their Methods** | How repositories work in JPA |
| **@Embeddable and @Embedded** | Working with embedded objects |
| **Creating JPA Repositories & Methods** | Implementing repository methods |
| **@Query Annotation** | Custom queries using @Query annotation |
| **Native Queries** | Executing raw SQL queries |
| **Query Named Parameters** | Using named parameters in queries |
| **@Transactional and @Modifying Annotation** | Managing transactions and updates |
| **JPA One-To-One Relationship** | Implementing One-To-One mapping |
| **Cascade Types** | Understanding different cascade types |
| **Fetch Types** | Eager vs Lazy loading strategies |
| **Uni & Bi-Directional Relationship** | Comparison of uni- and bi-directional relationships |
| **JPA One-To-Many Relationship** | Implementing One-To-Many mapping |
| **JPA Many-To-One Relationship** | Implementing Many-To-One mapping |
| **Paging and Sorting** | Implementing pagination and sorting |
| **JPA Many-To-Many Relationship** | Implementing Many-To-Many mapping |

