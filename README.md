# Hi, I'm Triasha Sarkar

### Machine Learning Engineer

I am an aerospace engineering MS graduate from Georgia Tech and a former Machine Learning Engineer at Rolls-Royce.

I entered Georgia Tech's Aerospace Engineering PhD program, transitioned to the MS, and completed the degree in August 2026. That path sharpened my focus on applied machine learning and engineering systems.

My work covers scientific ML, model evaluation, retrieval, time-series data, and ML systems. My aerospace background gave me experience with simulation, uncertainty, and engineering problems. I am targeting **Machine Learning Engineer** and **Applied ML Engineer** roles.

[Portfolio](https://triasha72.github.io/Portfolio/) ·
[LinkedIn](https://www.linkedin.com/in/triasha-sarkar/) ·
[Resume](https://triasha72.github.io/Portfolio/assets/Triasha_Sarkar_CV.pdf) ·
[Email](mailto:tsarkar34@gatech.edu)

---

## Featured Projects

### [AIRFAANS](https://github.com/triasha72/AIRFAANS)
**Scientific ML · CFD surrogates · Graph neural networks · Uncertainty · Jan 2026 – Apr 2026**

Built a geometry-aware study of aerodynamic CFD surrogates using official AirfRANS meshes. It compares a pointwise MLP, a MeshGraphNet-style GNN, and a compact point neural operator with simulation-level splits, train-only normalization, and force verification.

Across three matched seeds and all 200 official interpolation test meshes, MeshGraphNet had the lowest mean error for the four predicted flow fields and drag; the point operator had the lowest mean lift error. Reynolds/AoA OOD, uncertainty, and active-learning studies remain pending, so the project is not presented as operationally ready.

### [Surrogate Model Learning](https://github.com/triasha72/Surrogate-model-learning)
**Engineering data · Reliability · Uncertainty quantification · Distribution shift**

Built public engineering-data studies using grouped splits, Gaussian processes and conventional surrogates, multi-seed robustness analysis, split-conformal intervals, and distance-to-training-domain guards.

An airfoil Gaussian process reached R² 0.8145 on a physically grouped split; the 10-seed mean of 0.8662 ± 0.0680 showed material split sensitivity. Nominal 90% intervals did not retain 90% coverage after design shift, an explicit finding that shaped the evaluation approach.

### [EdgeGenBench](https://github.com/triasha72/EdgeGenBench)
**Scientific ML · Uncertainty · On-device inference**

Built a real-flight anomaly track on NASA DASHlink data alongside a separately labeled generated aircraft-design deployment benchmark. The recorded-flight model reached 0.7380 macro F1 on 17,780 aircraft-disjoint approaches and stayed blocked by its release gates; ONNX consistency remained above 99.55% under tested sensor corruptions.

### [NewsLens](https://github.com/triasha72/NewsLens)
**Recommendation · Real-time search · Distributed systems**

Built a leakage-aware news recommender with chronological evaluation, then added a separate real-time path so new articles could become searchable without tying event delivery to the model server. Go, Kafka, PostgreSQL, and FastAPI now handle keyed ingestion, idempotent writes, freshness-aware ranking, dead letters, and consumer recovery; the verified Docker run accepted all 500 events and reached a 79 ms sampled index-freshness p95.

### More technical work

- [IntegrityBench](https://github.com/triasha72/IntegrityBench) — every candidate remains blocked. A thresholded Civil Comments candidate reached 1.84% false acceptance on 97,320 held-out rows, but the frozen three-way candidate falsely allowed 59.32% of 2,802 human-annotated ToxicChat prompts.
- [AeroSynth-Eval](https://github.com/triasha72/AeroSynth-Eval) — AGDD real-image transfer study plus 1,735 GenAI-Bench preference votes. A separate 3,224-image DLR aircraft-dent track reached 0.9777 dent recall on a 645-image test but only 0.5969 ROC-AUC because of false alarms; it remains a baseline.
- [Equity Backtest](https://github.com/triasha72/Equity-Backtest) — expanding-window signal evaluation with real prices, turnover costs, a liquidity-based participation-cap stress test, a complete variant log, and an explicit survivorship-bias boundary.
- [Atlanta Mobility Resilience Digital Twin](https://github.com/triasha72/atlanta-mobility-resilience-digital-twin) — checksummed OpenStreetMap disruption simulation with 50 Census tract origins from 2024 ACS estimates, representing an estimated 216,659 residents. A 20-case MARTA planner review showed that the first schedule router misses walking transfers between nearby stops, so its accessibility percentages remain development outputs while that gap is fixed.
- [AeroRAG-X](https://github.com/triasha72/AeroRAG-X) — evaluation-first technical retrieval over 3,233 NASA report chunks, with hybrid retrieval, reranking, evidence checks, controlled citations, and containerized services. The manual 50-case aerospace audit is still pending.
- [Surrogate Model Learning](https://github.com/triasha72/Surrogate-model-learning) — public UCI airfoil, building, and concrete experiments with grouped splits, seed sensitivity, conformal coverage, and an extrapolation guard. A high-age concrete tail did not trigger the guard more often, so its limits are reported directly.

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

**ML and scientific ML:** PyTorch, PyTorch Geometric, scikit-learn, graph neural networks, neural operators, surrogate modeling, uncertainty quantification, Hugging Face Transformers, RAG, BM25, dense retrieval, reranking, recommender systems

**ML systems:** FastAPI, Kafka, Docker/Compose, Kubernetes, GitHub Actions, CI/CD, Prometheus, OpenTelemetry, ONNX, Core ML, Qualcomm QNN

**Engineering practice:** leakage-aware evaluation, protected test design, bootstrap comparison, failure analysis, physics checks, reproducible experiments
