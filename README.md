# Prashansa Agrrawal — Personal Portfolio Website

Personal portfolio website showcasing distributed systems architecture, applied AI/ML engineering, high-volume payment infrastructure, and enterprise projects.

🌐 **Live Website**: [prashansa-agrrawal.netlify.app](https://prashansa-agrrawal.netlify.app/)

---

## 🚀 Featured Projects

- **[FinDoc-RAG](https://github.com/Prashansa0410/financial-rag-system)** (Nov 2026 · Featured)
  - Enterprise-grade, verifiable Retrieval-Augmented Generation (RAG) system specialized for complex corporate SEC filings (Forms 10-K & 10-Q), evaluated on an NVIDIA A100-80GB GPU at BITS Pilani.
  - Combines dense vector search (`BAAI/bge-small-en-v1.5` + FAISS), sparse keyword search (`BM25Okapi`), Reciprocal Rank Fusion ($k=60$), Cross-Encoder reranking (`ms-marco-MiniLM-L-6-v2`), and entity pre-filtering with automated LLM-as-a-Judge audits (90% grounded faithfulness).
  - *Tech*: PyTorch, FAISS, BM25, Cross-Encoder, Qwen2.5-7B, Llama-3.1-8B Judge, FastAPI, Docker, NVIDIA A100.
  - *Links*: [GitHub Repo ↗](https://github.com/Prashansa0410/financial-rag-system)

- **[CrossPay-AI](https://github.com/Prashansa0410/CrossPay-AI)** (Nov 2026 · Featured)
  - Production-grade Small Language Model (SLM) cognitive copilot for cross-border payment exception triage, automated ISO 20022 `pacs.028` repair XML generation, and multi-corridor regulatory clearing RAG (RBI, Pay.UK, SEPA, NACHA).
  - *Tech*: DistilBERT (88.89% accuracy, 14.2ms latency), FLAN-T5-Base, sentence-transformers RAG, PyTorch, Streamlit.
  - *Links*: [Live Demo ↗](https://crosspay-ai-copilot.streamlit.app/) · [GitHub Repo ↗](https://github.com/Prashansa0410/CrossPay-AI)

- **[QueryPilot AI](https://github.com/Prashansa0410/querypilot-ai)** (Aug 2026 · Featured)
  - Cost-aware multi-model LLM router for database querying with deterministic SQL security interception and human-in-the-loop governance.
  - *Tech*: Next.js 15, FastAPI, SQLite, MCP, LLM Routing.

- **[OpsPulse AI](https://github.com/Prashansa0410/opspulse-ai)** (Aug 2026)
  - AI operational intelligence platform for logistics & commerce with ML SLA-risk prediction, anomaly detection, and explainable root-cause analysis.
  - *Tech*: Python, FastAPI, Next.js, Kafka, dbt, DuckDB, Docker.

- **[Async Order Processing Platform](https://github.com/Prashansa0410/async-order-processing-platform)**
  - High-throughput asynchronous order processing backend demonstrating thread safety, CompletableFuture pipelines, and clean architecture.
  - *Tech*: Java, CompletableFuture, Concurrency, SOLID.

- **[FluxBasis AI](https://github.com/Prashansa0410/FluxBasis-AI)**
  - Open-source ML reliability platform predicting flaky tests and surfacing CI/CD test insights.
  - *Tech*: Python, Scikit-learn, CI/CD, Test Telemetry.

- **[Data Pipeline Orchestration with Airflow](https://github.com/Prashansa0410/DAGUsingAirflow)**
  - Robust workflow orchestration using Apache Airflow TaskFlow API and dynamic task mapping.
  - *Tech*: Apache Airflow, Python, Docker, ETL.
