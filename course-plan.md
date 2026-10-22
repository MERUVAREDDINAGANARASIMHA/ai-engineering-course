# AI Engineering Course — Course Plan

Self-paced course following Scaler's *Advanced Program in AI & Agentic Systems*, Year 1 (15 modules).
Week numbers follow Scaler's schedule; go at your own pace. Every module is done in full, nothing skipped.
Cloud modules use **Azure** instead of AWS.

**Format of every lesson:** concept → exercise → review → next lesson.
**Rule:** don't move on until the exercise is reviewed.

---

## Module 1 — AI-Native Foundations (Weeks 1–4)
- [ ] 1.1 How LLMs work: tokens, training, context window, hallucination
- [ ] 1.2 Prompting fundamentals: instructions, roles, examples, structure
- [ ] 1.3 Long context, documents, and verification habits (when to trust)
- [ ] 1.4 Using AI tools well: chat, projects, file analysis, web search
- [ ] 1.5 Build a no-code assistant with instructions + knowledge
- [ ] 1.6 Simple no-code agents and automations, and their limits
- **Build:** a no-code assistant for a real work task

## Module 2 — Python & Coding Agents (Weeks 5–11)
- [ ] 2.1 Environment: uv/venv, VS Code, project layout
- [ ] 2.2 Core Python: types, data structures, functions, comprehensions
- [ ] 2.3 Files, JSON, exceptions, logging
- [ ] 2.4 Classes, dataclasses, type hints
- [ ] 2.5 Modules, packages, dependencies
- [ ] 2.6 Testing with pytest
- [ ] 2.7 Git and GitHub workflow
- [ ] 2.8 Working with coding agents: read, test and fix AI-written code
- [ ] 2.9 HTTP and APIs from Python (httpx)
- [ ] 2.10 Async basics
- **Build:** a tested CLI tool, published on GitHub

## Module 3 — LLM Apps & Evals (Weeks 12–14)
- [ ] 3.1 Calling an LLM API: messages, system prompts, parameters
- [ ] 3.2 Structured output: JSON schemas, Pydantic validation
- [ ] 3.3 Tool use / function calling basics
- [ ] 3.4 Evals: test sets, graders, LLM-as-judge, metrics
- [ ] 3.5 Iterating prompts with evals; cost and latency
- **Build:** an extraction app with an eval suite

## Module 4 — Frontend for AI Products (Weeks 15–16)
- [ ] 4.1 HTML, CSS, JavaScript essentials
- [ ] 4.2 React basics
- [ ] 4.3 Streaming chat interface
- [ ] 4.4 Login and live updates
- **Build:** a chat UI for the Module 3 app

## Module 5 — Backend Engineering & APIs (Weeks 17–20)
- [ ] 5.1 FastAPI: routes and Pydantic models
- [ ] 5.2 Typed APIs, validation, error handling
- [ ] 5.3 Background jobs and queues
- [ ] 5.4 Authentication basics (JWT, OAuth)
- [ ] 5.5 Testing APIs
- [ ] 5.6 Docker and docker-compose
- **Build:** the backend for the chat app

## Module 6 — SQL & Databases (Weeks 21–24)
- [ ] 6.1 Relational modelling and normalisation
- [ ] 6.2 Advanced SQL: CTEs, window functions
- [ ] 6.3 Postgres: indexes, query plans, transactions
- [ ] 6.4 ORMs and migrations (SQLAlchemy, Alembic)
- [ ] 6.5 Access rules: roles, row-level security
- [ ] 6.6 pgvector introduction
- **Build:** run the app on Postgres with access rules

## Module 7 — Data & Math for AI (Weeks 25–27)
- [ ] 7.1 NumPy and pandas
- [ ] 7.2 Linear algebra: vectors, dot product, cosine similarity, matrices
- [ ] 7.3 Probability and statistics
- [ ] 7.4 Calculus intuition: gradients and optimisation
- [ ] 7.5 Visualisation

## Module 8 — RAG Systems (Weeks 28–30) · Flagship project starts
- [ ] 8.1 Embeddings and vector search
- [ ] 8.2 Chunking and ingestion pipelines
- [ ] 8.3 Retrieval: hybrid search, reranking
- [ ] 8.4 Citations and grounding
- [ ] 8.5 RAG evals: retrieval quality and answer quality
- **Flagship:** RAG assistant over team notebook and semantic model documentation

## Module 9 — Agents, MCP & Multi-Agent (Weeks 31–33)
- [ ] 9.1 The agent loop: tools, planning, stopping
- [ ] 9.2 Human-in-the-loop approvals
- [ ] 9.3 MCP concepts; build an MCP server
- [ ] 9.4 Multi-agent patterns (orchestrator and workers)
- [ ] 9.5 Agent evals and failure modes
- **Build:** MCP server over Lakehouse metadata, plus an agent that uses it

## Module 10 — Cloud & DevOps on Azure (Weeks 34–36)
- [ ] 10.1 Azure basics: resource groups, identity, Key Vault
- [ ] 10.2 Containers on Azure (Container Apps / App Service)
- [ ] 10.3 CI/CD with GitHub Actions
- [ ] 10.4 Managed Postgres, storage, networking basics
- [ ] 10.5 Monitoring
- **Build:** deploy everything built so far

## Module 11 — Big Data & Data Pipelines (Weeks 37–39)
- [ ] 11.1 Spark internals: partitions, shuffles, tuning
- [ ] 11.2 Orchestration and scheduling
- [ ] 11.3 Data quality and incremental loads
- [ ] 11.4 Keeping RAG indexes fresh with pipelines

## Module 12 — ML Essentials (Weeks 40–43)
- [ ] 12.1 ML workflow: framing, splits, baselines
- [ ] 12.2 Regression and classification (scikit-learn)
- [ ] 12.3 Decision trees and gradient boosting
- [ ] 12.4 Feature engineering
- [ ] 12.5 Metrics and cross-validation
- [ ] 12.6 Explaining predictions (SHAP)
- [ ] 12.7 When ML beats an LLM

## Module 13 — Neural Networks, LLM Internals & Fine-Tuning (Weeks 44–46)
- [ ] 13.1 Neural network basics and backpropagation (PyTorch)
- [ ] 13.2 Embeddings and attention
- [ ] 13.3 Transformer architecture
- [ ] 13.4 Fine-tuning with LoRA; fine-tune vs prompt vs RAG

## Module 14 — LLMOps (Weeks 47–49)
- [ ] 14.1 Observability: tracing and logging
- [ ] 14.2 Safe releases: prompt versioning, regression evals
- [ ] 14.3 Cost and latency: caching, model routing
- [ ] 14.4 Guardrails and security (prompt injection)

## Module 15 — AI System Design (Weeks 50–52)
- [ ] 15.1 Design framework: requirements, constraints, trade-offs
- [ ] 15.2 Case studies: support bot, document processing, agent platform
- [ ] 15.3 Mock design review: defend your choices
- [ ] 15.4 Choose Year 2 track: ML Engineering or FDE

---

## Progress log
| Date | Lesson | Status | Notes |
|------|--------|--------|-------|
| 2026-10-22 | 1.1 | In progress | Exercise pending review |
