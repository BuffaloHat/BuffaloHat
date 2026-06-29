# Matthew Kennedy

### Data & Analytics Leader · 20+ years turning enterprise data into decisions

I spent two decades building and leading the analytics function for a multi-billion-dollar business, then went back to first principles to build modern data and AI systems end to end. I design the whole stack — ingestion and warehousing through retrieval-augmented and agentic LLM applications — with a bias toward evaluation, observability, and systems that hold up in production.

Manhattan Beach, CA · Open to senior / lead roles in analytics, RevOps, and AI engineering · kennedymatt@hotmail.com

---

## About Me

For 13+ years I led Data Analytics at **Skechers**, growing the function from 2 analysts to a team of 10 and reporting directly to the SVP of Sales for 11 years as a trusted, on-call analytics resource for the CFO and President. I built the flagship BI dashboard that became the corporate Sales standard and designed **"Position,"** a custom forecasting KPI that became the primary sales metric for a ~$2B business.

Since 2022 I've been building from first principles across data engineering and AI — shipping ELT pipelines, RAG systems, and agent architectures, and authoring a 400+ page field manual on production AI from foundations through deployment.

- **Currently building:** retrieval systems, LLM evaluation harnesses, and agentic workflows — local-first on Apple Silicon
- **Strengths:** sales / RevOps analytics, executive reporting, semantic-layer & KPI design, RAG and evals
- **How I work:** reproducible pipelines, evals before scale, clear translation from business question to working system

---

## Skills & Tools

**Data Engineering & Analytics**
Python · SQL · dbt · Jupyter · Prefect · DuckDB · PostgreSQL · Snowflake · Databricks · AWS · SAS · Git

**BI & Visualization**
MicroStrategy · Tableau · Metabase · BusinessObjects · Power BI · Alteryx

**AI / LLM Systems**
RAG · Hybrid RAG · GraphRAG · Agents · Multi-Agent Workflows · Prompt & Context Engineering · Rubric-Scored Evals

**Retrieval, Vectors & Models**
Qdrant · Pinecone · Chroma · Neo4j · BM25 · Cross-Encoder Reranking · Ollama · Nomic / Essentia embeddings

**Frameworks & Tooling**
LangChain · LangGraph · LangSmith · Streamlit · Claude Code · Docker · Pandoc

---

## Featured Projects

The full **Soapy** suite — an end-to-end exploration from data engineering through applied LLM systems.

### [Soapy Records](https://github.com/BuffaloHat/soapy-records-public)
Vinyl-collection visualization platform. End-to-end ELT: Python ingestion from the Discogs API → Parquet landing zone → dbt-core transformations on DuckDB (staging → intermediate → fact/dim marts), productionized with Prefect orchestration, PostgreSQL materialization, and containerized Metabase dashboards.
`Python` `dbt` `DuckDB` `Prefect` `PostgreSQL` `Metabase`

### [Soapy GrooveGraph](https://github.com/BuffaloHat/soapy-groovegraph-public)
AI music-discovery tool over a ~10,000-track personal library. Dual-retrieval architecture pairing Essentia audio-feature vectors in Qdrant for acoustic similarity with natural-language RAG, served on Ollama (Gemma 27b) + Nomic embeddings, with a Streamlit interface for query, similarity search, and feature inspection.
`Qdrant` `Essentia` `Ollama` `RAG` `Streamlit`

### [Soapy RAGlab](https://github.com/BuffaloHat/soapy-raglab-public)
RAG research lab benchmarking four retrieval patterns — naïve vector, hybrid + reranking, GraphRAG, and an agent-maintained LLM wiki — against a curated 480+ article corpus with a rubric-scored evaluation harness. Pure Python with Qdrant, Neo4j, BM25, and cross-encoder reranking, governed by a Claude Code harness layer.
`GraphRAG` `Neo4j` `BM25` `Evals` `Claude Code`

### [Soapy AI Field Manual](https://github.com/BuffaloHat/soapy-ai-field-manual-search)
A 400+ page applied AI/LLM engineering reference for building production systems end to end — six parts spanning transformer mechanics, baseline & deployment decisions, RAG architecture, prompt & context engineering, harness design, agent memory & architectures, and evaluation / security / deployment ops.
`LLM Engineering` `RAG` `Agents` `Evals` `Production`
