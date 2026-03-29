<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00FF00&center=true&vCenter=true&width=900&lines=%F0%9F%A7%A0+Shuvakant+Patra;Data+Scientist+%2B+Infrastructure+Engineer;Rust+Systems+Builder+%F0%9F%A6%80;ML+Architect+%7C+Compiler+Thinker;I+don't+build+models.+I+build+systems." alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Production%20ML%20Infrastructure-00FF00?style=for-the-badge&labelColor=000000" />
  <img src="https://img.shields.io/badge/Stack-Rust%20%2B%20Python%20%2B%20Systems-00FF00?style=for-the-badge&labelColor=000000" />
  <img src="https://img.shields.io/badge/Thinking-Compiler%20%7C%20AST%20%7C%20Pipelines-00FF00?style=for-the-badge&labelColor=000000" />
</p>

---

<table align="center">
<tr>
<td align="center" width="50%">

### ⚙️ Systems Philosophy

```
Models are only as good as
the infrastructure beneath them.

I build the infra.

Compiler → AST → Execution
Feature Store → DAG → Consistency
Data Pipeline → Scale → Reliability
Rust → Performance → Safety
```

</td>
<td align="center" width="50%">

### 🎯 Current Mission

```
Building a Compiler-Driven
Feature Store from scratch.

DSL-based feature definitions
→ Parsed into AST
→ Compiled into execution plan
→ Served with zero skew

Reproducibility. Consistency.
Production-grade, always.
```

</td>
</tr>
</table>

---

## 🔭 Primary Project — Currently Building

<table>
<tr>
<td>

### 🏗️ Compiler-Driven Feature Store

> *The hardest problem in ML isn't the model. It's the features.*

A production-grade feature store where **features are programs**, not just columns.

**Architecture:**

```
  ┌─────────────────────────────────────────────┐
  │           Feature DSL Definition            │
  │    feature("rolling_avg_7d") {              │
  │      window(7d).mean(transactions)          │
  │    }                                        │
  └────────────────────┬────────────────────────┘
                       │
                  [ PARSING ]
                       │
              ┌────────▼────────┐
              │  Abstract       │
              │  Syntax Tree    │
              └────────┬────────┘
                       │
               [ COMPILATION ]
                       │
              ┌────────▼────────┐
              │  Execution      │
              │  Plan (Rust)    │
              └────────┬────────┘
                       │
          ┌────────────▼────────────┐
          │   Online   │  Offline   │
          │  Serving   │  Training  │
          │  (no skew) │  (same fn) │
          └────────────────────────┘
```

**What it solves:**
- 🔴 Training-serving skew → eliminated at compiler level
- 🔴 Feature inconsistency → enforced via typed AST
- 🔴 Reproducibility gaps → execution plans are deterministic
- 🔴 Slow feature computation → Rust-powered engine

</td>
</tr>
</table>

---

## 🚀 Built Projects

<table>
<tr>
<td width="50%" valign="top">

### 🦀 Rust Expression Engine
**High-performance computation engine for ML feature pipelines**

- Expression parsing + evaluation from scratch
- Built entirely in Rust for maximum throughput
- Designed as the execution core for feature systems
- Real-time ML pipeline and backend compatible

`Rust` `Parsing` `Expression Trees` `Performance`

</td>
<td width="50%" valign="top">

### 🌊 Flood Susceptibility Model
**Geospatial ML system for flood risk prediction**

- Predicts flood-prone regions with high accuracy
- Inputs: rainfall, elevation, soil type, land cover
- Full pipeline: ingestion → preprocessing → evaluation
- Environmental + geospatial feature engineering

`Python` `XGBoost` `GeoSpatial` `Scikit-Learn`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ✈️ Flight Delay Prediction System
**Time-series ML system for aviation delay forecasting**

- Fuses weather, historical patterns, and congestion data
- Advanced time-series feature engineering
- Handles multi-source data pipelines
- Built for production-level inference workflows

`Python` `Time-Series` `Feature Engineering` `ML`

</td>
<td width="50%" valign="top">

### 📱 Smartphone Addiction Prediction
**Behavioral ML model for digital health analytics**

- Detects addiction patterns from behavioral signals
- Inputs: screen time, app usage, sleep cycle data
- Feature extraction from temporal behavioral logs
- Classification with interpretable outputs

`Python` `Behavioral ML` `Classification` `Health`

</td>
</tr>
</table>

---

## ⚙️ Tech Stack

### 👨‍💻 Languages

<p>
  <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/SQL-000000?style=for-the-badge&logo=postgresql&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/C++-000000?style=for-the-badge&logo=c%2B%2B&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/Shell-000000?style=for-the-badge&logo=gnu-bash&logoColor=00FF00" />
</p>

### 🤖 ML & Deep Learning

