# Felipe Madison

**Internet Systems Engineering · Local-First Architecture · Systems Tooling**

[Portfolio](https://felipemadson.github.io/portfolio/) · [Versão em Português](README.pt-BR.md) · [GitHub Profile](https://github.com/FelipeMadson)

---

### About Me

I am a Software Engineer and undergraduate student in **Internet Systems Technology (TSI)**. My work focuses on building deterministic developer tools, local-first architectures, resilient distributed queue systems, and private AI workflows.

I prioritize standard library capabilities, zero-dependency runtimes, strict typing, reproducible automated testing, and clean, accessible user interfaces.

---

### Core Engineering Stack

| Domain | Technologies & Patterns |
| :--- | :--- |
| **Languages & Runtimes** | Node.js 22/24 (Native ESM), TypeScript, Python 3.12+, SQL |
| **Frontend Architecture** | Angular 22 (Signals, Standalone Components, OnPush Change Detection), Semantic HTML5, Modern Responsive CSS, WCAG AA Accessibility |
| **Backend & Services** | FastAPI, Native Node.js HTTP/Streams, RESTful APIs, Structured Event Buses |
| **Persistence & Storage** | PostgreSQL (Relational Modeling, Constraints, Migrations), SQLite WAL Mode (`node:sqlite`), In-Memory Outboxes |
| **Security & Resilience** | Constant-Time HMAC-SHA256 (`timingSafeEqual`), Token-Bucket Rate Limiting, Replay Attack Guards, Dead-Letter Queues (DLQ), Circuit Breakers |
| **Quality & Verification** | Playwright E2E (Multi-Viewport Testing), Pytest, Vitest, Native Node Test Runner (`node:test`), Deterministic Container Sandboxes |

---

### Featured Flagship Projects

#### 1. [QueueGuard Platform](https://github.com/FelipeMadson/mitigacao-processamento-duplicado-filas-assincronas)
> **Fullstack Idempotent Asynchronous Queue Processing Platform**  
> *Stack: Angular 22 · Signals · FastAPI · PostgreSQL · Playwright · GitHub Actions CI*

- **Problem:** Asynchronous message brokers frequently deliver duplicates during network partitions or retries, causing double writes, lost leases, and inconsistent state.
- **Solution:** Implemented a fullstack deduplication architecture with atomic lease acquisition, PostgreSQL transactional migration schema, and a real-time reactive Angular 22 dashboard.
- **Verification:** Verified through unit, acceptance, and Playwright multi-viewport tests (390px, 768px, 1440px) with database restart persistence and automated CI pipeline.

#### 2. [WebhookVault](https://github.com/FelipeMadson/webhookvault)
> **Local-First Cryptographic Webhook Gateway & Replay Engine**  
> *Stack: Node.js (Native) · TypeScript · SQLite WAL · Timing-Safe Cryptography*

- **Problem:** Debugging webhooks from providers like GitHub, Stripe, or Shopify exposes local endpoints to timing attacks and replay vulnerabilities.
- **Solution:** Built an offline-capable gateway featuring constant-time HMAC-SHA256 signature verification (`timingSafeEqual`), automatic payload replay with recalculated signatures and fresh timestamps, and an embedded zero-dependency web dashboard.
- **Verification:** 22 automated deterministic tests with `node:test` and crash-recovery WAL validation.

#### 3. [CloudPulse Multi-Tenant Analytics](https://github.com/FelipeMadson/cloudpulse-multi-tenant-analytics)
> **Local-First Event Analytics Engine with Quota Enforcement**  
> *Stack: Node.js 22 · SQLite WAL · Prometheus Metrics · Token Bucket*

- **Problem:** Multi-tenant SaaS instrumentation often introduces heavy third-party vendor lock-in and risks cross-tenant telemetry leaks.
- **Solution:** Engineered a lightweight, local-first analytics engine with strict tenant isolation, token-bucket burst rate limiting, HMAC-signed outbound dispatching, and native Prometheus metrics exporters.
- **Verification:** 23 automated tests verifying strict multi-tenancy isolation and non-blocking sub-millisecond persistence.

#### 4. [EnvDoctor](https://github.com/FelipeMadson/envdoctor)
> **Sub-Second Developer Environment Diagnostics & Audit CLI**  
> *Stack: Node.js (Native ESM) · Cross-Platform (Ubuntu & Windows)*

- **Problem:** Environment drift, misconfigured runtime versions, port conflicts, and uncommitted secrets in `.env` files cause recurring onboarding failures.
- **Solution:** Developed a deterministic diagnostic CLI providing sub-60ms concurrent audits of runtimes, open TCP listening ports, and strict credential leak prevention.
- **Verification:** Cross-platform GitHub Actions CI matrix running on Ubuntu and Windows with Node.js 22 and 24.

#### 5. [CLI Cursor Manager](https://github.com/FelipeMadson/cli-cursor-manager)
> **ANSI Escape and Webterm Cursor Coordination Engine**  
> *Stack: Node.js (Native) · Zero Runtime Dependencies · Terminal Standards*

- **Problem:** Inconsistent cursor positioning and ANSI sequences across terminal emulators, xterm.js, and web terminals lead to visual artifacts and broken interactive prompts.
- **Solution:** Standardized cursor state management and animation frames with complete ANSI escape compatibility and zero external runtime dependencies.
- **Verification:** 29 automated tests verifying cross-terminal escape standard conformance.

#### 6. [I18n Studio](https://github.com/FelipeMadson/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma)
> **Multi-Platform Automated Translation Pipeline**  
> *Stack: Node.js · TypeScript · Local Schema Validation*

- **Problem:** Managing localization dictionaries across web, mobile, and server templates introduces syntax discrepancies and missing translation keys.
- **Solution:** Created an automated AST-based translation orchestrator that validates keys, detects collisions, and maintains clean schema parity across target platforms.
- **Verification:** 23 automated tests covering key resolution and structure validation.

---

### Engineering Principles

1. **Deterministic & Local-First:** Systems are designed to function reliably offline, respecting user data privacy and avoiding arbitrary cloud lock-in.
2. **Minimal Dependency Footprint:** I favor the native Node.js standard library and language primitives to ensure sub-100ms startup times, minimal maintenance overhead, and zero supply-chain security alerts.
3. **Evidence-Driven Engineering:** No feature is certified complete without passing automated test suites, measurable performance benchmarks, and reproducible execution artifacts.
4. **Accessible, Purposeful Design:** Interfaces must be structured, accessible (WCAG AA), responsive across all viewports, and free from superfluous visual clutter.

---

### Connect & Collaborate

- **GitHub:** [@FelipeMadson](https://github.com/FelipeMadson)
- **Interactive Portfolio:** [felipemadson.github.io/portfolio](https://felipemadson.github.io/portfolio/)
- **Contributions:** Open-source projects and code reviews are welcomed via GitHub issues and pull requests.
