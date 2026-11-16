

<p align="center"> <img src="Dashboard_main.png" alt="Overview page" width="100%"> </p>
# 🚦 Road Accident Analytics Dashboard | Power BI

An interactive, 8-page Power BI dashboard analysing **660,679 UK road accident records (2019–2022)** across 422 districts to identify accident patterns, severity, casualties, and contributing factors.

## 📊 Project Highlights

- **660,679** Total Accidents
- **896,568** Total Casualties
- **1,209,872** Vehicles Involved
- **422** Districts Analysed
- **15 Business Questions** Addressed
- **8 Interactive Dashboard Pages**

## 🛠️ Tools & Technologies

- **Power BI Desktop:** Dashboard development and data modelling
- **Power Query (M):** Data cleaning and transformation
- **DAX:** 16 measures using CALCULATE, DIVIDE, MAXX, RANKX, VALUES, and ALL
- **Data Visualization:** KPI cards, bar, column, donut, line, area, matrix, and map visuals

## 🔄 Project Workflow

1. Data understanding and profiling
2. Data cleaning and transformation using Power Query
3. Data modelling and calculated date columns
4. DAX measure creation and KPI calculations
5. Analysis of 15 business questions
6. Dashboard development and navigation
7. Measure validation and key insights generation

## 📈 Dashboard Pages

1. **Overview:** KPIs, accident trends, vehicle types, and map
2. **Accident Severity:** Fatal, serious, and slight accidents
3. **Urban vs Rural:** Accident distribution and monthly trends
4. **Road Conditions:** Weather, lighting, and road surface analysis
5. **Measures Verification:** Validation of DAX calculations
6. **Map Wise Analysis:** Accident locations using latitude and longitude
7. **All KPIs:** Consolidated performance metrics
8. **Key Insights:** Summary of important findings

## 💡 Key Insights

- Slight accidents account for **85.3%** of total accidents.
- Cars are involved in **75.4%** of accidents.
- Single carriageways account for **74.5%** of accidents.
- Urban areas contribute **63.8%** of total accidents.
- November records the highest accidents and casualties.
- Birmingham has the highest accident count (**13,491**).
- Yearly accidents declined by approximately **21%** between 2019 and 2022.
- Flooded roads show a higher fatal accident share (**2.26%**) than dry roads (**1.29%**).

## 🧹 Data Quality & Validation

- Handled missing values using `Unknown` without deleting records.
- Corrected date formats and standardised text columns.
- Handled coordinate errors while retaining records.
- Verified DAX measures against raw data.
- Documented district naming inconsistencies and geocoding limitations.

## 🚀 How to Run

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop).
2. Download `Accident_data_project.pbix` from this repository.
3. Open the file in Power BI Desktop.
4. If prompted, reconnect the source to `data/accident_data.csv`.
5. Explore all eight dashboard pages using the navigation panel.

## 🔮 Future Improvements

- Add Year, Region, and Vehicle Type slicers.
- Improve district-level data accuracy.
- Add year-over-year analysis using a Date table.
- Develop casualty density heatmaps.
- Publish the dashboard to Power BI Service.

## 👨‍💻 Author

**Avirag**

- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/atmakumaryadav/)
- GitHub: [Your GitHub Profile](YOUR_GITHUB_URL)

⭐ If you find this project useful, consider giving this repository a star!
