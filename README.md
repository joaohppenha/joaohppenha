<h1 align="center">Olá, eu sou João Henrique 👋 · Hi, I'm João Henrique 👋</h1>

<p align="center">
  <b>PT: Engenheiro de Backend & IA · Jurimetrista · Pesquisador na Cohere Open Labs</b><br/>
  <b>EN: Backend & AI Engineer · Jurimetrics Specialist · Cohere Open Labs Researcher</b><br/>
  <br/>
  LLMs & Structured Outputs · Distributed Data Pipelines · Medallion Architecture · Data Governance & Audit
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jhppenha/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---

<!-- Toggle de idioma / Language toggle -->
<details open>
<summary><b>🇧🇷 Português</b></summary>

## Sobre

Transformo infraestruturas de dados complexas em sistemas inteligentes através da união entre **Engenharia de Backend**, **IA Generativa** e **Governança de Dados**. Com uma trajetória sólida de mais de 10 anos na intersecção entre tecnologia e o setor jurídico, sou especialista em Jurimetria e atuo em todo o ciclo de vida do dado: desde a construção de pipelines distribuídos escaláveis até o design de arquiteturas de IA integradas a regras de negócio e conformidade.

Atualmente, sou graduando em Análise e Desenvolvimento de Sistemas (ADS) e divido minha atuação técnica em três frentes de alto impacto:

- **Engenharia de Backend & IA na FlyRank:** Desenvolvimento de infraestrutura de microsserviços, contratos de APIs estáveis e fluxos de IA baseados em recuperação (RAG) e saídas estruturadas (*structured outputs*).
- **Pesquisa Avançada na Cohere Open Labs:** Membro aprovado no ecossistema global de ciência aberta da Cohere, focado nas fronteiras de Large Language Models (LLMs), Processamento de Linguagem Natural (NLP) e computação quântica.
- **Governança & Auditoria de Dados no TCU:** Auditor de Dados Voluntário na Força-Tarefa Cidadã do Tribunal de Contas da União (TCU/OSB), atuando na auditoria de qualidade de dados (*Data Quality*), rastreabilidade (*Data Lineage*) e conformidade com a Lei de Acesso à Informação (LAI).

---

## Dominio Técnico & Infraestrutura

**Data Engineering & Platform:** Domínio de PySpark e Delta Lake em ambiente Databricks para processamento distribuído. Construção e orquestração de pipelines ponta a ponta sob a Arquitetura Medalhão (Bronze, Silver, Gold).

**AI, NLP & Backend:** Desenvolvimento em Python para microsserviços, APIs RESTful com FastAPI, automações complexas e integração avançada de LLMs, agentes inteligentes, Pydantic, RAG e Machine Learning (Scikit-learn, Pandas, NumPy).

**Databases & Storage:** Experiência avançada em ecossistemas SQL (PostgreSQL, SQL Server, MySQL, BigQuery e Databricks SQL), modelagem dimensional e vivência com bancos NoSQL e Cache (MongoDB, Redis, Cassandra).

**Visual Analytics & Observabilidade:** Criação de aplicações analíticas interativas em Streamlit, dashboards no Databricks SQL e Power BI para suporte direto à tomada de decisão executiva.

---

## Tecnologias & Ferramentas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![BigQuery](https://img.shields.io/badge/Google%20BigQuery-669DF6?style=flat&logo=googlecloud&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat&logo=apache-cassandra&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Power%20BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=power-bi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## Projetos em Destaque

### LLM Support Message Enrichment API — FastAPI & OpenRouter

> *API resiliente pronta para produção para classificação e enriquecimento de mensagens via LLM*

API em FastAPI que processa mensagens não estruturadas de suporte SaaS e extrai metadados estruturados validados via Pydantic usando modelos do OpenRouter. Projetada com foco em alta confiabilidade, resiliência e controle operacional em sistemas de produção.

**Destaques técnicos:** Validação estrita de schema Pydantic, autorreparo com 1-shot retry prompt, log de quarentena em JSONL, timeout estrito de 30s, kill switch instantâneo via variável de ambiente, logs estruturados de tokens/custos e suite de testes automatizada atingindo 87.5% de precisão.

`FastAPI` `Python` `OpenRouter` `Pydantic` `LLM` `Prompt Engineering` `Schema Validation` `Backend`

**Link:** https://github.com/joaohppenha/llm-enrichment-api

---

### Pipeline Medalhão — Acidentes de Trânsito PRF 2025

