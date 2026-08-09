# Hi, I'm Triasha Sarkar

**Applied ML / AI Engineer · Scientific Machine Learning · ML Systems**

I build machine learning systems for real engineering and scientific problems — from data and model development through evaluation, deployment, and observability.

My background combines **machine learning, numerical simulation, uncertainty-aware modeling, retrieval and recommendation systems, and aerospace engineering**. I am especially interested in ML systems that need to work reliably outside a notebook: evaluated on realistic data, deployed as services, monitored, and validated against domain constraints.

Previously, I worked in commercial aerospace systems engineering supporting Rolls-Royce Trent XWB-84 EP airworthiness activities. That experience shaped how I approach ML today: predictive performance matters, but so do failure modes, traceability, reproducibility, and knowing when a model should not be trusted.

---

## What I work on

**Applied ML Engineering**
Data validation · feature engineering · model training · leakage-aware evaluation · failure analysis · reproducible pipelines

**Generative AI & Retrieval**
RAG · lexical and dense retrieval · hybrid search · reranking · grounded generation · citation verification · LLM evaluation

**Scientific ML**
Surrogate modeling · uncertainty quantification · operator learning · physics-based validation · simulation-driven ML

**ML Systems**
FastAPI · Docker · CI/CD · model artifacts · cloud deployment · observability · latency and reliability testing

**Model Evaluation**
Held-out evaluation · bootstrap confidence intervals · ranking metrics · subgroup analysis · regression gates · physics-based checks

---

# Featured Projects

## [AeroRAG-X](https://github.com/triasha72/AeroRAG-X)

### Production-oriented RAG for aerospace technical knowledge

Built an end-to-end evidence-grounded RAG system over NASA technical reports.

**Key capabilities**

* Citation-preserving document ingestion and chunking
* BM25 and Sentence Transformer dense retrieval
* Reciprocal Rank Fusion hybrid search
* Cross-encoder reranking
* Evidence-sufficiency gating and grounded refusals
* Structured LLM generation with claim-level citations
* Retrieval and generation evaluation
* Held-out evaluation and CI regression policies
* FastAPI serving and Docker deployment
* Structured logging, Prometheus metrics, and OpenTelemetry tracing
* Private Google Cloud Run deployment

The system is built around one requirement: **technical claims should remain traceable to the evidence that supports them.**

---

## [EdgeGenBench](https://github.com/triasha72/EdgeGenBench)

### Uncertainty-aware Scientific ML and edge inference

A reproducible Scientific ML benchmark connecting aircraft design, surrogate modeling, uncertainty, optimization, and deployment.

**Key capabilities**

* Physics-based synthetic data generation
* Multi-output Ridge, Random Forest, and HistGradientBoosting surrogates
* Validation-based model selection
* Split-conformal and tree-quantile uncertainty estimation
* Safety-conscious feasibility classification
* False-safe-rate-aware decision thresholds
* Constrained multi-objective optimization
* Pareto-front extraction
* Physics-based validation of optimizer-selected designs
* ONNX export and model-equivalence testing
* Accuracy, model-size, and latency benchmarking

The strongest classical surrogate achieved approximately **0.995 mean test R²** in the current benchmark.

ONNX Runtime reduced recorded batch-1 Random Forest inference latency from approximately **13.8 ms to 0.3 ms**.

---

## [NewsLens](https://github.com/triasha72/NewsLens)

### Leakage-aware recommendation, search, and serving system

Built an end-to-end ML system using the Microsoft MIND news recommendation dataset.

**Key capabilities**

* Validated MIND-small ingestion
* DuckDB analytical warehouse and SQL feature pipelines
* Leakage-safe chronological train/validation splitting
* TF-IDF search and personalized recommendation
* Training-only popularity fallback for cold-start users
* NDCG, MRR, Recall, and Hit Rate evaluation
* Bootstrap confidence intervals and paired model comparison
* Subgroup, exposure, category, and failure analysis
* Versioned and checksummed model artifacts
* FastAPI inference service
* Docker and Docker Compose
* GitHub Actions CI/CD and container publication
* 400+ automated tests

