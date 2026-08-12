<!--
  Kawsar Ahmmed — GitHub Profile README
  Design goal: recruiter-first, modern, visual, and technically credible.
  Replace/add LinkedIn, email, portfolio, and resume links when ready.
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:0EA5E9,100:7C3AED&height=235&section=header&text=Kawsar%20Ahmmed&fontSize=48&fontColor=FFFFFF&fontAlignY=37&desc=AI%20%2F%20Machine%20Learning%20Engineer&descSize=19&descAlignY=58&animation=fadeIn" alt="Kawsar Ahmmed header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=2700&pause=850&color=38BDF8&center=true&vCenter=true&width=780&lines=Machine+Learning+%E2%80%A2+Deep+Learning+%E2%80%A2+Computer+Vision;Agentic+AI+%E2%80%A2+RAG+%E2%80%A2+LLM+Applications;Validation-first+experimentation+%E2%80%A2+End-to-end+systems" alt="Typing SVG" />
</a>

<br/>

<a href="https://github.com/kawsar07ahmmed0712-rgb">
  <img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<!--
Add these when your URLs are ready:
<a href="YOUR_LINKEDIN_URL"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="YOUR_PORTFOLIO_URL"><img src="https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="YOUR_RESUME_URL"><img src="https://img.shields.io/badge/Resume-0F766E?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Resume" /></a>
<a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
-->

<br/><br/>

<a href="#engineering-profile">Engineering Profile</a>&nbsp;&nbsp;•&nbsp;&nbsp;
<a href="#featured-engineering">Featured Engineering</a>&nbsp;&nbsp;•&nbsp;&nbsp;
<a href="#technology-stack">Technology Stack</a>&nbsp;&nbsp;•&nbsp;&nbsp;
<a href="#engineering-workflow">Workflow</a>&nbsp;&nbsp;•&nbsp;&nbsp;
<a href="#more-selected-work">More Work</a>

</div>

---

## Engineering Profile

I build **machine learning and AI systems end to end** — from data understanding and experimental baselines to evaluation, model integration, APIs, retrieval pipelines, and usable applications.

My work spans **classical ML, deep learning, computer vision, agentic AI, and retrieval-augmented generation**. I prefer evidence over unnecessary complexity: establish a strong baseline, validate correctly, inspect failure modes, then engineer the parts that actually improve the system.

<table>
<tr>
<td width="50%" valign="top">

### Applied Machine Learning

Tabular modelling, biomedical ML, feature engineering, model comparison, cross-validation, ensemble evaluation, and leakage-aware experimentation.

</td>
<td width="50%" valign="top">

### Agentic AI & RAG

Multi-agent workflows, retrieval pipelines, vector search, grounded generation, model orchestration, and LLM-backed applications.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Deep Learning & Vision

PyTorch/TensorFlow experimentation, image classification, representation learning workflows, and model evaluation for visual tasks.

</td>
<td width="50%" valign="top">

### AI Engineering

FastAPI/Flask services, WebSocket applications, modular pipelines, Docker/Linux workflows, reproducible repositories, and system integration.

</td>
</tr>
</table>

---

## Featured Engineering

> Four projects that best represent how I work across **ML research, AI systems, RAG, deep learning, and application engineering**.

<table>
<tr>
<td width="50%" valign="top">

### 01 / InterviX Aura

**Multi-Agent AI Interview System**

A browser-based mock-interview system built around coordinated **Interviewer, Candidate, and Evaluator agents**, with real-time communication between the client and backend.

**System flow**  
`Browser` → `WebSocket` → `FastAPI` → `AutoGen Agent Team` → `Evaluator Feedback`

**Engineering focus**
- Role-specific multi-agent orchestration
- Real-time WebSocket interaction
- Dedicated evaluator-agent feedback loop
- Hosted and local model support
- Separation of model clients, agent logic, UI, and tests

`AutoGen AgentChat` `FastAPI` `WebSocket` `Gemini` `Ollama`

