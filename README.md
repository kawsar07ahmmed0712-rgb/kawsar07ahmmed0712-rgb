<div align="center">

# Kawsar Ahmmed

### AI / Machine Learning Engineer

**Machine Learning · Deep Learning · Agentic AI · RAG · Computer Vision · Data Analytics**

Research-driven AI engineering with a focus on **experimentation, reliable evaluation, and end-to-end system building**.

[Profile](#profile) · [Projects](#selected-work) · [Expertise](#technical-expertise) · [Workflow](#engineering-workflow) · [Focus](#current-focus) · [Contact](#contact)

</div>

---

## Profile

> [!NOTE]
> I work across **classical machine learning, deep learning, computer vision, agentic AI, and retrieval-augmented generation**.  
> My goal is not just to train models, but to understand the data, validate decisions properly, and turn successful experiments into usable systems.

### Engineering Principles

| Focus | How I approach it |
|---|---|
| **Research** | Strong baselines, structured experiments, feature and model comparison |
| **Evaluation** | Cross-validation, leakage awareness, error analysis, reliable metrics |
| **Engineering** | Reproducible pipelines, modular code, APIs, and practical applications |

> **Core workflow**  
> `Problem` → `Data` → `Baseline` → `Experiment` → `Validate` → `Analyze` → `Engineer`

---

# Selected Work

## ◆ Machine Learning

<table>
<tr>
<td>

### 01 · Mechanisms of Action — Drug Response Prediction

**Biomedical Multi-Label Machine Learning**

A complete machine learning workflow for predicting drug **Mechanisms of Action (MoA)** using gene-expression features, cell-viability features, treatment metadata, feature engineering, multi-label modelling, and ensemble evaluation.

**Focus**  
`Multi-Label Classification` · `Biomedical ML` · `Feature Engineering` · `Ensemble Evaluation`

**Project highlights**
- Integrated gene-expression, cell-viability, and treatment-related features
- Structured the workflow around EDA, feature engineering, modelling, and evaluation
- Organized the repository into data, notebooks, source code, models, outputs, and reports

[**Explore repository →**](https://github.com/kawsar07ahmmed0712-rgb/moa-prediction-drug-response)

<details>
<summary><strong>Technical scope</strong></summary>

<br/>

- Data integration
- Exploratory data analysis
- Feature engineering
- Multi-label model training
- Ensemble-oriented final evaluation
- Separate `src/`, `models/`, `outputs/`, and `reports/` components

</details>

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td>

### 02 · Ames House Price Regression

**Advanced Regression & Feature Engineering**

An end-to-end supervised regression project for predicting house sale prices from the **Ames Housing** dataset, with emphasis on preprocessing, feature construction, cross-validation, model comparison, and ensemble modelling.

**Focus**  
`Regression` · `Cross-Validation` · `Feature Engineering` · `CatBoost` · `SVR` · `Stacking`

**Project highlights**
- Meaning-aware missing-value handling and outlier analysis
- Engineered area, bathroom, age, remodeling, and presence-indicator features
- Compared multiple linear, kernel, boosting, and ensemble approaches
- Used cross-validation with RMSE / log-RMSE evaluation

[**Explore repository →**](https://github.com/kawsar07ahmmed0712-rgb/Ames-Price-Regression)

<details>
<summary><strong>Technical scope</strong></summary>

<br/>

Selected engineered features include:

`TotalSF` · `TotalBathrooms` · `HouseAge` · `RemodAge` · `GarageAge` · `TotalPorchSF`

The repository separates exploratory work, feature engineering, model training, research notes, deployment artifacts, and tests.

</details>

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td>

### 03 · Credit Default Risk

**Tabular Classification & Risk Modelling**

A machine learning project focused on analysing and modelling **credit default risk** from structured tabular data.

**Focus**  
`Classification` · `Tabular ML` · `EDA` · `Risk Modelling`

**Project highlights**
- Exploratory analysis of structured credit-risk data
- Data preprocessing and feature-level investigation
- Classification-oriented model development
- Notebook-based experimentation with supporting analysis reports

[**Explore repository →**](https://github.com/kawsar07ahmmed0712-rgb/Credit_Default_Risk)

</td>
</tr>
</table>

---

## ◉ Deep Learning

<table>
<tr>
<td>

### German Traffic Sign Recognition

**PyTorch Computer Vision / Image Classification**

A deep learning project for **German traffic-sign recognition**, structured with dedicated notebook and source-code components.

**Focus**  
`PyTorch` · `Computer Vision` · `Deep Learning` · `Image Classification`

**Project highlights**
- Image preprocessing and classification workflow
- PyTorch-based experimentation
- Separation between exploratory notebooks and reusable source code
- Model-training and evaluation workflow for visual recognition

[**Explore repository →**](https://github.com/kawsar07ahmmed0712-rgb/Pytorch-German-Traffic-Sign-Recognition)

</td>
</tr>
</table>

---

## ⬡ Agentic AI

<table>
<tr>
<td>

### InterviX Aura

**Multi-Agent AI Interview System**

A mock-interview application built with **FastAPI, WebSocket, and AutoGen AgentChat**, using three coordinated AI roles: **Interviewer, Candidate, and Evaluator**.

**Focus**  
`AutoGen AgentChat` · `FastAPI` · `WebSocket` · `Gemini` · `Ollama`

**Project highlights**
- Role-specific multi-agent interview workflow
- Real-time browser communication through WebSocket
- Feedback generated by a dedicated evaluator agent
- Support for hosted and local LLM providers
- Separate model-client, agent-team, UI, and testing components

[**Explore repository →**](https://github.com/kawsar07ahmmed0712-rgb/InterviX_Aura)

<details>
<summary><strong>System structure</strong></summary>

<br/>

- `app.py` — FastAPI application and WebSocket endpoint
- `interview_team.py` — AutoGen agents and team logic
- `llm_clients.py` — Gemini / Ollama model clients
- `templates/` and `static/` — browser interface
- `tests/` — application tests

</details>

</td>
</tr>
</table>

---

## ▣ Data Analysis

<table>
<tr>
<td>

### Excel Analytics Dashboard

**Spreadsheet Analytics & Visual Reporting**

An Excel-based data-analysis project centered on turning structured data into an interactive dashboard and business-style reporting experience.

**Focus**  
`Microsoft Excel` · `Dashboarding` · `Data Analysis` · `Visual Reporting`

**Project highlights**
- Spreadsheet-based analytical workflow
- Dashboard-oriented reporting
- Interactive data exploration
- Business-facing presentation of structured information

[**Explore repository →**](https://github.com/kawsar07ahmmed0712-rgb/Excel_Dashboard)

</td>
</tr>
</table>

---

## ◇ RAG & LLM Systems

<table>
<tr>
<td>

### VitalVox Medical RAG

**Retrieval-Augmented Medical Assistant**

A Flask-based medical RAG application with **Pinecone-backed document retrieval**, Gemini and Ollama model support, source previews, and runtime health checks.

**Focus**  
`LangChain` · `Pinecone` · `Flask` · `Gemini` · `Ollama` · `RAG`

**Project highlights**
- PDF ingestion and chunking pipeline
- Pinecone vector indexing and retrieval
- Source-grounded response workflow
- Gemini and optional local Ollama model support
- Multipage web UI with chat workspace and source previews

[**Explore repository →**](https://github.com/kawsar07ahmmed0712-rgb/End_to_End_Medical_Chatbot)

<details>
<summary><strong>RAG pipeline</strong></summary>

<br/>

`Medical PDFs` → `Chunking` → `Embeddings` → `Pinecone Index` → `Relevant Context` → `LLM Response`

The application separates ingestion/indexing from runtime retrieval and generation, and supports both hosted and local model configurations.

</details>

</td>
</tr>
</table>

---

# Technical Expertise

### ◆ Machine Learning & Data
`Python` · `Scikit-learn` · `XGBoost` · `CatBoost` · `Pandas` · `NumPy`

### ◉ Deep Learning & NLP
`PyTorch` · `TensorFlow` · `Transformers`

### ⬡ LLM / Agentic AI / RAG
`LangChain` · `AutoGen` · `Pinecone` · `Gemini` · `Ollama`

### ◇ Backend & Applications
`FastAPI` · `Flask` · `REST APIs` · `WebSocket`

### ▣ Analytics & Workflow
`Jupyter Notebook` · `Microsoft Excel` · `SQL`

### ⌘ Engineering
`Git` · `GitHub` · `Docker` · `Linux`

---

# Engineering Workflow

> [!TIP]
> I prefer to increase complexity only when experiments justify it.

| Step | Objective |
|---|---|
| **01 · Understand** | Define the objective, target, constraints, and evaluation metric |
| **02 · Diagnose** | Inspect distributions, missing values, feature behaviour, class balance, and potential leakage |
| **03 · Baseline** | Build a simple, strong reference model before adding complexity |
| **04 · Experiment** | Improve features, representations, models, retrieval, or orchestration in controlled iterations |
| **05 · Validate** | Use appropriate validation strategies instead of relying on a single convenient split |
| **06 · Analyze** | Inspect failure cases, unstable behaviour, weak features, and model blind spots |
| **07 · Engineer** | Convert successful experiments into reproducible pipelines, APIs, or complete applications |

---

# Current Focus

<table>
<tr>
<td width="50%">

### Research & Modelling
- Advanced machine learning
- Model evaluation
- Deep learning
- Computer vision
- Error analysis

</td>
<td width="50%">

### AI Systems
- Agentic AI
- Multi-agent systems
- Retrieval-Augmented Generation
- Hybrid retrieval and reranking
- Grounded LLM applications

</td>
</tr>
</table>

---

# Project Index

| Project | Domain | Repository |
|---|---|---|
| **Mechanisms of Action — Drug Response** | Machine Learning | [Open →](https://github.com/kawsar07ahmmed0712-rgb/moa-prediction-drug-response) |
| **Ames House Price Regression** | Machine Learning | [Open →](https://github.com/kawsar07ahmmed0712-rgb/Ames-Price-Regression) |
| **Credit Default Risk** | Machine Learning | [Open →](https://github.com/kawsar07ahmmed0712-rgb/Credit_Default_Risk) |
| **German Traffic Sign Recognition** | Deep Learning / CV | [Open →](https://github.com/kawsar07ahmmed0712-rgb/Pytorch-German-Traffic-Sign-Recognition) |
| **InterviX Aura** | Agentic AI | [Open →](https://github.com/kawsar07ahmmed0712-rgb/InterviX_Aura) |
| **Excel Analytics Dashboard** | Data Analysis | [Open →](https://github.com/kawsar07ahmmed0712-rgb/Excel_Dashboard) |
| **VitalVox Medical RAG** | RAG / LLM | [Open →](https://github.com/kawsar07ahmmed0712-rgb/End_to_End_Medical_Chatbot) |

---

# Contact

**GitHub** — [kawsar07ahmmed0712-rgb](https://github.com/kawsar07ahmmed0712-rgb)  
**LinkedIn** — `Add your LinkedIn URL`  
**Email** — `Add your email`  
**Portfolio** — `Add your portfolio URL`

---

<div align="center">

### Build carefully · Validate properly · Engineer systems that work

<sub>Machine Learning · Deep Learning · Agentic AI · RAG · Computer Vision · Data Analytics</sub>

</div>