<p>
  <img src="https://img.shields.io/badge/PyTorch-000000?style=for-the-badge&logo=pytorch&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/TensorFlow-000000?style=for-the-badge&logo=tensorflow&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/Scikit--Learn-000000?style=for-the-badge&logo=scikit-learn&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/HuggingFace-000000?style=for-the-badge&logo=huggingface&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/XGBoost-000000?style=for-the-badge&logo=xgboost&logoColor=00FF00" />
</p>

### ⚙️ Infrastructure & MLOps

<p>
  <img src="https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/FastAPI-000000?style=for-the-badge&logo=fastapi&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/MLflow-000000?style=for-the-badge&logo=mlflow&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/Streamlit-000000?style=for-the-badge&logo=streamlit&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/Airflow-000000?style=for-the-badge&logo=apacheairflow&logoColor=00FF00" />
</p>

### 🛢️ Databases & Retrieval

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-000000?style=for-the-badge&logo=postgresql&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/MongoDB-000000?style=for-the-badge&logo=mongodb&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/ChromaDB-000000?style=for-the-badge&logo=databricks&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=00FF00" />
</p>

### 🤖 LLM Agents & Frameworks

<p>
  <img src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=python&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/LangGraph-000000?style=for-the-badge&logo=graphql&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/OpenAI-000000?style=for-the-badge&logo=openai&logoColor=00FF00" />
  <img src="https://img.shields.io/badge/Claude-000000?style=for-the-badge&logo=anthropic&logoColor=00FF00" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shuvakant6623&show_icons=true&theme=chartreuse-dark&bg_color=000000&border_color=00FF00&icon_color=00FF00&title_color=00FF00&text_color=CCFFCC&hide_border=false&rank_icon=github" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shuvakant6623&layout=compact&theme=chartreuse-dark&bg_color=000000&border_color=00FF00&title_color=00FF00&text_color=CCFFCC" width="38%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=shuvakant6623&theme=chartreuse-dark&background=000000&border=00FF00&stroke=00FF00&ring=00FF00&fire=00FF00&currStreakNum=00FF00&sideNums=CCFFCC&currStreakLabel=00FF00&sideLabels=CCFFCC&dates=888888" width="60%" />
</p>

---

## 📈 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=shuvakant6623&bg_color=000000&color=00FF00&line=00FF00&point=FFFFFF&area=true&area_color=003300&border_color=00FF00&title_color=00FF00" width="95%" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/shuvakant6623/shuvakant6623/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</p>

---

## 🧠 Systems Thinking Map

```
┌──────────────────────────────────────────────────────────────────────┐
│                     How I Think About Problems                       │
├──────────────────────────────────────────────────────────────────────┤
│                                                                      │
│   COMPILER LENS           SYSTEMS LENS          DATA LENS            │
│   ─────────────           ────────────          ─────────            │
│   Tokenize input          Define contracts       Source + lineage    │
│   Parse to AST            Define interfaces      Schema + types      │
│   Optimize plan           Handle failures        Transform + clean   │
│   Execute safely          Scale horizontally     Serve consistently  │
│                                                                      │
│   RUST LENS               ML INFRA LENS                              │
│   ─────────               ─────────────                              │
│   Own your memory         Features = Programs                        │
│   Zero-cost abstractions  Training ≡ Serving                         │
│   Fearless concurrency    Reproducibility first                      │
│   No undefined behavior   Monitor everything                         │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

---

## 🌱 Learning Roadmap

<table align="center">
<tr>
<td align="center">

**Now**
```
Compiler-Driven
Feature Store
(primary project)
```

</td>
<td align="center">→</td>
<td align="center">

**Next**
```
Advanced MLOps
Distributed Systems
Design Patterns
```

</td>
<td align="center">→</td>
<td align="center">

**Vision**
```
Production ML
Infrastructure
at Scale
```

</td>
</tr>
</table>

---

## 🌐 Connect

<p align="center">
  <a href="https://www.linkedin.com/in/shuvakant-patra-4b006835b" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-00FF00?style=for-the-badge&logo=linkedin&logoColor=000000" />
  </a>
  &nbsp;
  <a href="mailto:scientefic2612@gmail.com">
    <img src="https://img.shields.io/badge/Email-00FF00?style=for-the-badge&logo=gmail&logoColor=000000" />
  </a>
  &nbsp;
  <a href="https://leetcode.com/u/Shuvakant2809/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-00FF00?style=for-the-badge&logo=leetcode&logoColor=000000" />
  </a>
</p>

---

<p align="center">
  <img src="https://media.tenor.com/wQ6N85IYk4IAAAAC/matrix-hack.gif" width="380" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1500&color=00FF00&center=true&vCenter=true&width=700&lines=Think+in+Systems+%E2%9A%99%EF%B8%8F+%7C+Build+in+Rust+%F0%9F%A6%80+%7C+Scale+with+Data+%F0%9F%93%8A;The+best+ML+system+is+one+that+never+breaks+in+production." alt="Footer SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=shuvakant6623&color=00FF00&style=for-the-badge&label=PROFILE+VIEWS" />
</p>
