# 🛒 EazyStore – Modern Full-Stack E-Commerce Platform

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=600&size=28&duration=3000&pause=1000&color=4CAF50&center=true&vCenter=true&width=700&lines=Modern+Full-Stack+E-Commerce+Platform;Built+with+Spring+Boot+%2B+React;Secure+JWT+Authentication;Stripe+Payment+Integration;Dockerized+for+Easy+Deployment" />

<p>
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-success?style=for-the-badge&logo=springboot"/>
  <img src="https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react"/>
  <img src="https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql"/>
  <img src="https://img.shields.io/badge/Stripe-Payments-purple?style=for-the-badge&logo=stripe"/>
  <img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker"/>
  <img src="https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge"/>
</p>

*A scalable, secure, and production-ready e-commerce platform featuring authentication, role-based access control, payments, order management, and an intuitive shopping experience.*

</div>

---

# ✨ Overview

**EazyStore** is a complete full-stack e-commerce solution engineered using **Spring Boot**, **React**, and **MySQL**. The platform emphasizes security, scalability, and maintainability through layered architecture, JWT authentication, RBAC, Redis caching, and Dockerized deployment.

Whether it's customer shopping workflows or administrative product management, EazyStore delivers a seamless experience backed by clean architecture and industry-standard practices.

---

# 🚀 Key Features

## 👤 Authentication & Authorization

* JWT-based secure authentication
* Spring Security integration
* Role-Based Access Control (RBAC)
* Protected API endpoints
* Password encryption
* Session-free stateless architecture

---

## 🛍️ Customer Features

* User registration & login
* Browse products by category
* Search and filter products
* Product detail pages
* Shopping cart management
* Wishlist functionality
* Secure checkout
* Stripe payment integration
* Order history
* Profile management

---

## 🏪 Admin Features

* Dashboard overview
* Product CRUD operations
* Category management
* Inventory management
* Order management
* User management
* Role assignment
* Sales monitoring

---

## 💳 Payment Processing

* Secure Stripe Checkout
* Payment verification
* Order confirmation
* Transaction handling
* Failed payment recovery
* Automated order updates

---

## ⚡ Performance Optimizations

* Redis caching
* Optimized SQL queries
* Layered backend architecture
* Efficient REST API design
* Lazy loading where applicable
* Containerized deployment using Docker

---

# 🏗️ Tech Stack

| Layer            | Technologies                       |
| ---------------- | ---------------------------------- |
| Frontend         | React, Redux Toolkit, Tailwind CSS |
| Backend          | Spring Boot, Spring Security       |
| Authentication   | JWT                                |
| Database         | MySQL                              |
| Cache            | Redis                              |
| Payments         | Stripe                             |
| Containerization | Docker                             |
| API              | RESTful APIs                       |
| Build Tool       | Maven                              |
| State Management | Redux Toolkit                      |

---

# 📁 Project Structure

```text
EazyStore/
│
├── backend/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── entity/
│   ├── dto/
│   ├── config/
│   ├── security/
│   └── exception/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   ├── hooks/
│   ├── services/
│   └── layouts/
│
├── docker/
├── docs/
├── docker-compose.yml
└── README.md
```

---

# 🔄 Application Flow

```text
User
   │
   ▼
React Frontend
   │
JWT Authentication
   │
Spring Security
   │
Spring Boot REST APIs
   │
 ├────────► Redis Cache
 │
 ▼
MySQL Database
 │
 ▼
Stripe Payment Gateway
 │
 ▼
Order Processing
```

---

# 🔐 Security Highlights

* JWT token authentication
* BCrypt password hashing
* Stateless authentication
* Protected REST endpoints
* Role-Based Authorization
* Input validation
* Exception handling
* CORS configuration
* Secure payment processing

---

# 🎯 Core Modules

* Authentication
* User Management
* Product Catalog
* Categories
* Shopping Cart
* Wishlist
* Orders
* Payments
* Inventory
* Admin Dashboard

---

# 🐳 Docker Support

Run the complete application using Docker Compose:

```bash
docker-compose up --build
```

This starts:

* Spring Boot Backend
* React Frontend
* MySQL Database
* Redis Cache

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/eazystore.git

cd eazystore
```

## Backend

```bash
cd backend

mvn clean install

mvn spring-boot:run
```

## Frontend

```bash
cd frontend

npm install

npm run dev
```

---

# 💳 Stripe Configuration

Create a `.env` file and configure:

```env
STRIPE_SECRET_KEY=your_secret_key
STRIPE_PUBLIC_KEY=your_public_key
```

---

# 📊 Architecture

```
                +----------------------+
                |    React Frontend    |
                +----------+-----------+
                           |
                           |
                  REST API Calls
                           |
                           ▼
                +----------------------+
                |   Spring Boot APIs   |
                +----------+-----------+
                           |
            +--------------+--------------+
            |                             |
            ▼                             ▼
    Spring Security                 Redis Cache
            |                             |
            ▼                             |
       JWT Validation                     |
            |                             |
            +-------------+---------------+
                          |
                          ▼
                   MySQL Database
                          |
                          ▼
                   Stripe Payments
```

---

# 🌟 Highlights

* ✅ Production-ready layered architecture
* ✅ JWT Authentication & RBAC
* ✅ Secure REST APIs
* ✅ Stripe payment gateway
* ✅ Dockerized deployment
* ✅ Redis caching for performance
* ✅ Responsive React UI
* ✅ Redux Toolkit state management
* ✅ Clean code structure
* ✅ Scalable backend services

---

# 📈 Future Enhancements

* AI-powered product recommendations
* Elasticsearch integration
* Email notifications
* Coupon & discount engine
* Multi-vendor marketplace
* Real-time order tracking
* Analytics dashboard
* Product reviews & ratings
* WebSocket notifications
* Kubernetes deployment

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

**Built with ❤️ using Spring Boot, React, MySQL, Redis, Docker, and Stripe**

</div>
