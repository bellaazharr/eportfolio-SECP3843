# SECP3843 — Assignments

## 1. Individual Project: Flight Price Prediction (Apache Spark + Medallion Architecture)
**Status:** 🚧 In progress (proposal stage)

Predicting flight prices using a Bronze–Silver–Gold–Curated medallion architecture. Data sourced from Kaggle, IEEE DataPort, and the Open-Meteo API.

**Artifacts:**
- [ ] System Architecture Diagram (draw.io)
- [ ] ERD (draw.io)
- [ ] Star Schema (draw.io)
- [ ] Project proposal document
- [ ] Pipeline code

**Design notes:** Medallion architecture was chosen over a single ETL script so each layer (raw, cleaned, business-ready) can be validated independently. Weather data was added as a feature because flight prices are affected by disruptions, not just route/date.

→ Reflection: [`/Reflections/Flight-Price-Prediction.md`](../Reflections/Flight-Price-Prediction.md)

---

## 2. Group Assignment: Cloud Architecture in Data Engineering
**Partner:** Nurul Adriana
**Status:** ✅ Submitted

Covered functional cloud layers, real-world case examples, and a Pecha Kucha presentation.

**Artifacts:**
- [ ] Report/slides
- [ ] Pecha Kucha recording or slides

---

## 3. Group Assignment: Azure Data Engineering Pipeline
**Status:** ✅ Submitted

Built a pipeline using Azure Data Factory (ADF), Databricks, Synapse Analytics, and Power BI, following a structured tutorial per lecturer requirements.

**Artifacts:**
- [ ] Pipeline architecture screenshot
- [ ] Power BI dashboard screenshot

→ Reflection: [`/Reflections/Azure-Data-Engineering-Pipeline.md`](../Reflections/Azure-Data-Engineering-Pipeline.md)

---

## 4. Group Report: Inventory Risk Management (PPG Case Study)
**Status:** ✅ Submitted

Medallion architecture applied to inventory risk management on Azure. Contributed to Chapters 1 and 2.

**Artifacts:**
- [ ] Report excerpt or link
