# S-Quant — Quantifying the “S” in ESG  
AI-Powered Social Performance Quantification Platform Built on Google Cloud.

---

## 🌐 Overview / 專案簡介
**中文：**  
S-Quant 是一套建構於 Google Cloud 的 AI 社會績效量化平台，用於量化 ESG 中最難衡量的「社會」（S）面向。我們提供企業與銀行一致、可審計的社會風險指標與社會價值衡量工具。

**English:**  
S-Quant is an AI-powered social performance quantification platform built on Google Cloud. It provides consistent and auditable metrics for human rights risks and social value creation — enabling banks and enterprises to quantify the “S” in ESG.

---

## 🧩 Problem Statement / 問題背景
**中文：**  
- ESG 的 E（環境）有成熟的碳排與能源指標  
- G（治理）有完善制度與框架  
- **但 S（社會）長期缺乏可信、即時、可量化的數據**  
- 銀行難以將人權風險納入永續連結貸款（SLL）  
- 企業難以證明其社會績效與符合法規（如 CSDDD）

**English:**  
The “S” in ESG — human rights, labor conditions, workplace safety — remains largely unquantified. Banks cannot incorporate social risks into Sustainability-Linked Loans (SLL), and companies lack reliable real-time data to demonstrate social performance.

---

## 🚀 Solution / 解決方案
S-Quant consists of **two AI-driven engines**:

### 1️⃣ Human Rights Risk Engine (HRDD)
- Analyzes global multi-language news  
- Processes NGO reports  
- Reads anonymized internal grievance logs  
- Uses Vertex AI NLP for classification & severity scoring  
- Outputs a **Human Rights Risk Score**  
- Data stored in **BigQuery** for continuous HRDD

### 2️⃣ Social Return on Investment (SROI) Engine
- Converts social actions (training, DEI, safety initiatives) into **monetized social value**  
- Calculates SROI ratios for key programs  
- Visualized via dashboards in **Looker Studio**

---

## ☁️ Google Cloud Architecture / 技術架構
**Services Used:**
- Vertex AI (NLP models, text classification)
- BigQuery (data warehouse, KPIs)
- Cloud Run & Cloud Functions (pipelines & ingestion)
- Cloud Storage (raw data)
- Looker Studio (dashboards)

---

## 🔧 Architecture Diagram (ASCII)
```text
                ┌────────────────────────┐
                │     Data Sources       │
                │  - News / NGO Reports  │
                │  - Grievance Logs      │
                └───────────┬────────────┘
                            │
                     Raw Data (GCS)
                            │
                ┌───────────▼───────────┐
                │   Cloud Functions      │
                │  ETL / Preprocessing   │
                └───────────┬───────────┘
                            │
                    ┌───────▼────────┐
                    │   Vertex AI     │
                    │ NLP Inference   │
                    │  - HR Events    │
                    │  - Severity     │
                    └───────┬────────┘
                            │
                    ┌───────▼────────┐
                    │   BigQuery      │
                    │  HR Risk Tables │
                    │  SROI Metrics   │
                    └───────┬────────┘
                            │
                    ┌───────▼────────┐
                    │ Looker Studio   │
                    │ Dashboards       │
                    └─────────────────┘
