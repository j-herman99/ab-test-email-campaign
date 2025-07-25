# 📩 A/B Testing: Email CTA Conversion Optimization

![Built With: Python](https://img.shields.io/badge/Built%20With-Python-06b6d4?style=flat&labelColor=333&logo=python&logoColor=white)
![Libraries: Pandas | NumPy](https://img.shields.io/badge/Libraries-Pandas%20%7C%20NumPy-7dd3fc?style=flat&labelColor=333&logo=pandas&logoColor=white)
![Visualization: Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-9333ea?style=flat&labelColor=333&logo=matplotlib&logoColor=white)
![Stat Test: Z-Test (SciPy)](https://img.shields.io/badge/Stat%20Test-Z--Test%20(SciPy)-8b5cf6?style=flat&labelColor=333&logo=scipy&logoColor=white)
![Status: Complete](https://img.shields.io/badge/Status-Complete-facc15?style=flat&labelColor=333)
![Use Case: Conversion Optimization](https://img.shields.io/badge/Use%20Case-Conversion%20Optimization-14b8a6?style=flat&labelColor=333)
![Notebook: Jupyter](https://img.shields.io/badge/Notebook-Jupyter-f97316?style=flat&labelColor=333&logo=jupyter&logoColor=white)

A data-driven A/B testing project simulating a B2B SaaS email campaign to identify which call-to-action (CTA) drives more demo sign-ups — and whether the difference is statistically significant.

---

## 🧪 Executive Summary

**Project Type:** Conversion Analysis · Statistical Testing  
**Industry Focus:** SaaS Marketing  
**Skills:** A/B Testing · Python · Data Visualization · Tableau Public · Dashboard Reporting

---

## 📌 Overview

This project simulates an A/B test for a B2B SaaS company's email marketing campaign. The goal is to identify which CTA drives more demo sign-ups and whether the observed difference is statistically significant.

---

## 🎯 Business Objective

Optimize the demo signup rate through minimal copy changes to improve lead acquisition and marketing ROI.

---

## 🧰 Tools & Methods

- **Python**: pandas, matplotlib, seaborn, scipy  
  → Used for data simulation, statistical testing, and initial visualizations

- **Statistical Test**: z-test for two proportions  
  → Assessed significance of conversion rate difference between variants

- **Visualization**:
    - Python for exploratory/technical visuals
    - Tableau for executive dashboards and KPI tiles

- **Deliverables**:
    - Executive summary PDF
    - Tableau dashboard with conversion insights
    - Jupyter notebook with reproducible analysis

---

## 📊 KPI Results

| Variant | Conversion Rate | Lift (%) | Statistically Significant |
|--------|------------------|----------|----------------------------|
| A      | 8.10%            | –        | –                          |
| B      | 11.63%           | +43.6%   | ✅ (p = 0.0042)            |

---

## 🔍 Key Findings

- **Variant B** outperformed A with a **+43.6% lift in conversions**
- The difference is **statistically significant (p < 0.05)**
- Demonstrates the ROI of data-informed messaging and iteration

---

## 📈 Dashboard Preview

**Python Summary View**  
![Python Summary](01_project_artifacts/ab-test-exec-summary-deck.jpeg)

**Tableau KPI Dashboard**  
![Tableau Dashboard](01_project_artifacts/Dashboard.png)  
[▶️ View Interactive Version](https://public.tableau.com/views/ABTestingDashboard_17512047502410/Dashboard)

---

## 💼 Strategic Recommendations

✅ Roll out Variant B in all email campaigns  
📈 Apply similar A/B frameworks to landing pages and onboarding flows

---

## 📂 Files & Artifacts

| Type | File |
|------|------|
| 📓 Jupyter Notebook | [ab_testing_portfolio_project.ipynb](https://drive.google.com/file/d/1fXk9l9UX8wRMr8x36sUPDqlPKywo3_Kn/view?usp=sharing) |
| 📊 Dashboard Report (PDF) | [View PDF](https://drive.google.com/file/d/1FA05hbUgVMEAD-PGA4DehxPSglioaXm5/view?usp=drive_link) |
| 🖥️ Executive Slides | [View Slides (PPTX)](https://docs.google.com/presentation/d/1jp8f9UrzSMemDSTNyR4zWAvJ0gWU185R1hiSwevriQA/edit?usp=drive_link) |

---

## ✅ Project Folder Structure

```
ab_testing_email_campaign_project/
├── 01_project_artifacts/
│   ├── ab-test-exec-summary-deck.jpeg
│   ├── Dashboard.png
├── 02_documentation/
│   └── A_B Testing_Deck_Email Conversion Optimization.pdf
├── 03_data/
│   └── A_B_Test_Data.xlsx
├── 04_code/
│   └── ab_testing_portfolio_project.ipynb
├── requirements.txt
├── gitignore.txt
```

---
