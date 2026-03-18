# 📚 Guia de Skills Disponíveis

Este documento é uma referência rápida de todas as **skills** (habilidades, padrões e ferramentas) disponíveis para os agentes de Inteligência Artificial neste workspace. 

As skills são injetadas automaticamente no contexto do assistente dependendo da tarefa ou do especialista (`agent`) ativado, mas você também pode direcionar tarefas específicas consultando estes pilares.

---

### 🏛️ Fundamentos e Arquitetura
- **architecture**: Framework de decisões arquiteturais. Análise de requisitos, avaliação de trade-offs (prós e contras) e documentação baseada em ADR (Architecture Decision Records).
- **api-patterns**: Princípios de design de APIs. Auxilia a decisão entre REST, GraphQL e tRPC, além de definir formatos de respostas, paginação e controle de versão.
- **clean-code**: Padrões concisos e diretos para manter um código limpo. Evita over-engineering (complexidade desnecessária) e define que o próprio código deve ser sua documentação principal.
- **database-design**: Princípios de design de banco de dados. Focado em diagramação de schemas, estratégias de indexação, seleção de ORM e utilização de bancos de dados serverless.

### 💻 Desenvolvimento Backend e Linguagens
- **nodejs-best-practices**: Boas práticas com Node.js. Foco na escolha de frameworks, padrões assíncronos, segurança e arquitetura modular.
- **python-patterns**: Princípios de desenvolvimento em Python (tipagem, programação assíncrona, estrutura de projeto).
- **rust-pro**: Especialista em Rust (1.75+). Traz os padrões modernos assíncronos (Tokio, axum), além do controle de memória focado em performance avançada.
- **mcp-builder**: Fundamentos e padrões na hora de projetar e criar servidores que operam pelo Model Context Protocol (MCP).

### 🎨 Frontend, Mobile e UI/UX
- **frontend-design**: Princípios de UI/UX focados em web. Abrange layouts, tipografia, paletas de cores e fluidez estética sem depender de valores rígidos, e sim de conceitos de design moderno.
- **react-best-practices (expert)**: Mestre em performance utilizando React e Next.js baseado nos padrões de engenharia da Vercel. Excelente para remover "waterfalls" de carregamento e otimizar bundle no client-side.
- **mobile-design**: Princípios fundamentais para criar interfaces Mobile-first (iOS e Android), suportando fluxos para React Native e Flutter. Focado na experiência de toque, performance e convenções das plataformas.
- **tailwind-patterns**: Padrões modernos focados no Tailwind CSS v4+, adotando container queries, configurações *CSS-first* e arquitetura baseada em design tokens.
- **web-design-guidelines**: Revisor e auditor dedicado de UI. Valida o código focado em acessibilidade web, consistência de experiência do usuário (UX) e melhores recomendações do mercado.

### 🧪 Testes, QA e Debugging
- **systematic-debugging**: Focado em uma metodologia de depuração (debug) em 4 fases para resolver bugs complexos encontrando a causa raiz técnica e sistemática.
- **tdd-workflow**: Reforça o fluxo seguro do TDD (Ciclo Red-Green-Refactor) para garantir resiliência e foco no domínio dos testes.
- **testing-patterns**: Estratégias e padrões para montar testes de unidade, testes de integração e "mocking" seguro.
- **webapp-testing**: Princípios e arquitetura de testes robustos End-to-End (E2E) com frameworks como Playwright.

### 🛡️ Segurança e Performance
- **performance-profiling**: Métricas de análise e perfil de performance cobrindo técnicas puras de otimização de funil e gargalos.
- **vulnerability-scanner**: Traz os princípios de segurança OWASP 2025 focado na varredura passiva de código para blindar áreas sensíveis de injeções e ataques na cadeia de dependências.
- **code-review-checklist**: Passo a passo meticuloso usado durante avaliações e revisões de código de qualidade, rastreando falhas comuns e furos de segurança ou vazamento de segredos.
- **red-team-tactics**: Estratégias do tipo "Red Team" seguindo os preceitos globais da matriz MITRE ATT&CK para mapeamento crítico da superfície do sistema.

### ⚙️ DevOps, Infraestrutura e Terminal
- **bash-linux**: Especialista em regras de terminais Unix/Linux na raiz (Pipes potentes, manipulação de processos e criação de scripts utilitários robustos).
- **powershell-windows**: Compreensão de armadilhas clássicas, sintaxe de operadores avançados e tratamento seguro de erros via console do Windows.
- **server-management**: Decisão autônoma e estratégias do mundo real de dimensionamento de gestão de servidores raiz (monitoria, scaling).
- **deployment-procedures**: Padrões exigentes de procedimentos de Lançamento/Deploy sem queda. Traz esquemas de fluxos rollback, Canary deploy etc.

### 🧠 Comportamento e Orquestração do Agente
- **app-builder**: Orquestrador "mãe" central na hora de criar do *zero* aplicações full-stack a partir das ideias do usuário e interações conversacionais. 
- **behavioral-modes**: Modos base comportamentais que ativam diretrizes para a IA transitar entre ensino, depuração de erros, debate filosófico arquitetônico etc.
- **brainstorming**: O protocolo oficial socrático limitador (gatilho usado toda vez que recebemos solicitações vagas ou a criação de novas features que precisam antes passar por perguntas inteligentes).
- **intelligent-routing**: Lógica automatizada e autônoma sem a necessidade explícita do usuário mencionar que "precisa do agente X", sendo o motor para acionar agentes e skills sozinhos na medida da necessidade.
- **parallel-agents**: Coordenação de multi-agentes onde vários processos de especialistas rodam perfeitamente ao mesmo temporários focados numa meta gigante comum.
- **plan-writing**: Prática restrita de criação lógica, descritiva e cadenciada de Planos e Marcos de Arquitetura em passos controlados detalhadamente.
- **game-development**: Regras bases universais usadas caso a solicitação seja a criação e engenharia de Jogos/Engines.

### 🌍 Outros Utilitários Específicos
- **seo-fundamentals**: SEO focado em E-E-A-T e regras mais atuais do Google Search assim como medições contínuas de métricas Web Vitals.
- **geo-fundamentals**: Otimizações GE0, visando fazer com que o portal do projeto seja de fácil resposta e sumário para ser encontrado por *outras* turbinas de linguagem de IA (ChatGPT, Claude Search, Perplexity).
- **i18n-localization**: Localização técnica. Organização e arquitetura de strings internacionais, suportes da-direita-para-esqueda (RTL) etc.
- **documentation-templates**: Roteiros e gabaritos pré-dispostos para Readme robustos e com descrições automáticas amigáveis a novas abordagens.
