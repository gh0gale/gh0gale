<!-- ===================== HEADER ===================== -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:3B5BDB,100:70A5FD&height=220&section=header&text=Yash%20Ghogale&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Data%20Engineer%20%E2%80%A2%20Pipeline%20Architect%20%E2%80%A2%20AI%20Systems%20Builder&descSize=18&descAlignY=60&animation=fadeIn" width="100%" alt="header"/>
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=70A5FD&center=true&vCenter=true&width=700&height=50&lines=Pipelines+that+think.;Medallion+ETL+%E2%86%92+LangGraph+agents+%E2%86%92+live+products.;Deterministic+math.+Explainable+AI.+No+black+boxes.;B.Tech+CSE+(Data+Science)+%C2%B7+CGPA+9.05+%C2%B7+Class+of+2027" alt="typing animation"/>
  </a>
</div>

<br>

<div align="center">
  <a href="https://linkedin.com/in/yash-ghogale"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  &nbsp;
  <a href="mailto:info.ghogale@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  &nbsp;
  <a href="https://portfolio-agent-gh0gale.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=gh0gale&style=for-the-badge&color=6e40c9&label=PROFILE+VIEWS"/>
</div>

<br>

---

## `{ role: "data engineer", focus: "pipelines that think" }`

I build systems that **move, clean, model, and surface data**, with as little babysitting as possible.  
Final-year-track **B.Tech CSE (Data Science)** at **DJSCE, Mumbai** · Honors in **Computational Finance** · CGPA **9.05**

```yaml
now:
  building:   INVR (AI investment advisory + tutoring platform)
  exploring:  agentic workflows, open table formats, Databricks
  learning:   how to keep LLMs away from the math
  open_to:    Data Engineering / AI Engineering roles & internships
```

---

## `> currently building`

### 📈 INVR: *Context-aware. Mathematically grounded. No black boxes.*

An AI-powered investment advisory and tutoring platform that analyses any **NSE stock** across **4 trading timeframes** and returns an explainable verdict in **2-3 seconds**.

| | |
|---|---|
| **Scoring engine** | 20+ technical indicators · 15 weighted gates · fully deterministic |
| **Agent layer** | 5-node LangGraph workflow, LLM narration (gpt-oss-120b via Groq) in 0.5-1s |
| **Anti-hallucination** | Verdict is injected *after* inference, so the LLM never invents financial claims |
| **Tutor agent** | 4 intent-routing modes with per-user memory |
| **Feedback loop** | Compares predictions to real outcomes, flags threshold drift, retrains · **75-80% directional accuracy** over 2 years of backtesting |
| **Stack** | Medallion ETL · Supabase (Postgres) · FastAPI · ReactJS · LangChain · LangGraph |

---

## `> projects`

<table>
<tr>
<td width="50%" valign="top">

### 💸 SpendStream
*Personal-finance analytics from raw Gmail to behavioural insight*

- Categorises **300+ transactions** into **12 categories**
- Medallion data flow normalising **100+ merchants**, run by scheduled cron jobs
- TF-IDF + transformer embeddings + behavioural signals → logistic regression at **87.8% accuracy**
- Online refit loop with **~20-30ms** inference

`ETL` `Multimodal ML` `Supabase` `Gmail API` `FastAPI` `React`

</td>
<td width="50%" valign="top">

### 🚆 Travelr
*Smart multimodal commute and travel-companion matching*

- Compares Google Routes API against a custom **A\*** train router over a station graph
- **KD-tree** overlap detection finds meet points within **0.03-0.05 km**
- Live GPS over **WebSockets**, alerts pushed to **1,000+ users** at 0.4-0.6s per recommendation
- Redis caching re-runs the pipeline only on route changes

`Flutter` `Firebase` `FastAPI` `WebSockets` `Geospatial`

</td>
</tr>
</table>

<div align="center">
  <a href="https://github.com/gh0gale"><img src="https://github-readme-stats.vercel.app/api/pin/?username=gh0gale&repo=INVR&theme=tokyonight&hide_border=true" alt="INVR"/></a>
  <a href="https://github.com/gh0gale"><img src="https://github-readme-stats.vercel.app/api/pin/?username=gh0gale&repo=SpendStream&theme=tokyonight&hide_border=true" alt="SpendStream"/></a>
  <a href="https://github.com/gh0gale"><img src="https://github-readme-stats.vercel.app/api/pin/?username=gh0gale&repo=Travelr&theme=tokyonight&hide_border=true" alt="Travelr"/></a>