This project focuses on the full ML lifecycle: **data → modeling → evaluation → artifacts → serving → observability**.

---

## [NURBS-BEM EM Solver](https://github.com/triasha72/NURBS_BEM_EMSolver)

### Numerical physics + operator learning

Built a mesh-free electromagnetic solver from mathematical formulation through implementation to generate multi-fidelity simulation data for Scientific ML.

**Key capabilities**

* NURBS geometry processing
* Analytic geometry derivatives
* Biot-Savart integration
* Boundary Element Method field solution
* Multi-fidelity simulation dataset generation
* Closed-form physics verification
* Numerical convergence testing
* GNN–DeepONet architecture
* SIREN coordinate representation
* Physics-informed loss development
* Gradient and activation diagnostics
* Detection and correction of silent neural-network training failures

This project connects **numerical simulation, PDE-governed systems, and Scientific Machine Learning**.

---

# Technical Stack

### Languages & Data

`Python` · `SQL` · `C++` · `MATLAB` · `pandas` · `NumPy` · `SciPy` · `DuckDB`

### Machine Learning

`scikit-learn` · `PyTorch` · `TensorFlow` · regression · classification · clustering · recommender systems · surrogate modeling · uncertainty quantification

### LLM & Retrieval

`RAG` · `BM25` · `Sentence Transformers` · dense retrieval · hybrid retrieval · Reciprocal Rank Fusion · cross-encoder reranking · grounded generation · retrieval evaluation · generation evaluation

### ML Engineering

`FastAPI` · REST APIs · `Docker` · Docker Compose · `GitHub Actions` · CI/CD · `pytest` · `Ruff` · `mypy` · versioned model artifacts · `ONNX` · ONNX Runtime

### Cloud & Observability

`Google Cloud Run` · `Cloud Storage` · `Prometheus` · `OpenTelemetry` · structured logging · tracing · load testing · latency benchmarking

### Scientific ML

`DeepONet` · `GNNs` · `SIREN` · surrogate modeling · numerical simulation · uncertainty quantification · multi-objective optimization · physics-based validation

---

# Current Technical Direction

I am continuing to deepen my work in:

**Transformer fine-tuning**
PyTorch · Hugging Face · PEFT · LoRA/QLoRA

**Scalable Deep Learning**
GPU training · mixed precision · distributed training · profiling

**Scientific AI**
Neural operators · FNO · DeepONet · physics-informed learning

**Efficient Inference**
Quantization · model compression · hardware-aware deployment

**AI Systems**
Agentic workflows · tool use · evaluated AI pipelines

**ML Data Infrastructure**
Distributed data processing · orchestration · production feature pipelines

---

# Background

### Georgia Institute of Technology

**M.S. Aerospace Engineering**
Aerospace Systems Design Laboratory

Research spanning machine learning, uncertainty-aware modeling, simulation reliability, sustainable aviation, and engineering decision support.

### Alten India / Rolls-Royce

**Systems Engineer**

Commercial aerospace systems engineering and airworthiness support for the Rolls-Royce Trent XWB-84 EP.

My engineering background gives me a strong preference for ML systems that are **measurable, reproducible, explainable in their failure modes, and connected to the physical or operational system they support**.

---

# What I'm Looking For

I am interested in opportunities including:

**Applied Machine Learning Engineer** · **Machine Learning Engineer** · **AI Engineer** · **Scientific ML Engineer** · **Applied AI Engineer** · **ML Research Engineer**

Particularly interested in problems involving **real-world ML systems, scientific computing, engineering AI, retrieval and generative AI, uncertainty, model reliability, and deployment**.

---

# Connect

[Portfolio](https://triasha72.github.io/Portfolio) · [LinkedIn](https://www.linkedin.com/in/triasha-sarkar) · [Email](mailto:tsarkar34@gatech.edu)
