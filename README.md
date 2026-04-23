# 🐾 Waggle Pet Activity — Power BI Dashboard

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6e40c9,50:c9407a,100:ff6ec7&height=120&section=header" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=00B4B4&center=true&vCenter=true&width=700&lines=🐾+Waggle+Pet+Activity+Analysis;Power+BI+%7C+DAX+%7C+Data+Modeling;Lapdog+vs+Lapcat+%7C+US+Market+Insights" alt="Typing SVG" />

[![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiNjFlM2IxMDEtODU4Zi00ZTcwLWE5YWItNDkwNmUyMzBlOWJmIiwidCI6IjNlMTE2YjM1LWRkMjgtNDY2ZS1hZjdhLWFlZjZkZDMwYzY0MCIsImMiOjl9&pageName=0a3ea1486f61ad002ed5)
![DAX](https://img.shields.io/badge/DAX-Measures-6e40c9?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-Relational-c9407a?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Program](https://img.shields.io/badge/We'RHERE-Foundation-0078D4?style=for-the-badge)

</div>

---

## 📌 Project Overview

This project presents a comprehensive **Power BI dashboard** developed for **Waggle**, a US-based pet-tech startup. The business objective was twofold:

1. Evaluate the sustained performance of **Lapdog** — Waggle's flagship wearable tracker for dogs
2. Assess the commercial viability of **Lapcat** — the pilot-phase tracker for cats

The analysis draws on pet activity data, demographic profiles, and household financial data collected across all 50 US states between 2018 and 2020.

> *"Can Waggle successfully pivot from dogs to cats? The data tells a clear story."*

---

## 🔗 Live Interactive Dashboard

[![View Report](https://img.shields.io/badge/🚀_Live_Dashboard-Explore_Now-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiNjFlM2IxMDEtODU4Zi00ZTcwLWE5YWItNDkwNmUyMzBlOWJmIiwidCI6IjNlMTE2YjM1LWRkMjgtNDY2ZS1hZjdhLWFlZjZkZDMwYzY0MCIsImMiOjl9&pageName=0a3ea1486f61ad002ed5)

---

## 🚀 Key Insights & Strategic Findings

| # | Finding | Detail |
|---|---------|--------|
| 🐶 | **Lapdog dominates** | Steady +18% increase in daily step counts from 2018 to 2020 |
| 🐱 | **Lapcat pilot gap** | 1,000 units deployed — but avg. cat age is **10.1 years** (senior demographic) |
| 🎯 | **Strategic pivot needed** | Marketing must shift toward **younger cat owners** (cats aged 1–4) |
| 🗺️ | **Eastern US = top market** | Washington DC, NYC, Philadelphia show strongest device engagement |
| 💰 | **High-income opportunity** | $75–100k households show highest engagement; $100k+ show premium spending |

---

## 📊 Dashboard Pages

### 🏠 Page 1 — Home
Navigation hub introducing the project scope, dataset size, and analysis period.

![Home](screenshots/01_Home.png)

---

### 🐱🐶 Page 2 — Lapcat vs Lapdog
Side-by-side comparison of:
- Average daily step counts (2018–2020 trend)
- Age and weight distribution
- Activity level differences between species
- Population split visualization

![Lapcat vs Lapdog](screenshots/02_Lapcat_vs_Lapdog.png)

---

### 📊 Page 3 — General Info
Technical deep-dive including:
- Top dog and cat breeds by usage
- Activity duration by time of day
- Step count distribution by age group
- Weight vs. activity correlation

![General Info](screenshots/03_General_Info.png)

---

### 👨‍👩‍👧 Page 4 — Family Info
Household-level insights:
- Average income per pet owner group
- Annual pet spending breakdown
- US geographic market heatmap
- Income bracket distribution

![Family Info](screenshots/04_Family_Info.png)

---

### 🔍 Page 5 — Family Deep Dive
Advanced segmentation:
- Spending categories (food, vet, grooming, accessories, insurance)
- Family size vs. pet activity correlation
- City-level engagement analysis
- Full strategic recommendation summary

![Family Deep Dive](screenshots/05_Family_Deep_Dive.png)

---

## 🛠️ Tech Stack & Skills Applied

```
Power BI Desktop
├── Data Modeling
│   ├── Relationships between pet, family & tracker tables
│   └── Star schema design for optimal query performance
│
├── DAX Measures
│   ├── Average Dogs Step / Average Cats Step
│   ├── Average Income (filtered by pet type)
│   ├── Average Activity Duration (min)
│   ├── Average Weights
│   └── Dynamic population counts with CALCULATE
│
├── Interactive Visuals
│   ├── Line charts (step trend 2018–2020)
│   ├── Bar charts (breed breakdown, spending)
│   ├── Map visual (US geographic distribution)
│   ├── Card KPIs
│   └── Slicers (pet type, age group, state)
│
└── Geographic Mapping
    └── US-wide address data — 100% geocoding accuracy
```

---

## 💡 Business Recommendations

Based on the data analysis:

**1. Reposition Lapcat marketing**
Current Lapcat users are predominantly senior cats (avg. 10 years). Activity data for younger cats (1–4 yrs) shows nearly double the step counts. A marketing shift toward younger cat demographics is strongly supported by the data.

**2. Double down on Lapdog in Eastern US**
Washington DC, NYC, and Philadelphia show the highest device engagement. A focused campaign in these metro areas would maximize ROI.

**3. Develop a premium tier**
Households earning $100k+ demonstrate above-average pet spending willingness. A premium Lapdog/Lapcat bundle with advanced health analytics could capture this segment.

**4. Leverage multi-person households**
Families with 3+ members show ~20% higher pet activity. Targeted family-oriented campaigns could increase engagement rates.

---

## 📂 Repository Structure

```
Waggle-PowerBI/
├── VIT-Capstone_Project_2.pbix     ← Power BI report file
├── screenshots/
│   ├── 01_Home.png
│   ├── 02_Lapcat_vs_Lapdog.png
│   ├── 03_General_Info.png
│   ├── 04_Family_Info.png
│   └── 05_Family_Deep_Dive.png
└── README.md
```

---

## 📝 About This Project

This dashboard was developed as part of the **Data Engineering & Analytics Program** at **We'RHERE Foundation** (Amsterdam, 2025–2026).

The program covered end-to-end data workflows including pipeline engineering, data modeling, and BI visualization. This capstone project focuses on the analytics and visualization layer, demonstrating real-world business storytelling with Power BI.

---

<div align="center">

**Developed by Gamzenur Uzunlu**
*Data Engineer | Power BI Developer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gamzenuruzunlu-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gamzenuruzunlu/)
[![GitHub](https://img.shields.io/badge/GitHub-pinhanderler-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pinhanderler)
[![Email](https://img.shields.io/badge/Email-pinhanderler@gmail.com-c9407a?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pinhanderler@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff6ec7,50:c9407a,100:6e40c9&height=80&section=footer" width="100%"/>

</div>
