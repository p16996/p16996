# Hi, I'm Prathyusha Sathineni 👋

I'm an analytics engineer who likes building systems that don't just report what happened, but help someone figure out what to do next.

My background is in manufacturing and healthcare analytics — dashboards, alerting, predictive maintenance, operational reporting. Lately I've been rebuilding that same instinct with a modern stack: dbt, DuckDB, Dagster, and LLMs used as a reasoning layer instead of just a summarizer.

This GitHub is where that work lives.

---

## 🔧 What I'm Building

### [Predictive Maintenance & Anomaly Detection](https://github.com/p16996/predictive-maintenance-analysis)
A production-style monitoring system for industrial sensor data — built to answer not just "will this machine fail" but "why, and what should an engineer do about it."

- Multi-method anomaly detection (Z-score, IQR, Isolation Forest) with a consensus layer comparing all three
- Machine failure prediction on operational sensor data, with risk scoring from model probabilities
- Claude API integration that turns the highest-confidence anomalies into plain-English, actionable explanations for maintenance engineers, with token usage and cost tracked from real API responses rather than estimates
- Threshold tuning based on actual sensor behavior rather than textbook defaults — a real calibration problem I ran into and solved

### [Olist Analytics Pipeline](https://github.com/p16996/olist-analytics-pipeline) — *in progress*
A full analytics engineering build on e-commerce order data, structured the way I'd want a production pipeline to look.

- dbt models across staging, intermediate, and mart layers, with data quality tests and full documentation
- DuckDB as the local warehouse, Dagster for orchestration on a daily schedule
- Evidence.dev for dashboarding (currently in progress)
- Building toward a **Seller Exoneration Engine** — using an LLM as a structured reasoning layer over evidence (order timelines, logistics data, complaint patterns) to determine fault in delivery disputes, rather than using it to summarize text. The idea is to treat the LLM as something that reasons over structured evidence, not just paraphrases it.

---

## 🧰 Technologies I Work With

**Languages**
Python · SQL

**Analytics Engineering**
dbt · DuckDB · Dagster · Evidence.dev

**Data Engineering**
PySpark · Databricks · Azure Data Lake

**Machine Learning**
scikit-learn · Pandas · SciPy

**ML Focus Areas**
Anomaly Detection · Predictive Modeling · Time Series Forecasting

**AI / LLMs**
Anthropic Claude API · Prompt design for structured reasoning tasks

**Visualization**
Plotly · Streamlit · Tableau · Evidence.dev

**Tools & Cloud**
Git · GitHub · VS Code · AWS

---

## 📂 Other Projects

**Market Prediction** — ML models on financial datasets, focused on feature engineering and model evaluation.

**Time-Series Forecasting** — ARIMA and Exponential Smoothing models for trend and future value prediction.

**NLP & Sentiment Analysis** — Text classification and customer sentiment analysis.

---

## 💼 Background

I've spent 5+ years building analytics solutions across manufacturing and healthcare — predictive analytics, real-time monitoring, interactive dashboards, and high-frequency operational data processing. I usually describe my role as the bridge between domain expertise and working code: understanding what the business actually needs, then building the pipeline or dashboard that gets them there.

That background is what pulls me toward analytics engineering now — I want to own more of the stack, from the transformation layer to the reasoning layer on top of it.

---

## 📚 What I'm Focused On Right Now

- Analytics engineering (dbt, DuckDB, Dagster)
- LLMs as a reasoning layer, not just a chat interface
- Explainable, production-grade ML systems
- End-to-end data applications, not just notebooks

---

Thanks for stopping by — feel free to explore the repos or connect with me on [LinkedIn](https://linkedin.com/in/prathyushasathineni).
