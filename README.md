# 🛒 Power BI Store Analysis Dashboard

This project is a complete **data analysis workflow** built in **Power BI**, starting from raw data cleaning to an interactive dashboard.  
It simulates a **store performance analysis** project, covering sales, employees, branches, and products.

---

## 📊 Project Overview
- **Tool used:** Power BI Desktop  
- **Data Preparation:** Power Query (cleaning, transformations)  
- **Modeling:** Star schema relationships between Orders, Products, Branches, and Employees  
- **Measures:** Custom DAX for KPIs (Total Sales, Total Orders, Avg Experience, Top Country by Sales, etc.)  
- **Visualization:** Professional dashboard with slicer panel, KPI cards, charts, and tables  

---

## 🔧 Data Preparation (Power Query)
- Removed duplicates and handled missing values  
- Converted data types (dates, numbers, text)  
- Created a calculated column for **Years of Experience** (from Hiring Date)  
- Standardized columns for consistency  

---

## 📐 Data Modeling
- **Fact table:** Orders  
- **Dimension tables:** Products, Employees, Branches, Date  
- One-to-many relationships between dimensions and fact table (star schema)  

---

## 📈 Dashboard Features
- **KPI Cards:** Total Sales, Total Orders, Total Employees, Average Experience  
- **Bar Chart:** Total Orders by Country  
- **Line Chart:** Monthly Sales Trend  
- **Donut Chart:** Orders by Category  
- **Table:** Top Employees by Orders and Sales  
- **Custom Measure:** Top Country/Branch by Sales (dynamic KPI)  
- **Filter Panel:** Country, Category, Status, Month/Quarter  

---

## 🚀 Key Insights
- Identify the **best-performing countries and branches**  
- Monitor **monthly sales trends**  
- Compare **category contributions** (Hot Drinks, Cold Drinks, Desserts)  
- Track **employee performance** and sales contribution  

---

## 📂 Repository Structure
📁 Store-Analysis
├── Store Analysis.pbix # Power BI file
├── README.md # Project documentation
└── Data/ # (Optional) Source data files



## 🛠️ How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedH782/Power-Bi-Store-analysis-Dashboard.git
Open Store Analysis.pbix in Power BI Desktop.

Explore the dashboard and slicers interactively.

📸 Dashboard Preview
(Add a screenshot of your dashboard here, e.g., screenshot.png)

📌 Skills Demonstrated
Data Cleaning & Transformation (Power Query)

Data Modeling (Star Schema, Relationships)

DAX Calculations (KPIs, aggregations, TOPN logic)

Dashboard Design & Visualization

📄 License
This project is licensed under the MIT License – feel free to use and adapt.
