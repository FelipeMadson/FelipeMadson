# Felipe Madison

**Internet Systems Engineering · Distributed Architectures · High-Resilience Systems**

[Interactive Portfolio](https://felipemadson.github.io/portfolio/) · [Versão em Português](README.pt-BR.md) · [GitHub Profile](https://github.com/FelipeMadson)

```text
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                          FELIPE MADISON — SYSTEMS ARCHITECTURE                         │
│                         65+ Production Repositories on GitHub                          │
└────────────────────────────────────────────────────────────────────────────────────────┘
                                            │
     ┌───────────────────┬──────────────────┼──────────────────┬──────────────────┐
     ▼                   ▼                  ▼                  ▼                  ▼
┌───────────┐      ┌───────────┐      ┌───────────┐      ┌───────────┐      ┌───────────┐
│ JAVA 21   │      │ ANGULAR 18│      │ NEXT.JS 15│      │ RUST / GO │      │ PYTHON    │
│ ───────── │      │ ───────── │      │ ───────── │      │ ───────── │      │ ───────── │
│ Spring 3  │      │ Signals   │      │ React 19  │      │ Zero-Copy │      │ Django 5  │
│ Loom Thr. │      │ DDD Clean │      │ Actions   │      │ TokenBkt  │      │ Flask 3   │
│ Outbox    │      │ Result<T> │      │ Multi-Ten │      │ Low-Lat.  │      │ Polars RAG│
└───────────┘      └───────────┘      └───────────┘      └───────────┘      └───────────┘
```

---

### About Me

I am a Software Engineer and undergraduate in **Internet Systems Technology (TSI)**. My engineering practice centers on deterministic distributed systems, enterprise multi-tenancy, clean-room reverse engineering, and high-throughput concurrency models across modern polyglot environments.

I prioritize standard library capabilities, zero-dependency runtimes, compile-time contract enforcement, reproducible automated testing, and clean, accessible user interfaces.

---

### Core Engineering Stack

| Domain | Technologies & Patterns |
| :--- | :--- |
| **Enterprise JVM & Concurrency** | **Java 21**, Spring Boot 3.3, Project Loom (Virtual Threads), Transactional Outbox, Resilience4j, Micrometer |
| **Modern Frontend & Reactivity** | **Angular 18** (Signals, Standalone Components, OnPush Change Detection), **Next.js 15** (React 19, Server Actions, Zod) |
| **High-Performance Systems** | **Rust 1.75+** (Tokio, Zero-Copy Streams), **Go 1.22+** (Distributed Token Bucket Rate Limiting, Mutex Channels) |
| **Enterprise .NET** | **.NET 8 / C#** (CQRS, MediatR, Entity Framework Core, Transactional Outbox) |
| **Python Ecosystem** | **Python 3.12+** (Django 5 Multi-Tenant, Flask 3 Event Bus, FastAPI, Polars Vector RAG) |
| **Storage & Persistence** | PostgreSQL (RLS, Transactional DDL, Index Tuning), SQLite WAL Mode (`node:sqlite`), Redis |
| **Security & Resilience** | Constant-Time HMAC-SHA256 (`timingSafeEqual`), Circuit Breakers (Tri-State), Token Bucket Rate Limiting |
| **Quality & Verification** | Playwright E2E, JUnit 5, Pytest, Vitest, Native Node Test Runner (`node:test`), Automated CI/CD |

---

### Featured Flagship Repositories

#### 1. [Spring Boot 3 Fintech Transaction Engine](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine)
> **High-Throughput Financial Transaction Engine with Java 21 Virtual Threads (Project Loom)**  
> *Stack: Java 21 · Spring Boot 3.3 · Virtual Threads · Transactional Outbox · JUnit 5 · GitHub Actions CI*

- **Problem:** Conventional thread-per-request architectures exhaust OS threads under high concurrency, creating thread starvation and latency spikes during financial surges.
- **Solution:** Leveraged Java 21 Virtual Threads (`spring.threads.virtual.enabled: true`) for lightweight non-blocking execution, coupled with strict concurrent idempotency deduplication and `BigDecimal` monetary precision.
- **Verification:** Unit test suite verifying idempotency guarantees and HTTP problem details. Automated CI workflow and Dependabot integration.

#### 2. [Angular 18 Enterprise Clean Architecture](https://github.com/FelipeMadson/angular-enterprise-clean-architecture)
> **Production-Grade Angular 18 Architecture with Native Signals and Standalone Components**  
> *Stack: Angular 18 · TypeScript · Signals & Computed · Clean Architecture · OnPush*

- **Problem:** Traditional state management libraries (like NgRx) introduce extensive boilerplate and zone pollution, slowing down UI rendering in large enterprise dashboards.
- **Solution:** Engineered a pure Signal-based reactive state store with `signal` and `computed` primitives, DDD domain isolation, and the `Result<T, E>` pattern for strongly-typed error handling.
- **Verification:** Automated unit test suite validating reactive computed state and balance constraints with 100% pass rate.

#### 3. [Next.js 15 Enterprise SaaS Starter](https://github.com/FelipeMadson/nextjs-enterprise-saas-starter)
> **Full-Stack Next.js 15 App Router Multi-Tenant SaaS Platform**  
> *Stack: Next.js 15 · React 19 · Server Actions · Zod · Subdomain Multi-Tenancy*

- **Problem:** Multi-tenant SaaS architectures often suffer from cross-tenant data leaks and leaky client-side state abstractions.
- **Solution:** Implemented edge-resolved subdomain tenant isolation with runtime Zod contract validation and Server Actions, guaranteeing zero sensitive business logic leakage to the client.
- **Verification:** Automated tests covering tenant resolution and isolation constraints.

#### 4. [Reverse-Engineered API Gateway](https://github.com/FelipeMadson/reverse-engineered-api-gateway)
> **Clean-Room Reverse-Engineered Resilient Gateway with Zero External Dependencies**  
> *Stack: TypeScript · Node.js 22 · Native HTTP · Circuit Breaker · Token Bucket*

- **Problem:** Monolithic gateway bloatware exposes mission-critical systems to deep supply-chain vulnerabilities and heavyweight memory footprints.
- **Solution:** Clean-room reconstructed gateway featuring a tri-state Circuit Breaker (`CLOSED`, `OPEN`, `HALF_OPEN`), Token Bucket rate limiter per IP, and constant-time HMAC-SHA256 JWT validation using only standard library primitives.
- **Verification:** Comprehensive test suite with fast-fail circuit verification and formal [ARCHITECTURE_RECONSTRUCTION.md](https://github.com/FelipeMadson/reverse-engineered-api-gateway/blob/main/ARCHITECTURE_RECONSTRUCTION.md).

#### 5. [Django 5 Multi-Tenant SaaS Platform](https://github.com/FelipeMadson/django-multitenant-saas-platform)
> **Enterprise Subdomain Multi-Tenancy Platform with Django 5 and DRF**  
> *Stack: Python 3.12 · Django 5 · Django REST Framework · Pytest-Django*

- **Problem:** Shared database tables in enterprise B2B apps risk data contamination without explicit tenant schema boundaries.
- **Solution:** Engineered a robust tenant middleware isolating database operations by subdomain with automated tenant provisioning and custom DRF viewsets.
- **Verification:** Automated pytest test suite, GitHub Actions CI, and Dependabot weekly updates.

#### 6. [Flask 3 Microservices Event Bus](https://github.com/FelipeMadson/flask-microservices-event-bus)
> **Decoupled Pub/Sub Event Dispatcher with Transactional Outbox Pattern**  
> *Stack: Python 3.12 · Flask 3 · Marshmallow · Outbox Pattern · Pytest*

- **Problem:** Microservices communicating via direct HTTP calls face cascading failures when downstream endpoints become unavailable.
- **Solution:** Built an asynchronous, in-memory transactional outbox event bus ensuring at-least-once delivery semantics and schema contract validation.
- **Verification:** Automated tests covering subscriber handlers, outbox dispatching, and schema verification.

#### 7. [Rust Zero-Copy Event Stream](https://github.com/FelipeMadson/rust-zero-copy-event-stream)
> **High-Throughput In-Memory Stream Processing with Tokio**  
> *Stack: Rust 1.75+ · Tokio · Bytes · Cargo Tests*

- **Solution:** Zero-heap-allocation byte slice processing engine designed for ultra-low latency real-time telemetry pipelines.

#### 8. [Go Distributed Token Bucket](https://github.com/FelipeMadson/go-distributed-token-bucket)
> **Cloud-Native Concurrency Rate Limiter**  
> *Stack: Go 1.22+ · Goroutines · Channels · Mutex Benchmarking*

- **Solution:** Thread-safe distributed rate limiter preventing noisy neighbor denial-of-service in distributed clusters.

#### 9. [.NET 8 CQRS Transaction Outbox](https://github.com/FelipeMadson/dotnet-cqrs-transaction-outbox)
> **Clean Architecture Event-Driven Service**  
> *Stack: .NET 8 · C# · MediatR · EF Core · xUnit*

- **Solution:** Command Query Responsibility Segregation (CQRS) service featuring transactional outbox persistence for guaranteed message dispatch.

---

### 📚 Engineering Handbooks & Whitepapers

#### [Software Engineering Handbook](https://github.com/FelipeMadson/software-engineering-handbook)
> **In-Depth Architectural Guides, Resilient Distributed Patterns & Verification**  
> *Stack: TypeScript · Architecture Design · Node.js · Security Verification · GitHub Actions CI*

- **Idempotent Queue Architecture:** Deduplication, atomic leases, and outbox patterns.
- **CRDT Offline-First Synchronization:** Conflict-free replicated state and local-first data stores.
- **Multitenant Row-Level Security:** PostgreSQL RLS, tenant context isolation, and defense in depth.
- **Deterministic Dev Environments:** Reproducible toolchains, hermetic builds, and container sandboxes.

---

### Engineering Principles

1. **Deterministic & Local-First:** Systems are designed to function reliably offline, respecting user data privacy and avoiding arbitrary cloud vendor lock-in.
2. **Minimal Dependency Footprint:** Prioritizes native standard library primitives to ensure sub-100ms startup times, minimal maintenance overhead, and zero supply-chain security alerts.
3. **Evidence-Driven Engineering:** No feature is certified complete without passing automated test suites, measurable performance benchmarks, and reproducible execution artifacts.
4. **Accessible, Purposeful Design:** Interfaces must be structured, accessible (WCAG AA), responsive across all viewports, and free from superfluous visual clutter.

---

### Connect & Collaborate

- **GitHub:** [@FelipeMadson](https://github.com/FelipeMadson)
- **Interactive Portfolio:** [felipemadson.github.io/portfolio](https://felipemadson.github.io/portfolio/)
- **Contributions:** Open-source projects and code reviews are welcomed via GitHub issues and pull requests.
