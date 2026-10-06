# 🏙️ Dubai Real Estate Analytics Dashboard | Power BI

## 📌 Project Overview

This project presents an interactive **Dubai Real Estate Analytics Dashboard** developed in **Microsoft Power BI** using a synthetic dataset of **12,000 real estate transactions**.

The dashboard is designed to analyze real estate performance across multiple dimensions including **sales value, developers, projects, areas, property types, property sizes, pricing and transaction patterns**.

The project demonstrates practical skills in **Power BI, DAX, data modeling, data visualization, KPI development and interactive dashboard design**.

> **Disclaimer:** This project uses synthetic data created for learning and portfolio purposes. Developer names such as Emaar, DAMAC, Nakheel, Sobha Realty, Binghatti and others are used only as categorical labels. The figures shown do not represent actual company or Dubai real estate market performance.

---

## 🎯 Project Objectives

The dashboard was developed to answer business questions such as:

- What is the overall sales performance of the real estate portfolio?
- Which developers generate the highest sales value?
- Which projects contribute the most to sales?
- Which areas have the highest sales value and price per square foot?
- How does property size relate to property value?
- Which property types generate the most transactions?
- How are transactions distributed across bedroom categories?
- What proportion of transactions are off-plan versus ready properties?
- How do buyer and sales-channel patterns differ across the portfolio?

---

## 📊 Dataset

The project uses **12,000 synthetic Dubai real estate transactions**.

### Key Fields

- Transaction ID
- Transaction Date
- Developer
- Project Name
- Area
- Property Type
- Bedrooms
- Property Size (Sq.Ft.)
- List Price (AED)
- Discount %
- Sale Value (AED)
- Project Status
- Expected Handover Date
- Sales Channel
- Buyer Nationality
- Payment Method
- Commission (AED)

---

## 📈 Key KPIs

| KPI | Value |
|---|---:|
| Total Transactions | 12,000 |
| Total Sales Value | AED 44.04B |
| Average Property Value | AED 3.67M |
| Average Price / Sq.Ft. | AED 1.85K |
| Off-Plan Share | 64.58% |
| Total Commission | AED 1.21B |
| Total Developers | 8 |
| Total Projects | 280 |
| Total Areas | 12 |
| Average Property Size | 1.98K Sq.Ft. |

---

# 📑 Dashboard Pages

## 1️⃣ Executive Overview

Provides a high-level view of overall real estate performance.

### KPIs
- Total Transactions
- Total Sales Value
- Average Property Value
- Average Price / Sq.Ft.
- Off-Plan Share
- Total Commission

### Visualizations
- Monthly Sales Value Trend
- Project Status
- Top 5 Developers by Sales Value
- Transactions by Property Type
- Top 5 Areas by Sales Value

---

## 2️⃣ Developer & Project Performance

Analyzes developer and project-level performance.

### KPIs
- Total Developers
- Total Projects
- Average Price / Sq.Ft.
- Average Property Value
- Total Sales Value

### Visualizations
- Developer Ranking by Sales Value
- Average Price / Sq.Ft. by Developer
- Developer Price Positioning
- Top 10 Projects by Sales Value
- Transactions by Developer
- Top 5 Project Performance

The **Developer Price Positioning** scatter plot compares developers using average price per square foot and average property value.

---

## 3️⃣ Area & Property Analysis

Examines geographical and property-level trends across the portfolio.

### KPIs
- Total Areas
- Total Transactions
- Average Property Size
- Average Price / Sq.Ft.
- Total Sales Value

### Visualizations
- Top 5 Areas by Sales Value
- Average Price / Sq.Ft. by Area
- Property Size vs Average Sale Value
- Property Size Distribution
- Transactions by Property Type
- Transactions by Bedroom

The property-size scatter plot provides a transaction-level view of the relationship between **property size and sale value**.

---

## 4️⃣ Buyer & Sales Analysis

Analyzes customer composition, payment behavior and sales-channel performance.

### KPIs
- Total Transactions
- Total Sales Value
- Average Property Value
- Total Commission
- Average Discount

