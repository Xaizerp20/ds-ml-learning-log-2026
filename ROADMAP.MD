# DS/ML Plan 2026 — Industry-Focused Roadmap

This document outlines a 2026 roadmap to become job-ready for entry-level Data roles (DA / Junior DS / Junior ML), with an industry-first approach and a main portfolio project: Predictive Maintenance (RUL).

---

## Timeline
**9–12 months** total (time depends on weekly hours and consistency).

---

## Phase 0 — Professional Setup (3–5 days | 6–12h)
**Goal:** industry-standard environment.
- Python envs (venv/conda/uv), dependency management (pip-tools/poetry), `requirements` vs `pyproject`
- VS Code + Jupyter + Git/GitHub + terminal basics
- Code hygiene (black/ruff), clean notebooks, repo structure

**Deliverable:** repo template with `/notebooks`, `/src`, `/data`, `/reports`, `/tests`

---

## Phase 1 — Python for Data + Git (4–6 weeks | 40–70h)
**Goal:** comfortable Python for analysis and small pipelines.
- Python essentials: types/functions/collections, files (CSV/JSON/Parquet), logging, functional structure
- NumPy + pandas (joins/groupby/pivot/time index/missing/performance)
- matplotlib basics
- Professional Git (branching/PRs/commits/issues/README)

**Mini-projects:** industrial EDA + a small pipeline (CSV → clean → Parquet → metrics)

**Main project kickoff:** `predictive-maintenance-rul`
- Choose dataset: NASA CMAPSS (RUL)
- Deliverable: Data Card + initial EDA

---

## Phase 2 — SQL + Data Modeling + Business Metrics (4–6 weeks | 35–60h)
**Goal:** extract, join, understand business data.
- SQL: joins, CTEs, windows, cohorts/funnels/KPIs
- Data modeling: star schema, data quality
- Storytelling: decision-ready visuals and narratives

**Mini-projects:** failure analysis + KPI pack
**Main project:** model-ready dataset + no-leakage checks

---

## Phase 3 — Practical Statistics (4–6 weeks | 40–70h)
**Goal:** uncertainty, experiments, regression.
- Sampling, CI, bootstrap; correlation vs causation
- A/B testing, power, effect sizes, proxy metrics
- Linear regression assumptions, ridge/lasso, residual analysis

**Mini-projects:** simulated A/B + regression report
**Main project:** define RUL target + ridge baseline

---

## Phase 4 — Core Machine Learning (8–10 weeks | 90–140h)
**Goal:** strong models with correct evaluation.
- ML fundamentals: leakage, drift, bias/variance, pipelines
- Models: logistic/RF/GBM; regression RF/GBM/ElasticNet
- Feature engineering, SHAP/perm importance, imbalance handling
- Correct validation: time splits / walk-forward

**Mini-projects:** classification case + reproducible pipeline
**Main project:** Random Forest Regressor + time-based features + regime-level error analysis

---

## Phase 5 — Time Series + Predictive Maintenance (6–8 weeks | 70–110h)
**Goal:** plant-ready methodology.
- Time series components, stationarity, autocorrelation, temporal leakage
- PdM patterns: RUL / failure prediction / anomaly detection
- Industrial evaluation: horizon metrics, robustness, drift

**Mini-projects:** anomaly detection + Model Card
**Main project:** portfolio-ready structure + baseline/RF/GBM comparison + retraining plan

---

## Phase 6 — Production & MLOps (6–8 weeks | 60–100h)
**Goal:** deployment, monitoring, reproducibility.
- ML systems design: batch vs real-time, drift & quality checks, retraining triggers
- Tracking/versioning: MLflow or W&B (+ optional DVC)
- Deploy: FastAPI + Docker + tests + CI (GitHub Actions)

**Main project:** `/predict_rul` API + batch scoring + monitoring checks

---

## Phase 7 — Deep Learning + Practical GenAI (6–10 weeks | 60–120h) [Optional]
**Goal:** ML Engineer / DS roles involving DL.
- DL concepts: MLP/CNN/RNN/Transformers (conceptual) + regularization/optimizers/stable training
- GenAI productivity: prompting for EDA/docs/tests/refactors; output evaluation and reproducibility

---

## Coursera Plus Path (Beginner → Advanced)
1) Google Data Analytics PC (Phase 1–2)  
2) Google Advanced Data Analytics PC (Phase 3–4)  
3) IBM Data Science PC (Phase 1–4, alternative/companion)  
4) ML Specialization (Phase 4)  
5) ML in Production (Phase 6)  
6) MLOps Specialization (Phase 6)  
7) Deep Learning Specialization (Phase 7, optional)  
8) Generative AI with LLMs (Phase 7, optional)  
9) IBM Data Engineering PC (optional)

---

## Recommended Books
- Forecasting: Principles and Practice (3rd ed.)
- Designing Machine Learning Systems (Chip Huyen)
- Machine Learning Design Patterns
- Build a Large Language Model (From Scratch) [optional]

---

## Learning System (60/25/15)
- 60% practice (notebooks/projects)
- 25% courses
- 15% reading + notes + review



