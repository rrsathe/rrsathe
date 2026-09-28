# Hi, I'm Rahul Sathe

**AI Systems & High-Performance Software Engineer**  
B.Tech @ IIT Guwahati | Core Member @ IITG.ai | Open-Source Contributor to GROMACS

Building low-latency C++ systems, graph-based AI architectures, and production MLOps pipelines. My public work focuses on high-throughput software engines, causal inference frameworks, and computational biology.

[LinkedIn](https://linkedin.com/in/rrsathe) · [GitHub](https://github.com/rrsathe) · [GitLab](https://gitlab.com/rrsathe) · [Email](mailto:07rahulsathe@gmail.com)

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
  - Active contributor to one of the world's most widely used molecular dynamics simulation packages.
  - Refactoring codebase to adopt modern C++ patterns, resolving issues, and improving developer documentation (tracked on [GitLab](https://gitlab.com/gromacs/gromacs)).
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

## Technical Competencies

- **Languages:** C++ (C++20), Python, C, SQL, Bash, Go
- **Systems & Architecture:** Multithreading, Concurrency, gRPC, Protocol Buffers, Linux, Docker, CMake, GoogleTest
- **AI & Machine Learning:** PyTorch, Graph Neural Networks, LLMs, RAG & GraphRAG, Hugging Face, Scikit-learn
- **Data & MLOps:** Feast Feature Store, Apache Airflow, MLflow, Memgraph, PostgreSQL, Redis, Evidently AI

---

## Key Honors & Activities

- **IEEE CMES 2027 Submission:** Paper ID 181 on Graph ML for Huntington's Disease classification.
- **Inter IIT Tech Meet 14.0:** Contingent member representing IIT Guwahati in Data Science & AI.
- **Goldman Sachs India Hackathon 2026:** National Rank 244 (Quantitative Finance track).
- **Machine Learning Hackathon (IIT Guwahati AI Club):** 2nd Place.
