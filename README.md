<div align="center">

# Yash Ghogale

**I build data pipelines, then stop LLMs from touching the math.**

Mumbai · B.Tech CSE (Data Science), DJSCE · CGPA 9.05 · Honors in Computational Finance

[LinkedIn](https://linkedin.com/in/yash-ghogale) · [Portfolio](https://portfolio-agent-gh0gale.vercel.app) · [info.ghogale@gmail.com](mailto:info.ghogale@gmail.com)

<br>

<img src="assets/pipeline.svg" width="100%" alt="Raw data flows through bronze, silver and gold layers into a deterministic engine, then an LLM narrates the verdict"/>

</div>

---

## The idea I keep coming back to

Most "AI" products let the model do everything: fetch, calculate, decide, explain. That's where hallucinations come from.

I build the other way around. **Data engineering produces the truth. Deterministic code makes the decision. The LLM only explains it.** Each layer is testable on its own, and the model never gets the chance to invent a number.

Every project below is a version of that.

---

## INVR: stock analysis you can audit

*Live demo · July 2026 · [the thing I'm most proud of]*

Type in any NSE stock. In 2-3 seconds you get a verdict across 4 trading timeframes, plus a plain-English explanation of why.

```
              ┌─ 20+ technical indicators
 price data ──┤                                ┌─ deterministic verdict (no LLM)
 (medallion   └─ 15 weighted gates ────────────┤
  ETL)                                         └─ LangGraph (5 nodes)
                                                    │
                                                    ▼
                           LLM writes the narration (0.5-1s),
                           verdict injected AFTER inference
```

**Decisions I'd defend in an interview**

- **The verdict is injected after the LLM runs.** The model writes around the numbers and never generates them, so it can't hallucinate a financial claim.
- **15 weighted gates instead of one opaque score.** Any verdict can be traced to the exact gates that fired.
- **A feedback loop that checks itself.** Predictions are compared with real market outcomes, threshold drift is flagged, and the system retrains. Backtested over 2 years at **75-80% directional accuracy**.
- **A tutor mode, not just a verdict.** Four intent-routing modes with per-user memory, so it teaches instead of just answering.

`Supabase (Postgres)` `FastAPI` `ReactJS` `LangChain` `LangGraph` `Groq (gpt-oss-120b)`

---

## SpendStream: your inbox, turned into spending behaviour

*Live demo · March 2026*

Connects to Gmail, extracts transactions, and shows where the money actually goes.

- **300+ transactions** sorted into **12 categories**, with **100+ merchants** normalised through a medallion flow on scheduled cron jobs
- A classifier that blends **TF-IDF + transformer embeddings + behavioural signals** through logistic regression, reaching **87.8% accuracy**
- Corrections feed back into an online refit loop, and inference stays at **~20-30 ms**

*Why logistic regression and not a bigger model?* At 20-30 ms on a small, noisy dataset, a simple model on good features beat complexity I couldn't justify.

`Gmail API` `Supabase (PostgreSQL)` `FastAPI` `ReactJS` `Multimodal ML`

---

## Travelr: finding people going your way

*Demo folder · December 2025*

Picks the fastest of 3 travel modes (bus, train, private) and matches you with companions on overlapping routes.

- Pits the **Google Routes API** against a **custom A\* router** over a train station graph and picks the faster result
- **KD-tree** overlap detection places meet points within **0.03-0.05 km**
- **WebSocket** GPS tracking with binary-search event lookup and traffic-aware ETAs, pushing alerts to **1,000+ users** at 0.4-0.6 s per recommendation
- **Redis** re-runs the pipeline only when a route actually changes

`Flutter` `Firebase` `FastAPI` `WebSockets` `Geospatial`

---

## Where I learned to do this properly

**Analyst Intern, Godrej Infotech** · Jun-Jul 2025

Real enterprise data across **15+ business entities**:

- Designed relational schemas in SQL Server and turned raw feeds into audit-ready reporting
- Built SSIS ETL with **Slowly Changing Dimensions** on **8k+ records/day**, so historical reports stayed correct even when classifications changed
- Extended an **SSAS OLAP cube** with custom hierarchies and calculated measures, moving teams from "send me a SQL query" to self-serve drill-down

This is where "garbage in, garbage out" stopped being a slogan for me. INVR's medallion layers come straight from it.

---

## Toolbox

| | |
|---|---|
| **Data engineering** | ETL/ELT · medallion architecture · data modeling · PySpark · Databricks · SSIS · SSAS |
| **AI systems** | LangGraph · LangChain · RAG · ReAct agents · Transformers · NLP · pgvector · ChromaDB |
| **Backend** | FastAPI · Node.js · Express · REST · WebSockets · Redis |
| **Frontend** | React · HTML/CSS · Flutter |
| **Databases** | PostgreSQL · MySQL · MongoDB · Firebase · SQL Server |
| **Languages** | Python · C · C++ · SQL |
| **Cloud / tools** | AWS · Git · Postman |

**Certifications:** Generative AI for Data Science (Microsoft, 2026) · Cloud Foundations (AWS Academy, 2025)

---

## Now

- Building INVR out further: more timeframes, better drift detection
- Going deeper on Databricks and open table formats
- Looking for **data engineering / AI engineering** roles and internships. If you have a messy data problem, [email me](mailto:info.ghogale@gmail.com).

<br>

<div align="center">
  <sub>pipelines over spreadsheets. systems over scripts. always.</sub>
</div>
