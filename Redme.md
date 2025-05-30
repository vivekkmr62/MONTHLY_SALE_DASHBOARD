# 📊 Automated Monthly Sales Dashboard – Modi Naturals

This project presents a **fully automated and dynamic Monthly Sales Dashboard** built in **Microsoft Excel**, designed to track brand-wise and channel-wise performance at a regional level. Developed using real use-case logic from an FMCG domain, this dashboard enables decision-makers to monitor sales trends and channel contributions effectively, with minimal manual effort.

---

## 🗂️ Sheet Structure & Workflow

1. **`Data`**
   - Primary source of raw monthly sales data.
   - Maintained in Excel Table format to enable seamless Power Query refresh.

2. **`Clean Data`**
   - Processed using **Power Query** for data transformation and cleansing.
   - Output is loaded directly into the **Excel Data Model** to support scalable pivot-based reporting.

3. **`Helping Sheet`**
   - Acts as the backend layer.
   - Contains:
     - **Pivot tables** connected to the data model
     - **INDEX-MATCH** formulas for dynamic referencing
     - Lookup-driven calculations used for KPI block design

4. **`Graphs`**
   - Front-end dashboard view featuring:
     - Overall Sales (₹)
     - Channel-wise and region-wise breakdown
     - Dynamic visuals with conditional formatting
     - **Slicer-based filtering** (Brand-level)
     - Bar and doughnut charts for enhanced readability

---

## ⚙️ Key Functionalities

- ✅ **Fully Automated** – Just update the raw data, and refresh.
- ✅ **Brand Slicer** – Interactive filtering using slicers for quick brand-specific insights.
- ✅ **Power Query Integration** – Automated data cleansing and transformation.
- ✅ **Data Model-Based Pivot Tables** – Performance-optimized calculations.
- ✅ **INDEX-MATCH Formulas** – Used for dynamic lookups in helper layer.
- ✅ **Visual Highlights** – Conditional formatting on KPIs and bars for quick anomaly spotting.

---

## 📈 Dashboard Preview

### Negative Sales Scenario Snapshot 
https://github.com/vivekkmr62/MONTHLY_SALE_DASHBOARD/blob/main/DASHBOARD_Monthly_Sale%20%281%29.jpeg

### Actual Monthly Performance Snapshot

https://github.com/vivekkmr62/MONTHLY_SALE_DASHBOARD/blob/main/DASHBOARD_Monthly_Sale%20%282%29.jpeg
---

## 📌 Highlights

- Region-wise distribution of sales (East, North, South, West)
- Channel-level insights (General Trade, Modern Trade, Institution, Direct Customer)
- Intuitive layout with slicers, charts, and metrics for executive reporting
- Designed with scalability, automation, and professional aesthetics in mind

---

## 💡 Skills & Tools Demonstrated

- Microsoft Excel (Advanced)
- Power Query (ETL automation)
- Power Pivot / Data Model
- Dashboarding & Storytelling
- INDEX-MATCH & Lookup logic
- Slicer & Conditional Formatting
- Excel Table Design

---

## 🚀 How to Use

1. Open the `.xlsx` file.
2. Replace the raw data in the `Data` sheet with current month data (same structure).
3. Click on `Data > Refresh All` to update Power Query and Pivot Tables.
4. View results in the `Graphs` sheet using slicers or by scrolling through region-wise visual blocks.

---

## 🧑‍💼 About the Author

**Vivek Kumar**  
MIS Executive | Data Analyst in Progress  
Skilled in Power Query, Excel Automation, Power BI, and Sales Reporting.

[LinkedIn] https://www.linkedin.com/in/vivek-kumar-12247014a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

---

> 📌 *Note: The data used is sample/dummy data and does not represent actual business figures.*