# Felipe Madison

**Engenharia de Sistemas para Internet · Arquiteturas Distribuídas · Sistemas de Alta Resiliência**

[Portfólio Interativo](https://felipemadson.github.io/portfolio/) · [English Version](README.md) · [Perfil no GitHub](https://github.com/FelipeMadson)

```text
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                          FELIPE MADISON — ARQUITETURA DE SISTEMAS                      │
│                         65+ Repositórios em Produção no GitHub                         │
└────────────────────────────────────────────────────────────────────────────────────────┘
                                            │
     ┌───────────────────┬──────────────────┼──────────────────┬──────────────────┐
     ▼                   ▼                  ▼                  ▼                  ▼
┌───────────┐      ┌───────────┐      ┌───────────┐      ┌───────────┐      ┌───────────┐
│ JAVA 21   │      │ ANGULAR 18│      │ NEXT.JS 15│      │ RUST / GO │      │ PYTHON    │
│ ───────── │      │ ───────── │      │ ───────── │      │ ───────── │      │ ───────── │
│ Spring 3  │      │ Signals   │      │ React 19  │      │ Zero-Copy │      │ Django 5  │
│ Loom Thr. │      │ DDD Clean │      │ Actions   │      │ TokenBkt  │      │ Flask 3   │
│ Outbox    │      │ Result<T> │      │ Multi-Ten │      │ Baixa Lat.│      │ Polars RAG│
└───────────┘      └───────────┘      └───────────┘      └───────────┘      └───────────┘
```

---

### Sobre Mim

Sou Engenheiro de Software e graduando em **Tecnologia em Sistemas para Internet (TSI)**. Minha atuação foca no desenvolvimento de sistemas distribuídos determinísticos, isolamento multi-tenant corporativo, engenharia reversa clean-room e modelos de alta vazão de concorrência em ambientes poliglotas modernos.

Priorizo capacidades nativas da biblioteca padrão, runtimes com zero dependências externas desnecessárias, tipagem estrita com contratos verificáveis em compilação, testes automatizados reproduzíveis e interfaces acessíveis e elegantes.

---

### Matriz de Tecnologias

| Domínio | Tecnologias & Padrões |
| :--- | :--- |
| **JVM Corporativa & Concorrência** | **Java 21**, Spring Boot 3.3, Project Loom (Virtual Threads), Transactional Outbox, Resilience4j, Micrometer |
| **Frontend Moderno & Reatividade** | **Angular 18** (Signals, Standalone Components, OnPush Change Detection), **Next.js 15** (React 19, Server Actions, Zod) |
| **Sistemas de Alta Performance** | **Rust 1.75+** (Tokio, Zero-Copy Streams), **Go 1.22+** (Rate Limiting Distribuído com Token Bucket, Concorrência) |
| **.NET Corporativo** | **.NET 8 / C#** (CQRS, MediatR, Entity Framework Core, Transactional Outbox) |
| **Ecossistema Python** | **Python 3.12+** (Django 5 Multi-Tenant, Flask 3 Event Bus, FastAPI, Polars Vector RAG) |
| **Armazenamento & Persistência** | PostgreSQL (RLS, Migrações Transacionais, Otimização de Índices), SQLite WAL (`node:sqlite`), Redis |
| **Segurança & Resiliência** | HMAC-SHA256 em Tempo Constante (`timingSafeEqual`), Circuit Breakers (Tri-State), Token Bucket Rate Limiting |
| **Qualidade & Verificação** | Playwright E2E, JUnit 5, Pytest, Vitest, Native Node Test Runner (`node:test`), CI/CD Automatizado |

---

### Projetos Flagship em Destaque

#### 1. [Spring Boot 3 Fintech Transaction Engine](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine)
> **Motor de Transações Financeiras de Alta Vazão com Java 21 Virtual Threads (Project Loom)**  
> *Stack: Java 21 · Spring Boot 3.3 · Virtual Threads · Transactional Outbox · JUnit 5 · GitHub Actions CI*

- **Problema:** Arquiteturas convencionais de thread-por-requisição esgotam threads do sistema operacional sob alta concorrência, gerando gargalos e picos de latência em sistemas bancários.
- **Solução:** Utilização de Virtual Threads do Java 21 (`spring.threads.virtual.enabled: true`) para execução concorrente ultraleve, combinada com deduplicação concorrente por chave de idempotência e precisão monetária `BigDecimal`.
- **Verificação:** Suíte de testes unitários validando garantias de idempotência e detalhes de problemas RFC-7807. CI automatizado no GitHub Actions e Dependabot.

#### 2. [Angular 18 Enterprise Clean Architecture](https://github.com/FelipeMadson/angular-enterprise-clean-architecture)
> **Arquitetura Corporativa em Angular 18 com Signals Nativos e Standalone Components**  
> *Stack: Angular 18 · TypeScript · Signals & Computed · Clean Architecture · OnPush*

- **Problema:** Gerenciadores de estado tradicionais (como NgRx) adicionam excesso de boilerplate e poluição de zone.js, degradando o desempenho da interface em dashboards complexos.
- **Solução:** Store reativa baseada puramente em Signals (`signal` e `computed`), separação em camadas DDD e padrão `Result<T, E>` para tratamento estrito de erros tipados sem throw.
- **Verificação:** Suíte de testes automatizados com 100% de aprovação testando estado reativo derivado e regras de saldo.

#### 3. [Next.js 15 Enterprise SaaS Starter](https://github.com/FelipeMadson/nextjs-enterprise-saas-starter)
> **Plataforma SaaS Multi-Tenant Full-Stack em Next.js 15 App Router**  
> *Stack: Next.js 15 · React 19 · Server Actions · Zod · Multi-Tenancy por Subdomínio*

- **Problema:** Arquiteturas SaaS multi-tenant frequentemente enfrentam vazamento de dados entre clientes e complexidade excessiva no client-side.
- **Solução:** Resolução de subdomínios de borda com validação de esquemas Zod em tempo de execução e Server Actions, garantindo zero vazamento de lógica de negócio sensível.
- **Verificação:** Testes automatizados cobrindo resolução de tenants e restrições de isolamento.

#### 4. [Reverse-Engineered API Gateway](https://github.com/FelipeMadson/reverse-engineered-api-gateway)
> **Gateway de API Resiliente Reconstruído com Engenharia Reversa Clean-Room e Zero Dependências**  
> *Stack: TypeScript · Node.js 22 · HTTP Nativo · Circuit Breaker · Token Bucket*

- **Problema:** Gateways monolíticos e bibliotecas pesadas expõem sistemas a vulnerabilidades na cadeia de suprimentos e consumo excessivo de memória.
- **Solução:** Reconstrução clean-room com Circuit Breaker tri-state (`CLOSED`, `OPEN`, `HALF_OPEN`), controle de taxa Token Bucket por IP e validação nativa de tokens JWT com HMAC-SHA256.
- **Verificação:** Suíte completa de testes unitários com validação de fail-fast e documento formal [ARCHITECTURE_RECONSTRUCTION.md](https://github.com/FelipeMadson/reverse-engineered-api-gateway/blob/main/ARCHITECTURE_RECONSTRUCTION.md).

#### 5. [Django 5 Multi-Tenant SaaS Platform](https://github.com/FelipeMadson/django-multitenant-saas-platform)
> **Plataforma Multi-Tenant Corporativa por Subdomínio com Django 5 e DRF**  
> *Stack: Python 3.12 · Django 5 · Django REST Framework · Pytest-Django*

- **Problema:** Tabelas compartilhadas em aplicações B2B corporativas criam riscos de contaminação de dados sem fronteiras estritas de schemas.
- **Solução:** Middleware de tenancy isolando operações de banco de dados por subdomínio, provisionamento automatizado e viewsets customizados com DRF.
- **Verificação:** Suíte de testes com pytest, GitHub Actions CI e atualizações semanais via Dependabot.

#### 6. [Flask 3 Microservices Event Bus](https://github.com/FelipeMadson/flask-microservices-event-bus)
> **Barramento de Eventos Pub/Sub Desacoplado com Padrão Transactional Outbox**  
> *Stack: Python 3.12 · Flask 3 · Marshmallow · Padrão Outbox · Pytest*

- **Problema:** Microserviços comunicando-se exclusivamente via chamadas HTTP síncronas sofrem de falhas em cascata quando serviços a jusante oscilam.
- **Solução:** Barramento de eventos assíncrono em memória com padrão Outbox, garantindo entrega at-least-once e validação de contratos com esquemas Marshmallow.
- **Verificação:** Testes automatizados cobrindo despacho de eventos, handlers concorrentes e validação de contratos.

#### 7. [Rust Zero-Copy Event Stream](https://github.com/FelipeMadson/rust-zero-copy-event-stream)
> **Processamento de Streams em Memória de Alta Vazão com Tokio**  
> *Stack: Rust 1.75+ · Tokio · Bytes · Testes com Cargo*

#### 8. [Go Distributed Token Bucket](https://github.com/FelipeMadson/go-distributed-token-bucket)
> **Limitador de Taxa Concorrente Cloud-Native**  
> *Stack: Go 1.22+ · Goroutines · Canais · Benchmarking Mutex*

#### 9. [.NET 8 CQRS Transaction Outbox](https://github.com/FelipeMadson/dotnet-cqrs-transaction-outbox)
> **Serviço Orientado a Eventos com Clean Architecture**  
> *Stack: .NET 8 · C# · MediatR · EF Core · xUnit*

---

### Princípios de Engenharia

1. **Determinismo e Local-First:** Os sistemas são concebidos para funcionar confiavelmente offline, respeitando a privacidade dos dados e evitando dependência arbitrária de nuvem.
2. **Pegada Mínima de Dependências:** Priorizo as bibliotecas padrão e primitivas fundamentais para garantir inicialização abaixo de 100ms e zero alertas de segurança de cadeia de suprimentos.
3. **Engenharia Orientada a Evidências:** Nenhuma funcionalidade é declarada concluída sem suíte de testes automatizados, benchmarks mensuráveis e artefatos de execução reproduzíveis.
4. **Design Acessível e Funcional:** Interfaces devem ser estruturadas, acessíveis (WCAG AA), responsivas em todos os viewports e livres de ruído visual.

---

### Conecte-se

- **GitHub:** [@FelipeMadson](https://github.com/FelipeMadson)
- **Portfólio Interativo:** [felipemadson.github.io/portfolio](https://felipemadson.github.io/portfolio/)
- **Contribuições:** Projetos open-source e revisões de código são bem-vindos através de issues e pull requests.