> *Engenharia de Dados ponta a ponta com arquitetura Medalhão em Databricks*

Pipeline completo de dados públicos da PRF com **arquitetura Medalhão (Bronze → Silver → Gold)** em PySpark e Delta Lake no Databricks. Processa 72.524 registros com transformações distribuídas, particionamento, transações ACID e entrega analítica via dashboard Databricks SQL — do CSV bruto ao insight em ~2 minutos.

**Destaques técnicos:** arquitetura Medalhão, Delta Lake com versionamento ACID, orquestração via `dbutils.notebook.run()` (padrão Airflow-ready), 4 tabelas Gold com métricas derivadas e dashboard publicado.

`PySpark` `Delta Lake` `Databricks` `Arquitetura Medalhão` `ETL` `Python` `SQL` `Big Data` `Data Engineering`

**Link:** https://github.com/joaohppenha/projeto-acidentes-prf

---

### DJE-TJSP Scraper & Search Engine — Legal Analytics & Full-Text Search

> *Pipeline de dados jurídicos com OpenSearch e Streamlit para busca em Diários Oficiais*

Solução de Legal Analytics para automação de extração do Diário da Justiça Eletrônico do TJSP. Realiza raspagem, parsing de PDF/HTML e indexação em cluster OpenSearch com busca textual completa (Full-Text Search), entregando interface analítica em Streamlit para consultas jurídicas avançadas.

**Destaques técnicos:** OpenSearch, Streamlit, Web Scraping, PDF Parsing, Full-Text Search, Python, Legal Analytics.

`Python` `OpenSearch` `Streamlit` `Web Scraping` `Full-Text Search` `Legal Analytics` `ETL`

**Link:** https://github.com/joaohppenha/do-tjsp-scraper

---

### FlyRank Auth API — Supabase & FastAPI

> *RESTful API segura com autenticação JWT e injeção de dependências*

API backend robusta desenvolvida em FastAPI integrada ao Supabase Auth como Identity Provider. Implementa o ciclo completo de autenticação (signup, login, logout), rotas protegidas via injeção de dependências (`HTTPBearer`) e documentação interativa OpenAPI/Swagger UI.

**Destaques técnicos:** FastAPI, Supabase Auth, JWT Bearer Token, Pydantic, Swagger UI, python-dotenv.

`FastAPI` `Supabase` `JWT` `Python` `Pydantic` `REST API` `Backend` `Authentication`

**Link:** https://github.com/joaohppenha/flyrank-auth-a4

---

### Projeto: Shadow Tax Ledger — Engenharia de Dados e Compliance

Pipeline de dados orientado a eventos para espelhamento tributário em tempo real, simulando o impacto da Reforma Tributária Brasileira (IBS/CBS) via Shadow Accounting.

**Destaques técnicos:** Apache Airflow, Amazon SQS, S3, AWS Glue Catalog, Parquet, Amazon Athena, Streamlit. Dashboard executivo para CFO com KPIs de delta tributário e riscos de precificação.

`Airflow` `AWS` `SQS` `S3` `Athena` `Streamlit` `Parquet` `Python` `Compliance` `Data Engineering`

**Link:** https://github.com/joaohppenha/shadow-tax-ledger

---

### Task Management API — FastAPI & Async Engine

API RESTful concorrente para gerenciamento de tarefas em FastAPI com validação estrita via Pydantic, respostas parametrizadas e documentação OpenAPI.

`FastAPI` `Python` `Pydantic` `Uvicorn` `REST API` `Backend`

**Link:** https://github.com/joaohppenha/task-api-fastapi

---

### Task Management API — SQLite & Python Pure Backend

API backend para gestão de tarefas utilizando Python e persistência relacional com SQLite, aplicando padrões de modelagem de dados e arquitetura de software limpa.

`Python` `SQLite` `SQL` `REST API` `Database` `Backend`

**Link:** https://github.com/joaohppenha/task-api-sqlite

---

### Projeto "Jurimetria Preditiva e Provisão Financeira"

Sistema de predição de desfechos judiciais e provisionamento financeiro com Random Forest. Integra ETL de múltiplas fontes, análise estatística e dashboards Power BI. Gerou aumento de até 50% na eficiência da gestão de processos.

`Random Forest` `Python` `Power BI` `ETL` `Web Scraping` `SQL` `NoSQL` `Machine Learning`

**Link:** https://github.com/joaohppenha/jurimetria_preditiva

---

### Projeto "Financeira" — NoSQL

