<div align="center">

# Hi, I'm Bhanu 👋

### AI Engineer · LLM Systems · RAG Pipelines · Python

*Building intelligent systems that work in production — not just in notebooks.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhanupratap-bhadouria-922ba4168/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/bhanu-bhadouria)
[![Gmail](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:bhanubhadouria123@gmail.com)
[![Location](https://img.shields.io/badge/Pune%2C%20India-🇮🇳-lightgrey?style=flat)](https://github.com/bhanu-bhadouria)

</div>

---

## About me

I'm an AI Engineer at **IBM CIC**, where I've built and shipped a **production LLM** integrated into ServiceNow Virtual Agent — automating IT service resolution for enterprise clients. With 2.5 years of industry experience, my focus is on the applied side of AI: RAG pipelines, LLM integration, semantic search, and Python-based AI systems.

Before IBM, I interned at **Amdocs Innovation Lab** working on ML-driven automation for telecom operations (failed-order healing, error-recycle pipelines), and at **Spring Money** building backend APIs for a fintech app.

I hold a published paper on AI ethics (IJSRP, 2023) and Andrew Ng's Machine Learning specialisation. Right now I'm going deep on LLM engineering, MLOps, and building AI products end-to-end.

```python
bhanu = {
    "role"       : "AI Engineer (transitioning from enterprise → AI-native)",
    "current"    : "IBM CIC — LLM + ServiceNow integration",
    "interests"  : ["RAG Systems", "LLM Engineering", "NLP", "MLOps"],
    "building"   : ["IT Incident Predictor", "RAG Chatbot", "Resume Analyzer"],
    "learning"   : ["Deep Learning", "Transformers", "LangGraph", "FastAPI + ML deployment"],
    "ask_me"     : "RAG architectures, XGBoost + SHAP, or ServiceNow AI integration",
}
```

---

## 🚀 Featured Projects

### 🎯 [IT Incident Priority Predictor](https://github.com/bhanu-bhadouria/IT-Incident-priority-predictor) &nbsp;[![Live Demo](https://img.shields.io/badge/Live%20Demo-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://it-incident-priority-predictor-bpsb.streamlit.app)
> Auto-classify P1 IT incidents before manual escalation — XGBoost + SHAP explainability

**[→ Try the live demo](https://it-incident-priority-predictor-bpsb.streamlit.app)**

- End-to-end ML pipeline: EDA → feature engineering → model comparison → deployment on a **real ServiceNow-style dataset**
- Compared Decision Tree, Random Forest, and XGBoost — final model achieves **0.93 recall** and **0.76 F1** on 9:1 imbalanced data
- **SHAP explainability** surfaces per-prediction feature contributions — tells the engineer *why* a ticket was flagged, not just *that* it was
- Two-tab Streamlit app: single ticket prediction + batch CSV upload with downloadable results

`Python` `XGBoost` `SHAP` `scikit-learn` `Streamlit` `Pandas`

---

### 🤖 [RAG Chatbot with Hybrid Search](https://github.com/bhanu-bhadouria/RAG-Chatbot) &nbsp;[![Live Demo](https://img.shields.io/badge/Live%20Demo-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://rag-chatbot-bpsb.streamlit.app)
> Chat with any PDF using a ChatGPT-style interface — powered by hybrid FAISS + BM25 retrieval

**[→ Try the live demo](https://rag-chatbot-bpsb.streamlit.app)**

- Built **end-to-end RAG pipeline** from scratch: PDF ingestion → chunking → embedding → retrieval → generation
- Implemented **hybrid search** (FAISS semantic + BM25 keyword) for more robust retrieval than vector-only approaches
- Added **conversational memory** with query-history rewriting for context-aware multi-turn conversations
- Modular architecture: `ingest.py` → `retrieve.py` → `hybrid.py` → `generate.py` → `app.py`

`Python` `LangChain` `FAISS` `BM25` `Streamlit` `OpenAI API`

---

### 📄 [AI Resume Analyzer (ATS Scorer)](https://github.com/bhanu-bhadouria/Resume-Analyzer-AI)
> NLP-powered tool that scores how well your resume matches a job description — keyword + semantic similarity

- Engineered a **spaCy NLP pipeline** with lemmatisation, noise filtering, and synonym-aware normalisation
- Computed **multi-dimensional match score**: keyword overlap + skill-weighted score + sentence-embedding similarity
- Integrated **OpenAI API** to generate tailored resume improvement suggestions per job description
- Built a clean Streamlit interface with missing-keyword detection and match breakdown

`Python` `spaCy` `Sentence Transformers` `Scikit-learn` `OpenAI API` `Streamlit`

---

### 🌧️ [Rainfall & Flood Prediction](https://github.com/bhanu-bhadouria)
> Ensemble ML model predicting region-specific flood risk — 82% accuracy, deployed as a Django web app

- End-to-end pipeline from raw meteorological data to live web predictions via Django
- Targeted disaster preparedness for regions covering up to 5 million people

`Python` `Scikit-learn` `Django` `HTML/CSS`


---

## 🛠 Tech Stack

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1c3c3c?style=flat&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189733?style=flat&logo=xgboost&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-FF6B6B?style=flat&logoColor=white)

**NLP & Search**

![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat&logo=spacy&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154F5B?style=flat&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-005571?style=flat&logo=openapi-initiative&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=flat&logo=servicenow&logoColor=black)

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=bhanu-bhadouria&show_icons=true&theme=default&hide_border=true&count_private=true&include_all_commits=true" />
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhanu-bhadouria&layout=compact&theme=default&hide_border=true&langs_count=6" />

</div>

---

## 📝 Publication

**Overcoming Barriers and Promoting Responsible AI Development: Artificial Intelligence Ethical Considerations**
*IJSRP, Volume 13, Issue 9, September 2023 · ISSN 2250-3153*
[→ Read the paper](https://ijsrp.org/research-paper-0923.php?rp=P14113028)

---

## 🎓 Certifications

- **Supervised Machine Learning: Regression & Classification** — DeepLearning.AI / Coursera
- **Advanced Learning Algorithms** — DeepLearning.AI / Coursera
- **Python Mega Course Bootcamp** — Udemy
- **Azure AI Engineer Associate** *(in progress)*

---

## 💬 Let's connect

I'm actively exploring AI/ML engineering roles — particularly in LLM systems, RAG architectures, and applied NLP. If you're working on something interesting or want to talk shop, reach out.

[![LinkedIn](https://img.shields.io/badge/Let's%20connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhanupratap-bhadouria-922ba4168/)

---

<div align="center">
<sub>⭐ If any of my projects helped you, a star goes a long way!</sub>
</div>
