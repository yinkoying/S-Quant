# Project S-Quant: Quantifying the “S” in ESG

S-Quant 是一套以 Google Cloud 打造的 AI 社會績效量化平台，專注於解決 ESG 中最難量化的「社會面」。
(S-Quant is an AI-powered social performance quantification platform built on Google Cloud, focusing on solving the most difficult part of ESG to quantify: the "S".)

---

## 🎯 The Problem

In sustainable finance, the “E” in ESG has clear metrics like carbon emissions, and “G” is backed by governance indicators. However, the **“S” — social factors** such as human rights, labor conditions, and workplace safety — remains largely unquantified.

Banks struggle to incorporate social risks into Sustainability-Linked Loans (SLL), and companies lack reliable, real-time data to demonstrate their social performance.

## 💡 Our Solution

S-Quant is an **AI-powered social performance quantification platform** built on Google Cloud. Our solution helps banks and enterprises measure both human rights risks and social value creation in a consistent, auditable way.

Our platform is built on two core engines:

### 1. Human Rights Risk Engine (HRDD)

On the risk side, we use **Vertex AI** to analyze global multi-language news, NGO reports, and anonymized internal grievance logs. We classify and score human-rights-related events (e.g., forced labor, discrimination, harassment, safety incidents) and generate a **Human Rights Risk Score** for each company. All event-level and aggregated scores are stored and updated in **BigQuery**, enabling continuous Human Rights Due Diligence (HRDD).

### 2. Social Value Engine (SROI)

On the value side, we implement a **Social Return on Investment (SROI)** framework. Using company data on employee training, occupational safety programs, diversity initiatives, and community projects, we estimate the monetized social value created and compute **SROI ratios** for key initiatives. These results are also stored in **BigQuery** and visualized through dashboards.

## 🛠️ Technical Architecture

We leverage a serverless, scalable architecture on Google Cloud:

* **Vertex AI:** For NLP, multi-language analysis, and risk classification.
* **BigQuery:** As the central data warehouse for all scores, events, and SROI data.
* **Cloud Run / Cloud Functions:** For data ingestion, ETL, and serverless processing.
* **Looker Studio:** For visualizing dashboards and reports.

## 🚀 Impact

S-Quant provides banks with actionable, data-driven **social KPIs** that can be integrated into SLL structures. Our goal is to move sustainable finance beyond carbon-only metrics and enable a new generation of loans that truly price in human rights risks and social impact.

---

## 🎯 核心問題

在永續金融領域中，ESG 的「E」（環境）已有明確的衡量指標，如碳排放；「G」（治理）也有完善的制度性框架。然而，**「S」（社會面）**——例如人權、勞動條件、職場安全等——至今仍難以量化。

銀行難以將社會風險納入永續連結貸款（SLL）的評估之中，而企業也缺乏可信、即時的數據來證明自身的社會績效。

## 💡 我們的解決方案

S-Quant 是一套建構於 Google Cloud 之上的 **AI 驅動「社會績效量化平台」**。我們的解決方案協助銀行與企業，以一致、可審計的方式衡量人權風險與社會價值創造。

我們的平台建立在兩大核心引擎之上：

### 1. 人權風險引擎 (HRDD)

在風險面，我們使用 **Vertex AI** 分析全球多語新聞、NGO 報告與匿名化後的企業內部申訴紀錄。系統會自動分類與評分各類人權相關事件（例如強迫勞動、歧視、性騷擾、職安事故），並為每家企業產生「**人權風險指標**」（Human Rights Risk Score）。所有事件級與彙整後的分數皆儲存在 **BigQuery** 中，支持企業進行持續性的人權盡職調查（HRDD）。

### 2. 社會價值引擎 (SROI)

在價值面，我們採用「**社會投資報酬率**」（SROI）框架。透過企業提供的員工訓練、職安計畫、多元共融活動、社區投入等資料，我們將其轉換為可被驗證的「**貨幣化社會價值**」，並為重要方案計算 SROI 比率。這些資料同樣儲存在 **BigQuery** 中，並透過儀表板進行視覺化呈現。

## 🛠️ 技術架構

我們利用 Google Cloud 的無伺服器、可擴展架構：

* **Vertex AI:** 用於 NLP 推論、多語分析、人權風險分類。
* **BigQuery:** 作為核心資料倉儲，儲存所有風險分數、事件與 SROI 模型。
* **Cloud Run / Cloud Functions:** 處理輿情抓取、ETL 與無伺服器運算。
* **Looker Studio:** 用於儀表板視覺化。

## 🚀 專案影響力

S-Quant 為銀行提供可直接用於 SLL（永續連結貸款）結構設計的「**社會面 KPI**」。我們的目標，是讓永續金融不再只依靠碳排數據，而是真正將人權風險與社會影響納入金融定價，開啟新一代以人為本的永續貸款。
