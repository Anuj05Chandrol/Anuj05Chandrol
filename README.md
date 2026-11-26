<!-- Profile README: Anuj05Chandrol/Anuj05Chandrol -->

<div align="center">

  <img width="100%" alt="Anuj Chandrol — Data Science Engineering Graduate" src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:1D4ED8,100:06B6D4&height=220&section=header&text=ANUJ%20CHANDROL&fontSize=45&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Data%20Science%20Engineering%20Graduate&descAlignY=60&descSize=18" />

  <a href="https://github.com/Anuj05Chandrol"><img alt="Data Engineering, Analytics, Machine Learning and Python Development" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=Data+Engineering+%26+ETL;S3+Object+Storage+%26+Data+Lakes;SQL+%26+Business+Intelligence;Machine+Learning+%26+AI;Python+%26+Software+Development" /></a>

  ![Open to Work](https://img.shields.io/badge/OPEN_TO_WORK-22C55E?style=for-the-badge)
  ![Graduate](https://img.shields.io/badge/B.TECH-2026-2563EB?style=for-the-badge)
  ![Profile Views](https://komarev.com/ghpvc/?username=Anuj05Chandrol&color=0891b2&style=for-the-badge&label=PROFILE+VIEWS)

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anuj-chandrol-79b1a62a7)
  [![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anuj05chandrol@gmail.com)
  [![Repositories](https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Anuj05Chandrol?tab=repositories)

</div>

## 👨‍💻 About Me

I am a **2026 B.Tech Data Science Engineering graduate** from LNCT Group of Colleges, Bhopal, India.

I build practical data engineering pipelines, analytical workflows and machine learning applications using Python, SQL and modern data infrastructure.

My current engineering focus includes:

- End-to-end batch ETL pipelines and data integration.
- S3-compatible object storage and data lake architecture.
- Data quality validation and financial reconciliation.
- PostgreSQL databases and columnar Parquet storage.
- Automated testing, CI/CD and reproducible engineering benchmarks.

I am expanding into distributed data processing, real-time streaming, MLOps and generative AI.

**Open to entry-level opportunities:** Data Engineer · Data Analyst · Python Developer · Software Engineer · Data Science / ML roles across India.

## ⚡ Engineering Highlights

<div align="center">

![Records](https://img.shields.io/badge/Records_Processed-460%2C775-2563EB?style=for-the-badge)
![Tests](https://img.shields.io/badge/Automated_Tests-77_Passed-22C55E?style=for-the-badge)
![Coverage](https://img.shields.io/badge/Core_Coverage-93%25-22C55E?style=for-the-badge)
![Integrity](https://img.shields.io/badge/File_Integrity-100%25-0891B2?style=for-the-badge)
![Compression](https://img.shields.io/badge/Storage_Reduction-57.14%25-7C3AED?style=for-the-badge)

</div>

*Measured local results from the DataFlow Nexus synthetic-data engineering platform.*

## 🚀 Featured Project — DataFlow Nexus

[![DataFlow Nexus](https://img.shields.io/badge/Explore-DataFlow%20Nexus-2563EB?style=for-the-badge&logo=github)](https://github.com/Anuj05Chandrol/dataflow-nexus)
[![CI](https://github.com/Anuj05Chandrol/dataflow-nexus/actions/workflows/ci.yml/badge.svg)](https://github.com/Anuj05Chandrol/dataflow-nexus/actions/workflows/ci.yml)
![Status](https://img.shields.io/badge/Status-Active%20Development-blue)
![MinIO](https://img.shields.io/badge/MinIO-S3_Object_Storage-C72E49?logo=minio&logoColor=white)

A modular end-to-end data engineering platform simulating an e-commerce data ecosystem, integrating synthetic data generation, validated batch ETL, PostgreSQL ingestion, columnar storage, S3-compatible data lakes and automated file integrity verification.

### System Architecture

```mermaid
flowchart TD
    A[Synthetic Data Generator] --> B[Raw CSV Files]
    B --> C[Extraction Engine]

    C --> D[Local Bronze CSV]
    C --> E[Data Quality Engine]

    E --> F[Transformation Engine]

    F --> G[Local Silver Parquet]
    F --> H[PostgreSQL COPY Loader]

    H --> I[PostgreSQL Database]
    I --> J[SQL Analytics]

    D --> K[S3 Synchronization Engine]
    G --> K
    H --> K

    K --> L[MinIO Bronze Bucket]
    K --> M[MinIO Silver Bucket]

    L --> N[SHA-256 Verification]
    M --> N

    N --> O[Performance Reports]

    P[Gold Bucket - Reserved]

    Q[GitHub Actions CI] -.-> E
    Q -.-> H
    Q -.-> K

    classDef bronze fill:#B87333,color:#fff,stroke:#92400e
    classDef silver fill:#64748B,color:#fff,stroke:#475569
    classDef gold fill:#CA8A04,color:#fff,stroke:#A16207
    classDef database fill:#2563EB,color:#fff,stroke:#1D4ED8
    classDef quality fill:#16A34A,color:#fff,stroke:#15803D

    class D,L bronze
    class G,M silver
    class P gold
    class I,H database
    class E,N quality
```

### 📊 Batch ETL Benchmarks

| Metric | Local benchmark |
|---|---:|
| Synthetic records processed | **460,775** |
| Data generation time | 1.58 seconds |
| Batch ETL execution time | 24.642 seconds |
| ETL throughput | **18,699 records/sec** |
| Raw CSV size | 16.54 MiB |
| Parquet size | 7.09 MiB |
| Storage reduction | **57.14%** |

### 🗄️ Object Storage Benchmarks

| Metric | Local benchmark |
|---|---:|
| Data lake buckets | 3 |
| Bronze CSV objects | 5 |
| Silver Parquet objects | 5 |
| Total uploaded objects | 10 |
| SHA-256 verified objects | **10/10** |
| File integrity verification | **100%** |
| Total object storage | 23.6251 MiB |
| Upload and verification time | 44.6597 seconds |

### 🧪 Automated Testing

| Metric | Result |
|---|---:|
| Total automated tests | **77 passed** |
| Object storage unit tests | 19 passed |
| MinIO integration tests | 8 passed |
| Core package statement coverage | **93%** |
| Failed tests | **0** |
| Complete test execution time | 57.04 seconds |
| Code quality checks | Passed |

*Local synthetic-data benchmarks recorded November 25–26, 2026. These results represent single-machine workloads, not distributed production performance.*

### Implemented Capabilities

- Reproducible generation of customers, products, orders, order items and payments.
- Schema validation, primary key checks, foreign key checks and financial reconciliation.
- Typed Apache Parquet storage with Snappy compression.
- Transactional PostgreSQL bulk ingestion using COPY and full-refresh loading.
- SQL-based business analytics and performance reporting.
- Persistent Docker-based PostgreSQL and MinIO infrastructure.
- Automated Bronze, Silver and Gold bucket initialization.
- Boto3-powered S3 upload and download engine.
- SHA-256 checksum verification for uploaded and downloaded objects.
- Safe temporary-file downloads and corruption detection.
- Automated ETL and object storage synchronization.
- Unit testing, integration testing, regression testing and CI/CD.

### Technology Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![Boto3](https://img.shields.io/badge/Boto3-FF9900?style=flat-square)
![Apache Parquet](https://img.shields.io/badge/Apache_Parquet-2563EB?style=flat-square)
![PyArrow](https://img.shields.io/badge/PyArrow-475569?style=flat-square)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

### Project Resources

[Source Code & Documentation](https://github.com/Anuj05Chandrol/dataflow-nexus) ·
[Batch ETL Benchmark](https://github.com/Anuj05Chandrol/dataflow-nexus/blob/main/docs/benchmarks/batch_etl_460775.json) ·
[CI Results](https://github.com/Anuj05Chandrol/dataflow-nexus/actions) ·
[Releases](https://github.com/Anuj05Chandrol/dataflow-nexus/releases)

### Development Milestones

- [x] Development environment
- [x] Repository foundation
- [x] PostgreSQL infrastructure
- [x] Synthetic data generation
- [x] Batch ETL pipeline
- [x] Automated testing and GitHub CI foundation
- [x] MinIO object storage implementation and local testing
- [ ] Apache Spark distributed processing
- [ ] Apache Kafka streaming
- [ ] Apache Airflow orchestration
- [ ] dbt data warehouse
- [ ] Power BI dashboards
- [ ] Machine learning and MLflow
- [ ] FastAPI backend
- [ ] Next.js frontend
- [ ] Prometheus and Grafana monitoring

**Next milestones:** Apache Spark, million-record workload benchmarking, Kafka, Airflow and dbt.

## 🛠️ Technical Skills

### Hands-on Data Engineering

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?logo=minio&logoColor=white)
![Boto3](https://img.shields.io/badge/Boto3-FF9900)
![S3](https://img.shields.io/badge/S3_Compatible_Storage-569A31)
![Parquet](https://img.shields.io/badge/Apache_Parquet-2563EB)
![PyArrow](https://img.shields.io/badge/PyArrow-475569)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

| Area | Technologies and concepts |
|---|---|
| Data pipelines | Batch ETL, Faker, Pandas, PyArrow, Parquet, Snappy |
| Databases | SQL, PostgreSQL, SQLAlchemy, Psycopg, relational modeling |
| Object storage | MinIO, Boto3, Botocore, S3-compatible APIs |
| Data lake architecture | Bronze, Silver and Gold storage layers |
| Data reliability | Schema validation, referential integrity, financial reconciliation |
| File integrity | SHA-256, checksum validation, corruption detection |
| Infrastructure | Docker, Docker Compose, persistent volumes, WSL2 |
| DevOps | Git, GitHub, GitHub Actions, CI/CD |
| Testing | Pytest, pytest-cov, Ruff, unit and integration testing |
| Performance | Benchmarking, bulk COPY ingestion, columnar compression |

### Additional Skills and Academic Experience

| Area | Technologies and concepts |
|---|---|
| Programming | Python, Java, SQL, JavaScript, HTML, CSS |
| Machine learning | NumPy, Scikit-learn, TensorFlow, XGBoost, SHAP |
| Analytics | Power BI, Excel, Matplotlib, Seaborn |
| Web development | Flask, React, REST APIs |
| Developer tools | VS Code, Jupyter, Google Colab, Git, GitHub |
| CS fundamentals | DSA, OOP, DBMS, debugging and problem solving |

## 📂 Additional Projects

| Project | Description | Technologies | Availability |
|---|---|---|---|
| House Price Prediction | Real estate price prediction with model explainability and a web interface | Python, Flask, XGBoost, SHAP, Pandas | Source publication planned |
| Stock Market Trend Analyzer | Historical market data analysis, LSTM forecasting and visualization | Python, TensorFlow, yFinance, Matplotlib | Source publication planned |

## 📚 Currently Learning

| Specialization | Technologies and concepts |
|---|---|
| Distributed data engineering | Apache Spark, PySpark, Spark SQL |
| Real-time streaming | Apache Kafka, event-driven pipelines |
| Workflow orchestration | Apache Airflow |
| Analytical data engineering | dbt, dimensional modeling, data warehousing |
| Data infrastructure | Redis, distributed storage systems |
| Generative AI | Ollama, LangChain, RAG, vector databases |
| MLOps | MLflow, DVC, model monitoring |
| Full-stack development | FastAPI, Next.js, TypeScript |
| Observability | Prometheus, Grafana |
| Cloud and systems | AWS fundamentals, Linux |

## 🏗️ Engineering Portfolio Roadmap

| Project | Focus | Status |
|---|---|---|
| [**DataFlow Nexus**](https://github.com/Anuj05Chandrol/dataflow-nexus) | End-to-end data engineering | 🟢 Active development |
| RetailIQ | Retail analytics and business intelligence | Planned |
| FraudShield AI | Financial fraud detection | Planned |
| KnowledgeOS | Generative AI and document intelligence | Planned |
| ModelOps | Machine learning lifecycle automation | Planned |
| CareerIntel AI | Job market analytics | Planned |
| Professional portfolio website | Project case studies and demonstrations | Planned |

## 🏆 Certifications

| Certification | Issuer | Year |
|---|---|---|
| Data Analytics Job Simulation | Deloitte Australia — Forage | 2025 |
| Machine Learning I | Columbia+ | 2025 |
| SQL for Data Analysis | Udemy | 2025 |
| Python Basic Skill Certification | HackerRank | 2025 |
| Python Essentials 1 | Cisco Networking Academy | 2025 |

## 🎓 Education

**Bachelor of Technology — Data Science Engineering (2022–2026)**

LNCT Group of Colleges, Bhopal  
Rajiv Gandhi Proudyogiki Vishwavidyalaya (RGPV)

## 📈 GitHub Activity

<div align="center">

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Anuj05Chandrol/Anuj05Chandrol/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Anuj05Chandrol/Anuj05Chandrol/output/github-contribution-grid-snake.svg" />
    <img width="100%" alt="GitHub contribution snake" src="https://raw.githubusercontent.com/Anuj05Chandrol/Anuj05Chandrol/output/github-contribution-grid-snake.svg" />
  </picture>

</div>

<details>
<summary><b>View GitHub statistics and contribution history</b></summary>
<br />

<div align="center">

  <img width="48%" alt="GitHub statistics" src="https://github-readme-stats.vercel.app/api?username=Anuj05Chandrol&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" />

  <img width="48%" alt="Repository language distribution" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anuj05Chandrol&layout=compact&theme=tokyonight&hide_border=true" />

  <img width="75%" alt="GitHub streak" src="https://streak-stats.demolab.com?user=Anuj05Chandrol&theme=tokyonight&hide_border=true" />

  <img width="98%" alt="Contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=Anuj05Chandrol&theme=tokyo-night&hide_border=true&area=true" />

</div>

</details>

<details>
<summary><b>View automated GitHub metrics</b></summary>
<br />

<div align="center">

  <img width="95%" alt="Automated GitHub metrics" src="https://raw.githubusercontent.com/Anuj05Chandrol/Anuj05Chandrol/main/github-metrics.svg" />

</div>

</details>

## 🤝 Connect With Me

<div align="center">

**Open to entry-level engineering opportunities and technical collaboration.**

Interested in building reliable data pipelines, scalable data systems and intelligent software applications.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anuj-chandrol-79b1a62a7)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anuj05chandrol@gmail.com)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Anuj05Chandrol)

---

**Building reliable data systems, one engineering milestone at a time.**

<img width="100%" alt="Footer" src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:1D4ED8,100:06B6D4&height=120&section=footer" />

</div>
