# Hello, I am Felipe Madison 👋

<p align="left">
  <strong>🇺🇸 English Version</strong> &nbsp;|&nbsp; 
  <a href="README.pt-BR.md">🇧🇷 <strong>Versão em Português</strong></a>
</p>

> **Internet Systems Technology (TSI) Engineer**  
> 🎯 **Core Focus:** Distributed Systems, Local-First Architecture, Zero-Dependency Node.js & Developer Infrastructure  
> 📍 **GitHub:** [@FelipeMadson](https://github.com/FelipeMadson)

<p align="left">
  <a href="https://github.com/FelipeMadson"><img src="https://img.shields.io/github/followers/FelipeMadson?label=Followers&style=social" alt="Followers"></a>
  <img src="https://img.shields.io/badge/Automated%20Tests-301%20Passing-brightgreen.svg?logo=node.js" alt="Tests">
  <img src="https://img.shields.io/badge/Production%20Microservices-18%20Active-blue.svg?logo=github" alt="Projects">
  <img src="https://img.shields.io/badge/Runtime%20Dependencies-0%20(Native%20Stdlib%20Only)-success.svg" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/Security-CodeQL%20SAST%20100%25%20Passed-indigo.svg?logo=githubactions" alt="CodeQL">
  <img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg" alt="Conventional Commits">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-lightgrey.svg" alt="License"></a>
</p>

---

## ⚡ Polyglot Flagships & High-Throughput Distributed Systems

Exemplary production-grade repositories demonstrating deep mastery across Rust, Go, TypeScript/WASM, Java 21, and Cloud-Native architectures:

| Project | Ecosystem & Core Tech | Key Architectural Highlights | CI & Releases |
| :--- | :--- | :--- | :---: |
| **[rust-zk-snark-verifier-engine](https://github.com/FelipeMadson/rust-zk-snark-verifier-engine)** | **Rust 1.80+ · Zero-Knowledge Proofs · BN254 · Groth16** | Pure safe Rust zero-dependency pairing-based Groth16 zk-SNARK verifier over BN254 curve, 128-byte constant verification proofs, R1CS constraint solver, privacy-preserving credential attestation for scientific data sharing. | [![CI](https://github.com/FelipeMadson/rust-zk-snark-verifier-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/rust-zk-snark-verifier-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/rust-zk-snark-verifier-engine/releases) |
| **[blockchain-observatory-graph-indexer](https://github.com/FelipeMadson/blockchain-observatory-graph-indexer)** | **Go 1.22+ · Merkle Patricia Trie · Graph Theory · DeFi Security** | Custom Merkle Patricia Trie (MPT) state tracker, directed transaction flow graph with PageRank centrality and DFS cycle detection, heuristic reentrancy & flash loan exploit analyzer, REST daemon for RNP Blockchain Observatory. | [![CI](https://github.com/FelipeMadson/blockchain-observatory-graph-indexer/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/blockchain-observatory-graph-indexer/actions) · [Release v1.0.0](https://github.com/FelipeMadson/blockchain-observatory-graph-indexer/releases) |
| **[trust-id-agentic-authority-delegation](https://github.com/FelipeMadson/trust-id-agentic-authority-delegation)** | **Go 1.22+ · W3C DID · OPA · Merkle Tree** | Self-certifying W3C `did:key` (Ed25519), Verifiable Credentials 2.0, monotonic authority attenuation, OPA/Rego access gate, RFC 6962 Merkle audit trail for RNP Data Spaces. | [![CI](https://github.com/FelipeMadson/trust-id-agentic-authority-delegation/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/trust-id-agentic-authority-delegation/actions) · [Release v1.0.0](https://github.com/FelipeMadson/trust-id-agentic-authority-delegation/releases) |
| **[pqc-hybrid-kms-mesh](https://github.com/FelipeMadson/pqc-hybrid-kms-mesh)** | **Go 1.22+ · PQC (ML-KEM/ML-DSA) · ETSI QKD 014** | NIST FIPS 203 (ML-KEM-768) + X25519 hybrid KEM, NIST FIPS 204 (ML-DSA-65) hybrid signatures, ETSI GS QKD 014 REST interface, multidomain PoP key lifecycle. | [![CI](https://github.com/FelipeMadson/pqc-hybrid-kms-mesh/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/pqc-hybrid-kms-mesh/actions) · [Release v1.0.0](https://github.com/FelipeMadson/pqc-hybrid-kms-mesh/releases) |
| **[rust-ebpf-network-telemetry-probe](https://github.com/FelipeMadson/rust-ebpf-network-telemetry-probe)** | **Rust · Linux Kernel eBPF · XDP · Aya** | Sub-microsecond in-kernel packet inspection, zero socket buffer (`sk_buff`) allocation overhead, in-kernel BPF flow tables, Prometheus exporter. | [![CI](https://github.com/FelipeMadson/rust-ebpf-network-telemetry-probe/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/rust-ebpf-network-telemetry-probe/actions) · [Release v1.0.0](https://github.com/FelipeMadson/rust-ebpf-network-telemetry-probe/releases) |
| **[go-raft-distributed-consensus-kv](https://github.com/FelipeMadson/go-raft-distributed-consensus-kv)** | **Go 1.22+ · Raft Consensus · Linearizable KV** | Complete Raft state machine replication, randomized election timers (150-300ms), quorum log replication, linearizable reads, client sequence deduplication. | [![CI](https://github.com/FelipeMadson/go-raft-distributed-consensus-kv/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/go-raft-distributed-consensus-kv/actions) · [Release v1.0.0](https://github.com/FelipeMadson/go-raft-distributed-consensus-kv/releases) |
| **[cpp20-lmax-orderbook-engine](https://github.com/FelipeMadson/cpp20-lmax-orderbook-engine)** | **Modern C++20 · HFT · LMAX Disruptor** | Lock-free circular ring buffer, cache-line alignment (`alignas(64)`), Price-Time FIFO matching, zero-alloc hot path. | [![CI](https://github.com/FelipeMadson/cpp20-lmax-orderbook-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/cpp20-lmax-orderbook-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/cpp20-lmax-orderbook-engine/releases) |
| **[elixir-distributed-actor-cluster](https://github.com/FelipeMadson/elixir-distributed-actor-cluster)** | **Elixir 1.17+ · Erlang/OTP 27 · BEAM** | Consistent Hash Ring with 128 VNodes, dynamic supervisor trees (Let-it-Crash), partition resilience, zero SPOF. | [![CI](https://github.com/FelipeMadson/elixir-distributed-actor-cluster/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/elixir-distributed-actor-cluster/actions) · [Release v1.0.0](https://github.com/FelipeMadson/elixir-distributed-actor-cluster/releases) |
| **[dotnet-cqrs-event-sourcing-engine](https://github.com/FelipeMadson/dotnet-cqrs-event-sourcing-engine)** | **.NET 9 · C# 13 · CQRS · Event Sourcing** | Clean Architecture, aggregate deterministic replay, transactional outbox background worker, optimistic concurrency. | [![CI](https://github.com/FelipeMadson/dotnet-cqrs-event-sourcing-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/dotnet-cqrs-event-sourcing-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/dotnet-cqrs-event-sourcing-engine/releases) |
| **[go-distributed-telemetry-pipeline](https://github.com/FelipeMadson/go-distributed-telemetry-pipeline)** | **Go 1.22+ · OpenTelemetry · Latency Engine** | Thread-safe sliding-window ring buffer, zero-allocation P50/P90/P99 latency calculations, token bucket limiter, OTLP exporter. | [![CI](https://github.com/FelipeMadson/go-distributed-telemetry-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/go-distributed-telemetry-pipeline/actions) · [Release v1.0.0](https://github.com/FelipeMadson/go-distributed-telemetry-pipeline/releases) |
| **[fastapi-realtime-collaborative-engine](https://github.com/FelipeMadson/fastapi-realtime-collaborative-engine)** | **Python 3.12+ · FastAPI · WebSockets · CRDTs** | State-based CRDTs (LWW-Element-Set, PN-Counter), WebSocket room pub/sub, sub-ms sync, Pydantic v2. | [![CI](https://github.com/FelipeMadson/fastapi-realtime-collaborative-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/fastapi-realtime-collaborative-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/fastapi-realtime-collaborative-engine/releases) |
| **[rust-wasm-simd-vector-search](https://github.com/FelipeMadson/rust-wasm-simd-vector-search)** | **Rust 1.80+ · WebAssembly · 128-bit SIMD** | Client-side HNSW vector search graph, sub-ms cosine similarity, 100% zero-cloud data isolation. | [![CI](https://github.com/FelipeMadson/rust-wasm-simd-vector-search/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/rust-wasm-simd-vector-search/actions) · [Release v1.0.0](https://github.com/FelipeMadson/rust-wasm-simd-vector-search/releases) |
| **[rust-lsm-tree-storage-engine](https://github.com/FelipeMadson/rust-lsm-tree-storage-engine)** | **Rust 1.80+ · Systems Programming** | Embedded LSM-tree storage engine, thread-safe MemTable with SkipList, append-only WAL with `O_SYNC`. | [![CI](https://github.com/FelipeMadson/rust-lsm-tree-storage-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/rust-lsm-tree-storage-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/rust-lsm-tree-storage-engine/releases) |
| **[go-webhook-delivery-pipeline](https://github.com/FelipeMadson/go-webhook-delivery-pipeline)** | **Go 1.22+ · Concurrency & Worker Pools** | High-throughput concurrent dispatcher, worker pools, HMAC-SHA256 signatures, jittered exponential backoff. | [![CI](https://github.com/FelipeMadson/go-webhook-delivery-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/go-webhook-delivery-pipeline/actions) · [Release v1.0.0](https://github.com/FelipeMadson/go-webhook-delivery-pipeline/releases) |
| **[agentic-consensus-workflow-engine](https://github.com/FelipeMadson/agentic-consensus-workflow-engine)** | **TypeScript 5.8+ · Zod · Multi-Agent** | Multi-agent Byzantine-resistant quorum voting engine, deterministic DAG execution, structured schemas. | [![CI](https://github.com/FelipeMadson/agentic-consensus-workflow-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/agentic-consensus-workflow-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/agentic-consensus-workflow-engine/releases) |
| **[spring-boot-fintech-transaction-engine](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine)** | **Java 21 · Spring Boot 3.3 · Virtual Threads** | High-throughput financial ledger, Project Loom Virtual Threads, Transactional Outbox pattern, idempotency. | [![CI](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine/releases) |
| **[nextjs-enterprise-saas-starter](https://github.com/FelipeMadson/nextjs-enterprise-saas-starter)** | **Next.js 15 · React 19 · Server Actions** | Subdomain multi-tenancy, optimistic UI mutations, role-based access control (RBAC), Tailwind CSS v4. | [![CI](https://github.com/FelipeMadson/nextjs-enterprise-saas-starter/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/nextjs-enterprise-saas-starter/actions) · [Release v1.0.0](https://github.com/FelipeMadson/nextjs-enterprise-saas-starter/releases) |
| **[angular-enterprise-clean-architecture](https://github.com/FelipeMadson/angular-enterprise-clean-architecture)** | **Angular 18 · Signals · Clean Architecture** | Fine-grained reactivity without RxJS leaks, OnPush change detection, Standalone Components, DDD layers. | [![CI](https://github.com/FelipeMadson/angular-enterprise-clean-architecture/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/angular-enterprise-clean-architecture/actions) · [Release v1.0.0](https://github.com/FelipeMadson/angular-enterprise-clean-architecture/releases) |
| **[software-engineering-handbook](https://github.com/FelipeMadson/software-engineering-handbook)** | **Technical Writing · Architecture Manuals** | 10 comprehensive technical volumes backed by an immutable cryptographic SHA-256 verification ledger. | [![CI](https://github.com/FelipeMadson/software-engineering-handbook/actions/workflows/verify-integrity.yml/badge.svg)](https://github.com/FelipeMadson/software-engineering-handbook/actions) · [10 Volumes](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/ebooks) |

---

## 🏛️ Engineering Philosophy & Non-Negotiable Architectural Pillars

I architect software with rigorous engineering standards focused on **determinism, sub-millisecond efficiency, and rock-solid resilience**:

1. **Zero Runtime Dependencies:** Every application relies exclusively on Node.js native standard libraries (`node:test`, `node:crypto`, `node:sqlite`, `node:stream`, `node:http`). Eliminating third-party packages minimizes supply-chain vulnerability attack surfaces and enables instant &lt; 10ms process bootstrap.
2. **Domain-Driven Bespoke Design:** Every microservice features a tailor-made visual identity and an in-browser live simulator running 100% client-side via GitHub Pages with no backend dependency required.
3. **Zero-Trust Timing-Safe Cryptography:** HMAC-SHA256 signature verification performed with constant-time equality (`crypto.timingSafeEqual`) to thwart side-channel timing attacks, alongside cryptographically linked Merkle Tree block audit chains.
4. **Local-First Transactional Reliability:** Atomic SQLite persistence leveraging Write-Ahead Logging (`WAL`) with sub-millisecond fsync latency, ensuring resilience during power or network disruptions.
5. **Architectural Governance & Traceability:** Strict [Conventional Commits](https://www.conventionalcommits.org/), formal Architecture Decision Records ([ADRs](docs/adr)), C4 Model diagrams, and 100% green multi-platform GitHub Actions CI/CD pipelines.

---

## 🚀 Active Microservices & Live Interactive Simulators

Explore the **18 production microservices** below, categorized by their domain archetypes. **Click any simulator to launch and test the application directly in your browser:**

### 🧠 AI Studio & Neural Inference

_Local neural orchestrators with GGUF quantization (FP16/Q4_K_M), Cosine similarity RAG vector exploration, and streaming ReAct agents._

| Microservice | Live Interactive Simulator | Automated Tests | Repository & CI Status |
| :--- | :--- | :---: | :---: |
| **[Desenvolvimento De Um Agente Ai Personalizado Com Aws Agentcore](https://github.com/FelipeMadson/desenvolvimento-de-um-agente-ai-personalizado-com-aws-agentcore)**<br><small>Microsserviço Enterprise de IA com FastAPI, Vector RAG e Agentes ReAct</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/desenvolvimento-de-um-agente-ai-personalizado-com-aws-agentcore/) | `2 passing` | [![CI Status](https://github.com/FelipeMadson/desenvolvimento-de-um-agente-ai-personalizado-com-aws-agentcore/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/desenvolvimento-de-um-agente-ai-personalizado-com-aws-agentcore/actions) |
| **[Inteligencia Artificial Para Monitoramento De Desempenho De Aplicacoes](https://github.com/FelipeMadson/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes)**<br><small>Enterprise-grade microservice with clean architecture, zero dependencies, and deterministic tests.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes/) | `2 passing` | [![CI Status](https://github.com/FelipeMadson/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes/actions) |
| **[Qwenimageflow Orquestrador De Geracao De Imagens Com Quantizacao Local E Rag](https://github.com/FelipeMadson/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag)**<br><small>Workflow de geração de imagens textuais com latência elevada em nuvem e falta de personalização em modelos pré-treinados</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag/) | `18 passing` | [![CI Status](https://github.com/FelipeMadson/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag/actions) |

---

### 💻 Developer Tools & Interactive Web Terminals

_Interactive web terminal emulators with ANSI escape parsers, Tab autocompletion, keyboard history, and deterministic execution._

| Microservice | Live Interactive Simulator | Automated Tests | Repository & CI Status |
| :--- | :--- | :---: | :---: |
| **[Cli Cursor Manager](https://github.com/FelipeMadson/cli-cursor-manager)**<br><small>Desenvolvedores enfrentam dificuldades para gerenciar o cursor em interfaces de linha de comando de forma consistente entre diferentes terminais e plataformas, especialmente em cenários que exigem animações ou interações complexas</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/cli-cursor-manager/) | `18 passing` | [![CI Status](https://github.com/FelipeMadson/cli-cursor-manager/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/cli-cursor-manager/actions) |
| **[Cliforge Ferramenta De Criacao De Cli Com Autocompletcao Inteligente](https://github.com/FelipeMadson/cliforge-ferramenta-de-criacao-de-cli-com-autocompletcao-inteligente)**<br><small>Desenvolvedores enfrentam complexidade em implementar interfaces de linha de comando robustas com suporte a autocompletção em tempo real.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/cliforge-ferramenta-de-criacao-de-cli-com-autocompletcao-inteligente/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/cliforge-ferramenta-de-criacao-de-cli-com-autocompletcao-inteligente/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/cliforge-ferramenta-de-criacao-de-cli-com-autocompletcao-inteligente/actions) |
| **[Devbox A 1 Click Sandbox For Developers](https://github.com/FelipeMadson/devbox-a-1-click-sandbox-for-developers)**<br><small>Painful and time-consuming setup guides for development environments. DevBox is an automated local sandbox.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/devbox-a-1-click-sandbox-for-developers/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/devbox-a-1-click-sandbox-for-developers/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/devbox-a-1-click-sandbox-for-developers/actions) |
| **[Envdoctor](https://github.com/FelipeMadson/envdoctor)**<br><small>Validador e diagnóstico determinístico de ambientes de desenvolvimento local.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/envdoctor/) | `11 passing` | [![CI Status](https://github.com/FelipeMadson/envdoctor/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/envdoctor/actions) |
| **[Ideabank](https://github.com/FelipeMadson/ideabank)**<br><small>Fullstack Platform for Missing Software Demands, Collaborative Voting & 1-Click GitHub Issues Sync.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/ideabank/) | `23 passing` | [![CI Status](https://github.com/FelipeMadson/ideabank/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/ideabank/actions) |
| **[Logsentinel Memory Guard](https://github.com/FelipeMadson/logsentinel-memory-guard)**<br><small>Vazamento silencioso de memória em serviços Node.js devido a listeners de stream acumulados.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/logsentinel-memory-guard/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/logsentinel-memory-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/logsentinel-memory-guard/actions) |

---

### 📊 Enterprise Multi-Tenant SaaS Platforms

_Multi-tenant platforms featuring isolated tenant quotas, in-memory streaming ring buffers, live P99 latency percentile waves, and native Prometheus metrics._

| Microservice | Live Interactive Simulator | Automated Tests | Repository & CI Status |
| :--- | :--- | :---: | :---: |
| **[Cloudpulse Multi Tenant Analytics](https://github.com/FelipeMadson/cloudpulse-multi-tenant-analytics)**<br><small>Plataformas de métricas cobram fortunas por ingestão de eventos e não oferecem isolamento de dados por tenant.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/cloudpulse-multi-tenant-analytics/) | `18 passing` | [![CI Status](https://github.com/FelipeMadson/cloudpulse-multi-tenant-analytics/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/cloudpulse-multi-tenant-analytics/actions) |
| **[Desenvolvimento De Relatorios Mensais De Desenvolvimento](https://github.com/FelipeMadson/desenvolvimento-de-relatorios-mensais-de-desenvolvimento)**<br><small>Desenvolvedores precisam gerenciar e compartilhar suas jornadas de desenvolvimento, mas atualmente não há uma ferramenta eficiente para isso.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/desenvolvimento-de-relatorios-mensais-de-desenvolvimento/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/desenvolvimento-de-relatorios-mensais-de-desenvolvimento/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/desenvolvimento-de-relatorios-mensais-de-desenvolvimento/actions) |
| **[Submitbutton Com Status De Formulario Corrigido](https://github.com/FelipeMadson/submitbutton-com-status-de-formulario-corrigido)**<br><small>Problema com o useFormStatus retornando falso em formulários React</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/submitbutton-com-status-de-formulario-corrigido/) | `16 passing` | [![CI Status](https://github.com/FelipeMadson/submitbutton-com-status-de-formulario-corrigido/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/submitbutton-com-status-de-formulario-corrigido/actions) |

---

### 🛡️ Zero-Trust Security & Cryptographic Vaults

_High-assurance cryptographic labs with timing-safe HMAC-SHA256 verification, recursive token masking, SQLite WAL mode, and Merkle audit block chains._

| Microservice | Live Interactive Simulator | Automated Tests | Repository & CI Status |
| :--- | :--- | :---: | :---: |
| **[Expo Secure Secrets Cli](https://github.com/FelipeMadson/expo-secure-secrets-cli)**<br><small>Developers struggle with securely managing environment variables and secrets across different environments in mobile and cross-platform apps.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/expo-secure-secrets-cli/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/expo-secure-secrets-cli/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/expo-secure-secrets-cli/actions) |
| **[Profile Sync](https://github.com/FelipeMadson/profile-sync)**<br><small>Estudante de Tecnologia em Sistemas para Internet (TSI)</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/profile-sync/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/profile-sync/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/profile-sync/actions) |
| **[Webhookvault](https://github.com/FelipeMadson/webhookvault)**<br><small>Local-First Webhook Inspector, Deterministic Replayer & HMAC Verification Hub.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/webhookvault/) | `24 passing` | [![CI Status](https://github.com/FelipeMadson/webhookvault/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/webhookvault/actions) |

---

### 🧩 Chrome Browser Extensions (Manifest V3)

_Google Chrome Manifest V3 extensions featuring declarativeNetRequest rule interception, Omnibox address routing, and in-browser audit logs._

| Microservice | Live Interactive Simulator | Automated Tests | Repository & CI Status |
| :--- | :--- | :---: | :---: |
| **[Persistnetworkredirects Chrome Extension](https://github.com/FelipeMadson/persistnetworkredirects-chrome-extension)**<br><small>Console SPA Moderno em React 18 e Vite</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/persistnetworkredirects-chrome-extension/) | `11 passing` | [![CI Status](https://github.com/FelipeMadson/persistnetworkredirects-chrome-extension/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/persistnetworkredirects-chrome-extension/actions) |

---

### 🌐 Localization & System Matrix Platforms

_Cross-platform localization suites featuring ICU plural form validation, missing-key graph traversal, and 1-click export to Web JSON, Android XML, and iOS .strings._

| Microservice | Live Interactive Simulator | Automated Tests | Repository & CI Status |
| :--- | :--- | :---: | :---: |
| **[I18n Studio Automatizando Traducoes Para Aplicativos Multiplataforma](https://github.com/FelipeMadson/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma)**<br><small>Tradução de múltiplos idiomas para aplicativos iOS, macOS, Android e JS pode ser um processo doloroso.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma/) | `18 passing` | [![CI Status](https://github.com/FelipeMadson/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma/actions) |
| **[Model Based Design Platform For Engineers](https://github.com/FelipeMadson/model-based-design-platform-for-engineers)**<br><small>Engineers and scientists use outdated, monolithic tools for complex system design and simulation tasks.</small> | [🎮 **Launch Simulator**](https://felipemadson.github.io/model-based-design-platform-for-engineers/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/model-based-design-platform-for-engineers/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/model-based-design-platform-for-engineers/actions) |

---



## 📊 Engineering Technology Matrix

```
┌────────────────────────────────────────────────────────────────────────┐
│                      FELIPE MADISON — TSI TECH STACK                   │
├───────────────────┬──────────────────────────────┬─────────────────────┤
│ Runtimes & Base   │ Node.js 22 & 24 LTS (ESM)    │ Native TypeScript   │
│ Databases         │ SQLite WAL Mode (node:sqlite)│ Relational Schemas  │
│ Cryptography      │ HMAC-SHA256, SubtleCrypto    │ Merkle Audit Chains │
│ Quality & Testing │ Native node:test & assert    │ Chaos Fuzzing (100%)│
│ CI/CD & Security  │ GitHub Actions, CodeQL SAST  │ Conventional Commits│
│ Web Simulators    │ HTML5, Modern CSS, Canvas 2D │ Zero Bundler/Vanilla│
└───────────────────┴──────────────────────────────┴─────────────────────┘
```

---

## 📬 Contact & Collaboration

* **GitHub:** [https://github.com/FelipeMadson](https://github.com/FelipeMadson)
* **Status:** 100% of repositories are public with passing test suites, documentation, and active GitHub Pages simulators.
* Feel free to inspect source code, review architectural ADRs, or open issues and pull requests!
