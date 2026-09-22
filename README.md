# Hi, I'm Prathyusha Sathineni 👋

I'm an **Analytics Engineer / Senior Data Analyst** focused on building analytics systems that turn data into decisions.

My background is in manufacturing and healthcare analytics, where I've worked on operational reporting, sensor monitoring, alerting, data validation, and interactive dashboards.

More recently, I've been building end-to-end analytics and AI systems using **Python, SQL, PySpark, Databricks, dbt, DuckDB, Dagster, BigQuery, and LLM APIs**.

I'm particularly interested in the layer between reliable data and useful decisions — where analytics engineering, machine learning, and AI come together.

---

## 🔧 What I'm Building

### [StreamLens — AI Analyst for YouTube Trends]([https://github.com/p16996/streamlens-3.0](https://github.com/prathyushaprojects/streamlens-3.0)) — *private, DM or connect on LinkedIn for access*

An AI-powered analytics application that lets users ask natural-language questions about YouTube trending data and get answers backed by actual SQL queries and database results.

* Built a daily ingestion pipeline using the **YouTube API, Cloud Run, Cloud Scheduler, and BigQuery**
* Designed partitioned and clustered BigQuery tables for trending snapshots and video history
* Built a **Gemini-powered natural-language-to-SQL agent** that generates and executes analytical queries
* Added SQL guardrails, row limits, query-cost controls, refusal handling, and retry logic
* Uses separate least-privilege service accounts for ingestion and read-only analytics access
* Every response shows the **SQL used and estimated query cost**, making the AI's reasoning traceable
* Added automated ingestion monitoring and alerting for pipeline failures
* Built a hand-verified evaluation suite covering aggregation, filtering, unsupported questions, and zero-result cases
* Streamlit interface for interacting with the analytics agent

The project is intentionally focused on **short-term trend analysis within the available data**, rather than claiming long-term forecasting or prediction.

The goal: make an AI analyst that can answer questions from real data while making its work visible and auditable.

---

### [Predictive Maintenance & Anomaly Detection](https://github.com/p16996/predictive-maintenance-analysis)

An industrial sensor analytics system combining anomaly detection, machine-failure classification, and AI-generated explanations.

* Multi-method anomaly detection using **Z-score, IQR, and Isolation Forest**, with consensus scoring across methods
* Machine-failure classification using operational sensor data, with risk scoring based on model probabilities
* Threshold calibration based on observed sensor behavior rather than relying only on textbook defaults
* **Claude API** integration that generates plain-English explanations for detected anomalies
* Real API token usage and cost tracking rather than estimated costs
* Streamlit interface for reviewing risk levels, anomalies, and supporting signals

The goal is not just to identify an anomaly, but to make the result understandable and useful to someone investigating the equipment.

---

### [Olist Analytics Pipeline](https://github.com/p16996/olist-analytics-pipeline)

An end-to-end analytics engineering project built around real e-commerce marketplace data.

* **dbt** staging, intermediate, and mart models
* Data-quality tests and documented transformations
* **DuckDB** as the analytical warehouse
* **Dagster** for orchestration
* **Evidence.dev** for analytics dashboards
* Seller, pricing, delivery, and review analysis across marketplace transactions
* Building an AI layer that reasons over structured business evidence rather than simply summarizing text

The focus is on building the full path from **raw data → tested transformations → analytical models → business insight → AI-assisted reasoning**.

---

## 🧰 Technologies I Work With

**Languages**
Python · SQL · PySpark · Spark SQL

**Analytics Engineering**
dbt · DuckDB · Dagster · BigQuery · Databricks · Delta Lake · Evidence.dev

**Data Engineering**
ETL · Data Validation · Data Quality · Schema Design · Data Modeling · Analytics Pipelines · Apache Spark

**Machine Learning**
scikit-learn · Predictive Modeling · Anomaly Detection · Statistical Analysis · Time-Series Analysis

**AI / LLMs**
Google Gemini API · Vertex AI · Anthropic Claude API · SQL-generating agents · AI guardrails · Prompt engineering

**Visualization**
Plotly · Plotly Dash · Streamlit · Tableau · Matplotlib · Evidence.dev

**Cloud & Tools**
GCP · Cloud Run · Azure Data Lake · AWS · Docker · Git · GitHub · VS Code · Jupyter

---

## 📂 Other Projects

**Market Prediction**
Machine-learning models on financial datasets, focused on feature engineering and model evaluation.

**Time-Series Forecasting**
ARIMA and Exponential Smoothing models for trend and future-value prediction.

**NLP & Sentiment Analysis**
Text classification and customer sentiment analysis using traditional machine-learning approaches.

---

## 💼 Background

My professional experience spans **manufacturing, healthcare analytics, and application development**.

At Novelis, I worked as an **Analytics Developer**, building Python, PySpark, and SQL solutions in Databricks for sensor monitoring and maintenance alerting. I also built automated Teams/email notifications, SQL-based schema validation, and interactive Plotly Dash visualizations.

My work contributed to a **25% reduction in unplanned equipment downtime** and a **50% reduction in incident response time** across global manufacturing operations.

That experience shaped how I approach analytics:

> Reliable data is only useful when it helps someone make a better operational decision.

That's why I'm moving deeper into analytics engineering — owning more of the path from **data → transformation → analysis → application → decision support**.

---

## 📚 What I'm Focused On Right Now

* Analytics engineering with **dbt, DuckDB, Dagster, BigQuery, and Databricks**
* Building reliable, testable analytics pipelines
* Applying ML to real operational problems
* Using LLMs as a **reasoning layer over structured data**
* Building AI systems with guardrails, validation, monitoring, and cost controls
* Turning analytical outputs into usable data applications

---

## 📫 Connect

[LinkedIn](https://linkedin.com/in/prathyushasathineni) · [GitHub](https://github.com/p16996)

Thanks for stopping by.
