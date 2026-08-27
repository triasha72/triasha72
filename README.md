# Hi, I'm Triasha Sarkar

### Machine Learning Engineer | Search, Recommendation, GenAI Evaluation, and ML Systems

I am an aerospace engineering MS graduate from Georgia Tech and a former Machine Learning Engineer at Rolls-Royce India. I build ML systems that are useful beyond a notebook: the data and evaluation have to be sound, the service has to be deployable, and failures have to be visible.

My recent work covers retrieval and ranking, recommender systems, RAG and multimodal evaluation, scientific ML, and on-device inference. I am currently targeting **Machine Learning Engineer**, **Applied ML/AI Engineer**, **Search or Recommendation Engineer**, and **GenAI Evaluation / ML Systems** roles.

[Portfolio](https://triasha72.github.io/Portfolio/) ·
[LinkedIn](https://www.linkedin.com/in/triasha-sarkar/) ·
[Resume](https://triasha72.github.io/Portfolio/assets/Triasha_Sarkar_CV.pdf) ·
[Email](mailto:tsarkar34@gatech.edu)

---

## Featured Projects

### [AeroRAG-X](https://github.com/triasha72/AeroRAG-X)
**Retrieval · RAG evaluation · Agentic workflows · ML systems**

Built an evaluation-first technical knowledge system over 3,233 citation-preserving NASA report chunks. It combines hybrid retrieval, fusion, reranking, pgvector search, evidence checks, controlled citations, bounded agents, and containerized FastAPI services.

### [NewsLens](https://github.com/triasha72/NewsLens)
**Recommendation · Real-time search · Distributed systems**

Built a leakage-aware news recommender with chronological evaluation, then added a separate real-time path so new articles could become searchable without tying event delivery to the model server. Go, Kafka, PostgreSQL, and FastAPI now handle keyed ingestion, idempotent writes, freshness-aware ranking, dead letters, and consumer recovery; the verified Docker run accepted all 500 events and reached a 79 ms sampled index-freshness p95.

### [EdgeGenBench](https://github.com/triasha72/EdgeGenBench)
**Scientific ML · Uncertainty · On-device inference**

Built an aircraft-design surrogate benchmark that connects uncertainty estimates and constrained optimization to deployment. Exported and tested models across ONNX, Core ML, and Qualcomm QNN, then added an installable iPhone browser app; the QNN deployment retained 0.997 mean held-out R² on Snapdragon hardware.

### [AeroSynth-Eval](https://github.com/triasha72/AeroSynth-Eval)
**Multimodal AI · VLM evaluation · Reproducibility**

Built a fixed 48-scenario evaluation suite for synthetic aerospace inspection imagery. A real free-GPU Kaggle batch attempted all 12 development cases with one Qwen2-VL session; eight passed the strict response schema, while four failures were retained for analysis rather than hidden.

### More technical work

- [Equity Backtest](https://github.com/triasha72/Equity-Backtest) — expanding-window signal evaluation with transaction costs and a complete record of tested specifications.
- [Atlanta Mobility Resilience Digital Twin](https://github.com/triasha72/atlanta-mobility-resilience-digital-twin) — OSMnx and NetworkX simulation of how road disruptions change travel time, access, and equity across Atlanta.
- [Surrogate Model Learning](https://github.com/triasha72/Surrogate-model-learning) — comparison of Gaussian process, response-surface, and radial-basis models, with emphasis on where each method fails.

---

## Experience

### Georgia Tech Aerospace Systems Design Laboratory
**Graduate Research Assistant under Prof. Dimitri Mavris · May 2025 – Aug 2026**

- Audited a rocket-motor simulation study that was failing without errors or output, built a leakage-safe classifier with 96.8% accuracy across 15,120 simulations, and traced the failures to an uncapped convergence loop.
- Worked on source-aware retrieval and evaluation for the Delta Air Lines-sponsored HERO safety program.
- Built surrogate, uncertainty, demand, and life-cycle models for GREEN TEA and Project EAGLE; the GREEN TEA model remains in sponsor use.

### Rolls-Royce India
**Machine Learning Engineer · Jul 2023 – Apr 2025**

- Built Python workflows for diagnostics, anomaly detection, predictive maintenance, and mixed-frequency aircraft-engine time series.
- Turned certification requirements into reproducible analyses and model checks, then reviewed the findings with lifecycle engineers.

### Rolls-Royce DataLabs
**Data Science Intern · May 2021 – Jul 2021**

- Cleaned aircraft-engine sensor data, designed features, compared predictive and anomaly-detection models, and summarized recurring failure patterns for engineering review.

---

## Technical Toolkit

**Languages and data:** Python, Go, SQL, C++, MATLAB, pandas, NumPy, SciPy, DuckDB, PostgreSQL/pgvector

**ML and GenAI:** PyTorch, scikit-learn, Hugging Face Transformers, PEFT/LoRA, LangGraph, RAG, BM25, dense retrieval, reranking, recommender systems, uncertainty estimation

**ML systems:** FastAPI, Kafka, Docker/Compose, Kubernetes, GitHub Actions, CI/CD, Prometheus, OpenTelemetry, ONNX, Core ML, Qualcomm QNN

**Engineering practice:** leakage-aware evaluation, protected test design, bootstrap comparison, failure analysis, physics checks, reproducible experiments
