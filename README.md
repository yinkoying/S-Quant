# S-Quant — Quantifying the “S” in ESG  
AI-Powered Social Performance Quantification Platform Built on Google Cloud

---

## 🌐 Overview / 專案簡介

**中文：**  
S-Quant 是一套建構於 Google Cloud 的 AI 社會績效量化平台，專注於量化 ESG 中最難衡量的「社會」（S）面向。我們協助企業與銀行，以一致、可審計的方式衡量人權風險與社會價值。

**English:**  
S-Quant is an AI-powered social performance quantification platform built on Google Cloud. It provides consistent and auditable metrics for human rights risks and social value creation — enabling banks and enterprises to quantify the “S” in ESG.

---

## 🧩 Problem Statement / 問題背景

**中文：**  
- ESG 的 E（環境）有成熟的碳排與能源指標  
- G（治理）有制度性衡量框架  
- **但 S（社會）長期缺乏可信、即時、可量化的數據**  
- 銀行難以將社會風險納入永續連結貸款（SLL）  
- 企業難以展示社會績效與符合法規（如 CSDDD）

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
- Stored in **BigQuery** for continuous HRDD

### 2️⃣ Social Return on Investment (SROI) Engine
- Converts social actions (training, DEI, safety initiatives) into **monetized social value**  
- Computes SROI ratios  
- Visualized via **Looker Studio** dashboards

---

## ☁️ Google Cloud Architecture / 技術架構

**Services Used:**
- Vertex AI — NLP models & inference  
- BigQuery — data warehouse, KPI computation  
- Cloud Run & Cloud Functions — ingestion, pipelines  
- Cloud Storage — raw data layer  
- Looker Studio — dashboards & analytics  

---

## 🏗 Architecture Diagram (ASCII)

以下是最穩定、不會跑版的流程圖：

