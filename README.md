# Luiz Felipe

**Engenheiro de IA Sênior · Tech Lead Backend**  
São Paulo, Brasil · [E-mail](mailto:luiz23.lfsc@gmail.com) · [LinkedIn](https://www.linkedin.com/in/luizfelipe-techlead/)

Desenvolvo sistemas de IA aplicada: agentes conversacionais, busca com RAG, APIs e automações integradas a processos de negócio. Meu foco está na engenharia que sustenta essas soluções — contratos de API, persistência, testes, controle de custo, observabilidade e operação.

Sou fundador da Lufe Digital Wave e formado em Ciências Econômicas pela PUC-SP. Trago essa combinação de engenharia e visão de negócio para decidir o que automatizar, como medir o resultado e quais limites o sistema precisa respeitar.

## Comece por estes projetos

| Projeto | O que você encontra | O que avaliar |
| --- | --- | --- |
| [Atende AI](https://github.com/LufeDigitalWave/atende-ai) | Demonstração de agentes SDR e FAQ/RAG, com FastAPI, React e dados fictícios. | Separação entre geração de dados, montagem de prompts e execução; streaming SSE, testes e [avaliação de conversas](https://github.com/LufeDigitalWave/atende-ai/blob/main/docs/EVALUATION.md). |
| [Freela Food](https://github.com/LufeDigitalWave/freela-food) | Marketplace de food service com FastAPI, PostgreSQL/PostGIS, filas e frontend Next.js. | Modelagem de domínio, fluxos de candidatura e convite, migrations e [testes de backend](https://github.com/LufeDigitalWave/freela-food/tree/main/tests). |
| [Motor de recomendação determinístico](https://github.com/LufeDigitalWave/deterministic-recommendation-engine) | Exemplo de recomendação com normalização, filtros e pontuação ponderada. | Decisões explicáveis, configuração de pesos e uso de PostgreSQL sem LLM no caminho de recomendação. |

Os repositórios têm escopos diferentes: aplicações de demonstração, templates e cases documentais. Nos projetos executáveis, consulte as instruções do respectivo README. Resultados e métricas de sistemas privados não devem ser atribuídos automaticamente a estes projetos públicos.

## Código para uma avaliação técnica rápida

Três exemplos focados em decisões que costumo discutir em backend e IA aplicada. Cada um roda offline com Python e biblioteca padrão, tem testes de comportamento e CI. O README mostra como executar; `EVALUATION.md` liga as invariantes aos testes.

| Exemplo | Problema demonstrado | Onde avaliar |
| --- | --- | --- |
| [Pedidos e outbox](https://github.com/LufeDigitalWave/commerce-platform-case-study) | O mesmo evento chega duas vezes, ou uma escrita falha no meio da transação. | [Código](https://github.com/LufeDigitalWave/commerce-platform-case-study/tree/main/order_flow) · [Testes e decisões](https://github.com/LufeDigitalWave/commerce-platform-case-study/blob/main/EVALUATION.md) |
| [CRM multi-tenant](https://github.com/LufeDigitalWave/multi-tenant-crm-case-study) | Uma operação tenta acessar dados de outra organização; um lote precisa reverter por inteiro. | [Código](https://github.com/LufeDigitalWave/multi-tenant-crm-case-study/tree/main/tenant_crm) · [Testes e decisões](https://github.com/LufeDigitalWave/multi-tenant-crm-case-study/blob/main/EVALUATION.md) |
| [Política de ferramentas para agentes](https://github.com/LufeDigitalWave/sales-intelligence-case-study) | Uma proposta não confiável precisa ser validada e aprovada antes de preparar um rascunho. | [Código](https://github.com/LufeDigitalWave/sales-intelligence-case-study/tree/main/tool_policy) · [Testes e decisões](https://github.com/LufeDigitalWave/sales-intelligence-case-study/blob/main/EVALUATION.md) |

São **implementações didáticas novas**, não código extraído dos sistemas privados. Usam dados sintéticos e não chamam serviços externos. Os testes demonstram o comportamento destes exemplos, não resultados de produção de clientes.

## Outros cases técnicos anonimizados

Estes seis cases são **documentação técnica, não aplicações executáveis**. Apresentam problemas, stacks e decisões de arquitetura sem divulgar clientes ou implementações proprietárias. Os diagramas são abstrações; os roteiros de validação não representam testes executados nos sistemas de origem.

| Case | Foco da discussão técnica |
| --- | --- |
| [Atendimento e demandas](https://github.com/LufeDigitalWave/govtech-operations-case-study) | Recebimento de eventos, registro de demandas e acompanhamento operacional. |
| [Hábitos e bem-estar](https://github.com/LufeDigitalWave/wellness-platform-case-study) | Interfaces web e móvel, registros pessoais e limites de privacidade. |
| [Solicitação de serviços](https://github.com/LufeDigitalWave/service-request-website-case-study) | Conteúdo modular, composição de solicitações e encaminhamento para atendimento. |
| [Diretório e descoberta conversacional](https://github.com/LufeDigitalWave/local-discovery-case-study) | Busca apoiada em registros, moderação e gestão de conteúdo publicado. |
| [Consolidação de conversas](https://github.com/LufeDigitalWave/conversation-digest-case-study) | Janelas de processamento, retomada e revisão de resumos. |
| [Portfólio modular](https://github.com/LufeDigitalWave/developer-portfolio-case-study) | Separação de conteúdo e interface, navegação e estado de demonstrações. |

## Áreas de atuação

- **IA aplicada:** agentes LLM, RAG, saídas estruturadas, avaliação e integração com ferramentas.
- **Backend e dados:** Python, FastAPI, TypeScript, PostgreSQL, pgvector, Redis e APIs.
- **Automação e operação:** n8n, webhooks, integrações com WhatsApp e CRM, Docker, GitHub Actions e observabilidade.

Em uma avaliação técnica, posso discutir decisões de arquitetura, limites dos exemplos, estratégias de teste e evolução para produção. Tenho interesse em oportunidades de **Engenharia de IA e liderança técnica de backend**.

[Entre em contato por e-mail](mailto:luiz23.lfsc@gmail.com) · [Veja os repositórios públicos](https://github.com/LufeDigitalWave?tab=repositories)

<details>
<summary>English summary</summary>

I'm Luiz Felipe, a Senior AI Engineer and Backend Tech Lead based in São Paulo, Brazil. I work on applied AI systems, conversational agents, RAG, APIs and business automation, with a focus on testing, observability and operational constraints.

Start with **Atende AI** for conversational applications, **Freela Food** for backend and domain modeling, and the **deterministic recommendation engine** for explainable decision pipelines. These public demos and templates illustrate engineering approaches; they do not contain private client implementations.

For a focused code review, explore the three offline Python examples: transactional order processing, tenant-scoped data access, and an approval gate for untrusted tool proposals. They are new educational implementations with synthetic data, behavioral tests and CI—not private client source code. The other six case studies are documentation-only architecture discussions, not runnable applications or evidence of production test results.

Contact: [luiz23.lfsc@gmail.com](mailto:luiz23.lfsc@gmail.com).

</details>
