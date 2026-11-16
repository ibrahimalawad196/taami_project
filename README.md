# 🍱 Taami Project - Food Data Analysis & Operational Insights
This project analyzes operational records from **Taami (Food Preservation Charity)** to identify donation trends, uncover the root causes of food waste, and provide insights to optimize food distribution, reduce waste, and enhance community food security.

> **Privacy Note:** This project uses real operational data provided by Taami. All personal information and private entities have been anonymized in compliance with data privacy policies. Only sample aggregated insights and structural frameworks are shared publicly.

---

## 📌 Project Overview & Objectives
The primary goal is to convert raw administrative logs into strategic metrics that support decision-making:
- **Descriptive & Diagnostic Analysis:** Summarize historical donation flows and diagnose anomalies (such as data-entry errors and decimal-placement issues).
- **Waste Reduction:** Minimize invalid food quantities and track waste patterns over time.
- **Donor Performance:** Identify key donors contributing the highest rates of valid meals versus waste.
- **Operational Efficiency:** Structure metrics by day, week, and month.

---
## ⚙️ Methodology & Data Framework

This project leverages two core analytical methodologies:

1. **Descriptive Analysis:** Organizes and summarizes historical data to answer “What happened?”
2. **Diagnostic Analysis:** Pinpoints the root causes behind data anomalies and waste spikes to answer “Why did it happen?”

### Approved Excel Workbook Structure:
Following the transition from exploratory Python prototypes, the complete analysis is structured into multiple dedicated sheets within Excel:

* **`Donation Data:`** The core primary dataset containing raw entries and corrective adjustment columns.
* **`Data Analysis:`** Comprehensive data audit showing comparisons "Before and After Correction".
* **`Statistical Summary:`** Key metrics including Mean, Standard Deviation, Max/Min values, and Medians.
* **`Data Quality:`** Supplementary sheet measuring utilization rates and data engineering metrics.
* **`Data Logic Check:`** Tracks and resolves flagged records to minimize logical discrepancies.
* **`Run Chart:`** Tracks daily valid weights across 101 days against the Median line.
---
## 🚀 Project Timeline & Phases

### Phase 1: Initial Discovery & Data Cleaning (Aug – Oct 2025)
* **Status:** ✅ Completed
* **Scope:** Cleaned and structured raw logs covering **101 operational days** (Dec 18, 2024 – Mar 29, 2025). Computed baseline daily and weekly averages for valid and invalid donations.

### Phase 2: Deep-Dive Diagnostics & Final Reporting (Sep – Nov 2026)
* **Status:** ✅ Completed
* **Scope:** Conducted thorough error corrections (such as fixing decimal placement anomalies in 48 flagged records, e.g., correcting record #4460 from 12,768 kg to 127.68 kg). Evaluated monthly growth trends and finalized comprehensive reporting for the charity’s leadership.

---
## 🛠️ Tools and Technologies
| Tool / Technology | Purpose |
| :--- | :--- |
| **Excel** | Data cleaning, validation, statistical aggregation, and multi-sheet reporting |
| **Python (Pandas / NumPy)** | Initial data exploration, text filtering, and preprocessing logic |
| **ChatGPT / Gemini / Copilot** | Conceptual structuring, formula syntax guidance, and workflow organization |
| **GitHub** | Version control, documentation, and project portfolio hosting |
