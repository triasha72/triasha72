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

The external evidence track now covers QASPER and SciFact human annotations. SciFact reaches 89.89% evidence-document recall@10. I also audited 20,283 TREC RAG relevance judgments and 2,840 citation-support judgments, then verified that the NASA provenance guard rejects 200/200 deliberately wrong source IDs. The manual 50-case aerospace audit is still pending.

### [NewsLens](https://github.com/triasha72/NewsLens)
**Recommendation · Real-time search · Distributed systems**

Built a leakage-aware news recommender with chronological evaluation, then added a separate real-time path so new articles could become searchable without tying event delivery to the model server. Go, Kafka, PostgreSQL, and FastAPI now handle keyed ingestion, idempotent writes, freshness-aware ranking, dead letters, and consumer recovery; the verified Docker run accepted all 500 events and reached a 79 ms sampled index-freshness p95.

### [EdgeGenBench](https://github.com/triasha72/EdgeGenBench)
**Scientific ML · Uncertainty · On-device inference**

Built a real-flight anomaly track on NASA DASHlink data alongside a separately labeled generated aircraft-design deployment benchmark. The recorded-flight model reached 0.7380 macro F1 on 17,780 aircraft-disjoint approaches and stayed blocked by its release gates; ONNX consistency remained above 99.55% under tested sensor corruptions.

### More technical work

- [IntegrityBench](https://github.com/triasha72/IntegrityBench) — three-way Civil Comments moderator remains blocked after 59.32% false acceptance on 2,802 human-annotated ToxicChat prompts. A separate 99,718-pair BeaverTails run cuts false acceptance to 18.79% but raises false rejection to 16.43% and has no escalation class.
- [AeroSynth-Eval](https://github.com/triasha72/AeroSynth-Eval) — AGDD real-image transfer study plus 1,735 GenAI-Bench preference votes. The next DLR track is a verified MIT release with 6,000+ labelled aircraft-dent images; training is pending archive and split audit.
- [Equity Backtest](https://github.com/triasha72/Equity-Backtest) — expanding-window signal evaluation with real prices, transaction costs, a complete variant log, and an explicit survivorship-bias boundary.
- [Atlanta Mobility Resilience Digital Twin](https://github.com/triasha72/atlanta-mobility-resilience-digital-twin) — checksummed OpenStreetMap disruption simulation with 50 Census tract origins from 2024 ACS estimates, representing an estimated 216,659 residents. Destinations and observed traffic calibration remain open.
- [Surrogate Model Learning](https://github.com/triasha72/Surrogate-model-learning) — public UCI airfoil and building experiments with grouped splits, seed sensitivity, conformal coverage, and an extrapolation guard. A normalized conformal diagnostic improved building-load coverage to 87.93% and 87.07%, still below its 90% target and still awaiting confirmation on untouched data.

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
