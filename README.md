# Hi, I'm Rahul Sathe

### Building High-Performance C++ Systems • Graph ML • Production MLOps

**B.Tech @ IIT Guwahati** | **Core Member @ IITG.ai** | **Open-Source Contributor to GROMACS**

I build low-latency C++ software engines, graph-based AI architectures, and production MLOps pipelines. My public work focuses on high-throughput matching systems, causal inference frameworks, and computational biology.

<p align="left">
  <a href="https://www.linkedin.com/in/rrsathe"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/rrsathe"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://gitlab.com/rrsathe"><img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white" alt="GitLab" /></a>
  <a href="mailto:07rahulsathe@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## Start Here

- **[Trading Server Engine](https://github.com/rrsathe/TradingServerEngine)** — C++20 price-time priority matching engine with gRPC/Protobuf APIs, thread-safe execution, and 5,000 updates/sec throughput.
- **[Causal RAG](https://github.com/rrsathe/causal-rag-rca)** — Root-cause attribution framework over 19,000+ transcripts using Memgraph dynamic subgraphs and Dialog2Flow clustering (Inter IIT Tech Meet 14.0).
- **[TopoHYFA: Hypergraph Gene Imputation](https://github.com/rrsathe/TopoHYFA)** — Topology-aware hypergraph neural network recovering critical gene signals from cross-tissue variance collapse; evaluated on GTEx (IEEE CMES 2027 submission).
- **[MLOps Demand Forecasting](https://github.com/rrsathe/mlops-demand-forecasting)** — End-to-end production pipeline on 61k+ records with Feast feature store, Airflow DAG orchestration, and Evidently AI monitoring.

---

## Featured Projects & Systems

### High-Performance Systems & Infrastructure
- **[Trading Server Engine](https://github.com/rrsathe/TradingServerEngine)**
  - Implemented price-time priority order book supporting Limit, Market, FOK, FAK, and GFD execution modes.
  - Engineered thread-safe matching with $O(1)$ order cancellation and background worker for order expiration.
  - Decoupled market feed via Observer pattern with PostgreSQL audit persistence; benchmarked 5k updates/s.
- **[GROMACS Open-Source Contributions](https://gitlab.com/gromacs/gromacs)**
  - Active contributor to GROMACS molecular dynamics simulation package.
  - Modernizing codebase patterns to modern C++, resolving issues, and improving developer documentation (tracked on [GitLab](https://gitlab.com/gromacs/gromacs)).
- **[GreenPipeline AI](https://github.com/rrsathe/greenpipeline-ai)**
  - Graph-based CI/CD pipeline optimizer that compiles GitLab CI workflows into Directed Acyclic Graphs (DAGs), reducing runtime and compute footprint by up to 60%.

### Graph ML, Generative AI & MLOps
- **[Causal RAG (Inter IIT Tech Meet 14.0)](https://github.com/rrsathe/causal-rag-rca)**
  - Built root-cause attribution system across 19,000+ dialogue transcripts using Memgraph graph databases.
  - Developed Dialog2Flow via agglomerative clustering to project conversational dialogues into directed causal graphs.
  - Traversed causal chains via probabilistic backward BFS, achieving 0.81 faithfulness score on evaluations.
- **[TopoHYFA (Computational Biology & Graph ML)](https://github.com/rrsathe/TopoHYFA)**
  - Diagnosed cross-tissue variance collapse (16.2% retained) in hypergraph factorization models on GTEx cohorts.
  - Formulated Gaussian log-likelihood ratio features across a 200-edge network, elevating classification AUC from 0.465 to 0.615 ($p = 0.028$).
- **[MLOps Demand Forecasting System](https://github.com/rrsathe/mlops-demand-forecasting)**
  - 168-hour load forecasting pipeline orchestrating 43 leakage-free time-series features in Feast.
  - Automated 3 Airflow DAGs, MLflow experiment tracking, Dockerized FastAPI inference (<200ms latency), and data drift monitoring with Evidently AI.

---

## Tech Stack

### Languages & Systems
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

### Machine Learning & Data Science
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

### Backend, MLOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Honors & Activities

- **IEEE CMES 2027 Paper Submission:** Paper ID 181 on Graph ML for Huntington's Disease classification.
- **Inter IIT Tech Meet 14.0:** Contingent member representing IIT Guwahati in Data Science & AI.
- **Goldman Sachs India Hackathon 2026:** National Rank 244 (Quantitative Finance track).
- **Machine Learning Hackathon (IIT Guwahati AI Club):** 2nd Place.

---

## Connect

<p align="left">
  <a href="https://www.linkedin.com/in/rrsathe"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/rrsathe"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://gitlab.com/rrsathe"><img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white" alt="GitLab" /></a>
  <a href="mailto:07rahulsathe@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
