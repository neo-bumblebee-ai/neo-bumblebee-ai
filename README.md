# Jignesh Patel — AI Engineer & Architect

17 years building production data systems. Now applying that foundation to enterprise AI — RAG pipelines, agentic workflows, and LLM evaluation frameworks.

I care about what happens after the demo: retrieval that handles real queries, outputs that are auditable, and quality gates that catch regressions before they reach production.

---

## 6-month AI engineering series

One production-ready project per month, built and shipped in public.

| Month | Project | Focus | Status |
|-------|---------|-------|--------|
| Jan | [Databricks AI Engineering Challenge](https://github.com/neo-bumblebee-ai/databricks-ai-engineering-challenge) | ML pipelines on Databricks | ✅ Complete |
| Feb | [Traditional RAG Pipeline](https://github.com/neo-bumblebee-ai/traditional-rag-pipeline) | End-to-end retrieval-augmented generation | ✅ Complete |
| Mar | [Agentic RAG with LangGraph](https://github.com/neo-bumblebee-ai/agentic-rag-langgraph) | Multi-step agentic reasoning | ✅ Complete |
| Apr | [Finance RAG — Ask My 10-Ks](https://github.com/neo-bumblebee-ai/finance-rag) | Hybrid retrieval · cited answers · decision support | ✅ Complete |
| May | LLMOps Evaluation Platform | Systematic LLM quality measurement | 🔜 Coming |
| Jun | Enterprise AI Platform *(capstone)* | Full production AI system, end to end | 🔜 Coming |

Each project is evaluated, containerised, observable, and CI-gated.

---

## What I focus on

**Retrieval that works on real data.** Hybrid BM25 + vector search with RRF fusion catches exact financial terms, ticker symbols, and semantic queries that pure vector search misses.

**Answers you can audit.** Citation enforcement maps every LLM claim to a source document, filing date, and page number.

**Confidence you can act on.** Structured output with confidence scoring, per-claim citations, and decision recommendations grounded solely in retrieved context.

**Quality that doesn't drift.** RAGAS evaluation in CI blocks any PR that drops faithfulness, answer relevancy, or context precision below threshold.

**Full production visibility.** Langfuse traces every request — cost, latency, and confidence score — in production.

---

## Stack

**AI / LLM** — LangChain · LangGraph · OpenAI API · HuggingFace · PEFT/LoRA · RAGAS · Langfuse  
**Retrieval** — FAISS · ChromaDB · BM25 · Reciprocal Rank Fusion · Cohere Rerank  
**Backend** — FastAPI · PostgreSQL · Redis · Docker · Kubernetes · GitHub Actions · Azure  
**Data — 17 yrs** — Databricks · PySpark · dbt · Azure Synapse · Talend · Informatica

---

[LinkedIn](https://linkedin.com/in/jigneshrpatel) · Building in public
