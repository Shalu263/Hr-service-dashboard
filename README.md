## 📊 People Services — Enterprise HR & Workforce Analytics Dashboard

### An executive-level **Power BI HR Analytics Dashboard** designed to analyze the complete **Employee Lifecycle**—from recruitment and onboarding to performance, learning & development, and attrition. 

### This project empowers HR leaders, MIS managers, and executive teams to make data-driven workforce planning decisions, optimize L&D spend, identify recruitment funnel bottlenecks, and mitigate attrition risks.

### 🎯 Key Business Problems Solved

1. **Workforce Headcount & Growth Tracking:** Real-time visibility into overall employee volume, active contracts, and net growth month-over-month[cite: 2].
2. **Turnover & Attrition Drivers:** Detailed breakdown of voluntary vs. involuntary terminations categorized by tenure, age group, and department[cite: 3].
3. **Recruitment Funnel Efficiency:** Tracking applicant conversion stages (Screening %, Interview %, Offer %, Hire %) to identify recruitment bottlenecks[cite: 5].
4. **L&D ROI Optimization:** Tracking total training investments ($10.98M+), cost per participant, course completion rates, and internal vs. external vendor costs[cite: 4].
5. **360° Employee Profiling:** Individual drill-down cards tracking employee engagement, performance ratings, leave logs, overtime hours, and training history[cite: 7].

---

---

## 🛠️ Technical Stack & Features

* **Tool:** Microsoft Power BI Desktop
* **Data Transformation:** Power Query (ETL pipeline for data cleaning, unpivoting, type casting, and null handling)
* **Data Modeling:** Star Schema Data Model with a dedicated `Dim_Calendar` table and bidirectional filters where required
* **DAX Formulas:** Custom measures including:
  * `Turnover Rate %`
  * `Net Add L12M`
  * `Training Cost Per Person`
  * `Funnel Conversion %`
  * `YTD Headcount Growth %`
* **Interactivity:** Custom UI navigation sidebar, cross-filtering slicers (Division, Job Function, Business Unit, Date Range), dynamic tooltips, and drill-through capabilities.

---

### 📊 Core KPIs Summary

* **Headcount:** 1,692 Active Employees
* **Turnover Rate (L12M):** 32.45%
* **Training Expenditure:** $10.98M across 2,000 Unique Participants
* **Recruitment Volume:** 3,000 Applicants | 622 Hires | 20.73% Vacancies Filled
* **Performance Benchmark:** 73.97% employees rated

---

