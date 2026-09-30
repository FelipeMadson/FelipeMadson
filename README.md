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
