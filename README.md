<div align="center">

# Hi there, I'm Adhyayan Verma 👋

**MS Computer Science @ NYU Tandon** · Data & ML Engineer · Full-Stack Builder

[![LinkedIn](https://img.shields.io/badge/LinkedIn-adhyayanverma-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/adhyayanverma)
[![Email](https://img.shields.io/badge/Email-av4159@nyu.edu-D14836?style=flat&logo=gmail&logoColor=white)](mailto:av4159@nyu.edu)
[![Location](https://img.shields.io/badge/New%20York%2C%20USA-🗽-lightgrey?style=flat)](#)

</div>

---

## 🧑‍💻 About Me

I'm a graduate student at **NYU Tandon School of Engineering** (MS CS, 2025–2027), with 3+ years of industry experience as a Data Engineer at **Optum**, where I built pipelines processing millions of healthcare records daily. I thrive at the intersection of **big data infrastructure**, **machine learning**, and **full-stack engineering**, and I'm actively seeking **Summer 2026 internships** in Software Engineering, ML/AI, and Data Engineering.

- 🔭 Currently building distributed systems and ML experiments at NYU
- 🌱 Exploring neural scaling laws, μP (Maximal Update Parameterization), and LLM fine-tuning
- 💬 Ask me about Kafka, Spark, Airflow, PyTorch, or system design
- 📍 Based in New York City

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frameworks & Libraries**

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat&logo=svelte&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)

**Data & Streaming**

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat&logo=apachehadoop&logoColor=black)

**Cloud, Infra & Databases**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat&logoColor=white)

---

## 🚀 Featured Projects

### 🦠 [NYC Disease Outbreak Surveillance System](https://github.com/adhyayanverma/BigDataNYCDiseaseSurveillance)

> Real-time distributed epidemiological surveillance platform that detected outbreaks **2–7 days earlier** than official NYC DOH reports.

- **Streaming:** Apache Kafka + Spark Streaming with **<5 min** end-to-end latency
- **Ingestion:** 5+ heterogeneous sources (Reddit, Bluesky, NYC 311, RSS feeds, Syndromic Surveillance) with 55% noise reduction via contextual NLP and 3-tier semantic deduplication
- **Storage:** Polyglot persistence across AWS S3, PostgreSQL + TimescaleDB, and ChromaDB
- **Analytics:** DBSCAN geospatial clustering, rolling Z-score anomaly detection (7-day, 3σ)
- **Dashboard:** Streamlit interface with sub-second query response

`Kafka` `PySpark` `Airflow` `PostgreSQL` `TimescaleDB` `ChromaDB` `DBSCAN` `NLP` `Streamlit` `AWS`

---

### 📐 [Scaling Laws in SVG Generation](https://github.com/adhyayanverma/MLProject) *(NYU · 2026)*

> Trained **5 GPT-2-style transformer architectures** (1.4M–89M parameters) on 400K+ SVG files to derive domain-specific neural scaling laws for structured visual syntax.

- **Best model** (SP XL, 89M params): validation loss **0.2505**, perplexity **1.285**, with **100% XML validity and SVG render rate**
- **Scaling law:** Derived a domain-specific power law (**α ≈ 0.077**) via log-log regression across four orders of model magnitude; SVG scales ~20% slower than NLP due to strict zero-tolerance syntax constraints
- **μP vs SP:** Benchmarked Standard vs. Maximal Update Parameterization across all scales; achieved **zero-shot LR transfer** (1.4M → 34M params) and identified a depth boundary where μP destabilizes at 12-layer depth
- **Preprocessing:** 3-stage pipeline (minification, coordinate normalization, filtering) over **185M tokens** with BPE tokenization (4k vocab), achieving **3× sequence compression** within a 1,024-token context window

`GPT-2` `μP` `PyTorch` `BPE Tokenization` `Scaling Laws` `Transformer` `SVG` `Google Colab A100`

---

### 🌳 [Treestagram](https://github.com/adhyayanverma/treestagram)

> Full-stack social platform built over 9 agile sprints, integrating the **NYC Open Data tree database** with social networking features.

- **Backend:** Django REST API · **Frontend:** Svelte · **Deployed** on AWS Elastic Beanstalk
- **Features:** Follow trees, geo-tagged photo posts, personalized borough-filtered feeds, real-time group chats, like/comment system
- **Roles:** 3-tier role system (user, caretaker, admin) with stewardship workflows and content moderation
- **DevOps:** Full CI/CD via Travis CI, continuous test coverage reporting via Coveralls

`Django` `Svelte` `PostgreSQL` `AWS` `Travis CI` `Coveralls` `REST API`

---

## 💼 Experience

| Role | Company | Period |
|------|---------|--------|
| 🎓 MS Computer Science | NYU Tandon School of Engineering | 2025 – 2027 |
| 🌿 Co-Founder | Gulmohar Gardens | 2025 |
| ⚙️ Data Engineer | Optum India | 2021 – 2024 |
| 💻 Software Engineer Intern | Mobisprint | 2020 |

### Highlights from Optum (3 years)
- Built scalable ETL pipelines processing **millions of healthcare records daily**, boosting aggregation efficiency by **40%**
- Migrated orchestration from Oozie → Apache Airflow, improving execution speed by **32.5%**
- Reduced data resolution time by **25%** through cross-functional data observability initiatives
- Engineered reproducible Python-based workflows with automated data quality checks and SQL-based anomaly detection

### Mobisprint Internship
- Shipped a production **Alexa skill** delivering real-time COVID-19 insights using Alexa Skill Kit + AWS Lambda
- Reduced response latency by **30%** via serverless optimization

---

## 📊 GitHub Stats

<div align="center">

![Adhyayan's GitHub Stats](https://github-readme-stats.vercel.app/api?username=adhyayanverma&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=adhyayanverma&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

</div>

---

## 🎓 Education

**New York University, Tandon School of Engineering** · *New York, USA*
MS in Computer Science · 2025 – 2027

**Birla Institute of Technology (BIT) Mesra** · *India*
BE in Computer Science & Engineering · 2017 – 2021

---

<div align="center">

*Open to Summer 2026 internships in Software Engineering, ML/AI & Data Engineering*

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adhyayanverma)
[![Email](https://img.shields.io/badge/Email%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:av4159@nyu.edu)

</div>
