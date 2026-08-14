# 🏦 Retail Lending Origination & Risk-Based Pricing Engine

> **Production-Grade Direct Lending Decisioning Framework**  
> Dual Credit Scoring | CBK KESONIA Pricing | Alternative Data Integration | 75,000-Applicant Panel

---

## 📋 Executive Summary

This flagship project constructs an **end-to-end automated loan decisioning engine** for Kenya's direct lending and fintech ecosystem. Grounded in **Central Bank of Kenya (CBK) Risk-Based Credit Pricing Model (RBCPM)** compliance, the engine ingests **traditional credit bureau (CRB) data** alongside **alternative mobile money signals** (M-Pesa velocity, Till/Paybill turnover, diaspora remittances) across three product tiers.

**75,000 historical loan applicants** are scored using a **dual-model architecture**:
- **Logistic Regression:** Interpretable, regulatory-auditable scorecard (WoE/IV-transformed features)
- **XGBoost:** Non-linear risk detection capturing mobile money signal interactions

Dynamic approval routing (Auto-Approve/Manual Review/Auto-Decline) is paired with **CBK KESONIA-compliant pricing** (APR = 8.75% baseline + 2.5% operational cost + 1.0% funds cost + dynamic risk premium K(PD)) and **product mix optimization** to maximize net interest income (NII) subject to portfolio risk caps (5.0% PD) and capital constraints (KES 100M/month).

---
