# Prashansa Agrrawal — Personal Portfolio Website

Personal portfolio website showcasing distributed systems architecture, applied AI/ML engineering, high-volume payment infrastructure, and enterprise projects.

🌐 **Live Website**: [prashansa-agrrawal.netlify.app](https://prashansa-agrrawal.netlify.app/)

---

## 🚀 Featured Projects & Benchmarks

> **Evaluation Standard**: Project achievements and benchmarks follow Google's **"Accomplished [X], as measured by [Y], by doing [Z]"** impact formula.

- **[RouteFlow AI](https://github.com/Prashansa0410/cross-border-payment-routing-ml)** (Nov 2026 · Featured)
  - **Accomplished risk-calibrated payment success prediction**, as measured by achieving an **Expected Calibration Error (ECE) of 0.66%**, 0.6980 ROC-AUC, and 0.0761 Brier score, by architecting a Platt-calibrated `HistGradientBoostingClassifier` on 50,000 multi-corridor transaction records.
  - **Accomplished sub-hour settlement latency forecasting**, as measured by reducing Mean Absolute Error (MAE) by **38.5%** (from 113.4m to 69.7m) with an **R² of 0.942**, by fitting a log-transformed `HistGradientBoostingRegressor` with cyclical temporal feature engineering.
  - **Accomplished automated multi-corridor capital optimization**, as measured by enforcing strict SLA reliability floors (≥85% success) and Pareto utility scoring at **<15ms p95 API response times**, by engineering a constrained multi-objective decision engine atop a thread-safe Singleton FastAPI architecture.
  - **Accomplished continuous production reliability**, as measured by **100% CI/CD pass rate across 26 automated pytest tests** and **0.0000 Population Stability Index (PSI)**, by implementing directional ML property tests, invariance suites, and Pydantic v2 data contracts.
  - *Tech*: Python, Scikit-learn, HistGradientBoosting, FastAPI, Pydantic v2, Docker, Multi-Objective Optimization.
  - *Links*: [Live Demo ↗](https://routeflow-ai.onrender.com/) · [GitHub Repo ↗](https://github.com/Prashansa0410/cross-border-payment-routing-ml)

- **[FinDoc-RAG](https://github.com/Prashansa0410/financial-rag-system)** (Nov 2026 · Featured)
  - **Accomplished high-precision corporate disclosure retrieval**, as measured by achieving **40.0% Hit@1** and **50.0% Hit@3** in **10.10ms**, by architecting a hybrid retrieval pipeline combining `BAAI/bge-small-en-v1.5` dense vector search (FAISS IndexFlatIP) and `BM25Okapi` sparse lexical search via Reciprocal Rank Fusion (RRF, k=60).
  - **Accomplished fine-grained candidate passage re-ranking**, as measured by driving a **60.0% Rank Change Rate** on retrieved candidate pools, by integrating a Cross-Encoder (`ms-marco-MiniLM-L-6-v2`) performing joint query-passage cross-attention over financial disclosures.
  - **Accomplished zero cross-company entity contamination**, as measured by **100% false-positive elimination** and moving ground-truth target disclosures directly to Rank #1, by formulating an entity-aware metadata pre-filtering mechanism.
  - **Accomplished hallucination-free financial synthesis**, as measured by achieving **90.0% grounded faithfulness** in dual-criterion LLM audits, by engineering an automated LLM-as-a-Judge audit (`meta-llama/Llama-3.1-8B-Instruct`) on Qwen2.5-7B outputs with strict negative abstention guardrails.
  - *Tech*: PyTorch, FAISS, BM25, Cross-Encoder, Qwen2.5-7B, Llama-3.1-8B Judge, FastAPI, Docker, NVIDIA A100.
  - *Links*: [GitHub Repo ↗](https://github.com/Prashansa0410/financial-rag-system)

- **[CrossPay-AI](https://github.com/Prashansa0410/CrossPay-AI)** (Nov 2026 · Featured)
  - **Accomplished automated real-time wire exception classification**, as measured by attaining **88.89% validation accuracy** at **sub-15ms inference latency** across 10 error classes, by fine-tuning a `DistilBERT` transformer model on historical MT103 and pacs.008 correspondent payment failure logs.
  - **Accomplished automated regulatory-compliant payment repair**, as measured by generating **100% schema-compliant ISO 20022 pacs.028.001.01 XML** repair records with zero hallucinated elements, by coupling `FLAN-T5-Base` with dynamic schema structural guardrails.
  - **Accomplished multi-jurisdiction clearing compliance retrieval**, as measured by delivering sub-second regulatory clause mapping, by developing a domain-specialized RAG knowledge engine using `all-MiniLM-L6-v2` vector embeddings across RBI, SEPA, Pay.UK, and NACHA mandates.
  - *Tech*: DistilBERT (88.89% accuracy, 14.2ms latency), FLAN-T5-Base, sentence-transformers RAG, PyTorch, Streamlit.
  - *Links*: [Live Demo ↗](https://crosspay-ai-copilot.streamlit.app/) · [GitHub Repo ↗](https://github.com/Prashansa0410/CrossPay-AI)

- **[QueryPilot AI](https://github.com/Prashansa0410/querypilot-ai)** (Aug 2026 · Featured)
  - **Accomplished enterprise LLM operational cost reduction**, as measured by reducing API spend by an estimated **65%** while intercepting **100% of destructive statements**, by architecting a semantic complexity router dispatching routine queries to economical models and complex joins to reasoning models.
  - **Accomplished deterministic database security guardrails**, as measured by zero unvetted schema modifications or bulk data deletions across query executions, by engineering an AST-based SQL security risk engine intercepting DROP, TRUNCATE, and DELETE operations for human authorization.
  - *Tech*: Next.js 15, FastAPI, SQLite, MCP, LLM Routing.
  - *Links*: [Live Demo ↗](https://querypilot-ai-liart.vercel.app/) · [GitHub Repo ↗](https://github.com/Prashansa0410/querypilot-ai)

- **[OpsPulse AI](https://github.com/Prashansa0410/opspulse-ai)** (Aug 2026)
  - **Accomplished proactive SLA breach prevention across fulfillment pipelines**, as measured by surfacing risk flags across **11 real-time operational views**, by implementing supervised ML SLA-risk prediction and explainable root-cause attribution models.
  - **Accomplished safe self-service operational analytics for non-technical users**, as measured by **100% read-only data compliance** with zero unauthorized mutations, by building an AI Operations Analyst enforcing single-statement validation and row limits.
  - *Tech*: Python, FastAPI, Next.js, Kafka, dbt, DuckDB, Docker.
  - *Links*: [Live Demo ↗](https://opspulse-ai-alpha.vercel.app/) · [GitHub Repo ↗](https://github.com/Prashansa0410/opspulse-ai)

- **[Async Order Processing Platform](https://github.com/Prashansa0410/async-order-processing-platform)**
  - **Accomplished non-blocking order lifecycle execution**, as measured by eliminating thread-starvation bottlenecks under simulated traffic spikes, by implementing an asynchronous pipeline utilizing Java `CompletableFuture` (supplyAsync, thenApply, thenAccept).
  - *Tech*: Java, CompletableFuture, Concurrency, SOLID.

- **[FluxBasis AI](https://github.com/Prashansa0410/FluxBasis-AI)**
  - **Accomplished early detection of non-deterministic CI test failures**, as measured by isolating intermittent failures before deployment, by engineering a modular pipeline ingesting execution telemetry across Selenium, Playwright, Pytest, and TestNG.
  - *Tech*: Python, Scikit-learn, CI/CD, Test Telemetry.

- **[Data Pipeline Orchestration with Airflow](https://github.com/Prashansa0410/DAGUsingAirflow)**
  - **Accomplished automated, resilient ETL task execution**, as measured by achieving zero-downtime scheduled batch runs and reproducible containerized execution, by building DAGs using Apache Airflow's TaskFlow API with dynamic task mapping.
  - *Tech*: Apache Airflow, Python, Docker, ETL.
