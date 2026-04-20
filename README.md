<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Kavyanjali%20Karan&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Data%20Analyst%20%7C%20ML%20Developer%20%7C%20GenAI%20Applications&descAlignY=58&descColor=a78bfa" alt="header"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kavyanjali-karan)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:karankavyanjali77@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karankavyanjali77-sys)
![Profile Views](https://komarev.com/ghpvc/?username=karankavyanjali77-sys&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS)

</div>

---

## 👩‍💻 About Me

> **Data Analyst & ML Developer** who builds and deploys real, working AI systems — not just notebooks.

I'm a Computer Science undergraduate at ITER, SOA University (graduating 2027), selected for **McKinsey Forward Program**, **Google Gen AI Academy APAC**, and **Guidewire Hackathon** (2026) — and a **Round 2 qualifier at L&T Technology Services Techgium** national hackathon (Oct 2025).

My work spans RAG-based LLM systems, ML pipelines, business intelligence dashboards, and funnel analytics — all deployed end-to-end.

- 🔭 Currently building **Churn Autopsy** — a production-style churn prediction system with a FastAPI inference layer and SHAP explainability
- 🧠 Exploring **LLMs, vector databases, and agentic AI architectures**
- 📊 Building analytics tools that translate raw data into business decisions
- 📍 Based in **India** — open to Data Analyst / Junior Data Scientist internships & fresher roles (India & International)

---

## 🏆 Achievements & Recognition

| Programme | Organisation | Year |
|---|---|---|
| Forward Program — Selected Participant | McKinsey & Company | 2026 |
| Gen AI Academy APAC — Selected Participant | Google | 2026 |
| Guidewire Hackathon — Seed 2 Phase | Guidewire Software | 2026 |
| Techgium National Hackathon — Round 2 Qualifier | L&T Technology Services | Oct 2025 |

---

## 🚀 Featured Projects

### 🔬 [Churn Autopsy](https://github.com/karankavyanjali77-sys/churn-autopsy)
> *Why customers leave — predicted before they do*

**Stack:** `Python` · `Scikit-learn` · `SMOTE` · `SHAP` · `FastAPI` · `Streamlit` · `Joblib` · `Pydantic`

**Highlights:**
- 🧠 Trained Logistic Regression vs Random Forest vs Gradient Boosting — best model selected via 5-fold stratified CV (ROC-AUC: **0.744**)
- ⚖️ SMOTE oversampling inside the pipeline to handle 33% class imbalance — test set never touched
- 🔌 Served predictions via **FastAPI REST endpoint** (`POST /predict`) returning churn probability + top-3 SHAP explanations + business retention action per customer
- 📊 Interactive Streamlit dashboard consuming the API — risk banner, probability bar, SHAP reason cards, recommended intervention
- 🏗️ Production-style separation: `src/train.py` → `models/churn_pipeline.pkl` → `api/main.py` → `app.py`

---

### 🤖 [RAG PDF Chatbot](https://github.com/karankavyanjali77-sys/ai-pdf-rag-chatbot)
> *Ask questions over any PDF in natural language — powered by a full RAG pipeline*

**Stack:** `Python` · `LangChain` · `FAISS` · `Sentence Transformers` · `Groq LLM` · `Streamlit` · `PyPDF`

**Highlights:**
- 📄 Multi-PDF ingestion with semantic chunking
- 🔍 FAISS vector store for fast similarity search
- 💬 Context-aware Q&A with source-page citation
- ⚡ Groq LLM for low-latency inference — answers across 100-page documents in under 5 seconds
- 🖥️ Deployed chat-style UI via Streamlit

---

### 📊 [AI-Powered Customer Segmentation Dashboard](https://github.com/karankavyanjali77-sys/customer-segmentation-ml)
> *Production-deployed ML pipeline with real-time cluster predictions*

**Stack:** `Python` · `Scikit-learn` · `KMeans` · `Pandas` · `Joblib` · `Streamlit` · `Matplotlib`

**Highlights:**
- 🧮 StandardScaler + KMeans (5 clusters) pipeline with Joblib model persistence — iterated across 72 commits
- 📈 Named business profiles: VIP · Upsell Targets · Retention Risk · Budget Loyalists · Discount Seekers
- 💡 Dashboard auto-generates segment-specific marketing recommendations at prediction time
- 📥 Downloadable CSV prediction reports

---

### 🧠 [Mental Health & Remote Work EDA](https://github.com/karankavyanjali77-sys/-mental-health-eda)
> *5,000-row employee survey → 6 publication-quality charts → HR policy brief*

**Stack:** `Python` · `Pandas` · `Seaborn` · `Plotly` · `Jupyter Notebooks`

**Highlights:**
- 📋 76.1% of employees reported a mental health condition; 51.1% lacked employer resources
- 📉 Stress rates highest in Finance (35.6%), Healthcare (35.3%), Education (34.5%)
- 📝 Findings structured as a 4-recommendation HR policy brief written for a non-analytical audience

---

### 📈 [SaaS Funnel Conversion Intelligence Tool](https://github.com/karankavyanjali77-sys/saas_funnel_project)
> *Track user drop-off across 4 product lifecycle stages*

**Stack:** `Python` · `Pandas` · `Plotly`

**Highlights:**
- 📉 63.7% of users dropped at Site Visit → Sign-Up — identified as the single highest-leverage intervention point
- 📱 Mobile conversion (0.6%) trailed desktop (4.2%) by 3.6 percentage points — representing **$8,828 in recoverable monthly revenue**
- 📊 Output structured as a one-page prioritisation brief written for a product manager

---

### 🛒 [E-Commerce Sales Analytics Dashboard](https://github.com/karankavyanjali77-sys/ecommerce_analytics)
> *Revenue seasonality, top-SKU identification, and regional patterns*

**Stack:** `Python` · `Pandas` · `Plotly` · `SQL`

**Highlights:**
- 📦 SQL window functions and CTEs to identify top-margin SKUs driving disproportionate returns across 8 categories
- 🗺️ Regional revenue pattern analysis via interactive Plotly dashboards
- 💰 Monthly trend and category-mix views structured for a category manager audience

---

### 📁 [CSV Data Analyzer Pro](https://github.com/karankavyanjali77-sys/csv-data-analyzer)
> *Automated dataset profiling — no code required for the end user*

**Stack:** `Python` · `Pandas` · `Streamlit` · `Plotly`

**Highlights:**
- 🔍 Flags implicit nulls, mixed column types, and silent zero-inflation — anomalies visual inspection misses
- 📊 One-click stakeholder-ready Excel/CSV report generation
- ⏱️ Reduces a 30+ minute manual profiling process to a single file upload

---

## 🛠️ Tech Stack

### AI & Machine Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-8B0000?style=flat-square&logo=python&logoColor=white)

### Data & Analytics
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=flat-square&logo=matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square&logo=python&logoColor=white)

