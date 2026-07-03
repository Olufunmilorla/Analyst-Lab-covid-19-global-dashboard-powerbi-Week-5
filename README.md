📊 COVID-19 Global Dashboard | Microsoft Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analytics-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-success)
![MIT License](https://img.shields.io/badge/License-MIT-green)

An interactive **Microsoft Power BI** dashboard built using the **Johns Hopkins University (JHU CSSE) COVID-19 Global Time-Series Dataset**. This project demonstrates an end-to-end analytics workflow, from data preparation and modeling to KPI development, visualization, and data storytelling.

---

# 📑 Table of Contents

- Project Overview
- Business Problem
- Project Objectives
- Dataset
- Tools & Technologies
- Data Preparation
- Data Modeling
- DAX Measures
- Dashboard Features
- Key KPIs
- Dashboard Preview
- Key Insights
- Recommendations
- Skills Demonstrated
- Repository Structure
- How to Use
- Future Improvements
- Author
- License

---

# 📌 Project Overview

The COVID-19 pandemic produced one of the largest publicly available health datasets in history. While the raw data contains valuable information, it is difficult to interpret without proper analysis and visualization.

This project transforms global COVID-19 time-series data into an interactive dashboard that enables users to monitor trends, compare countries, explore geographic distribution, and evaluate key pandemic metrics over **1,143 reporting days (22 January 2020 – 9 March 2023)**.

Developed as part of the **AnalystLab Africa Data Analytics Internship**, this project showcases practical Business Intelligence and data visualization skills using Microsoft Power BI.

---

# 🎯 Business Problem

Healthcare organizations and decision-makers need reliable and interactive reporting to understand the spread and impact of COVID-19. Raw datasets alone make it difficult to identify trends or compare countries effectively.

This dashboard addresses that challenge by presenting critical metrics through interactive visualizations and KPIs that support data-driven decision-making.

---

# 🎯 Project Objectives

- Analyze global COVID-19 trends.
- Track confirmed, recovered, and death cases.
- Compare countries by pandemic impact.
- Visualize worldwide case distribution.
- Build interactive KPI reporting.
- Communicate findings through data storytelling.

---

# 📂 Dataset

**Source:** Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE)

Files used:
- `time_series_covid19_confirmed_global.csv`
- `time_series_covid19_deaths_global.csv`
- `time_series_covid19_recovered_global.csv`

The dataset contains cumulative daily COVID-19 records by country/region, province/state, latitude, longitude, and reporting date.

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Microsoft PowerPoint
- GitHub

---

# 🧹 Data Preparation

The datasets were prepared using Power Query by:

- Importing and validating multiple CSV files
- Reviewing data types
- Handling missing values
- Unpivoting date columns
- Cleaning and standardizing data
- Preparing tables for relationship modeling

---

# 🔗 Data Modeling

A relational model was created using the Confirmed, Death, and Recovered datasets with supporting date relationships to ensure accurate calculations and interactive filtering across all visuals.

---

# 📐 DAX Measures

Custom DAX measures were created for:

- Total Confirmed Cases
- Total Recovered Cases
- Total Death Cases
- Death Rate
- Daily New Cases
- Time-based calculations

These measures dynamically update based on user selections.

---

# 📊 Dashboard Features

- KPI Cards
- Global COVID-19 Trend Analysis
- Top 10 Countries by Confirmed Cases
- Global Distribution Map
- Recovery vs. Death Comparison
- Daily New Cases Trend
- Top 10 Countries by Total Death Cases
- Interactive Date, Country, and Province/State slicers
- Cross-filtering between visuals

---

# 📈 Key Performance Indicators

| KPI | Value |
|------|------:|
| Total Confirmed Cases | **677 Million** |
| Total Recovered Cases | **131 Million** |
| Total Death Cases | **7 Million** |
| Death Rate | **1.02%** |


---

# 🖼 Dashboard Preview

Add your screenshots inside the **Images** folder.

```text
Images/
├── dashboard-overview.png
├── trend-analysis.png
├── map-analysis.png
└── kpi-cards.png
```




---

# 🔍 Key Insights

- Global confirmed COVID-19 cases increased significantly throughout the reporting period, with the highest growth observed during **2022**.
- The **United States** recorded the highest cumulative number of confirmed COVID-19 cases.
- The **United States** also recorded the highest cumulative number of COVID-19 deaths.
- **India** recorded the highest cumulative number of recovered cases.
- The map visualization demonstrates the widespread global impact of COVID-19 across major regions.
- Despite more than **677 million confirmed cases**, the dashboard reports an overall **death rate of 1.02%**, indicating recoveries substantially exceeded fatalities.

---

# 💡 Recommendations

- Strengthen global disease surveillance systems.
- Prioritize healthcare resources in high-impact regions.
- Continue investment in healthcare infrastructure.
- Promote international collaboration and transparent data sharing.
- Leverage interactive dashboards for evidence-based public health decisions.

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Power Query
- Data Transformation
- Data Modeling
- DAX
- Dashboard Design
- KPI Development
- Data Visualization
- Business Intelligence
- Data Storytelling
- Analytical Thinking

---

# 📁 Repository Structure

```text
covid19-global-dashboard-powerbi/
│
├── Dashboard/
│   └── COVID19_Global_Dashboard.pbix
├── Data/
├── Images/
├── Presentation/
├── README.md
├── LICENSE
└── .gitignore
```

---

# ▶️ How to Use

1. Clone this repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. Refresh the dataset if required.
4. Explore the dashboard using the available filters and slicers.

---

# 🔮 Future Improvements

- Live API integration
- Automated data refresh
- Vaccination analytics
- Predictive analytics
- Mobile dashboard optimization

---

# 👤 Author

**Olufunmilola Ogunmefun**

**Aspiring Data Analyst | Power BI Developer | Business Intelligence**

- GitHub: https://github.com/Olufunmilorla
- LinkedIn: https://www.linkedin.com/in/olufunmilola11

---

# 📄 License

This project is licensed under the **MIT License**.

---

⭐ If you found this project helpful, consider giving the repository a star.
