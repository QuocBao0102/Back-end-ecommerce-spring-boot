# 🛒 E-Commerce Backend API (Spring Boot)

## 📌 Introduction

This project is a **backend RESTful API for an E-commerce system** built using Spring Boot.
It handles core business logic such as authentication, product management, cart, and order processing.

The architecture follows a layered design to ensure scalability, maintainability, and clean code practices.

---

## 🚀 Features

* 🔐 Authentication & Authorization (Spring Security + JWT)
* 👤 User Management (Register / Login)
* 📦 Product Management (CRUD APIs)
* 🗂 Category Management
* 🛒 Shopping Cart
* 📑 Order Management
* ⚠️ Global Exception Handling
* 📄 DTO (Payload) pattern
* 🔍 API validation

---

## 🛠 Tech Stack

* **Backend:** Spring Boot
* **Security:** Spring Security, JWT
* **Database:** MySQL
* **ORM:** Spring Data JPA (Hibernate)
* **Build Tool:** Maven

---

## 🏗 Project Structure

```bash
src/main/java/com/ecommerce/project/
│── config          # Configuration (CORS, Bean, App config)
│── controller      # REST API endpoints
│── exceptions      # Global exception handling
│── model           # Entity classes (database models)
│── payload         # DTO (request/response objects)
│── repositories    # JPA repositories (data access layer)
│── security        # JWT + Spring Security config
│── service         # Business logic
│── util            # Utility classes
│── SbEcomApplication.java  # Main entry point
```

---

## ⚙️ Installation & Run

### 1. Clone project

```bash
git clone https://github.com/QuocBao0102/Back-end-ecommerce-spring-boot.git
cd Back-end-ecommerce-spring-boot
```

### 2. Configure database

Edit file `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=your_password
```

---

### 3. Run application

```bash
mvn spring-boot:run
```

👉 Server runs at: `http://localhost:8080`

---



## 📂 Images

Project screenshots are stored in `/images` folder.

---

## 🧠 Future Improvements

* ✅ Swagger API documentation
* ✅ Docker support
* ✅ Payment integration (VNPay / Stripe)
* ✅ Unit testing
* ✅ Redis caching

---

## 👨‍💻 Author

* **Quoc Bao Ho**
* GitHub: https://github.com/QuocBao0102

---

## ⭐ Support

If you find this project useful, please give it a ⭐ on GitHub!
