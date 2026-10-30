# 📊 Sales & Orders Analytics Dashboard - Power BI & Excel Portfolio
📌 Project Overview
This project delivers an enterprise-grade, multi-page business intelligence suite designed to monitor and evaluate commercial performance across orders, products, suppliers, and customers. The goal is to transform raw operational transactions into interactive, executive-ready insights that streamline decision-making, track key performance indicators (KPIs), and uncover operational bottlenecks.

📂 Dataset Information
- Scope: Comprehensive commercial transactional data covering customer purchasing habits, product categories, supplier performance, and regional distribution.
- Core Dimensions & Metrics: Order volume, revenue generation, supplier fulfillment rates, customer demographics, and geographical performance.
- Deliverable: A 6-page interactive dashboard suite equipped with advanced drill-through navigation and root-cause analysis tools.

🛠️ Tech Stack & Workflow
- Business Intelligence: Power BI Desktop & Power Service (Interactive Dashboards, Drill-Through, Decomposition Trees).
- Advanced Analytics & DAX: Custom measure formulation for time intelligence, running totals, Year-over-Year growth, and profit margins.
- Data Transformation & ETL: Power Query for data cleaning, type correction, normalization, and relational Star Schema modeling.
- Spreadsheet Modeling: Microsoft Excel (Advanced formulas, Pivot Tables & Charts, data validation, and preliminary data exploration).
- Visual Mapping: Azure Maps integrated for regional geographic performance tracking.

🔍 Key Workflow & Steps
1. ETL & Data Preparation: Imported multi-source transactional datasets into Power Query, performing rigorous data cleaning, handling missing values, and standardizing data formats.
2. Data Modeling & Star Schema: Structured relational table relationships to optimize query performance and ensure accurate cross-filtering across visuals.
3. DAX Formulation & Metrics Design: Authored custom DAX calculations and time intelligence functions to dynamically evaluate sales trends and profitability margins.
4. Interactive Dashboard Architecture: Designed a 6-page multi-layered report featuring dynamic KPI summary cards, trend lines, geographic mapping, and decomposition trees.
5. Root-Cause Analysis Setup: Configured drill-through navigation to empower leadership to drill down from high-level summaries into granular operational anomalies.

📊 Key Insights & Business Value
- Executive Visibility: Replaces manual spreadsheet reporting with an automated, single-pane-of-glass interface to track commercial health instantly.
- Operational Efficiency: Rapidly identifies underperforming regions, product categories, and supplier delays, enabling leadership to take corrective action.
- Decision Acceleration: Empowers sales directors and regional managers with self-service drill-downs and geographic insights to optimize inventory and marketing strategies.

📁 Repository Structure
├── Sales_Orders_Dataset.xlsx               # Raw / Staged transactional dataset
├── Sales_Orders_Analytics_Dashboard.pbix   # Power BI interactive report suite
├── SQL_Queries/                            # (Optional) Data extraction & backend scripts
│   └── sales_analysis.sql                  
├── dashboard_preview_overview.png          # Visual output / dashboard screenshot
├── regional_map_analysis.png               # Visual output / geographic breakdown
└── README.md                               # Project Documentation