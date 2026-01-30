NexusAnalytics: Supply Chain Risk & Revenue Optimization

📌 Business Problem Statement
In modern global commerce, logistics delays and fraudulent transactions directly erode profit margins. For a large-scale distributor like DataCo, identifying "where" and "why" these inefficiencies happen is critical.

NexusAnalytics was built to solve three core business challenges:
Late Delivery Risk: Predicting shipments likely to be delayed before they leave the warehouse.
Revenue Leakage: Identifying regions with high sales volume but negative net profit.
Customer Intelligence: Segmenting the global customer base to prioritize high-value B2B and B2C relationships.

🛠 Tech Stack
Data Engineering: SQL (PostgreSQL), Python (SQLAlchemy).
Data Analysis: Pandas, NumPy, Matplotlib, Seaborn.
Machine Learning: Scikit-Learn (Random Forest, XGBoost).
Business Intelligence: Power BI / Tableau.
Version Control: Git & GitHub.

📊 Data Architecture
This project utilizes the DataCo Smart Supply Chain Dataset, a complex 180,000-row dataset featuring 52 variables across logistics, finance, and production. To ensure system performance, the data was normalized into a Star Schema:

tbl_customers: Demographics and segmentation data.
tbl_orders: Core transaction records and status.
tbl_products: Categorization and pricing.
tbl_shipping: Logistics modes and lead-time tracking.
tbl_finance: Profitability and fraud flags.
  Note: The raw dataset is excluded via .gitignore to maintain repository performance.

🚀 12-Week Roadmap
Week 1-3: Data Engineering, SQL Schema Design, and Operational Logic.
Week 4-6: Python Integration and Exploratory Data Analysis (EDA).
Week 7-9: RFM Customer Segmentation and Predictive Risk Modeling.
Week 10-12: BI Dashboarding, Automation, and Executive Reporting.

📂 Project Structure
Plaintext
├── data/           # (Excluded) Raw DataCo CSV files
├── sql_scripts/    # Table DDL, CTEs, and Views
├── notebooks/      # Jupyter Notebooks for EDA and Modeling
├── src/            # Python scripts for ETL and Automation
├── docs/           # ERD diagrams and Weekly Internship Reports
└── README.md       # Project Overview