<a href="https://github.com/kawsar07ahmmed0712-rgb/InterviX_Aura">
  <img src="https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github&logoColor=white" alt="InterviX Aura repository" />
</a>

</td>
<td width="50%" valign="top">

### 02 / VitalVox Medical RAG

**Retrieval-Augmented Medical Assistant**

A Flask-based RAG application that converts medical PDFs into retrievable knowledge and uses source-grounded context to support LLM responses.

**RAG flow**  
`PDFs` → `Chunking` → `Embeddings` → `Pinecone` → `Retrieved Context` → `LLM Response`

**Engineering focus**
- PDF ingestion and chunking pipeline
- Pinecone-backed vector retrieval
- Source-grounded generation workflow
- Gemini + optional local Ollama support
- Multipage UI with source previews and runtime checks

`LangChain` `Pinecone` `Flask` `Gemini` `Ollama` `RAG`

<a href="https://github.com/kawsar07ahmmed0712-rgb/End_to_End_Medical_Chatbot">
  <img src="https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github&logoColor=white" alt="VitalVox Medical RAG repository" />
</a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 03 / Mechanisms of Action

**Biomedical Multi-Label Machine Learning**

An end-to-end ML workflow for predicting drug **Mechanisms of Action** from gene-expression features, cell-viability signals, and treatment metadata.

**ML flow**  
`Omics Features` → `EDA` → `Feature Engineering` → `Multi-Label Models` → `Ensemble Evaluation`

**Engineering focus**
- Multi-source biomedical feature integration
- Structured experimentation and EDA
- Feature engineering for high-dimensional data
- Multi-label modelling workflow
- Repository separation across data, notebooks, source, models, outputs, and reports

`Multi-Label Classification` `Biomedical ML` `Feature Engineering` `Ensembles`

<a href="https://github.com/kawsar07ahmmed0712-rgb/moa-prediction-drug-response">
  <img src="https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github&logoColor=white" alt="Mechanisms of Action repository" />
</a>

</td>
<td width="50%" valign="top">

### 04 / German Traffic Sign Recognition

**PyTorch Computer Vision / Image Classification**

A deep-learning image-classification project organized around a reproducible visual-recognition workflow with dedicated notebook and reusable source-code components.

**Vision flow**  
`Images` → `Preprocessing` → `PyTorch Training` → `Evaluation` → `Inference Workflow`

**Engineering focus**
- Image preprocessing pipeline
- PyTorch-based model experimentation
- Separation of exploratory notebooks and reusable code
- Training and evaluation workflow for visual recognition

`PyTorch` `Computer Vision` `Deep Learning` `Image Classification`

<a href="https://github.com/kawsar07ahmmed0712-rgb/Pytorch-German-Traffic-Sign-Recognition">
  <img src="https://img.shields.io/badge/VIEW_REPOSITORY-181717?style=for-the-badge&logo=github&logoColor=white" alt="German Traffic Sign Recognition repository" />
</a>

</td>
</tr>
</table>

---

## Technology Stack

<div align="center">

### Core Engineering

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,fastapi,flask,docker,git,github,linux,bash,vscode,anaconda&perline=12" alt="Core engineering stack" />
</a>

<br/><br/>

### ML / Data

<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
<img src="https://img.shields.io/badge/XGBoost-1F5A96?style=flat-square" alt="XGBoost" />
<img src="https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black" alt="CatBoost" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter" />
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />

### Agentic AI / RAG / LLM

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/AutoGen-2563EB?style=flat-square&logo=microsoft&logoColor=white" alt="AutoGen" />
<img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white" alt="Pinecone" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
<img src="https://img.shields.io/badge/RAG-0F766E?style=flat-square" alt="RAG" />
<img src="https://img.shields.io/badge/Vector%20Search-7C3AED?style=flat-square" alt="Vector Search" />

### Backend / Systems

<img src="https://img.shields.io/badge/REST%20APIs-0EA5E9?style=flat-square" alt="REST APIs" />
<img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSocket" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />

</div>

---

## Engineering Workflow