</div>

---

## `> experience`

**Analyst Intern · Godrej Infotech Ltd** · *Jun 2025 - Jul 2025 · Mumbai*

```text
raw feeds ──► SQL Server schemas ──► SSIS ETL (SCD) ──► SSAS OLAP cube ──► BI drill-down
   15+ entities        15+ schemas        8k+ records/day      custom hierarchies
```

- Designed relational schemas in **SQL Server (SSMS, SSIS)** for **15+ entities**, turning raw feeds into audit-ready reporting.
- Built ETL workflows with **Slowly Changing Dimensions** processing **8k+ records/day**, keeping fact and dimension integrity across classification changes.
- Extended an **SSAS OLAP cube** with custom hierarchies and calculated measures, moving business teams from SQL-request reporting to multidimensional drill-down.

---

## `> domain map`

```text
Data Engineering   ████████████████████  ETL/ELT · Medallion Architecture · Data Modeling · PySpark
                   ████████████████      Databricks · SSIS · SSMS · SSAS · Open Tables

AI / LLM Systems   ███████████████████   LangGraph · LangChain · RAG · ReAct · Prompt Engineering
                   ██████████████        Transformers · NLP · pgvector · ChromaDB · Ollama

Backend & Web      █████████████████     FastAPI · Node.js · Express · REST · ReactJS · WebSockets
                   ████████████          Postman · Redis

BI & Databases     ███████████████       PostgreSQL · MySQL · MongoDB · Firebase · OLAP · Power BI
```

---

## `> tech stack`

<div align="center">

**Languages & Core**

<img src="https://skillicons.dev/icons?i=py,c,cpp,postgres,mysql,git,linux&perline=7" alt="languages"/>

**Backend, Web & Infra**

<img src="https://skillicons.dev/icons?i=react,nodejs,express,fastapi,html,css,postman,redis,aws,vercel&perline=10" alt="web"/>

**Data & Cloud**

<img src="https://skillicons.dev/icons?i=supabase,mongodb,firebase,flutter&perline=4" alt="data"/>

<br>

<img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>

</div>

---

## `> git log`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gh0gale&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github&card_width=420" height="175" alt="stats"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gh0gale&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&card_width=320" height="175" alt="top langs"/>
</div>

<br>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=gh0gale&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&stroke=F0A500&ring=F0A500&fire=ff6b6b" width="70%" alt="streak"/>
</div>

<br>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=gh0gale&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph" width="95%" alt="activity graph"/>
</div>

<br>

<div align="center">
  <img src="/metrics_plugin_isocalendar_fullyear.svg" width="480" alt="isocalendar"/>
</div>

<br>

<!-- Snake animation: requires the GitHub Action described in the setup notes -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gh0gale/gh0gale/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/gh0gale/gh0gale/output/github-contribution-grid-snake.svg"/>
    <img alt="snake animation" src="https://raw.githubusercontent.com/gh0gale/gh0gale/output/github-contribution-grid-snake-dark.svg"/>
  </picture>
</div>

---

## `> certifications & education`

- 🎓 **B.Tech CSE (Data Science)**, DJSCE, Mumbai University · 2023-2027 · CGPA **9.05** · Honors in Computational Finance
- 🏅 **Generative AI for Data Science**, Microsoft · Sep 2026
- ☁️ **Cloud Foundations**, AWS Academy · Jun 2025

---

## `> let's connect`

Got a data pipeline that needs taming, or an AI workflow that keeps hallucinating? Say hi.

<div align="center">
  <a href="mailto:info.ghogale@gmail.com">📧 info.ghogale@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/yash-ghogale">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://portfolio-agent-gh0gale.vercel.app">Portfolio</a>
</div>

<br>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=13&pause=1000&color=F0A500&center=true&vCenter=true&width=600&lines=pipelines+over+spreadsheets.+systems+over+scripts.+always." alt="footer"/>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:70A5FD,50:3B5BDB,100:0D1117&height=100&section=footer" width="100%" alt="footer wave"/>
