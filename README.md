# Hi, I'm Lamine Sow 👋

**Engineering student in Computer Science (Sup Galilée, Université Sorbonne Paris Nord)** working on **Machine Learning, LLMs / RAG, MLOps and Operations Research**.

I like projects that leave the notebook: a model, an honest evaluation protocol, an API, monitoring, and a decision layer on top when the problem needs one.

🎯 **Looking for a 6-month end-of-studies internship (Data Science / ML / AI engineering), starting March 2027.**

🌐 Portfolio: **[lamine-sow.me](https://lamine-sow.me)**

---

## 🚀 Featured Projects

| Project | What it does | Key results |
|---|---|---|
| [**nyc-taxi-mlops**](https://github.com/Lamine2004Sow/nyc-taxi-mlops) | Self-healing MLOps platform: FastAPI model served on Kubernetes from the MLflow registry, Prometheus alert on MAE drift triggers an automatic retraining Job | 6-month 2020 replay: COVID shock detected and fixed with no human action (holdout MAE 4.49 → 3.09); challenger promoted only if ≥ 2 % better on unseen data |
| [**legal-rag-agent**](https://github.com/Lamine2004Sow/legal-rag-agent) | LangGraph agent over the French Civil and Consumer Codes (~5,100 articles): guardrail, query rewriting, hybrid FAISS + BM25 search (RRF), deterministic citation checking | On 60 labelled questions: 90 % expected-article recall, 92.3 % citation precision, 100 % correct refusals, 0 % wrong answers |
| [**legal-embeddings-finetune**](https://github.com/Lamine2004Sow/legal-embeddings-finetune) 🚧 | Fine-tuning multilingual-e5 on legal retrieval with LLM-generated, filtered training pairs | 11,088 question/article pairs kept out of 12,849; test set frozen before training; bootstrap CIs and McNemar test. Work in progress |
| [**DermTriage**](https://github.com/Lamine2004Sow/DermTriage) | Skin lesion classification on HAM10000 (7 classes) with PyTorch and ResNet-18 transfer learning, lesion-level splits | Macro-F1 0.661 (5 folds) vs 0.260 for a colour baseline; 6 variants compared with pre-registered decision rules |
| [**evrptw-solver**](https://github.com/Lamine2004Sow/evrptw-solver) | Electric vehicle routing with time windows and recharging: C++17 ILS + memetic genetic algorithm, Gurobi MILP | Best-known fleet found on 54/56 large instances (+0.17 % distance); 18 instances below the published reference; 0 infeasible over 1,876 runs |
| [**roadef2020**](https://github.com/Lamine2004Sow/roadef2020) | ROADEF/EURO 2020 challenge: RTE grid maintenance scheduling under uncertainty | Simulated annealing within 0.52 % of the best known solution; 8/15 optima proven with ILP; certified gap cut from 55.9 % to 1.3 % on A_02 with valid inequalities |
| [**ring-star**](https://github.com/Lamine2004Sow/ring-star) | Ring-Star problem (circular metro line design): ILP with flow variables, greedy heuristic, stochastic local search | NP-hardness proof, PuLP/CBC model |

---

## 💼 Experience

**Machine Learning / Data Science Intern, Sonatel (Orange group)**, Dakar, May–Jul 2026
- Built an XGBoost model predicting fibre network failures 6 months ahead: **88 % fewer false negatives** than the existing business rule (PR-AUC 0.81 vs 0.28).
- 8-year network history (2018–2026) built as a pair, leakage-free evaluation, calibrated predictions explained with SHAP and aggregated into risk maps for field teams.

---

## 🛠️ Tech Stack

### Machine Learning & Deep Learning

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### LLM, RAG & NLP

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### MLOps & Deployment

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

### Optimization & Operations Research

![Gurobi](https://img.shields.io/badge/Gurobi-EE3524?style=for-the-badge&logoColor=white)
![CPLEX](https://img.shields.io/badge/CPLEX-052FAD?style=for-the-badge&logo=ibm&logoColor=white)
![PuLP](https://img.shields.io/badge/PuLP-4B8BBE?style=for-the-badge&logoColor=white)
![C++](https://img.shields.io/badge/C++17-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-9558B2?style=for-the-badge&logo=julia&logoColor=white)

### Languages, Databases & Tools

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 🧩 How I Build Projects

```text
Business problem → Data (leakage-free splits) → Model → Honest evaluation
      → Explanation / calibration → Optimization or decision layer
      → API → Monitoring → Automatic retraining
```

What I care about:
- **Evaluation first**: test sets frozen before training, baselines, confidence intervals, decision rules fixed in advance.
- **Reliability**: guardrails and verified citations for LLMs, non-regression tests, reproducible runs.
- **From prediction to action**: risk scores and forecasts turned into prioritised interventions or optimised plans.

---

## 📊 GitHub Stats

![Lamine's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Lamine2004Sow&theme=tokyonight&include_all_commits=true)

![GitHub Streak](https://streak-stats.demolab.com/?user=Lamine2004Sow&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Lamine2004Sow&theme=tokyonight&layout=compact)

---

## 🌐 Connect With Me

[![Portfolio](https://img.shields.io/badge/Portfolio-lamine--sow.me-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://lamine-sow.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mouhamadou-lamine-sow-118097334/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lamine.2004pro.sow@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=Lamine2004Sow&style=for-the-badge&color=blue)
