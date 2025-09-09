# 🌟 E-commerce Portfolio

> *“Building backend systems with clarity, strategy, and craftsmanship — inspired by Krishna’s wisdom: calm, strategic, and precise in every action.”*

Welcome to my **E-commerce Portfolio** — a showcase of **production-grade Spring Boot microservices** demonstrating **scalability, maintainability, and real-world problem-solving**.  

---

## 🏗️ High-Level Architecture

**World-Class Microservices Architecture:**

```
                  ┌─────────────────────┐
                  │  API Gateway Service │
                  └─────────┬───────────┘
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
┌───────────────┐   ┌───────────────┐   ┌───────────────┐
│ Product       │   │ User Service  │   │ Payment       │
│ Service       │   │               │   │ Service       │
└─────┬─────────┘   └─────┬─────────┘   └─────┬─────────┘
      │                   │                   │
      ▼                   ▼                   ▼
  ┌──────────┐       ┌──────────┐       ┌──────────┐
  │  MySQL / │       │  MySQL / │       │  MySQL / │
  │    H2    │       │    H2    │       │    H2    │
  └──────────┘       └──────────┘       └──────────┘
                            │
                            ▼
                  ┌─────────────────────┐
                  │ Email Notification  │
                  │ Service             │
                  └─────────────────────┘

Service Discovery (Eureka) monitors all services.
Kafka handles event-driven workflows.
```

* **API Gateway**: Centralized entry point routing requests seamlessly  
* **Service Discovery**: Dynamic microservice lookup with Eureka  
* **Product Service**: Advanced product & category management  
* **User Service**: Authentication & Authorization using JWT + RBAC  
* **Payment Service**: Payment lifecycle management using **Strategy + Factory patterns**  
* **Email Service**: Event-driven notifications for real-time updates  
* **Databases**: MySQL (production), H2 (demo)  
* **Messaging**: Kafka for event-driven workflows  

---

## ✨ Key Highlights

* **Architectural Excellence:** Layered design (Controller → Service → Repository), DTO-first, and robust exception handling  
* **Design Patterns Applied:**  
  * **Strategy + Factory** → Payment Gateway selection  
  * **Event-Driven Architecture** → Email Service notifications  
  * **RBAC + JWT** → User Service security  
  * **Microservices Orchestration** → Eureka + API Gateway  
* **Recruiter-Friendly:** Demonstrates **scalable, maintainable, production-ready microservices**  
* **Tech Stack Mastery:**  

```
Java ☕ | Spring Boot 🌱 | MySQL 🗄️ | H2 🧩 | Kafka ⚡ | Redis 🔄 | JWT 🔑 | Eureka 🌐 | Maven 📦
```

---

## 📦 Microservices Portfolio

| Microservice            | Purpose                        | Highlights                                                              | Repo Link                                                      |
| ----------------------- | ------------------------------ | ----------------------------------------------------------------------- | -------------------------------------------------------------- |
| **Product Service**     | Product & Category Management  | Dynamic search, pagination, sorting, microservice-ready                 | [GitHub](https://github.com/ramesh-nair-dev/Product-Service)   |
| **User Service**        | Authentication & Authorization | JWT-based auth, RBAC, enterprise exception handling                     | [GitHub](https://github.com/ramesh-nair-dev/UserService)       |
| **Payment Service**     | Payment Processing             | Razorpay & Stripe integration, Strategy + Factory, lifecycle management | [GitHub](https://github.com/ramesh-nair-dev/PaymentService)    |
| **Email Service**       | Event-driven Notifications     | Minimal footprint, Kafka & SMTP integration                             | [GitHub](https://github.com/ramesh-nair-dev/EmailService)      |
| **Service Discovery**   | Eureka Registry                | Dynamic lookup, cloud-native, HA-ready                                  | [GitHub](https://github.com/ramesh-nair-dev/ServiceDiscovery)  |
| **API Gateway Service** | Request Routing                | Centralized routing, seamless downstream service integration            | [GitHub](https://github.com/ramesh-nair-dev/APIGatewayService) |

---

## ⚡ Quick Start

```bash
git clone https://github.com/ramesh-nair-dev
cd <service-directory>
mvn spring-boot:run
```

* Switch to **H2 in-memory DB** for demos in `application.properties`  
* Access services via **API Gateway** at `http://localhost:8080`  

---

## 🌐 Why This Portfolio Matters

* Demonstrates **scalable, maintainable, production-grade microservices**  
* Highlights **real-world problem-solving and architecture skills**  
* Showcases **advanced Spring Boot, distributed systems, and backend craftsmanship**  
* Prepares you for **interviews, practical demos, and recruiter evaluation**  

---

## 🧘 Philosophy & Approach

Inspired by **Krishna’s psychology**:

* **Calm & Strategic:** Every service built with **clear responsibility, clean flow, and predictable behavior**  
* **Precision in Action:** Exception handling and DTO-first approach reduce ambiguity  
* **Wisdom in Design:** Patterns like **Strategy, Factory, and Event-driven** chosen to optimize **scalability and maintainability**  

This is **not just code**, but **engineered systems reflecting thoughtful, deliberate backend craftsmanship**.  

---

## 👤 Author

**Ramesh Nair** – Backend Engineer | Java | Spring Boot | System Design Enthusiast  

* Focused on **high-quality, scalable backend systems**  
* Passionate about **clean architecture, design patterns, and distributed systems**  
* Experienced with **microservices, event-driven systems, and cloud-native design**  

📫 Reach me at: [ramesh200212@gmail.com](mailto:ramesh200212@gmail.com)  
🌐 GitHub: [https://github.com/ramesh-nair-dev](https://github.com/ramesh-nair-dev)  

---