### Planned / Final Visualizations
- Transactions by Buyer Nationality
- Sales Value by Buyer Nationality
- Transactions by Payment Method
- Transactions by Sales Channel
- Sales Value by Sales Channel
- Commission by Sales Channel

---

## 🎛️ Interactive Filters

The dashboard includes interactive slicers that allow users to analyze performance dynamically by:

- Developer
- Year
- Area
- Project Status

Selections automatically update the relevant KPIs and visualizations.

---

## 🔍 Key Insights

- The synthetic portfolio contains **12,000 transactions** representing approximately **AED 44.04B** in total sales value.
- The average property value is approximately **AED 3.67M**.
- Average pricing is approximately **AED 1.85K per Sq.Ft.**
- Approximately **64.58% of transactions are Off-Plan** in the synthetic dataset.
- **Emaar** records the highest sales value among the developer categories in this dataset.
- **Palm Jumeirah** records the highest sales value among the analyzed areas.
- Apartments account for the largest share of transactions.
- Property values generally increase as property size increases, although substantial variation is visible across individual transactions.
- The dashboard allows developer, area, year and project-status performance to be compared interactively.

---

## 🛠️ Tools & Techniques

### Microsoft Power BI
- Data Modeling
- DAX Measures
- Calculated Columns
- KPI Cards
- Interactive Slicers
- Scatter Plots
- Bar & Column Charts
- Donut Charts
- Tables
- Cross Filtering
- Custom Sorting
- Dashboard Formatting

### DAX

Examples of measures used in the project include:

**Total Transactions**

    Total Transaction =
    DISTINCTCOUNT(
        Dubai_Real_Estate_Analytics_12000_Transactions_SYNTHETIC[Transaction_ID]
    )

**Average Price per Sq.Ft.**

    Average Price per SqFt =
    DIVIDE(
        [Total Sales Value],
        [Total Property Size]
    )

Additional measures were created for:

- Total Sales Value
- Average Property Value
- Total Commission
- Off-Plan Transactions
- Off-Plan Share
- Average Discount
- Total Developers
- Total Projects
- Total Areas
- Average Property Size

---

## 🗂️ Data Model

The Power BI model includes:

- Main Real Estate Transaction Table
- Calendar Table
- Supporting Dimension Tables
- Dedicated Measures Table

A calendar table is used to support date-based filtering and chronological month/year analysis.

---

## 💼 Skills Demonstrated

This project demonstrates practical ability in:

- Business Intelligence
- Real Estate Analytics
- Data Modeling
- DAX
- KPI Development
- Data Visualization
- Dashboard Design
- Business Performance Analysis
- Interactive Reporting
- Data Storytelling

---

## 📁 Repository Structure

    Dubai-Real-Estate-Analytics-Power-BI-Dashboard/
    │
    ├── README.md
    ├── Dashboard/
    │   └── Dubai_Real_Estate_Analytics.pbix
    │
    ├── Dataset/
    │   ├── Dubai_Real_Estate_Analytics_12000_Transactions_SYNTHETIC.csv
    │   └── Dubai_Real_Estate_Analytics_Data_Dictionary.csv
    │
    └── Screenshots/
        ├── Executive_Overview.png
        ├── Developer_Project_Performance.png
        ├── Area_Property_Analysis.png
        └── Buyer_Sales_Analysis.png

---

## 📷 Dashboard Preview

### Executive Overview
![Executive Overview](Screenshots/Executive_Overview.png)

### Developer & Project Performance
![Developer & Project Performance](Screenshots/Developer_Project_Performance.png)

### Area & Property Analysis
![Area & Property Analysis](Screenshots/Area_Property_Analysis.png)

### Buyer & Sales Analysis
![Buyer & Sales Analysis](Screenshots/Buyer_Sales_Analysis.png)

---

## ⚠️ Disclaimer

This dashboard was created as a **portfolio and learning project using synthetic data**.

The developer names, locations and other categorical labels are used for analytical demonstration only. All transaction values, sales figures, commissions, project performance figures and other metrics are synthetic and **should not be interpreted as actual Dubai market or company performance**.

---

## 👤 Author

**Harshit Tiwary**

Data Analytics | HR Analytics | Power BI | Advanced Excel | SQL