Sistema completo de empréstimo consignado utilizando MongoDB, Redis e Cassandra. Inclui modelagem, CRUD, consultas avançadas, cache, otimizações de performance e execução via Docker.

`MongoDB` `Redis` `Cassandra` `Docker` `Jupyter` `NoSQL` `Python`

**Link:** https://github.com/joaohppenha/projeto-banco-de-emprestimo-consignado

---

### Projeto "Acessibilidade nos Cinemas Brasileiros" — Power BI

Análise descritiva do cenário de acessibilidade física dos cinemas brasileiros com dados da ANCINE. Uso de Power Query, DAX, gráficos, mapas e storytelling com dados.

`Power BI` `Power Query` `DAX` `Data Visualization` `Open Data`

**Link:** https://github.com/joaohppenha/projeto_acessibilidade_nos_cinemas

---

### Projeto Jurisconsulto — SQL e Python

Modelagem e implementação de banco de dados relacional para escritório de advocacia em MySQL. Aplicativo CLI em Python para gestão jurídica e geração automática de preâmbulos de petições.

`MySQL` `Python` `SQL` `mysql-connector-python` `CLI`

**Link:** https://github.com/joaohppenha/projeto-jurisconsulto

---

### Projeto STF

Pipeline ETL em Python sobre dados públicos do Supremo Tribunal Federal: extração de planilhas Excel, limpeza, transformação e visualização de dados.

`Python` `Pandas` `ETL` `Excel` `Data Visualization` `Git`

**Link:** https://github.com/joaohppenha/projeto-STF

---

## Coleção Fundamentos