```mermaid
flowchart LR
    A[Problem & Metric] --> B[Data Diagnostics]
    B --> C[Strong Baseline]
    C --> D[Controlled Experiments]
    D --> E[Leakage-safe Validation]
    E --> F[Error Analysis]
    F --> G[Pipeline / API / App]
    G --> H[Iterate with Evidence]
```

<table>
<tr>
<td width="25%" align="center"><b>01</b><br/><sub>Understand the target, constraints, and metric.</sub></td>
<td width="25%" align="center"><b>02</b><br/><sub>Inspect data quality, distributions, and leakage risk.</sub></td>
<td width="25%" align="center"><b>03</b><br/><sub>Build a strong reference before adding complexity.</sub></td>
<td width="25%" align="center"><b>04</b><br/><sub>Change one meaningful thing at a time.</sub></td>
</tr>
<tr>
<td width="25%" align="center"><b>05</b><br/><sub>Validate with a split strategy that matches the problem.</sub></td>
<td width="25%" align="center"><b>06</b><br/><sub>Study errors, weak cases, and unstable behavior.</sub></td>
<td width="25%" align="center"><b>07</b><br/><sub>Turn successful experiments into reusable systems.</sub></td>
<td width="25%" align="center"><b>08</b><br/><sub>Iterate only when evidence justifies it.</sub></td>
</tr>
</table>

---

## More Selected Work

<table>
<tr>
<td width="33%" valign="top">

### Ames Price Regression

Advanced supervised regression with meaning-aware preprocessing, feature construction, cross-validation, model comparison, and ensemble modelling.

`Regression` `CatBoost` `SVR` `Stacking`

[Open repository →](https://github.com/kawsar07ahmmed0712-rgb/Ames-Price-Regression)

</td>
<td width="33%" valign="top">

### Credit Default Risk

Tabular classification project focused on structured credit-risk analysis, preprocessing, feature investigation, and predictive modelling.

`Classification` `Tabular ML` `EDA` `Risk Modelling`

[Open repository →](https://github.com/kawsar07ahmmed0712-rgb/Credit_Default_Risk)

</td>
<td width="33%" valign="top">

### Excel Analytics Dashboard

Spreadsheet analytics project for transforming structured data into an interactive dashboard and business-facing reporting workflow.

`Excel` `Dashboarding` `Analytics` `Reporting`

[Open repository →](https://github.com/kawsar07ahmmed0712-rgb/Excel_Dashboard)

</td>
</tr>
</table>

---

## GitHub Pulse

<details>
<summary><b>Open contribution activity</b></summary>
<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=kawsar07ahmmed0712-rgb&theme=tokyo-night&hide_border=true&area=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=kawsar07ahmmed0712-rgb&theme=github-compact&hide_border=true&area=true" />
  <img alt="Kawsar Ahmmed contribution activity" src="https://github-readme-activity-graph.vercel.app/graph?username=kawsar07ahmmed0712-rgb&theme=github-compact&hide_border=true&area=true" />
</picture>

</div>

</details>

<!--
OPTIONAL CONTRIBUTION SNAKE
1. Add the companion .github/workflows/snake.yml file provided with this README.
2. Run the workflow once from GitHub Actions.
3. Uncomment this block.

## Contribution Trail

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kawsar07ahmmed0712-rgb/kawsar07ahmmed0712-rgb/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kawsar07ahmmed0712-rgb/kawsar07ahmmed0712-rgb/output/github-snake.svg" />
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/kawsar07ahmmed0712-rgb/kawsar07ahmmed0712-rgb/output/github-snake.svg" />
</picture>
-->

---

## Contact

<div align="center">

**Interested in AI engineering, applied ML, RAG systems, agentic workflows, and computer vision.**

<a href="https://github.com/kawsar07ahmmed0712-rgb">
  <img src="https://img.shields.io/badge/GitHub-kawsar07ahmmed0712--rgb-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" />
</a>

<!-- Add LinkedIn / Email / Portfolio / Resume buttons here when ready. -->

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,55:0EA5E9,100:0F172A&height=120&section=footer" alt="footer" />
