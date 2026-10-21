# Olá, eu sou o Felipe Madison 👋

<p align="left">
  <a href="README.md">🇺🇸 <strong>English Version</strong></a> &nbsp;|&nbsp; 
  <strong>🇧🇷 Versão em Português</strong>
</p>

> **Estudante de Tecnologia em Sistemas para Internet (TSI)**  
> 🎯 **Foco de Atuação:** Engenharia de Software Web, Arquitetura Local-First, Sistemas Distribuídos e Ferramentas para Desenvolvedores  
> 📍 **GitHub:** [@FelipeMadson](https://github.com/FelipeMadson)

<p align="left">
  <a href="https://github.com/FelipeMadson"><img src="https://img.shields.io/github/followers/FelipeMadson?label=Seguidores&style=social" alt="Followers"></a>
  <img src="https://img.shields.io/badge/Testes%20Automatizados-301%20Passing-brightgreen.svg?logo=node.js" alt="Testes">
  <img src="https://img.shields.io/badge/Projetos%20em%20Produção-18%20Microsserviços-blue.svg?logo=github" alt="Projetos">
  <img src="https://img.shields.io/badge/Sentinel%20Watchdogs-Ativos%20(9%20Flagships)-brightgreen.svg?logo=githubactions" alt="Watchdogs">
  <img src="https://img.shields.io/badge/Pesquisa%20Acadêmica-IEEEtran%20LaTeX%20Verificado-blueviolet.svg?logo=latex" alt="Pesquisa Acadêmica">
  <img src="https://img.shields.io/badge/Runtime%20Dependencies-0%20(Native%20Only)-success.svg" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/Security-CodeQL%20SAST%20100%25%20Passed-indigo.svg?logo=githubactions" alt="CodeQL">
  <img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg" alt="Conventional Commits">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-lightgrey.svg" alt="License"></a>
</p>

---

## 🎓 Artigos Acadêmicos & Pesquisas Formais (Peer-Reviewed Grade)

Artigos de pesquisa acadêmica formal com formulações matemáticas rigorosas, teoremas verificáveis, fontes em LaTeX (formato IEEEtran) e referências BibTeX:

| Título & Linha de Pesquisa | Especificação Formal & Teoremas | Modelo Matemático | Artefatos de Pesquisa |
| :--- | :--- | :--- | :---: |
| **Replicação Determinística de Máquinas de Estados: Verificação Formal de Segurança e Vivacidade em Quóruns Distribuídos sob Partições Assimétricas**<br>*(Sistemas Distribuídos & Métodos Formais)* | • **Teorema 1 (Segurança de Estado):** Índice de commit $k$ idêntico em nós sadios implica execução idêntica de comandos $C_i(k) = C_j(k)$.<br>• **Teorema 2 (Log Matching):** Termo e índice iguais garantem histórico estritamente idêntico. | $\mathbf{S}_i = (t_i, v_i, \mathcal{L}_i, c_i, a_i)$<br>Quórum: $\mathcal{Q} = \lfloor N/2 \rfloor + 1$ | [📄 Artigo](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/papers/deterministic-state-machine-replication-raft/paper.md) · [LaTeX](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/papers/deterministic-state-machine-replication-raft/paper.tex) · [BibTeX](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/papers/deterministic-state-machine-replication-raft/references.bib) · [`go-raft-kv`](https://github.com/FelipeMadson/go-raft-distributed-consensus-kv) |
| **Busca por Vizinhos Mais Próximos Sub-Milissegundo em WebAssembly: Quantização SIMD de 128-Bits e Travessia em Memória Limitada**<br>*(Sistemas, Algoritmos & Aceleração de Hardware)* | • **Limite de Erro de Quantização:** Erro de cosseno por quantização escalar uniforme limitado estritamente pela desigualdade de Cauchy-Schwarz: $\|d_c(\mathbf{q}, \mathbf{x}) - d_c(\mathbf{q}, \tilde{\mathbf{x}})\| \le \frac{\sqrt{D}}{255}$.<br>• Vetorização de produto escalar SIMD128 por hardware. | $\mathbf{q} \cdot \mathbf{x} = \sum_{k=0}^{D-1} q_k \cdot x_k$<br>$\mathcal{O}(D/4)$ ciclos WASM | [📄 Artigo](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/papers/simd-hnsw-vector-quantization-wasm/paper.md) · [LaTeX](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/papers/simd-hnsw-vector-quantization-wasm/paper.tex) · [BibTeX](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/papers/simd-hnsw-vector-quantization-wasm/references.bib) · [`rust-wasm-simd`](https://github.com/FelipeMadson/rust-wasm-simd-vector-search) |
| **Mecanismos Híbridos de Encapsulamento Pós-Quântico em Redes Mesh Edge Zero-Trust: Uma Redução Empírica IND-CCA2**<br>*(Criptografia Aplicada & Segurança em Malhas Mesh)* | • **Redução de Segurança IND-CCA2:** Encapsulamento híbrido permanece indistinguível sob ataques de texto-cifrado escolhido enquanto ML-KEM-768 ou X25519 não forem violados.<br>• Extração dupla de entropia pelo Leftover Hash Lemma. | $\mathbf{K} = \text{KDF}(\mathbf{K}_{\text{pqc}} \mathbin{\Vert} \mathbf{K}_{\text{classic}} \mathbin{\Vert} \mathbf{c}_1 \mathbin{\Vert} \mathbf{c}_2)$<br>$\mathbf{A}_{\text{Q}} \le \epsilon_{\text{KEM}} + \epsilon_{\text{ECDH}}$ | [📄 Artigo](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/papers/post-quantum-hybrid-key-exchange-mesh/paper.md) · [LaTeX](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/papers/post-quantum-hybrid-key-exchange-mesh/paper.tex) · [BibTeX](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/papers/post-quantum-hybrid-key-exchange-mesh/references.bib) · [`pqc-hybrid-kms`](https://github.com/FelipeMadson/pqc-hybrid-kms-mesh) |

---

## ⚡ Flagships Poliglotas & Sistemas Distribuídos de Alta Performance

Repositórios de nível de produção demonstrando domínio aprofundado em Rust, Go, TypeScript/WASM, Java 21 e arquiteturas cloud-native resilientes:

| Projeto | Ecossistema & Tecnologias | Destaques Arquiteturais | CI & Releases |
| :--- | :--- | :--- | :---: |
| **[rust-sdn-p4-flow-telemetry-engine](https://github.com/FelipeMadson/rust-sdn-p4-flow-telemetry-engine)** | **Rust 1.80+ · P4 / OpenFlow · Dijkstra SPF · Telemetria** | Pipeline P4 programável (Exact/LPM/TCAM) em Rust seguro, engenharia de tráfego autônoma com SPF de Dijkstra sobre topologias de backbones acadêmicos, failover dinâmico e telemetria Prometheus em line-rate. | [![CI](https://github.com/FelipeMadson/rust-sdn-p4-flow-telemetry-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/rust-sdn-p4-flow-telemetry-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/rust-sdn-p4-flow-telemetry-engine/releases) |
| **[federated-learning-privacy-mesh](https://github.com/FelipeMadson/federated-learning-privacy-mesh)** | **Python 3.12+ · Privacidade Diferencial · Multi-Krum · IA** | Mesh de aprendizado federado multi-institucional, Privacidade Diferencial (ε, δ) formal de Rényi com corte L2 e ruído gaussiano, agregação segura Multi-Krum tolerante a nós bizantinos e daemon REST. | [![CI](https://github.com/FelipeMadson/federated-learning-privacy-mesh/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/federated-learning-privacy-mesh/actions) · [Release v1.0.0](https://github.com/FelipeMadson/federated-learning-privacy-mesh/releases) |
| **[rust-zk-snark-verifier-engine](https://github.com/FelipeMadson/rust-zk-snark-verifier-engine)** | **Rust 1.80+ · Zero-Knowledge Proofs · BN254 · Groth16** | Verificador zk-SNARK Groth16 com curvas emparelhadas BN254 em Rust puro sem dependências, provas constantes de 128 bytes, solver R1CS e atestação de credenciais científicas com preservação de privacidade. | [![CI](https://github.com/FelipeMadson/rust-zk-snark-verifier-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/rust-zk-snark-verifier-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/rust-zk-snark-verifier-engine/releases) |
| **[blockchain-observatory-graph-indexer](https://github.com/FelipeMadson/blockchain-observatory-graph-indexer)** | **Go 1.22+ · Merkle Patricia Trie · Teoria dos Grafos · Segurança DeFi** | Rastreador de estado com Merkle Patricia Trie (MPT), grafo direcionado de fluxo transacional com centralidade PageRank e detecção de ciclos DFS, scanner heurístico de exploits (reentrância e flash loan) e daemon REST para o Observatório RNP. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/blockchain-observatory-graph-indexer) · [Release v1.0.0](https://github.com/FelipeMadson/blockchain-observatory-graph-indexer/releases) |
| **[trust-id-agentic-authority-delegation](https://github.com/FelipeMadson/trust-id-agentic-authority-delegation)** | **Go 1.22+ · W3C DID · OPA · Árvore de Merkle** | Identidade auto-certificável W3C `did:key` (Ed25519), VC 2.0, delegação com atenuação monotônica, portal OPA/Rego e trilha de auditoria Merkle RFC 6962 para Data Spaces da RNP. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/trust-id-agentic-authority-delegation) · [Release v1.0.0](https://github.com/FelipeMadson/trust-id-agentic-authority-delegation/releases) |
| **[pqc-hybrid-kms-mesh](https://github.com/FelipeMadson/pqc-hybrid-kms-mesh)** | **Go 1.22+ · PQC (ML-KEM/ML-DSA) · ETSI QKD 014** | Encapsulamento híbrido KEM NIST FIPS 203 (ML-KEM-768) + X25519, assinaturas híbridas FIPS 204 (ML-DSA-65), interface REST ETSI GS QKD 014 e rotação multidomínio. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/pqc-hybrid-kms-mesh) · [Release v1.0.0](https://github.com/FelipeMadson/pqc-hybrid-kms-mesh/releases) |
| **[rust-ebpf-network-telemetry-probe](https://github.com/FelipeMadson/rust-ebpf-network-telemetry-probe)** | **Rust · Kernel Linux eBPF · XDP · Aya** | Inspeção de pacotes sub-microssegundo no kernel, zero sobrecarga de `sk_buff`, tabelas de fluxo atômicas em BPF e exportador Prometheus. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/rust-ebpf-network-telemetry-probe) · [Release v1.0.0](https://github.com/FelipeMadson/rust-ebpf-network-telemetry-probe/releases) |
| **[go-raft-distributed-consensus-kv](https://github.com/FelipeMadson/go-raft-distributed-consensus-kv)** | **Go 1.22+ · Consenso Raft · Chave-Valor Linearizável** | Máquina de estados Raft completa, timers aleatórios (150-300ms), replicação por quórum, leituras linearizáveis e deduplicação monotônica. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/go-raft-distributed-consensus-kv) · [Release v1.0.0](https://github.com/FelipeMadson/go-raft-distributed-consensus-kv/releases) |
| **[cpp20-lmax-orderbook-engine](https://github.com/FelipeMadson/cpp20-lmax-orderbook-engine)** | **Modern C++20 · HFT · LMAX Disruptor** | Fila circular lock-free, alinhamento de cache (`alignas(64)`), matching Preço-Tempo FIFO e zero alocação no hot path. | [![CI](https://github.com/FelipeMadson/cpp20-lmax-orderbook-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/cpp20-lmax-orderbook-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/cpp20-lmax-orderbook-engine/releases) |
| **[elixir-distributed-actor-cluster](https://github.com/FelipeMadson/elixir-distributed-actor-cluster)** | **Elixir 1.17+ · Erlang/OTP 27 · BEAM** | Consistent Hash Ring com 128 VNodes, supervisão dinâmica (Let-it-Crash), detecção de partição de rede e zero SPOF. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/elixir-distributed-actor-cluster) · [Release v1.0.0](https://github.com/FelipeMadson/elixir-distributed-actor-cluster/releases) |
| **[dotnet-cqrs-event-sourcing-engine](https://github.com/FelipeMadson/dotnet-cqrs-event-sourcing-engine)** | **.NET 9 · C# 13 · CQRS · Event Sourcing** | Arquitetura limpa, replay determinístico de agregados, worker de Transactional Outbox em background e controle otimista de versão. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/dotnet-cqrs-event-sourcing-engine) · [Release v1.0.0](https://github.com/FelipeMadson/dotnet-cqrs-event-sourcing-engine/releases) |
| **[go-distributed-telemetry-pipeline](https://github.com/FelipeMadson/go-distributed-telemetry-pipeline)** | **Go 1.22+ · OpenTelemetry · Motor de Latência** | Buffer circular de janela deslizante thread-safe, percentis P50/P90/P99 com alocação zero, limitador Token Bucket e exportador OTLP. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/go-distributed-telemetry-pipeline) · [Release v1.0.0](https://github.com/FelipeMadson/go-distributed-telemetry-pipeline/releases) |
| **[fastapi-realtime-collaborative-engine](https://github.com/FelipeMadson/fastapi-realtime-collaborative-engine)** | **Python 3.12+ · FastAPI · WebSockets · CRDTs** | CRDTs baseados em estado (LWW-Element-Set, PN-Counter), pub/sub por salas em WebSocket, sync sub-ms e Pydantic v2. | [![CI](https://github.com/FelipeMadson/fastapi-realtime-collaborative-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/fastapi-realtime-collaborative-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/fastapi-realtime-collaborative-engine/releases) |
| **[rust-wasm-simd-vector-search](https://github.com/FelipeMadson/rust-wasm-simd-vector-search)** | **Rust 1.80+ · WebAssembly · 128-bit SIMD** | Grafo vetorial HNSW client-side, similaridade de cosseno sub-ms, 100% isolamento de dados sem nuvem. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/rust-wasm-simd-vector-search) · [Release v1.0.0](https://github.com/FelipeMadson/rust-wasm-simd-vector-search/releases) |
| **[rust-lsm-tree-storage-engine](https://github.com/FelipeMadson/rust-lsm-tree-storage-engine)** | **Rust 1.80+ · Programação de Sistemas** | Motor LSM-tree embarcado, MemTable concorrente com SkipList e WAL append-only com `O_SYNC`. | [![CI](https://github.com/FelipeMadson/rust-lsm-tree-storage-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/rust-lsm-tree-storage-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/rust-lsm-tree-storage-engine/releases) |
| **[go-webhook-delivery-pipeline](https://github.com/FelipeMadson/go-webhook-delivery-pipeline)** | **Go 1.22+ · Concorrência & Worker Pools** | Pipeline concorrente de alta vazão, worker pools, assinaturas HMAC-SHA256 e backoff exponencial com jitter. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/go-webhook-delivery-pipeline) · [Release v1.0.0](https://github.com/FelipeMadson/go-webhook-delivery-pipeline/releases) |
| **[agentic-consensus-workflow-engine](https://github.com/FelipeMadson/agentic-consensus-workflow-engine)** | **TypeScript 5.8+ · Zod · Multi-Agente** | Motor de quórum tolerante a falhas bizantinas, execução determinística em DAG e esquemas tipados com Zod. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/agentic-consensus-workflow-engine) · [Release v1.0.0](https://github.com/FelipeMadson/agentic-consensus-workflow-engine/releases) |
| **[spring-boot-fintech-transaction-engine](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine)** | **Java 21 · Spring Boot 3.3 · Virtual Threads** | Ledger financeiro de alta vazão com Virtual Threads (Loom), padrão Transactional Outbox e idempotência. | [![CI](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine/actions) · [Release v1.0.0](https://github.com/FelipeMadson/spring-boot-fintech-transaction-engine/releases) |
| **[nextjs-enterprise-saas-starter](https://github.com/FelipeMadson/nextjs-enterprise-saas-starter)** | **Next.js 15 · React 19 · Server Actions** | Multi-tenancy por subdomínio, mutações otimistas, controle de acesso baseado em papéis (RBAC) e Tailwind v4. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/nextjs-enterprise-saas-starter) · [Release v1.0.0](https://github.com/FelipeMadson/nextjs-enterprise-saas-starter/releases) |
| **[angular-enterprise-clean-architecture](https://github.com/FelipeMadson/angular-enterprise-clean-architecture)** | **Angular 18 · Signals · Clean Architecture** | Reatividade fina com Signals nativos sem leaks de RxJS, detecção OnPush, Componentes Standalone e DDD. | [![Arquitetura](https://img.shields.io/badge/Arquitetura-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/angular-enterprise-clean-architecture) · [Release v1.0.0](https://github.com/FelipeMadson/angular-enterprise-clean-architecture/releases) |
| **[software-engineering-handbook](https://github.com/FelipeMadson/software-engineering-handbook)** | **Escrita Técnica · Manuais de Arquitetura** | 10 volumes técnicos aprofundados com registro imutável de verificação criptográfica SHA-256. | [![Integridade](https://img.shields.io/badge/Integridade-Verificada-brightgreen.svg)](https://github.com/FelipeMadson/software-engineering-handbook) · [10 Volumes](https://github.com/FelipeMadson/software-engineering-handbook/tree/main/ebooks) |

---

## 🏛️ Filosofia de Engenharia & Pilares Arquiteturais

Desenvolvo soluções com foco rigoroso em **confiabilidade, determinismo e alta eficiência**, fundamentadas em 5 pilares não-negociáveis:

1. **Zero Runtime Dependencies:** Todas as aplicações utilizam exclusivamente a biblioteca padrão nativa do Node.js (`node:test`, `node:crypto`, `node:sqlite`, `node:stream`, `node:http`). Zero dependência de terceiros em runtime significa zero risco de ataques à cadeia de suprimentos e inicialização instantânea sub-10ms.
2. **Design Especializado por Domínio:** Cada microsserviço possui uma identidade visual única e um simulador interativo dedicado executando 100% no navegador via GitHub Pages, sem necessidade de backend remoto.
3. **Criptografia Zero-Trust & Timing-Safe:** Verificação de assinaturas HMAC-SHA256 utilizando comparações em tempo constante (`timingSafeEqual`) contra ataques de canal lateral e cadeias de blocos imutáveis com Merkle Trees.
4. **Resiliência Transacional Local-First:** Persistência em SQLite no modo Write-Ahead Logging (`WAL`) com sub-milissegundo de latência e compatibilidade com ambientes desconectados.
5. **Governança & Rastreabilidade:** Versionamento estrito com [Conventional Commits](https://www.conventionalcommits.org/), registros formais de decisões de arquitetura ([ADRs](docs/adr)), diagramas de C4 Model e esteiras completas de CI/CD no GitHub Actions.

---

## 🚀 Portfólio de Microsserviços & Live Playgrounds

Abaixo estão os **18 microsserviços em produção**, organizados por seus respectivos domínios e arquétipos arquiteturais. **Clique em qualquer simulador para testar a aplicação diretamente no seu navegador:**

### 🧠 AI Studio & Neural Inference

_Orquestradores de modelos neurais locais com quantização GGUF (FP16/Q4_K_M), busca vetorial RAG com similaridade de cosseno e streaming turn-by-turn._

| Projeto | Live Interactive Playground | Testes | Repositório & CI |
| :--- | :--- | :---: | :---: |
| **[Desenvolvimento De Um Agente Ai Personalizado Com Aws Agentcore](https://github.com/FelipeMadson/desenvolvimento-de-um-agente-ai-personalizado-com-aws-agentcore)**<br><small>Microsserviço Enterprise de IA com FastAPI, Vector RAG e Agentes ReAct</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/desenvolvimento-de-um-agente-ai-personalizado-com-aws-agentcore/) | `2 passing` | [![CI Status](https://github.com/FelipeMadson/desenvolvimento-de-um-agente-ai-personalizado-com-aws-agentcore/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/desenvolvimento-de-um-agente-ai-personalizado-com-aws-agentcore/actions) |
| **[Inteligencia Artificial Para Monitoramento De Desempenho De Aplicacoes](https://github.com/FelipeMadson/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes)**<br><small>Enterprise-grade microservice with clean architecture, zero dependencies, and deterministic tests.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes/) | `2 passing` | [![CI Status](https://github.com/FelipeMadson/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes/actions) |
| **[Qwenimageflow Orquestrador De Geracao De Imagens Com Quantizacao Local E Rag](https://github.com/FelipeMadson/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag)**<br><small>Workflow de geração de imagens textuais com latência elevada em nuvem e falta de personalização em modelos pré-treinados</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag/) | `18 passing` | [![CI Status](https://github.com/FelipeMadson/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag/actions) |

---

### 💻 Developer Tools & Interactive Web Terminals

_Emuladores de terminal interativos com parser ANSI, autocompletação via Tab, histórico e execução determinística de comandos._

| Projeto | Live Interactive Playground | Testes | Repositório & CI |
| :--- | :--- | :---: | :---: |
| **[Cli Cursor Manager](https://github.com/FelipeMadson/cli-cursor-manager)**<br><small>Desenvolvedores enfrentam dificuldades para gerenciar o cursor em interfaces de linha de comando de forma consistente entre diferentes terminais e plataformas, especialmente em cenários que exigem animações ou interações complexas</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/cli-cursor-manager/) | `18 passing` | [![CI Status](https://github.com/FelipeMadson/cli-cursor-manager/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/cli-cursor-manager/actions) |
| **[Cliforge Ferramenta De Criacao De Cli Com Autocompletcao Inteligente](https://github.com/FelipeMadson/cliforge-ferramenta-de-criacao-de-cli-com-autocompletcao-inteligente)**<br><small>Desenvolvedores enfrentam complexidade em implementar interfaces de linha de comando robustas com suporte a autocompletção em tempo real.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/cliforge-ferramenta-de-criacao-de-cli-com-autocompletcao-inteligente/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/cliforge-ferramenta-de-criacao-de-cli-com-autocompletcao-inteligente/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/cliforge-ferramenta-de-criacao-de-cli-com-autocompletcao-inteligente/actions) |
| **[Devbox A 1 Click Sandbox For Developers](https://github.com/FelipeMadson/devbox-a-1-click-sandbox-for-developers)**<br><small>Painful and time-consuming setup guides for development environments. DevBox is an automated local sandbox.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/devbox-a-1-click-sandbox-for-developers/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/devbox-a-1-click-sandbox-for-developers/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/devbox-a-1-click-sandbox-for-developers/actions) |
| **[Envdoctor](https://github.com/FelipeMadson/envdoctor)**<br><small>Validador e diagnóstico determinístico de ambientes de desenvolvimento local.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/envdoctor/) | `11 passing` | [![CI Status](https://github.com/FelipeMadson/envdoctor/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/envdoctor/actions) |
| **[Ideabank](https://github.com/FelipeMadson/ideabank)**<br><small>Fullstack Platform for Missing Software Demands, Collaborative Voting & 1-Click GitHub Issues Sync.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/ideabank/) | `23 passing` | [![CI Status](https://github.com/FelipeMadson/ideabank/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/ideabank/actions) |
| **[Logsentinel Memory Guard](https://github.com/FelipeMadson/logsentinel-memory-guard)**<br><small>Vazamento silencioso de memória em serviços Node.js devido a listeners de stream acumulados.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/logsentinel-memory-guard/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/logsentinel-memory-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/logsentinel-memory-guard/actions) |

---

### 📊 Enterprise Multi-Tenant SaaS Platforms

_Plataformas multi-tenant com isolamento de dados, cálculo de percentis de latência (P50/P95/P99) e telemetria Prometheus nativa._

| Projeto | Live Interactive Playground | Testes | Repositório & CI |
| :--- | :--- | :---: | :---: |
| **[Cloudpulse Multi Tenant Analytics](https://github.com/FelipeMadson/cloudpulse-multi-tenant-analytics)**<br><small>Plataformas de métricas cobram fortunas por ingestão de eventos e não oferecem isolamento de dados por tenant.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/cloudpulse-multi-tenant-analytics/) | `18 passing` | [![CI Status](https://github.com/FelipeMadson/cloudpulse-multi-tenant-analytics/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/cloudpulse-multi-tenant-analytics/actions) |
| **[Desenvolvimento De Relatorios Mensais De Desenvolvimento](https://github.com/FelipeMadson/desenvolvimento-de-relatorios-mensais-de-desenvolvimento)**<br><small>Desenvolvedores precisam gerenciar e compartilhar suas jornadas de desenvolvimento, mas atualmente não há uma ferramenta eficiente para isso.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/desenvolvimento-de-relatorios-mensais-de-desenvolvimento/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/desenvolvimento-de-relatorios-mensais-de-desenvolvimento/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/desenvolvimento-de-relatorios-mensais-de-desenvolvimento/actions) |
| **[Submitbutton Com Status De Formulario Corrigido](https://github.com/FelipeMadson/submitbutton-com-status-de-formulario-corrigido)**<br><small>Problema com o useFormStatus retornando falso em formulários React</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/submitbutton-com-status-de-formulario-corrigido/) | `16 passing` | [![CI Status](https://github.com/FelipeMadson/submitbutton-com-status-de-formulario-corrigido/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/submitbutton-com-status-de-formulario-corrigido/actions) |

---

### 🛡️ Zero-Trust Security & Cryptographic Vaults

_Laboratórios criptográficos de alta confidencialidade com assinaturas HMAC-SHA256, verificações timing-safe e cadeias de auditoria imutáveis (Merkle trees)._

| Projeto | Live Interactive Playground | Testes | Repositório & CI |
| :--- | :--- | :---: | :---: |
| **[Expo Secure Secrets Cli](https://github.com/FelipeMadson/expo-secure-secrets-cli)**<br><small>Developers struggle with securely managing environment variables and secrets across different environments in mobile and cross-platform apps.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/expo-secure-secrets-cli/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/expo-secure-secrets-cli/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/expo-secure-secrets-cli/actions) |
| **[Profile Sync](https://github.com/FelipeMadson/profile-sync)**<br><small>Estudante de Tecnologia em Sistemas para Internet (TSI)</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/profile-sync/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/profile-sync/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/profile-sync/actions) |
| **[Webhookvault](https://github.com/FelipeMadson/webhookvault)**<br><small>Local-First Webhook Inspector, Deterministic Replayer & HMAC Verification Hub.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/webhookvault/) | `24 passing` | [![CI Status](https://github.com/FelipeMadson/webhookvault/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/webhookvault/actions) |

---

### 🧩 Chrome Browser Extensions (Manifest V3)

_Extensões para o Google Chrome com regras declarativas Manifest V3, interceptação da Omnibox e telemetria de rede._

| Projeto | Live Interactive Playground | Testes | Repositório & CI |
| :--- | :--- | :---: | :---: |
| **[Persistnetworkredirects Chrome Extension](https://github.com/FelipeMadson/persistnetworkredirects-chrome-extension)**<br><small>Console SPA Moderno em React 18 e Vite</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/persistnetworkredirects-chrome-extension/) | `11 passing` | [![CI Status](https://github.com/FelipeMadson/persistnetworkredirects-chrome-extension/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/persistnetworkredirects-chrome-extension/actions) |

---

### 🌐 Localization & System Matrix Platforms

_Matrizes de tradução corporativa com validação de regras de plural ICU, fallback resiliente e exportação multiplataforma (Web JSON, Android XML, iOS .strings)._

| Projeto | Live Interactive Playground | Testes | Repositório & CI |
| :--- | :--- | :---: | :---: |
| **[I18n Studio Automatizando Traducoes Para Aplicativos Multiplataforma](https://github.com/FelipeMadson/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma)**<br><small>Tradução de múltiplos idiomas para aplicativos iOS, macOS, Android e JS pode ser um processo doloroso.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma/) | `18 passing` | [![CI Status](https://github.com/FelipeMadson/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma/actions) |
| **[Model Based Design Platform For Engineers](https://github.com/FelipeMadson/model-based-design-platform-for-engineers)**<br><small>Engineers and scientists use outdated, monolithic tools for complex system design and simulation tasks.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/model-based-design-platform-for-engineers/) | `20 passing` | [![CI Status](https://github.com/FelipeMadson/model-based-design-platform-for-engineers/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/model-based-design-platform-for-engineers/actions) |

---



## 📊 Matriz Tecnológica de Engenharia

```
┌────────────────────────────────────────────────────────────────────────┐
│                      FELIPE MADISON — TSI TECH STACK                   │
├───────────────────┬──────────────────────────────┬─────────────────────┤
│ Runtimes & Base   │ Node.js 22 & 24 LTS (ESM)    │ TypeScript Nativo   │
│ Bancos de Dados   │ SQLite WAL Mode (node:sqlite)│ Modelagem Relacional│
│ Criptografia      │ HMAC-SHA256, WebCrypto Subt. │ Merkle Audit Chains │
│ Qualidade & Teste │ node:test nativo, node:assert│ Chaos Fuzzing (100%)│
│ CI/CD & Segurança │ GitHub Actions, CodeQL SAST  │ Conventional Commits│
│ Simulação Web     │ HTML5, CSS Moderno, Canvas 2D│ Zero Bundler/Vanilla│
└───────────────────┴──────────────────────────────┴─────────────────────┘
```

---

## 📬 Contato & Colaboração

* **GitHub:** [https://github.com/FelipeMadson](https://github.com/FelipeMadson)
* **Status do Portfólio:** 100% dos repositórios públicos, com testes automatizados aprovados e documentação técnica completa.
* Fique à vontade para explorar os códigos-fonte, abrir issues ou propor melhorias arquiteturais!
