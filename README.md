# Yogesh Kulkarni

**M.Sc. Data Science & Artificial Intelligence** : Saarland University, Germany  
Previously **3 years as SDE** at Jio Platforms (Reliance), building SAP billing systems at telecom scale.

I like problems where the modelling has to survive contact with a real system — messy data, deployment constraints, someone depending on the output. Right now I'm most drawn to **trustworthy and adversarial ML**, and I'm looking for research assistant (HiWi) and working-student roles in Saarbrücken where I can go deeper on it.

---

## Selected Work

### 🔐 Trustworthy Machine Learning : CISPA, SS 2026
Four attack-and-defense projects on the privacy, robustness, and IP properties of neural networks.

| Task | What I built | Approach |
|---|---|---|
| Membership Inference | Attack recovering whether a sample was in training data | LiRA with 16 shadow models + XGBoost meta-classifier |
| Stolen Model Detection | Defense identifying stolen copies among 360 candidates | 9-signal ensemble: weight similarity, CKA, boundary probing |
| Adversarial Robustness | Model hardened against unknown attacks | TRADES + PGD adversarial training |
| Watermark Forgery | Attack forging invisible watermarks across 8 schemes | Multi-domain steganographic alignment |

→ [MARKST-47/TML-26](https://github.com/MARKST-47/TML-26) · with [@MARKST-47](https://github.com/MARKST-47) · PyTorch, XGBoost, HPC (HTCondor)

---

### ✈️ Airline On-Time Performance Audit : SAP BTP
An operational analytics platform over **12.3 million** US DOT flight records, from raw CSVs to a deployed cloud dashboard.

| Layer | What it does |
|---|---|
| Data | Streaming ETL + pre-computed aggregates — sub-second dashboards over 12M rows |
| Classification | Composite carrier reliability score; surfaces airlines a single metric would flatter |
| Analysis | Root-cause delay study — isolates the late-aircraft cascade peaking 17:00–19:00 |
| AI | Grounded LLM summaries and management PDF reports via SAP AI Core |

→ [SAPBTP_GROUP3_TOPIC3](https://github.com/MUHEB-ai/SAPBTP_GROUP3_TOPIC3) · *my parts: classification, association analysis, AI integration, PDF reporting, deployment* · SAP CAP, HANA Cloud, Fiori Elements, Node.js

---

### 📐 ML From Scratch
Linear regression, logistic regression, and KNN in pure NumPy : gradient descent, loss surfaces, and decision boundaries implemented rather than imported.

→ [crypticyogi/ml-from-scratch](https://github.com/crypticyogi/ml-from-scratch) · Python, NumPy, Matplotlib

---

## Background

Before grad school I spent three years at Jio Platforms working on SAP Convergent Invoicing: billing logic, ABAP programs, and integration workflows for a system serving 400M+ subscribers. It taught me what production scale actually costs, and that's the perspective I bring to ML work now.

---

## Toolkit

| | |
|---|---|
| **ML** | Python · PyTorch · scikit-learn · NumPy · Pandas · XGBoost |
| **Enterprise** | ABAP · SAP Convergent Invoicing · SAP CAP/CDS · S/4HANA · BTP |
| **Infra** | Git · Linux · Cloud Foundry · HANA · HTCondor · FastAPI · LaTeX |

---

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yogesh_Kulkarni-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/yogeshkulkarni06/)
[![Email](https://img.shields.io/badge/Email-Saarland_University-EA4335?style=flat&logo=gmail)](mailto:yoku00002@stud.uni-saarland.de)
