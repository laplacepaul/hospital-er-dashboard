# 🏥 Hospital Emergency Room Dashboard

A multi-page **Power BI analytics dashboard** analyzing 9,216 emergency room patient visits across 19 months (April 2023 – October 2024). Built to surface operational inefficiencies, monitor care quality targets, and support data-driven resource planning.

---

## 📊 Dashboard Overview

The dashboard is structured across **four views**, each serving a distinct analytical purpose:

| View | Purpose |
|------|---------|
| **Monthly View** | Time-filtered KPIs for a selected month — volumes, wait times, satisfaction, referrals |
| **Consolidated View** | Full 19-month aggregated trends for strategic and executive reporting |
| **Patient Details** | Granular drill-down table with individual patient records |
| **Key Takeaways** | Narrative summary translating findings into plain-language insights for stakeholders |

---

## 📌 Key Metrics

| Metric | Value |
|--------|-------|
| Total Patients | 9,216 |
| Average Wait Time | 35.3 minutes |
| Wait Time Target | 30 minutes |
| % Seen Within Target | 59.32% |
| Avg Satisfaction Score | 4.99 / 10 |
| Total Referrals | 3,816 (41.4%) |
| Admission Rate | 49.16% |

---

## 🔍 Key Findings

- **Wait time target consistently missed** — avg 35.3 min exceeds the 30-min benchmark; 40.68% of patients did not receive care within the target window
- **Peak demand on Mondays** (1,377 patients), Saturdays, and Tuesdays; busiest hours at 7 AM, 11 AM, 1 PM, and 11 PM
- **General Practice** is the top referral destination (1,840 patients), followed by Orthopedics (995) and Physiotherapy (276)
- **Adults aged 30–39** form the largest patient group (1,200); the population is racially diverse across 7 categories
- **Near-equal admission split** — 49.16% admitted vs 50.84% treated and discharged, indicating high average case severity
- **Satisfaction scores moderate** at 4.99/10, closely tied to wait time performance

---

## 🛠 Tools & Skills Used

- **Power BI Desktop** — dashboard design, report layout, interactive filtering
- **Power Query** — data transformation, cleaning, and shaping
- **DAX** — calculated measures and KPI logic
- **Data Modeling** — relationships across patient, referral, and time tables
- **Data Visualization** — donut charts, bar charts, heatmaps, KPI cards, tables

---

## 📁 Files

```
hospital-er-dashboard/
├── Hospiatl_ER_Dashboard.pbix   # Power BI source file
├── Hospiatl_ER_Dashboard.pdf    # Exported dashboard (all 4 views)
├── ER_Dashboard_Portfolio.html  # Portfolio case study page
└── README.md
```

---

## 💡 Business Value

This dashboard enables hospital administrators to:

- **Identify and quantify** operational bottlenecks (e.g., 40.7% of patients missing the 30-min target)
- **Optimize staffing** using day/hour heatmaps showing peak demand windows
- **Monitor referral patterns** across 7 departments for capacity planning
- **Track patient satisfaction** trends alongside wait time data
- **Report to executives** through the plain-language Key Takeaways view

---

## 👤 Author

**Paul Adeyemi**  
Financial Data Scientist | MSc Engineering Mathematics (University of L'Aquila & Brno University of Technology)  
📧 Paul2001.timilehin@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/paul-adeyemi-836b4a23) · [GitHub](https://github.com/laplacepaul)
