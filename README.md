<div align="center">

# hey, I'm Yash 👋

### I make messy data trustworthy, then let AI explain it.

<img src="assets/pipeline.svg" width="100%" alt="data flows through bronze, silver, gold into a deterministic engine, then an LLM narrates"/>

</div>

<br>

I'm a student in Mumbai who got a little obsessed with one question:

> **Why do AI products confidently say wrong things, and how do you build one that can't?**

My answer so far: don't let the model near the numbers. Clean the data properly, let plain code make the decision, and use the LLM only to explain it in human words. Everything I build is another attempt at that.

<br>

## things I've built

### 📈 [INVR](https://github.com/gh0gale): a stock advisor that can't make up numbers
Type in any NSE stock and get a verdict plus an explanation. The scoring is completely deterministic. The LLM never sees the verdict until after it has written its part, and then the real result is slotted in. It checks itself against what the market actually did, too.
<br>`FastAPI · LangGraph · Supabase · React` · **[live demo →](https://portfolio-agent-gh0gale.vercel.app)**

### 💸 [SpendStream](https://github.com/gh0gale): where does my money actually go?
It reads your Gmail, finds the transactions, and tells you what your spending says about you. Every correction you make teaches the classifier, and it still answers in ~25 ms.
<br>`Gmail API · Supabase · scikit-learn · React` · **[live demo →](https://portfolio-agent-gh0gale.vercel.app)**

### 🚆 [Travelr](https://github.com/gh0gale): find someone heading your way
It races the Google Routes API against my own A\* train router, then matches you with people on overlapping routes and tracks everyone live.
<br>`Flutter · FastAPI · WebSockets · Redis`

<br>

<details>
<summary><b>the numbers, if you like numbers</b></summary>
<br>

- **INVR:** 20+ indicators, 15 weighted gates, 4 timeframes, verdicts in 2-3 s, narration in under a second, 75-80% directional accuracy backtested over 2 years
- **SpendStream:** 300+ transactions, 12 categories, 100+ merchants normalised, 87.8% accuracy
- **Travelr:** meet points accurate to 30-50 m, live alerts for 1,000+ users

</details>

<details>
<summary><b>where I learned to take data seriously</b></summary>
<br>

A summer as an analyst intern at **Godrej Infotech**, building ETL, schemas and an OLAP cube across 15+ business entities. It taught me that a dashboard is only as honest as the pipeline underneath it. INVR's layered design comes straight from that.

</details>

<details>
<summary><b>what I work with</b></summary>
<br>

Python, SQL, C++ · PySpark, Databricks, ETL/ELT · LangGraph, LangChain, RAG · FastAPI, React, Node · Postgres, Mongo, Firebase · AWS

</details>

<br>

## right now

🔧 making INVR smarter about when its own rules stop working  
📚 going deeper on Databricks and open table formats  
🎓 finishing my B.Tech in CS (Data Science) at DJSCE, class of 2027  
🔎 looking for data and AI engineering roles. If you have a data mess, **[email me](mailto:info.ghogale@gmail.com)**.

<br>

<div align="center">

[LinkedIn](https://linkedin.com/in/yash-ghogale) · [Portfolio](https://portfolio-agent-gh0gale.vercel.app) · [Email](mailto:info.ghogale@gmail.com)

<sub>pipelines over spreadsheets. systems over scripts. always.</sub>

</div>
