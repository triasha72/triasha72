# Hi, I'm Triasha Sarkar

### Machine Learning Engineer

I am an aerospace engineering MS graduate from Georgia Tech and a former Machine Learning Engineer at Rolls-Royce. I build ML systems that are useful beyond a notebook: the data and evaluation have to be sound, the service has to be deployable, and failures have to be visible.

I entered Georgia Tech's Aerospace Engineering PhD program, transitioned to the MS, and completed the degree in August 2026. That path sharpened my focus on applied machine learning and engineering systems.

My strongest work is in retrieval and ranking, ML evaluation, scientific ML, and deployment-focused engineering. I am targeting **Machine Learning Engineer**, **Applied ML Engineer**, and **Retrieval / Evaluation Engineer** roles.

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

Built a real-flight anomaly track on NASA DASHlink data alongside a separately labeled generated aircraft-design deployment benchmark. The recorded-flight model reached 0.7380 macro F1 on 17,780 aircraft-disjoint approaches and stayed blocked by its release gates; ONNX consistency remained above 99.55% under tested sensor corruptions.

### More technical work

- [IntegrityBench](https://github.com/triasha72/IntegrityBench) — Civil Comments moderation candidate with safety thresholds, a fail-closed API, human-review routing, model registry, shadow comparison, rollback, and an intentionally blocked release.
- [AeroSynth-Eval](https://github.com/triasha72/AeroSynth-Eval) — public AGDD real-image transfer study where mixed training improved macro F1 but reduced crack recall, so the augmentation was not called a safety win.
- [Equity Backtest](https://github.com/triasha72/Equity-Backtest) — expanding-window signal evaluation with real prices, transaction costs, a complete variant log, and an explicit survivorship-bias boundary.
- [Atlanta Mobility Resilience Digital Twin](https://github.com/triasha72/atlanta-mobility-resilience-digital-twin) — checksummed public OpenStreetMap disruption simulation; the first 672-node downtown run remains clearly bounded as free-flow routing over illustrative OD points, not observed traffic or an equity result.
- [Surrogate Model Learning](https://github.com/triasha72/Surrogate-model-learning) — public UCI airfoil and building experiments with grouped splits, seed sensitivity, conformal coverage, and an extrapolation guard.

---

## Experience

### Georgia Tech Aerospace Systems Design Laboratory
**Graduate Research Assistant under Prof. Dimitri Mavris · May 2025 – Aug 2026**

- Audited a rocket-motor simulation study that was failing without errors or output, built a leakage-safe classifier with 96.8% accuracy across 15,120 simulations, and traced the failures to an uncapped convergence loop.
- Worked on source-aware retrieval and evaluation for the Delta Air Lines-sponsored HERO safety program.
- Built surrogate, uncertainty, demand, and life-cycle models for GREEN TEA and Project EAGLE; the GREEN TEA model remains in sponsor use.

### Rolls-Royce
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
