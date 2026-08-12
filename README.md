# Hi, I'm Reshma 👋

I work in data science — 16 years in retail across personalization, site merch, marketing, customer growth, loyalty and digital ads. 

Currently at: Walmart

Previously at: TripAdvisor, Chewy, Staples & Macys

Interests: Machine Learning, Agentic AI 

📍 San Jose, CA · [LinkedIn](https://www.linkedin.com/in/reshma-shah-ai-analytics/)

---

## 🔭 What I'm building now

### [customer-intelligence-platform](https://github.com/reshshah/data-science-portfolio/tree/main/customer-intelligence-platform)

A scalable machine learning platform that turns raw customer data (orders, web events, support tickets, marketing touches) into trained, evaluated churn, propensity and uplift models.

---

## 🧰 Smaller projects

### [data-science-portfolio](https://github.com/reshshah/data-science-portfolio)

Standalone scripts and small apps from marketing and growth analytics problems I've worked on:

| Tool | What it does |
|---|---|
| Marketing Mix Modeling Assistant | A simple OLS + Lasso MMM with budget suggestions — deliberately basic, no adstock or saturation yet |
| LLM Sentiment & Topic Pipeline | LLM-based review classification with topic extraction |
| Breakeven ROAS Calculator | A small Streamlit tool for margin-aware ROAS thresholds |
| A/B Test Sample Size Calculator | Two-sample power analysis for experiment design |

---

## 🔭 What I will build next

### [AgentOps — Multi-Agent Churn Prediction](https://github.com/reshshah/agentops-churn-prediction)

A work-in-progress multi-agent system for subscription churn, designed spec-first: the architecture, agent contracts, and design tradeoffs are documented in the repo, and I'm implementing it phase by phase against that spec. The design covers streaming feature ingestion (Kafka), an XGBoost + LightGBM ensemble with SHAP, Claude-generated explanations, and CUPED-based experimentation.

`Python` `XGBoost` `Kafka` `Redis` `FastAPI` `Anthropic Claude` `SHAP` `CUPED`

---

## Things I've come to believe about ML systems

- The model is rarely the hard problem — feature freshness, auditability, and the decision layer above the model usually matter more.
- Explainability is a product feature. A churn score nobody understands is a churn score nobody acts on.
- Experiments should compound: each outcome should make the next decision smarter.

---

## Tools I use

**ML:** Python · XGBoost · LightGBM · scikit-learn · SHAP · statsmodels
**LLM / Agents:** Anthropic Claude · OpenAI · RAG
**Infra:** Kafka · Redis · FastAPI · Docker · GitHub Actions
**Experimentation:** CUPED · power analysis · causal lift measurement
