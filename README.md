<div align="center">

<!-- ANIMATED HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Rishi%20Sehgal&fontSize=55&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%7C%20ML%20Researcher%20%7C%20Builder&descAlignY=60&descSize=18&animation=fadeIn" width="100%"/>

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&multiline=false&width=700&lines=Building+AI+systems+that+actually+work.;6-Agent+Equity+Research+%7C+AlphaLens;Reinforcement+Learning+%7C+RAG+%7C+LangGraph;Northeastern+University+%E2%80%94+Applied+AI+%26+ML" alt="Typing SVG" />
</a>

<br/>

<!-- SOCIAL BADGES -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rishi_Sehgal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rishisehgal)
[![GitHub](https://img.shields.io/badge/GitHub-RishiSehgal-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RishiSehgal)
[![Email](https://img.shields.io/badge/Email-sehgal.r@northeastern.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sehgal.r@northeastern.edu)
[![Portfolio](https://img.shields.io/badge/Portfolio-Coming_Soon-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](#)

<br/>

<!-- PROFILE VIEWS COUNTER -->
![Profile Views](https://komarev.com/ghpvc/?username=RishiSehgal&style=for-the-badge&color=8B5CF6&label=PROFILE+VIEWS)

</div>

---

## 🧠 About Me

```python
class RishiSehgal:
    def __init__(self):
        self.name        = "Rishi Sehgal"
        self.school      = "Northeastern University"
        self.focus       = ["Applied AI", "Machine Learning", "Agentic Systems"]
        self.currently   = "Building production-grade AI pipelines"
        self.languages   = ["Python", "JavaScript", "SQL", "Bash"]
        self.frameworks  = ["PyTorch", "LangChain", "Streamlit", "FastAPI", "React"]
        self.tools       = ["Claude Code", "MCP Servers", "GitHub Actions", "Docker"]
        self.interests   = ["Reinforcement Learning", "RAG", "LLM Orchestration"]
        self.motto       = "Ship fast. Think deep. Build things that matter."

    def greet(self):
        return "Hey 👋 — I turn AI research into real, working systems."
```

> I'm a CS student at **Northeastern University** specializing in applied AI and machine learning. I love building complete, polished systems — from RL agents to RAG pipelines — and deploying them end-to-end. If it involves agents, bandits, or LLMs, I'm probably already building it.

---

## 🚀 Featured Projects

### 📈 [AlphaLens — Multi-Agent AI Equity Research System](https://github.com/RishiSehgal/alphalens)
> *LangGraph · Multi-Agent · RAG · Financial AI · Gemini · ChromaDB*

A production-grade, 6-agent LangGraph system that replicates a full investment research desk in software — each agent maps to a real analyst role, collaborates via typed shared state, and calls live financial APIs.

- **Architecture**: 6 specialized agents — Junior Analyst, Research Associate, Quant Analyst, Risk Officer, Senior Analyst, Editor — with parallel fan-out/fan-in execution and typed shared state
- **Live Data Integrations**: SEC EDGAR, Alpha Vantage, FRED, yfinance — with 4× exponential backoff and graceful degradation
- **RAG Pipeline**: ChromaDB over SEC 10-K filings using 3,072-dim Gemini embeddings; Verification agent cross-checks narrative vs. quant data; achieved **Recall@5 = 1.00** and **Numerical Accuracy = 1.00** on AAPL/NVDA golden eval set
- **Quant Engine**: 3-stage DCF valuation (bear/base/bull), Monte Carlo simulation (10K paths, GBM), RSI/MACD technicals, Sharpe/Sortino ratios, options Greeks surface, 9-category risk scanner
- **Features**: Multi-ticker comparison, earnings transcript analysis (Whisper STT → chunk → embed), unusual options activity scanner, PDF report export, grounded Q&A with interactive charts

[![View Project](https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github)](https://github.com/RishiSehgal/alphalens)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat&logo=databricks&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat&logo=google&logoColor=white)
![SEC EDGAR](https://img.shields.io/badge/SEC_EDGAR-003087?style=flat&logo=data:image/png;base64,&logoColor=white)

---

### 🎓 [MentorIQ — RL-Powered Student Retention System](https://github.com/RishiSehgal/mentoriq-rl-student-retention)
> *Reinforcement Learning · Multi-Agent · NumPy · Streamlit*

A sophisticated 4-agent orchestration system for predicting and preventing student dropout, built from scratch in pure NumPy.

- **Algorithms**: LinUCB Contextual Bandits + Proximal Policy Optimization (PPO)
- **Architecture**: 4-layer agent hierarchy with inter-agent communication
- **Deliverables**: Full Streamlit dashboard, PDF technical report, live GitHub deployment
- **Stack**: Python · NumPy · Streamlit · Matplotlib · Scikit-learn

[![View Project](https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github)](https://github.com/RishiSehgal/mentoriq-rl-student-retention)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

---

### 📰 [GenAI News Researcher](https://github.com/RishiSehgal/genai-news-researcher)
> *RAG · LangChain · FAISS · Google Gemini*

An end-to-end RAG pipeline that ingests live news articles, builds semantic search indexes, and answers complex research questions with grounded citations.

- **Retrieval**: FAISS vector store with HuggingFace sentence embeddings
- **Generation**: Google Gemini API with LangChain orchestration
- **Interface**: Clean Streamlit UI with source attribution
- **Stack**: Python · LangChain · FAISS · HuggingFace · Gemini API · Streamlit

[![View Project](https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github)](https://github.com/RishiSehgal/genai-news-researcher)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat&logo=google&logoColor=white)

---

## 🛠️ Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### AI / ML
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### Frameworks & Tools
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1B2A?style=for-the-badge&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logo=databricks&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Dev & Agentic Tools
![Claude Code](https://img.shields.io/badge/Claude_Code-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=RishiSehgal&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=A78BFA&icon_color=A78BFA&text_color=ffffff"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RishiSehgal&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=A78BFA&text_color=ffffff"/>

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=RishiSehgal&theme=tokyonight&hide_border=true&background=0d1117&stroke=A78BFA&ring=A78BFA&fire=FF6B6B&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=A78BFA&sideLabels=A78BFA&dates=888888)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=RishiSehgal&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8)

</div>

---

## 📈 Contribution Graph

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=RishiSehgal&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=A78BFA&line=A78BFA&point=ffffff)

</div>

---

## 🎯 Current Focus

```
🔬  Exploring multi-agent LLM orchestration frameworks
🤖  Deepening expertise in agentic AI tooling (Claude Code, MCP)
📦  Building and deploying production-ready ML pipelines
🧪  Experimenting with RLHF and preference-based optimization
🌐  Connecting research papers → working implementations
```

---

## 🤝 Let's Connect

<div align="center">

I'm always open to collaborating on interesting AI/ML projects, discussing research, or just talking shop.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rishisehgal)
[![Email Me](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sehgal.r@northeastern.edu)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RishiSehgal)

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>

*"The best way to predict the future is to build it."*

</div>
