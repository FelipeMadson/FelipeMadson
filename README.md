# Olá, eu sou o Felipe Madison 👋

> **Estudante de Tecnologia em Sistemas para Internet (TSI)**  
> 🎯 **Foco de Atuação:** Engenharia de Software Web, Arquitetura Local-First, Sistemas Distribuídos e Ferramentas para Desenvolvedores  
> 📍 **GitHub:** [@FelipeMadson](https://github.com/FelipeMadson)

<p align="left">
  <a href="https://github.com/FelipeMadson"><img src="https://img.shields.io/github/followers/FelipeMadson?label=Seguidores&style=social" alt="Followers"></a>
  <img src="https://img.shields.io/badge/Testes%20Automatizados-301%20Passing-brightgreen.svg?logo=node.js" alt="Testes">
  <img src="https://img.shields.io/badge/Projetos%20em%20Produção-18%20Microsserviços-blue.svg?logo=github" alt="Projetos">
  <img src="https://img.shields.io/badge/Runtime%20Dependencies-0%20(Native%20Only)-success.svg" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/Security-CodeQL%20SAST%20100%25%20Passed-indigo.svg?logo=githubactions" alt="CodeQL">
  <img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg" alt="Conventional Commits">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-lightgrey.svg" alt="License"></a>
</p>

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
| **[Inteligencia Artificial Para Monitoramento De Desempenho De Aplicacoes](https://github.com/FelipeMadson/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes)**<br><small>Microsserviço corporativo de alta robustez com clean architecture e zero dependências de runtime.</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes/) | `2 passing` | [![CI Status](https://github.com/FelipeMadson/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/inteligencia-artificial-para-monitoramento-de-desempenho-de-aplicacoes/actions) |
| **[Qwenimageflow Orquestrador De Geracao De Imagens Com Quantizacao Local E Rag](https://github.com/FelipeMadson/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag)**<br><small>Workflow de geração de imagens textuais com latência elevada em nuvem e falta de personalização em modelos pré-treinados</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag/) | `18 passing` | [![CI Status](https://github.com/FelipeMadson/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/qwenimageflow-orquestrador-de-geracao-de-imagens-com-quantizacao-local-e-rag/actions) |

---

### 💻 Developer Tools & Web Terminals

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

### 📊 Enterprise Multi-Tenant SaaS

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

### 🧩 Chrome Browser Extensions

_Extensões para o Google Chrome com regras declarativas Manifest V3, interceptação da Omnibox e telemetria de rede._

| Projeto | Live Interactive Playground | Testes | Repositório & CI |
| :--- | :--- | :---: | :---: |
| **[Persistnetworkredirects Chrome Extension](https://github.com/FelipeMadson/persistnetworkredirects-chrome-extension)**<br><small>Console SPA Moderno em React 18 e Vite</small> | [🎮 **Abrir Simulador**](https://felipemadson.github.io/persistnetworkredirects-chrome-extension/) | `11 passing` | [![CI Status](https://github.com/FelipeMadson/persistnetworkredirects-chrome-extension/actions/workflows/ci.yml/badge.svg)](https://github.com/FelipeMadson/persistnetworkredirects-chrome-extension/actions) |

---

### 🌐 Localization & System Matrix Studios

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
