# 🦎 FlexERP

## 🧭 Descrição do Projeto

O **FlexERP** é um sistema de gestão empresarial full stack, desenvolvido para se adaptar a diferentes tipos de negócios — desde pequenas empresas até grandes operações.  
Seu principal diferencial é a **flexibilidade modular**, permitindo configurar e ativar apenas os módulos necessários conforme o tipo de negócio, tornando o sistema **dinâmico, escalável e personalizável**.

A proposta do FlexERP é ser uma plataforma de **gestão centralizada**, capaz de abranger processos como controle financeiro, estoque, vendas, RH, CRM, relatórios, e muito mais — tudo com uma interface moderna, segura e intuitiva.

---

## 🎯 Objetivos do Projeto

- Desenvolver um **ERP versátil**, que possa ser facilmente adaptado a diferentes modelos de negócio.  
- Oferecer **autonomia e personalização**, permitindo ao usuário escolher módulos e recursos conforme suas necessidades.  
- Implementar uma **arquitetura robusta**, com foco em escalabilidade, segurança e performance.  
- Fornecer **insights estratégicos** através de dashboards e relatórios inteligentes.  
- Integrar **metodologias ágeis (Scrum)** no desenvolvimento e gestão do projeto.  

---

## ⚙️ Principais Funcionalidades (MVP + Futuras)

### 🧩 MVP (Mínimo Produto Viável)
- Cadastro e autenticação de usuários (login, senha e login social via Google).  
- Controle de permissões e perfis de acesso.  
- Gestão de clientes, fornecedores e produtos.  
- Controle financeiro básico (entradas, saídas, categorias e relatórios).  
- Dashboard com métricas gerais do negócio.  
- CRUD completo e interface intuitiva.  
- Configuração de módulos ativos (flexibilidade do sistema).  

### 🚀 Funcionalidades Futuras
- Emissão de notas fiscais eletrônicas (NF-e).  
- Integração com APIs externas (bancos, marketplaces, CRMs).  
- Controle de estoque avançado com alertas de reposição.  
- Automação de tarefas e notificações inteligentes.  
- Aplicativo mobile (Android/iOS).  
- Painel de relatórios e BI com gráficos dinâmicos.  
- Sistema multi-empresa e multiusuário.

  ---

  # 🧩 Stack — FlexERP

| **Camada** | **Tecnologias** | **Observações** |
|-------------|------------------|------------------|
| **Frontend (Web)** | Next.js + Chart.js + TypeScript + TailwindCSS + ShadCN UI | Mantém o front moderno, performático e responsivo. Comunicação com o back via REST (ou GraphQL). |
| **Backend (API REST)** | Python + FastAPI + Uvicorn + Pydantic + SQLAlchemy + FastAPI Users | Substitui o Spring Boot: framework moderno, rápido e com documentação automática (Swagger). Estrutura leve e tipada. |
| **Banco de Dados** | PostgreSQL (Supabase / Neon.tech) | Continua igual — compatível com SQLAlchemy e ideal para ERP modular. |
| **Infraestrutura e Hospedagem** | Render (backend) + Vercel (frontend) + Supabase (banco) | Totalmente integrável. Render e Supabase suportam FastAPI sem custo inicial. |
| **Containerização** | Docker + Docker Compose | Criação de containers para FastAPI, PostgreSQL e Redis. Facilita deploy e ambiente local. |
| **CI/CD** | GitHub Actions + Pytest Workflow | Automatiza build, testes e deploy contínuo. Configura pipeline para executar testes Pytest e deploy no Render. |
| **Design e UX** | Figma | Mantém o design system e prototipagem. |
| **Documentação** | Swagger (automático via FastAPI) + Scalar + README.md + Notion/Jira | FastAPI gera documentação interativa nativa (Swagger e ReDoc). |
| **Metodologia Ágil** | Scrum (Jira e GitHub Projects) | Sprints, backlog, epics e acompanhamento contínuo. |
| **Autenticação** | OAuth2 + JWT (FastAPI Users / Authlib) | Login com Google, autenticação segura e controle de acesso baseado em papéis (roles). |
| **Qualidade e Padronização** | Black / Ruff / MyPy / Pre-commit Hooks (Husky equivalente) | Linter, formatação automática e análise estática de tipos — garantem padrão e qualidade do código antes dos commits. |
| **Padrão de Arquitetura** | Clean Architecture + Service Layer + Repository Pattern (FastAPI modular) | Estrutura limpa, orientada a domínio, com camadas independentes e de fácil manutenção. |
| **Testes** | Pytest (backend) + React Testing Library (frontend) + Postman (APIs) | Testes unitários, integração e E2E. Pytest é rápido e amplamente usado em APIs Python. |

## Estratégia de Stack

- ✅ **Custo zero inicial** — ideal para desenvolvimento, testes e MVP.  
- ⚙️ **Arquitetura modular e escalável** — preparada para crescer com microsserviços no futuro.  
- 🌐 **Deploy simplificado** — integração direta com GitHub e plataformas gratuitas.  
- 🧩 **Fácil migração para AWS** — a estrutura atual é compatível com EC2, RDS e S3.  
- 💡 **Stack moderna e valorizada no mercado**, com tecnologias usadas por grandes empresas.
