# Felipe Madison

**Engenharia de Sistemas para Internet · Arquitetura Local-First · Ferramentas de Sistema**

[Portfólio](https://felipemadson.github.io/portfolio/) · [English Version](README.md) · [Perfil no GitHub](https://github.com/FelipeMadson)

---

### Sobre Mim

Sou Desenvolvedor de Software e graduando em **Tecnologia em Sistemas para Internet (TSI)**. Minha atuação é focada na construção de ferramentas determinísticas para desenvolvedores, arquiteturas local-first, sistemas distribuídos resilientes para filas e fluxos de IA local.

Priorizo recursos nativos da biblioteca padrão, runtimes com zero dependências externas, tipagem estrita, testes automatizados reproduzíveis e interfaces limpas e acessíveis.

---

### Stack Tecnológica & Competências

| Domínio | Tecnologias & Padrões |
| :--- | :--- |
| **Linguagens & Runtimes** | Node.js 22/24 (ESM Nativo), TypeScript, Python 3.12+, SQL |
| **Arquitetura Frontend** | Angular 22 (Signals, Componentes Standalone, Detecção OnPush), HTML5 Semântico, CSS Moderno Responsivo, Acessibilidade WCAG AA |
| **Backend & Serviços** | FastAPI, Node.js HTTP/Streams nativo, APIs RESTful, Barramentos de Eventos Estruturados |
| **Persistência & Armazenamento** | PostgreSQL (Modelagem Relacional, Restrições, Migrações), SQLite Modo WAL (`node:sqlite`), Outboxes em Memória |
| **Segurança & Resiliência** | HMAC-SHA256 em Tempo Constante (`timingSafeEqual`), Limitador de Taxa Token-Bucket, Proteção contra Replay, Dead-Letter Queues (DLQ), Circuit Breakers |
| **Qualidade & Verificação** | Playwright E2E (Multi-Viewport), Pytest, Vitest, Node Test Runner Nativo (`node:test`), Ambientes Determinísticos em Contêineres |

---

### Projetos em Destaque

#### 1. [QueueGuard Platform](https://github.com/FelipeMadson/mitigacao-processamento-duplicado-filas-assincronas)
> **Plataforma Fullstack de Processamento Idempotente de Filas Assíncronas**  
> *Stack: Angular 22 · Signals · FastAPI · PostgreSQL · Playwright · CI no GitHub Actions*

- **Problema:** Brokers de mensagens assíncronas frequentemente realizam entregas duplicadas em falhas de rede ou retentativas, provocando escritas duplicadas, contenção de leases e inconsistência de dados.
- **Solução:** Implementação de uma arquitetura completa de desduplicação com aquisição atômica de lease, esquema relacional com migrações PostgreSQL e painel reativo em tempo real em Angular 22.
- **Verificação:** Verificado por testes unitários, testes de aceitação e Playwright em múltiplos viewports (390px, 768px, 1440px) com persistência confirmada após reinício do banco de dados e pipeline de CI no GitHub Actions.

#### 2. [WebhookVault](https://github.com/FelipeMadson/webhookvault)
> **Gateway Criptográfico Local-First para Webhooks com Motor de Replay**  
> *Stack: Node.js (Nativo) · TypeScript · SQLite WAL · Criptografia Timing-Safe*

- **Problema:** Depurar webhooks de provedores como GitHub, Stripe e Shopify expõe endpoints de desenvolvimento a ataques de temporização e vulnerabilidades de replay.
- **Solução:** Gateway operável offline com verificação de assinatura HMAC-SHA256 em tempo constante (`timingSafeEqual`), replay com recálculo automático de assinaturas e timestamps atualizados, e painel web integrado Dark Mode com zero dependências externas.
- **Verificação:** 22 testes determinísticos automatizados com `node:test` e validação de recuperação após falhas com SQLite WAL.

#### 3. [CloudPulse Multi-Tenant Analytics](https://github.com/FelipeMadson/cloudpulse-multi-tenant-analytics)
> **Motor de Telemetria de Eventos Local-First com Imposição de Cotas**  
> *Stack: Node.js 22 · SQLite WAL · Métricas Prometheus · Token Bucket*

- **Problema:** Instrumentação de SaaS multi-tenant frequentemente acarreta dependência de provedores proprietários de nuvem e risco de vazamento de dados entre tenants.
- **Solução:** Motor leve local-first com isolamento rigoroso por tenant, controle de vazão por token-bucket, despacho assinado por HMAC e exportadores nativos de métricas Prometheus.
- **Verificação:** 23 testes automatizados validando isolamento estrito de dados e persistência sub-milissegundo não-bloqueante.

#### 4. [EnvDoctor](https://github.com/FelipeMadson/envdoctor)
> **CLI de Diagnóstico e Auditoria de Ambientes Dev em Sub-Segundo**  
> *Stack: Node.js (ESM Nativo) · Multiplataforma (Ubuntu e Windows)*

- **Problema:** Divergências de configuração de ambiente, versões incompatíveis de runtimes, conflitos de portas TCP e vazamento de segredos em arquivos `.env`.
- **Solução:** CLI determinística com auditoria concorrente em menos de 60ms de runtimes, portas TCP ativas e prevenção rígida de vazamento de credenciais.
- **Verificação:** Matriz de CI no GitHub Actions executando em Ubuntu e Windows com Node.js 22 e 24.

#### 5. [CLI Cursor Manager](https://github.com/FelipeMadson/cli-cursor-manager)
> **Motor de Coordenação de Cursor para ANSI e Webterm**  
> *Stack: Node.js (Nativo) · Zero Dependências de Runtime · Padrões de Terminal*

- **Problema:** Inconsistências de posicionamento de cursor e códigos de escape ANSI entre emuladores de terminal, xterm.js e terminais web geram artefatos visuais e quebras de interface.
- **Solução:** Padronização do ciclo de vida do cursor e quadros de animação com suporte a padrões ANSI e zero dependências de terceiros.
- **Verificação:** 29 testes automatizados garantindo conformidade com padrões de escape.

#### 6. [I18n Studio](https://github.com/FelipeMadson/i18n-studio-automatizando-traducoes-para-aplicativos-multiplataforma)
> **Esteira Automatizada de Tradução Multiplataforma**  
> *Stack: Node.js · TypeScript · Validação de Esquema Local*

- **Problema:** Gestão de dicionários de internacionalização entre web, mobile e templates de servidor provoca divergências de sintaxe e chaves ausentes.
- **Solução:** Orquestrador automatizado baseado em AST para validação de chaves, detecção de colisões e garantia de paridade de esquemas entre plataformas.
- **Verificação:** 23 testes automatizados cobrindo resolução de chaves e validação estrutural.

---


### 📚 Manuais de Engenharia & Arquitetura de Software

#### [Software Engineering Handbook](https://github.com/FelipeMadson/software-engineering-handbook)
> **Guias Arquiteturais Aprofundados, Padrões Distribuídos Resilientes & Verificação**  
> *Stack: TypeScript · Design Arquitetural · Node.js · Verificação de Segurança · GitHub Actions CI*

Série publicada de manuais práticos de engenharia de software cobrindo tópicos de missão crítica com implementações verificadas:
- **Arquitetura de Filas Idempotentes:** Deduplicação, leases atômicos e padrões outbox.
- **Sincronização Offline-First com CRDT:** Estado replicado sem conflitos e persistência local-first.
- **Segurança Multitenant com Row-Level Security:** PostgreSQL RLS, isolamento de contexto e defesa em profundidade.
- **Ambientes Determinísticos de Desenvolvimento:** Toolchains reproduzíveis, builds herméticos e sandboxes.
- **Isolamento de Segredos em CI/CD:** Integração segura com cofres em memória e prevenção de vazamentos.

---

### Princípios de Engenharia

1. **Determinismo & Local-First:** Sistemas projetados para operar de forma confiável localmente, preservando a privacidade dos dados e evitando dependência arbitrária de nuvens comerciais.
2. **Uso Eficiente da Biblioteca Padrão:** Preferência pelos recursos nativos do Node.js e da linguagem para garantir inicialização abaixo de 100ms, manutenção simplificada e zero vulnerabilidades de cadeia de suprimentos.
3. **Engenharia Baseada em Evidências:** Nenhuma funcionalidade é declarada concluída sem suítes de testes automatizados aprovadas, benchmarks mensuráveis e artefatos de execução verificados.
4. **Design Limpo e Acessível:** Interfaces estruturadas, acessíveis (WCAG AA), totalmente responsivas e livres de poluição visual.

---

### Conexão & Colaboração

- **GitHub:** [@FelipeMadson](https://github.com/FelipeMadson)
- **Portfólio Interativo:** [felipemadson.github.io/portfolio](https://felipemadson.github.io/portfolio/)
- **Contribuições:** Contribuições e revisões de código são bem-vindas via GitHub issues e pull requests.
