# ⚡ EV Cars Dashboard — Power BI Project

A complete Electric Vehicle analytics project built using **Microsoft Power BI** and **Excel**. The project explores EV adoption data across targets, categories, and performance metrics, writing DAX measures, and designing an interactive dashboard to help analysts, policymakers, and EV enthusiasts uncover trends in adoption rates, target achievements, and market distribution.

---

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoftpowerbi&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-6B4FBB?style=for-the-badge&logo=microsoftpowerbi&logoColor=white)
![KPI Analysis](https://img.shields.io/badge/Project-KPI%20Analysis-0078D4?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## 📁 Project Structure

```
EV-Cars-Dashboard/
│
├── EV_Target_Data.xlsx      # EV adoption dataset
├── EV_Cars.pbix             # Power BI dashboard file
└── README.md                # Project documentation
```

---

## 📊 Dataset Overview

The dataset `EV_Target_Data` contains EV performance and target records with columns including:

| Column | Description |
|--------|-------------|
| Vehicle Category | Type / segment of the EV |
| Target | Set adoption or sales target |
| Actual | Recorded actual adoption / sales figure |
| Region / Market | Geographic area of the data |
| Time Period | Month / Quarter / Year of the record |
| Achievement % | Percentage of target achieved |
| EV Type | BEV / PHEV / HEV classification |
| Metric | KPI being tracked (sales, registrations, etc.) |

> **Note:** Update column names above to match your actual dataset columns before publishing.

---

## 📈 Dashboard Visuals

The dashboard includes **11 interactive visuals** across **2 pages**:

### Page 1 — Overview

| Visual | Description |
|--------|-------------|
| **KPI Card 1** | Primary EV performance KPI |
| **KPI Card 2** | Secondary performance metric |
| **KPI Card 3** | Third key indicator |
| **Line Chart** | EV adoption trend over time |
| **Clustered Column Chart** | Category-wise target vs. actual comparison |
| **Bar Chart** | Regional or segment-wise breakdown |
| **Column Chart** | Period-over-period performance |
| **Donut Chart** | Market share distribution by EV type |
| **Slicer** | Interactive filter for cross-visual exploration |
| **Text Box** | Dashboard title / description label |

### Page 2 — Distribution

| Visual | Description |
|--------|-------------|
| **Donut Chart** | Detailed share breakdown across categories |

---

## 🔍 Key Insights

- ⚡ **BEV (Battery Electric Vehicles)** dominate the market share across most regions
- 📈 EV adoption shows a consistent **upward trend** year-over-year
- 🎯 Certain categories consistently **exceed their targets**, while others show a performance gap
- 🌍 Regional distribution reveals strong adoption clusters in specific markets
- ⏱️ Shorter target cycles tend to have **higher achievement rates** compared to annual targets
- 🏆 The **top-performing segment** leads both in volume and target completion percentage

---

## 🛠️ Tools & Features Used

- **Microsoft Power BI Desktop** (v1.31)
- **Microsoft Excel** — Data source & preparation
- **DAX (Data Analysis Expressions)** — KPI measures, target achievement calculations, custom aggregations
- **Power Query (M Language)** — Data cleaning, type transformation & column structuring
- **Data Modeling** — Relationship mapping and field categorization
- KPI Cards, Line, Bar, Column & Donut Charts, Slicers
- Interactive Dashboard with cross-visual filtering

---

## 🚀 How to Use

1. Download both files (`EV_Target_Data.xlsx` and `EV_Cars.pbix`)
2. Open `EV_Cars.pbix` in **Power BI Desktop**
3. If prompted, update the data source path to point to `EV_Target_Data.xlsx`
4. Click **Refresh** to load the latest data
5. Use the **Slicer** to filter all visuals by category or time period
6. Hover over charts to explore individual data point details

---

## 👤 Author
>
> 🔗 [LinkedIn](https://www.linkedin.com/in/your-linkedin/) | 🐙 [GitHub](https://github.com/your-username)

---

⭐ If you found this project helpful, give it a star!

