# Hi, I'm Triasha Sarkar

### Machine Learning Engineer

I build reliable machine-learning systems for engineering and scientific problems, from model development and evaluation through deployment, observability, and failure analysis.

My work currently spans **agentic RAG**, **LLM adaptation and evaluation**, **multimodal VLM evaluation**, **time-series diagnostics**, **recommendation systems**, **scientific ML**, and **production-oriented ML systems**.

My aerospace background strongly influences how I approach AI: model capability matters, but so do provenance, evaluation integrity, safe failure behavior, reproducibility, and knowing when a system should not make a claim.

[Portfolio](https://triasha72.github.io/Portfolio/) ·
[LinkedIn](https://www.linkedin.com/in/triasha-sarkar/) ·
[Email](mailto:tsarkar34@gatech.edu)

---

## Selected Projects

### [AeroRAG-X](https://github.com/triasha72/AeroRAG-X)
**Agentic RAG · LLM Evaluation · ML Systems**

Evaluation-first knowledge system over **3,233 citation-preserving NASA NTRS chunks**.

- Built hybrid BM25 + dense retrieval, Reciprocal Rank Fusion, cross-encoder reranking, pgvector, evidence-sufficiency gating, and application-controlled citations.
- Adapted Qwen3-0.6B with PEFT/LoRA and developed protected evaluation for answerability, grounded refusal, citation validity, evidence support, and semantic claim coverage.
- Built a stateful LangGraph agent with schema-constrained planning, registered tool routing, bounded execution, checkpointing, human-in-the-loop review, fault injection, and safe failure handling.
- Decomposed the system into Agent, Retrieval, and Inference FastAPI services with Docker Compose, PostgreSQL/pgvector, OpenTelemetry, Prometheus, retries, health/readiness checks, and safe degradation.
- Developed TRL/GRPO grounded-agent experiment infrastructure with multi-objective rewards, anti-reward-hacking gates, leakage controls, and paired Base/LoRA/GRPO evaluation contracts.

---

### [AeroSynth-Eval](https://github.com/triasha72/AeroSynth-Eval)
**Multimodal AI · VLM Evaluation · Reliability Engineering**

Human-aligned evaluation tooling for synthetic aerospace inspection imagery.

- Designed a frozen **48-scenario** benchmark with a protected **36/12 development-test split**.
- Materialized **48 deterministic synthetic assets** with generation metadata and SHA-256 provenance.
- Built typed evaluation, annotation, prompt and response contracts with strict protected-test and metadata validation.
- Integrated an optional local MLX-VLM development runner with exact asset/scenario/rubric binding.
- Automated validation with Ruff, strict mypy, pytest and GitHub Actions.

---

### [NewsLens](https://github.com/triasha72/NewsLens)
**Recommender Systems · Production ML**

Leakage-aware recommendation and serving over Microsoft MIND-small.

- Chronological train/validation evaluation with DuckDB and TF-IDF personalization.
- Training-only popularity fallback recovered all content-model abstentions.
- Final held-out results: **NDCG@10 0.3664**, **Recall@10 0.5955**, **Hit Rate@10 0.6762**.
- FastAPI, non-root Docker/Compose, readiness/tracing/latency telemetry, multi-platform GHCR publishing, and **400+ tests**.

---

### [EdgeGenBench](https://github.com/triasha72/EdgeGenBench)
**Scientific ML · Uncertainty · Efficient Inference**

Reproducible aircraft-design benchmark linking surrogate models to uncertainty-aware engineering decisions.

- Compared Ridge, Random Forest, and HistGradientBoosting surrogates on a **6,000-sample** deterministic benchmark.
- Best model reached **0.9952 mean held-out R²**.
- Added tree-quantile and split-conformal uncertainty plus a feasibility classifier with **99.89% ROC AUC** and **2.12% false-safe rate**.
- Evaluated 20,000 optimization candidates, extracted 47 Pareto designs, and validated selected designs against the physics model.
- Exported models to ONNX with equivalence tests; batch-1 surrogate latency improved from **13.795 ms to 0.305 ms**.

---

## Experience

### Georgia Tech Aerospace Systems Design Laboratory
**Graduate Research Assistant · May 2025 - Aug 2026**

- Built a leakage-resistant failure-detection workflow over **15,120 time-series thrust simulations**, achieving **96.8% accuracy / 0.986 ROC AUC** on unseen geometries.
- Contributed to the **Delta Air Lines-sponsored HERO** project on source-aware retrieval for analyst-led safety and risk assessment.
- Built a GREET lifecycle surrogate and integrated it with economic and transportation models for the **U.S. Endowment-sponsored GREEN TEA** project.

### Alten India, embedded at Rolls-Royce
**Machine Learning Engineer · Oct 2023 - Apr 2025**

- Developed Python diagnostics, anomaly-detection and predictive-maintenance workflows for multivariate aircraft-engine sensor data.
- Built Azure Databricks data pipelines and engineered 1 Hz / 10 Hz time-series features.
- Worked with lifecycle engineers to validate failure modes and convert model signals into proactive maintenance insights.

---

## Technical Stack

**Languages & data:** Python, SQL/MySQL, C++, MATLAB, pandas, NumPy, SciPy, DuckDB, PostgreSQL/pgvector, Azure Blob Storage, Azure Databricks

**GenAI & ML:** Hugging Face Transformers, PEFT/LoRA, TRL/GRPO, LangGraph, LangChain, RAG, BM25, dense retrieval, RRF, cross-encoder reranking, Sentence Transformers, PyTorch, TensorFlow, scikit-learn, MLX-LM/MLX-VLM

**ML systems:** FastAPI, REST APIs, Docker/Compose, Google Cloud Run, GitHub Actions, Prometheus, OpenTelemetry, CI/CD, distributed tracing, health/readiness contracts, fault injection

**Scientific ML & evaluation:** surrogate modeling, uncertainty quantification, conformal prediction, constrained optimization, physics validation, held-out evaluation, bootstrap analysis, failure analysis

---

## Current Focus

Reliable AI systems that combine **grounding, agentic tool use, model evaluation, failure recovery, multimodal evaluation, post-training experimentation, and reproducible deployment**.
