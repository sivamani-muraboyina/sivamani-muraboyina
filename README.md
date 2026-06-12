<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100=0f3460&height=200&section=header&text=Sivamani%20Muraboyina&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=GenAI%20Engineer%20%C2%B7%20RAG%20Systems%20%C2%B7%20LLM%20Applications&descAlignY=58&descSize=16" width="100%"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sivamanimuraboyina-5873b52a7)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sivamani.m23@iiits.in)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com)
[![Portfolio](https://img.shields.io/badge/Live%20Projects-00C7B7?style=for-the-badge&logo=streamlit&logoColor=white)](#-deployed-projects)

![Profile Views](https://komarev.com/ghpvc/?username=sivamani-muraboyina&color=0f3460&style=for-the-badge&label=Profile+Views)

</div>

---

## 🧠 About Me

```python
class SivamaniMuraboyina:
    role        = "GenAI Engineer (Fresher)"
    institute   = "IIIT Sri City — B.Tech AI & Data Science (2023–2027)"
    cgpa        = 7.78

    stack = {
        "GenAI"  : ["RAG", "LLMs", "LangChain", "FAISS", "BM25", "Groq API",
                    "Prompt Engineering", "Sentence Transformers"],
        "ML"     : ["Scikit-learn", "Feature Engineering", "EDA", "Pandas", "NumPy"],
        "Web"    : ["FastAPI", "Flask", "Streamlit", "Pydantic"],
        "DevOps" : ["Docker", "Git", "GitHub", "Hugging Face", "Streamlit Cloud"],
    }

    deployed_apps = ["ClaimLenZ 🏥", "DocMind 📄"]
    achievement   = "Top 5 — IIITS'26 National Hackathon 🏆"
    open_to       = ["GenAI Internships", "LLM Engineering Roles", "Applied AI Roles"]
```

---

## 🚀 Deployed Projects

<table>
<tr>
<td width="50%" valign="top">

### 🏥 ClaimLenZ
> AI-powered OPD insurance claim adjudication · Built for Plum

[![Live App](https://img.shields.io/badge/Live%20App-00C7B7?style=flat-square&logo=streamlit&logoColor=white)](https://claimlenz-for-plum-by-siva.streamlit.app)
[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sivamani-muraboyina/ClaimLenZ)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

Parses OPD claim documents, applies insurance policy rules, and adjudicates claims — approved, rejected, or flagged — with reasoning. Deployed on Streamlit Cloud.

**Key features:**
- 📋 Policy rule engine with structured reasoning
- ✅ Multi-outcome adjudication (approve / reject / flag)
- 🔍 Groq LLM-powered claim parsing
- ☁️ Live on Streamlit Cloud

</td>
<td width="50%" valign="top">

### 📄 DocMind
> Conversational PDF intelligence via Hybrid RAG

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sivamani-muraboyina/DOCMIND)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logoColor=white)

Natural language Q&A over PDFs using a Hybrid RAG pipeline — FAISS dense search + BM25 sparse search fused via Reciprocal Rank Fusion (RRF), with cross-encoder reranking.

**Key features:**
- 🔀 RRF fusion — dense + sparse retrieval
- 🎯 Cross-encoder reranking for precision
- 🗂️ Session-based index management
- 💬 Source-attributed multi-turn Q&A

</td>
</tr>
</table>

---

## 🏗️ DocMind Architecture

```
PDF Input
    │
    ▼
┌─────────────────────────────────────────────────────────────┐
│                    Document Classifier                       │
│            (selects chunking strategy by doc type)          │
└───────────────────────┬─────────────────────────────────────┘
                        │
          ┌─────────────┴──────────────┐
          ▼                            ▼
  ┌──────────────┐            ┌──────────────┐
  │  FAISS Index │            │  BM25 Index  │
  │ (dense embed)│            │(sparse keyword│
  └──────┬───────┘            └──────┬───────┘
         │                           │
         └─────────┬─────────────────┘
                   ▼
         ┌──────────────────┐
         │  Reciprocal Rank │
         │  Fusion  (RRF)   │
         └────────┬─────────┘
                  ▼
         ┌──────────────────┐
         │  Cross-Encoder   │
         │   Reranking      │
         └────────┬─────────┘
                  ▼
         ┌──────────────────┐
         │   Groq LLM       │
         │ (answer + source │
         │  attribution)    │
         └────────┬─────────┘
                  ▼
         Multi-turn Q&A Response
```

---

## 🛠️ Tech Stack

<div align="center">

**GenAI & LLM**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Sentence Transformers](https://img.shields.io/badge/Sentence_Transformers-8A2BE2?style=for-the-badge&logoColor=white)

**ML & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Web & API**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=sivamani-muraboyina&show_icons=true&theme=tokyonight&hide_border=true&count_private=false" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sivamani-muraboyina&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&hide=jupyter%20notebook" height="165"/>
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=sivamani-muraboyina&theme=tokyonight&hide_border=true" width="60%"/>
</div>

---

## 🏆 Highlights

| Achievement | Details |
|---|---|
| 🥇 **IIITS'26 National Hackathon** | Top 5 Most Promising Ideas — AI Trip Planner for business & leisure travel |
| 🏥 **ClaimLenZ** | Deployed AI adjudication tool — built as technical assignment for Plum |
| 📄 **DocMind** | Hybrid RAG system with RRF fusion + cross-encoder reranking |
| 🎓 **IIIT Sri City** | B.Tech AI & Data Science · CGPA 7.78 |
| 📚 **Class XII** | 98.3% — VIT Junior College |

---

## 📌 Pinned Repos — What to Look At

| Repo | What it shows |
|---|---|
| [`ClaimLenZ`](https://github.com/sivamani-muraboyina/ClaimLenZ) | End-to-end GenAI deployment · policy rule engine · Groq LLM |
| [`DOCMIND`](https://github.com/sivamani-muraboyina/DOCMIND) | Hybrid RAG · FAISS + BM25 · RRF fusion · FastAPI backend |
| [`LoanEligibilityPrediction`](https://github.com/sivamani-muraboyina/LoanEligibilityPrediction) | ML pipeline · feature engineering · Docker · Streamlit |
| [`HousePricePrediction`](https://github.com/sivamani-muraboyina/HousePricePrediction) | Ridge Regression · end-to-end web app · Scikit-learn |

---

<div align="center">

**Open to GenAI, LLM Engineering, and Applied AI roles — internships & full-time**

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sivamanimuraboyina-5873b52a7)
[![Email](https://img.shields.io/badge/Email%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sivamani.m23@iiits.in)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=100&section=footer" width="100%"/>

</div>
