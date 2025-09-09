# 🌟 Ramesh Nair – Microservices Portfolio

> *“Building backend systems with clarity, strategy, and craftsmanship — inspired by Krishna’s wisdom: calm, strategic, and precise in every action.”*

Welcome to my **Microservices Portfolio** — a showcase of **production-grade Spring Boot microservices** demonstrating **scalability, maintainability, and real-world problem-solving**.  

---

## 🏗️ High-Level Architecture

**World-Class Microservices Architecture:**  

```mermaid
flowchart TD
    subgraph Gateway
        A[API Gateway Service] 
    end

    subgraph Core Services
        B[Product Service] 
        C[User Service] 
        D[Payment Service] 
        E[Email Notification Service] 
    end

    subgraph Infrastructure
        F[(MySQL / H2 DB)] 
        G[Eureka Service Discovery]
        H[Kafka Event Bus]
    end

    A --> B
    A --> C
    A --> D
    D --> E
    B --> F
    C --> F
    D --> F
    E --> F
    B --> G
    C --> G
    D --> G
    A --> G
    D --> H --> E
