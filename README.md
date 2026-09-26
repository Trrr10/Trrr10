<h1 align="center">Hey, I'm Trrishaa 👋</h1>

<p align="center">
  <b>Computer Science undergrad · Backend & ML · Systems · FinTech · AI</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/trrishaa-balakrishnan-708866353/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:trrishaa.balakrishnan24@spit.ac.in">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## A little about me

I'm a Computer Science student at **S.P.I.T., Mumbai** who likes understanding what is happening *underneath* the thing I'm building.

I started with the usual "make something that works."

Then I started asking questions like:

> What happens if the request arrives twice?

> What if the worker crashes halfway through?

> What if the database succeeds but the client never gets the response?

> What if the data I'm feeding the model is wildly imbalanced?

> What happens when the network disappears?

And somehow, those questions became my favourite part of software engineering.

I'm particularly interested in **backend systems, distributed systems, financial technology, and AI** — especially where they overlap.

I like building things that have to deal with messy data, unreliable systems, real-world constraints, and edge cases that aren't visible in the happy path.

Also: I will absolutely spend an unreasonable amount of time figuring out *why* something broke instead of just patching it until it works.

---

## What I'm working with

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=java,python,c,js" />
</p>

### Backend / Databases

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,postgres,mongodb,supabase" />
</p>

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,html,css,tailwind" />
</p>

### ML / AI

`scikit-learn` · `XGBoost` · `LightGBM` · `SHAP` · `Pandas` · `NumPy` · `Ollama` · `Groq` · `Sarvam AI`

### Tools

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,vercel" />
</p>

---

# Things I've built

## 💳 PayFlow — Fault-Tolerant Payment Processing

**[GitHub →](https://github.com/Trrr10/PayFlow)**

A distributed payment processing system built around a simple question:

**What happens when money moves through a system and something goes wrong halfway through?**

PayFlow uses a **producer-consumer architecture** where payment requests enter a job queue and workers process them asynchronously.

Some of the problems I specifically worked around:

* 🔁 **Idempotency** — preventing duplicate transactions when the same request is retried
* 💥 **Worker failures** — handling crashes without silently losing jobs
* ⏳ **Retry with exponential backoff** — retrying transient failures without hammering the system
* 🔐 **JWT authentication**
* 💰 **Atomic wallet transactions**
* 🗄️ **MongoDB transactions and duplicate-key handling**
* 📡 **Socket.IO** for real-time queue and system monitoring
* 📊 A live dashboard showing queue health and transaction activity

**Stack:** `React` `Node.js` `Express` `MongoDB` `Socket.IO` `JWT`

---

## 🧠 Fraud Detection — Explainable ML

**[GitHub →](https://github.com/Trrr10/Fraud-Detection)**

A fraud detection pipeline built on a **240K+ transaction dataset** with an extreme class imbalance of roughly **231:1**.

Instead of treating this as a simple classification problem, I focused on what happens when the thing you're trying to detect is the tiny minority.

The pipeline involved:

* Feature engineering
* Statistical feature validation using the **Mann–Whitney U test**
* Handling severe class imbalance
* **Borderline-SMOTE**
* **Isolation Forest**
* XGBoost
* LightGBM
* Random Forest ensembles
* Macro-level evaluation using **AUC / F1**
* Ablation testing
* **SHAP** for model explainability

The goal wasn't just:

> "The model predicted fraud."

It was:

> **"Why did the model think this transaction was suspicious?"**

**Stack:** `Python` `Pandas` `scikit-learn` `XGBoost` `LightGBM` `SHAP`

---

## 🏆 PathWay AI — Offline-First AI Tutoring

**[GitHub →](https://github.com/Trrr10/Pathway---AI)**

An AI tutoring platform designed around a constraint that often gets ignored:

**not everyone has reliable internet.**

PathWay connects students, teachers, and mentors while supporting an **offline-first learning experience**.

The AI component runs locally using **Ollama + Llama 3.1**, reducing dependence on a constant internet connection.

Built during the **EnCode Hackathon**, where it won the hackathon.

**Stack:** `React` `Node.js` `Supabase` `Ollama` `Llama 3.1`

---

## 📦 StockOS — Voice-Powered Inventory

**[GitHub →](https://github.com/Trrr10/StockOS)**

A stock management system built around a very simple observation:

> If someone has to type the same inventory updates all day, maybe the computer should just listen.

StockOS uses **voice input** to make inventory operations faster while combining structured inventory management with AI-powered insights.

**Stack:** `React` `Supabase` `Express.js` `Sarvam AI` `Groq`

---

## 📈 Stochron — Financial Sentiment Index

**[GitHub →](https://github.com/Trrr10/Stochron)**

Backend and risk-scoring work for a financial sentiment platform.

The interesting part isn't just throwing an ML model at financial news.

The platform uses a **lexicon-based financial sentiment engine** to convert messy market news into a normalized **Financial Sentiment Index**, with category-level weighting and market regime classification.

I work primarily on the backend side:

* FastAPI services
* PostgreSQL data modelling
* Supabase
* Article processing
* Sentiment/risk scoring
* API design
* Analysis endpoints
* Configurable scoring weights

Currently exploring how **ML can complement — rather than replace — the deterministic lexicon-based engine.**

**Stack:** `FastAPI` `Python` `PostgreSQL` `Supabase` `React`

---

# 🧩 What I like building

I'm especially drawn to problems involving:

**Distributed Systems**

Queues · retries · idempotency · transactions · concurrency · failure handling

**Backend Engineering**

APIs · databases · authentication · system architecture · data modelling

**Machine Learning**

Imbalanced datasets · feature engineering · explainability · evaluation · anomaly detection

**FinTech**

Payments · financial data · risk signals · transaction systems · market sentiment

**AI**

LLMs · local inference · AI-assisted systems · voice interfaces · ML + rule-based hybrids

---

# 📚 Currently improving

```text
Java
├── Data Structures & Algorithms
├── OOP
├── Problem Solving
└── Competitive Programming

Backend
├── FastAPI
├── REST APIs
├── PostgreSQL
├── Distributed Systems
└── System Design

Computer Science
├── DBMS
├── Operating Systems
├── Computer Networks
└── Software Architecture

```

I also enjoy the slightly painful process of taking something I *thought* I understood and discovering that I absolutely did not.

---

# 💭 Beyond the code

I'm a **Bharatanatyam dancer** , so apparently I enjoy both debugging distributed systems and spending years learning choreography.

I also like:

📖 Reading
✍️ Writing
💃 Dancing

I tend to notice small details, which is either a useful engineering trait or a terrible personality trait depending on the situation.

---


# 📊 GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Trrr10&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Trrr10&layout=compact&theme=transparent&hide_border=true" height="170"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Trrr10&theme=transparent&hide_border=true" />
</p>

---

<h3 align="center">
  <i>Still building. Still breaking things. Still figuring out why they broke.</i>
</h3>

<p align="center">
  If you're working on something interesting in systems, AI, ML, or fintech — I'd love to hear about it.
</p>
