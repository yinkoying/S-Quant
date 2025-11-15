**S-Quant — Quantifying the “S” in ESG **

**Project Name: S-Quant — Quantifying the “S” in ESG**

In sustainable finance, the “E” in ESG has clear metrics like carbon emissions, and “G” is backed by governance indicators. However, the “S” — social factors such as human rights, labor conditions, and workplace safety — remains largely unquantified. Banks struggle to incorporate social risks into Sustainability-Linked Loans (SLL), and companies lack reliable, real-time data to demonstrate their social performance.

**S-Quant is an AI-powered social performance quantification platform built on Google Cloud.** Our solution helps banks and enterprises measure both human rights risks and social value creation in a consistent, auditable way.

On the **risk side**, we use Vertex AI to analyze global multi-language news, NGO reports, and anonymized internal grievance logs. We classify and score human-rights-related events (e.g., forced labor, discrimination, harassment, safety incidents) and generate a **Human Rights Risk Score** for each company. All event-level and aggregated scores are stored and updated in BigQuery, enabling continuous **Human Rights Due Diligence (HRDD)**.

On the **value side**, we implement a **Social Return on Investment (SROI)** framework. Using company data on employee training, occupational safety programs, diversity initiatives, and community projects, we estimate the monetized social value created and compute **SROI ratios** for key initiatives. These results are also stored in BigQuery and visualized through dashboards.

Using Vertex AI, BigQuery, Cloud Run, Cloud Functions, and Looker Studio, **S-Quant provides banks with actionable, data-driven social KPIs** that can be integrated into SLL structures. Our goal is to move sustainable finance beyond carbon-only metrics and enable a new generation of loans that truly price in human rights risks and social impact.

---

**專案名稱：S-Quant — 讓 ESG 中的「S」被真正量化**

在永續金融領域中，ESG 的「E」（環境）已有明確的衡量指標，如碳排放；「G」（治理）也有完善的制度性框架。然而，「S」（社會面）——例如人權、勞動條件、職場安全等——至今仍難以量化。銀行無法將社會風險納入永續連結貸款（SLL）的評估之中，而企業也缺乏可信、即時的數據來證明自身的社會績效。

**S-Quant 是一套建構於 Google Cloud 之上的 AI 驅動「社會績效量化平台」。** 我們的解決方案協助銀行與企業，以一致、可審計的方式衡量人權風險與社會價值。

在**風險面**，我們使用 Vertex AI 分析全球多語新聞、NGO 報告與匿名化後的企業內部申訴紀錄。系統會自動分類與評分人權相關事件（如強迫勞動、歧視、性騷擾、職安事故），並為每家公司產生「**人權風險指標（Human Rights Risk Score）**」。所有事件級與彙整後的分數皆儲存在 BigQuery 中，支援企業進行持續性 **HRDD（人權盡職調查）**。

在**價值面**，我們採用「**社會投資報酬率（SROI）**」框架。透過企業提供的員工訓練、職安計畫、多元共融活動、社區投入等資料，我們將其轉換為可驗證的貨幣化社會價值，並計算各項專案的 **SROI 比率**。這些資料同樣儲存在 BigQuery 中，並透過儀表板呈現。

透過 Vertex AI、BigQuery、Cloud Run、Cloud Functions 與 Looker Studio，**S-Quant 為銀行提供可直接用於 SLL 結構設計的「社會面 KPI」**。我們的目標，是讓永續金融不再只依靠碳排，而是真正將人權風險與社會影響納入金融定價，開啟新一代以人為本的永續貸款。