- **Fundamentos SQL** — DDL, DML, DQL, DTL, DCL com BigQuery → [github.com/joaohppenha/fundamentos-sql](https://github.com/joaohppenha/fundamentos-sql)
- **Fundamentos Python** — 5 projetos cobrindo variáveis, estruturas de controle, listas, funções, arquivos e exceções → [github.com/joaohppenha/fundamentos-python](https://github.com/joaohppenha/fundamentos-python)

---

## 📌 Áreas de Atuação & Interesse

- ⚙️ Backend Engineering · Microservices · API Design · FastAPI
- 🤖 Generative AI · RAG · Structured Outputs · Prompt Engineering
- ⚙️ Data Engineering · Distributed Pipelines · Medallion Architecture
- ⚖️ Jurimetria · Legal Analytics · Data Governance & Audit (TCU)
- 🗄️ SQL & NoSQL Databases · Vector Stores · Data Modeling
- ☁️ Cloud Data Platforms · Databricks · BigQuery · AWS

</details>

---

<details>
<summary><b>🇺🇸 English</b></summary>

## About

I transform complex data infrastructures into intelligent systems by bridging **Backend Engineering**, **Generative AI**, and **Data Governance**. With over 10 years of experience at the intersection of technology and the legal domain, I specialize in Jurimetrics and operate across the entire data lifecycle: from building scalable distributed pipelines to designing AI architectures aligned with business rules and compliance.

Currently pursuing a degree in Systems Analysis and Development (ADS), my technical work spans three high-impact fronts:

- **Backend & AI Engineering at FlyRank:** Developing microservice infrastructure, stable API contracts, and AI workflows based on Retrieval-Augmented Generation (RAG) and structured outputs.
- **Advanced Research at Cohere Open Labs:** Accepted member of Cohere's global open-science ecosystem, focusing on the frontiers of Large Language Models (LLMs), Natural Language Processing (NLP), and quantum computing.
- **Data Governance & Audit at TCU:** Volunteer Data Auditor at the Citizen Task Force of the Brazilian Federal Court of Accounts (TCU/OSB), auditing Data Quality, Data Lineage, and compliance with the Access to Information Law (LAI).

---

## Technical Expertise & Infrastructure

**Data Engineering & Platform:** Proficiency in PySpark and Delta Lake on Databricks for distributed data processing. End-to-end pipeline design under Medallion Architecture (Bronze, Silver, Gold).

**AI, NLP & Backend:** Python development for microservices, RESTful APIs with FastAPI, complex automations, and advanced integration of LLMs, intelligent agents, Pydantic, RAG, and Machine Learning tools (Scikit-learn, Pandas, NumPy).

**Databases & Storage:** Advanced expertise across SQL ecosystems (PostgreSQL, SQL Server, MySQL, BigQuery, and Databricks SQL), dimensional modeling, and NoSQL/Caching stores (MongoDB, Redis, Cassandra).

**Visual Analytics & Observability:** Interactive analytical web applications using Streamlit, Databricks SQL dashboards, and Power BI for direct C-level decision support.

---

## Technologies & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![BigQuery](https://img.shields.io/badge/Google%20BigQuery-669DF6?style=flat&logo=googlecloud&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat&logo=apache-cassandra&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Power%20BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=power-bi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## Featured Projects

### LLM Support Message Enrichment API — FastAPI & OpenRouter

> *Resilient, production-ready API for unstructured message classification and metadata extraction via LLM*

FastAPI endpoint that processes unstructured SaaS support messages and extracts structured metadata validated with Pydantic using OpenRouter LLMs. Built with a strong focus on high reliability, production resiliency, and operational control.

**Technical highlights:** Strict Pydantic schema validation, 1-shot repair retry prompt, JSONL quarantine logging, hard 30s timeout, environment-based kill switch, structured token/cost metrics, and an automated evaluation suite achieving 87.5% accuracy.

`FastAPI` `Python` `OpenRouter` `Pydantic` `LLM` `Prompt Engineering` `Schema Validation` `Backend`

**Link:** https://github.com/joaohppenha/llm-enrichment-api

---

### Medallion Pipeline — PRF Traffic Accidents 2025

> *End-to-end Data Engineering with Medallion Architecture on Databricks*

Complete pipeline for public PRF data using **Medallion Architecture (Bronze → Silver → Gold)** with PySpark and Delta Lake on Databricks. Processes 72,524 records with distributed transformations, partitioning, ACID transactions, and analytical delivery via Databricks SQL dashboard — from raw CSV to insight in ~2 minutes.

**Technical highlights:** Medallion architecture, Delta Lake with ACID versioning, orchestration via `dbutils.notebook.run()` (Airflow-ready pattern), 4 Gold tables with derived metrics, and published dashboard.

`PySpark` `Delta Lake` `Databricks` `Medallion Architecture` `ETL` `Python` `SQL` `Big Data` `Data Engineering`

**Link:** https://github.com/joaohppenha/projeto-acidentes-prf

---

### DJE-TJSP Scraper & Search Engine — Legal Analytics & Full-Text Search

> *Legal data pipeline with OpenSearch and Streamlit for Official Gazette search*

Legal Analytics solution for automated extraction from TJSP Electronic Gazette. Features web scraping, PDF/HTML parsing, and indexing into an OpenSearch cluster with Full-Text Search, served through an interactive Streamlit UI for advanced legal research.

**Technical highlights:** OpenSearch, Streamlit, Web Scraping, PDF Parsing, Full-Text Search, Python, Legal Analytics.

`Python` `OpenSearch` `Streamlit` `Web Scraping` `Full-Text Search` `Legal Analytics` `ETL`

**Link:** https://github.com/joaohppenha/do-tjsp-scraper

---

### FlyRank Auth API — Supabase & FastAPI

> *Secure RESTful API with JWT Authentication and Dependency Injection*

Robust backend API built with FastAPI integrated with Supabase Auth as Identity Provider. Implements full user authentication lifecycles (signup, login, logout), protected endpoints via dependency injection (`HTTPBearer`), and interactive OpenAPI/Swagger UI documentation.

**Technical highlights:** FastAPI, Supabase Auth, JWT Bearer Token, Pydantic, Swagger UI, python-dotenv.

`FastAPI` `Supabase` `JWT` `Python` `Pydantic` `REST API` `Backend` `Authentication`

**Link:** https://github.com/joaohppenha/flyrank-auth-a4

---

### Shadow Tax Ledger — Data Engineering & Compliance

Event-driven data pipeline for real-time tax mirroring, simulating the impact of Brazil's Tax Reform (IBS/CBS) via Shadow Accounting.

**Technical highlights:** Apache Airflow, Amazon SQS, S3, AWS Glue Catalog, Parquet, Amazon Athena, Streamlit. Executive dashboard for CFO with tax delta KPIs and pricing risk exposure.

`Airflow` `AWS` `SQS` `S3` `Athena` `Streamlit` `Parquet` `Python` `Compliance` `Data Engineering`

**Link:** https://github.com/joaohppenha/shadow-tax-ledger

---

### Task Management API — FastAPI & Async Engine

Concurrent RESTful API for task management built with FastAPI featuring strict Pydantic validation, parameterized responses, and OpenAPI documentation.

`FastAPI` `Python` `Pydantic` `Uvicorn` `REST API` `Backend`

**Link:** https://github.com/joaohppenha/task-api-fastapi

---

### Task Management API — SQLite & Python Pure Backend

Backend API for task management utilizing Python and relational persistence with SQLite, applying data modeling best practices and clean software architecture.

`Python` `SQLite` `SQL` `REST API` `Database` `Backend`

**Link:** https://github.com/joaohppenha/task-api-sqlite

---

### Predictive Jurimetrics & Financial Provisioning

Judicial outcome prediction system and dynamic financial provisioning using Random Forest. Integrates ETL from multiple sources, statistical analysis, and Power BI dashboards. Delivered up to 50% improvement in case management efficiency.

`Random Forest` `Python` `Power BI` `ETL` `Web Scraping` `SQL` `NoSQL` `Machine Learning`

**Link:** https://github.com/joaohppenha/jurimetria_preditiva

---

### Financeira — NoSQL Project

Complete payroll loan system using MongoDB, Redis, and Cassandra. Includes data modeling, CRUD, advanced queries, caching, performance optimizations, and a reproducible Docker environment.

`MongoDB` `Redis` `Cassandra` `Docker` `Jupyter` `NoSQL` `Python`

**Link:** https://github.com/joaohppenha/projeto-banco-de-emprestimo-consignado

---

### Accessibility in Brazilian Cinemas — Power BI

Descriptive analysis of the physical accessibility landscape of Brazilian cinemas using ANCINE open data. Includes Power Query, DAX formulas, charts, maps, and data storytelling.

`Power BI` `Power Query` `DAX` `Data Visualization` `Open Data`

**Link:** https://github.com/joaohppenha/projeto_acessibilidade_nos_cinemas

---

### Jurisconsulto — SQL & Python

Relational database modeling and implementation for a law firm in MySQL. Python CLI application for legal case management and automatic generation of legal petition headers.

`MySQL` `Python` `SQL` `mysql-connector-python` `CLI`

**Link:** https://github.com/joaohppenha/projeto-jurisconsulto

---

### STF Project

Python ETL pipeline on public data from Brazil's Supreme Court: extraction from Excel spreadsheets, cleaning, transformation, and data visualization.

`Python` `Pandas` `ETL` `Excel` `Data Visualization` `Git`

**Link:** https://github.com/joaohppenha/projeto-STF

---

## Fundamentals Collection

- **SQL Fundamentals** — DDL, DML, DQL, DTL, DCL with BigQuery → [github.com/joaohppenha/fundamentos-sql](https://github.com/joaohppenha/fundamentos-sql)
- **Python Fundamentals** — 5 projects covering variables, control flow, lists, functions, files, and exceptions → [github.com/joaohppenha/fundamentos-python](https://github.com/joaohppenha/fundamentos-python)

---

## 📌 Areas of Expertise & Interest

- ⚙️ Backend Engineering · Microservices · API Design · FastAPI
- 🤖 Generative AI · RAG · Structured Outputs · Prompt Engineering
- ⚙️ Data Engineering · Distributed Pipelines · Medallion Architecture
- ⚖️ Jurimetrics · Legal Analytics · Data Governance & Audit (TCU)
- 🗄️ SQL & NoSQL Databases · Vector Stores · Data Modeling
- ☁️ Cloud Data Platforms · Databricks · BigQuery · AWS

</details>

---

<!-- ATS Keywords: Backend Engineer, AI Engineer, Data Engineer, Data Analyst, Data Scientist, Python, FastAPI, Pydantic, OpenRouter, OpenAI, PyTorch, Cohere, RAG, Structured Outputs, PySpark, SQL, ETL, ELT, Data Pipeline, Medallion Architecture, Delta Lake, Databricks, Apache Spark, Big Data, Machine Learning, Scikit-learn, Random Forest, Power BI, Streamlit, PostgreSQL, MySQL, MongoDB, Redis, Cassandra, NoSQL, Docker, Git, BigQuery, Data Governance, Data Quality, Data Lineage, TCU, Jurimetria, Jurimetrics, Legal Tech, OpenSearch, Supabase, JWT -->

<p align="center">
  <i>PT: Conectando engenharia pesada, IA e governança para resolver problemas complexos de negócio.</i><br/>
  <i>EN: Connecting heavy engineering, AI, and governance to solve complex business problems.</i>
</p>

---

## Contato · Contact

**LinkedIn:** https://www.linkedin.com/in/jhppenha/