### BI & Deployment
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

### Tools & Cloud
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=karankavyanjali77-sys&theme=midnight-purple&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=karankavyanjali77-sys&theme=midnight-purple&hide_border=true&include_all_commits=true&count_private=true&layout=compact" />

</div>

<div align="center">

![Streak](https://nirzak-streak-stats.vercel.app/?user=karankavyanjali77-sys&theme=midnight-purple&hide_border=true)

</div>

---

## 🏗️ What Sets Me Apart

| Strength | Evidence |
|---|---|
| **Ships production-style systems** | Churn Autopsy: training pipeline → REST API → dashboard — 3 independent layers |
| **Explains ML decisions** | SHAP per-customer explanations — not just global feature importance |
| **Translates data into decisions** | Mental Health EDA → HR policy brief; Funnel tool → $8,828 revenue opportunity identified |
| **Selected by global organisations** | McKinsey · Google · Guidewire · L&T Technology Services |
| **Builds for real users** | All deployed apps have clean UIs designed for non-technical audiences |
| **End-to-end ML engineering** | train.py → .pkl → FastAPI endpoint → Streamlit UI |

---

## 📬 Let's Connect

Actively seeking **Data Analyst / Junior Data Scientist / ML Engineer** internships and fresher roles — open to India and international opportunities.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kavyanjali-karan)
[![Email](https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:karankavyanjali77@gmail.com)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" alt="footer"/>

*"Build things that are useful. Then make them better."*

</div>
