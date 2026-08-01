
# Geldium Delinquency Prediction — GenAI-Powered Data Analytics

**Tata iQ × Forage Job Simulation** | Completed August 2026

A four-stage analytics project simulating real-world work at Geldium, a consumer lending company, in partnership with Tata iQ. The goal: predict customer delinquency before it happens, identify which signals actually matter, and design a fair, semi-automated collections strategy around those predictions.

---

## 📌 Project Overview

| | |
|---|---|
| **Industry** | Financial services — credit risk & collections |
| **Dataset** | `Geldium_Delinquency_prediction_dataset.xlsx` (500 customer records, 19 fields) |
| **Tools** | Excel, GenAI (as analytical thinking partner), PowerPoint, Word |
| **Focus** | EDA → Predictive modeling design → Business storytelling → AI-driven strategy |

**Problem statement:** Geldium's existing process for identifying at-risk customers was reactive and imprecise. This project asks whether delinquency can be predicted in advance, which customer attributes are the strongest signals, and how those predictions can be acted on automatically — without introducing unfair bias into decisions that affect real customers.

---

## 🧩 Task Breakdown

### Task 1 — Exploratory Data Analysis
Assessed data quality across the 500-record dataset: flagged missing values, inconsistent labels, and outliers, and proposed a handling plan.

**Key finding:** No single variable predicts delinquency in isolation. Customers with *both* high debt-to-income ratio *and* high credit utilization show a **3x higher delinquency rate** than the general population — an interaction effect that only appears when the two variables are examined together.

📄 Deliverable: EDA report (Word)

### Task 2 — Predictive Modeling Plan
Designed (conceptually, no code) a scoring model to flag at-risk customers.

- **Recommended model:** Logistic regression — prioritized for interpretability and regulatory defensibility in a lending context
- **Benchmark model:** Gradient boosted trees
- **Top 5 features** selected based on Task 1 findings
- **Evaluation plan:** Precision, recall, F1, AUC, plus fairness checks across protected groups

📄 Deliverable: Modeling plan (Word)

### Task 3 — Business Report & Data Storytelling
Translated technical findings into a plain-language brief for a non-technical executive audience (Head of Collections).

- Top 3 risk factors, explained without jargon
- One SMART recommendation: proactive outreach to the highest-risk segment, targeting a **15% reduction in delinquency**
- Two identified fairness risks, each paired with a mitigation

📄 Deliverable: One-page business report (Word)

### Task 4 — AI-Driven Collections Strategy
Designed how the model would operate as a live, semi-automated system.

- End-to-end workflow: **data → decision → action → learning loop**
- Clear split between autonomous actions and actions requiring human review
- Responsible AI guardrails to prevent discriminatory or non-compliant outcomes
- Expected business and customer outcomes

📄 Deliverable: Executive strategy deck (PowerPoint)

---

## 🔍 Methodology

GenAI was used throughout as a **thinking partner, not a black box** — helping structure analysis, draft language, and stress-test model logic. Every AI-assisted claim was independently verified against the underlying data (correlations, group averages, sample sizes) before being included in a deliverable. This is the core skill the simulation assesses: using AI tools productively while retaining independent judgment about what the data actually shows.

---

## 📈 Outcome

One consistent insight — the debt-to-income × credit-utilization risk segment — threads through all four deliverables, reframed for a different audience each time:

| Task | Audience | How the insight is framed |
|------|----------|---------------------------|
| 1 | Analysts | A statistical pattern worth investigating |
| 2 | Data science | An engineered feature driving model design |
| 3 | Business stakeholders | The basis for a measurable action |
| 4 | Executives | The trigger condition for an automated workflow |

That consistency demonstrates the ability to carry one data-driven insight cleanly from raw analysis to executive decision-making.

---

## 🛠 Skills Demonstrated

`AI Analytics & Strategy` · `Exploratory Data Analysis` · `Data Quality Management` · `Model Selection & Validation` · `Predictive Analytics` · `Analytical Reporting` · `Business Communication` · `Ethical Reasoning & Regulatory Compliance` · `Process Automation` · `Strategic Decision Making`

---

## 📎 Source

Tata iQ — *GenAI Powered Data Analytics Job Simulation* on [Forage](https://www.theforage.com/). Completion certificate available and added to LinkedIn Licenses & Certifications.
