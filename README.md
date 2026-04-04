<h1 align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=16FF00&height=150&section=header&text=Shuvakant%20Patra&fontSize=42&fontAlign=50&fontAlignY=35&fontColor=0A0A0A" alt="Header" />
</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=900&size=24&duration=2500&pause=600&color=16FF00&center=true&vCenter=true&multiline=true&repeat=true&width=900&lines=Data+Scientist+%2B+Infrastructure+Engineer;Rust+Systems+Builder+%F0%9F%A6%80;Compiler-first+ML+Infra;Production+%E2%9A%99%EF%B8%8F+always-on" alt="Typing intro" />
</p>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Prod%20ML%20Infra-16FF00?style=for-the-badge&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Stack-Rust%20%7C%20Python%20%7C%20Systems-16FF00?style=for-the-badge&labelColor=0A0A0A" />
  <img src="https://img.shields.io/badge/Mindset-Compiler%20%7C%20AST%20%7C%20Pipelines-16FF00?style=for-the-badge&labelColor=0A0A0A" />
</p>

---

<table align="center">
<tr>
<td align="center" width="50%">

### ⚙️ Systems Philosophy

```
Models are only as good as the infrastructure beneath them.
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
Building a Compiler-Driven Feature Store from scratch.
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

<table align="center" width="100%">
<tr>
<td align="center">

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
- Execution core for feature systems
- Real-time ML pipeline & backend compatible

`Rust` `Parsing` `Expression Trees` `Performance`

</td>
<td width="50%" valign="top">

### 🌊 Flood Susceptibility Model
**Geospatial ML system for flood risk prediction**
- Predicts flood-prone regions with high accuracy
- Inputs: rainfall, elevation, soil type, land cover
- Pipeline: ingestion → preprocessing → evaluation
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
- Production-grade inference workflows

`Python` `Time-Series` `Feature Engineering` `ML`

</td>
<td width="50%" valign="top">

### 📱 Smartphone Addiction Prediction
**Behavioral ML model for digital health analytics**
- Detects addiction patterns from behavioral signals
- Inputs: screen time, app usage, sleep cycle data
- Feature extraction from temporal behavioral logs
- Interpretable classification outputs

`Python` `Behavioral ML` `Classification` `Health`

</td>
</tr>
</table>

---

## 🧬 Core Stack 

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,python,cpp,postgres,redis,docker,kubernetes,fastapi,nginx,aws,gcp,linux,bash,git,githubactions&theme=dark" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv,aws,azure,vercel,cloudflare&theme=dark" />
</p>

---

## 🛰️ Systems I Love Designing

- 🧱 **Compiler-driven feature platforms** — DSL → AST → optimized execution plans in Rust.
- 📡 **Low-latency feature serving** — online/offline parity, skew-free by construction.
- 🧩 **Typed data contracts** — DAGs with lineage, schema evolution safety, and CI for data.
- 🚦 **Observability-first** — tracing, metrics, circuit breakers, chaos drills.
- 🕸️ **Streaming + batch harmony** — Kafka / Arrow / Parquet with reproducible jobs.
- ⚡ **Performance** — zero-cost abstractions, memory safety, fearless concurrency.

---

## 📊 Live Dashboards

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shuvakant6623&show_icons=true&theme=chartreuse-dark&bg_color=000000&border_color=16FF00&icon_color=16FF00&title_color=16FF00&text_color=CFFFFF&hide_border=false&rank_icon=github&cache_seconds=0" alt="GitHub stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shuvakant6623&layout=compact&theme=chartreuse-dark&bg_color=000000&border_color=16FF00&title_color=16FF00&text_color=CFFFFF&hide_border=false&cache_seconds=0" alt="Top languages" width="48%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=shuvakant6623&theme=chartreuse-dark&background=000000&border=16FF00&stroke=16FF00&ring=16FF00&fire=16FF00&currStreakNum=16FF00&sideNums=CFFFFF&currStreakLabel=16FF00&sideLabels=CFFFFF&dates=8BC34A" width="80%" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=shuvakant6623&theme=2077" width="92%" />
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" alt="Snake animation" width="100%" />
</p>

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdTN1Z2E2eXhlZ2V4b2tpdDRmZTFxNXA0dW83eWtsbGV0cGd1cDJlaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/26tn33aiTi1jkl6H6/giphy.gif" width="320" alt="Matrix coder" />
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
    <img src="https://img.shields.io/badge/LinkedIn-16FF00?style=for-the-badge&logo=linkedin&logoColor=0A0A0A" />
  </a>
  &nbsp;
  <a href="mailto:scientefic2612@gmail.com">
    <img src="https://img.shields.io/badge/Email-16FF00?style=for-the-badge&logo=gmail&logoColor=0A0A0A" />
  </a>
  &nbsp;
  <a href="https://leetcode.com/u/Shuvakant2809/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-16FF00?style=for-the-badge&logo=leetcode&logoColor=0A0A0A" />
  </a>
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1500&color=16FF00&center=true&vCenter=true&width=700&lines=Think+in+Systems+%E2%9A%99%EF%B8%8F+%7C+Build+in+Rust+%F0%9F%A6%80+%7C+Scale+with+Data+%F0%9F%93%8A;The+best+ML+system+is+one+that+never+breaks+in+production." alt="Footer SVG" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=16FF00&height=120&section=footer" alt="Footer" />
</p>
