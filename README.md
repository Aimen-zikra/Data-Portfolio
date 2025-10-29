# Data Portfolio 👩🏻‍💻

Hello! I'm Aimen Zikra, a budding data analyst passionate about turning raw data into actionable insights.

Welcome to my Data Analytics and Engineering Portfolio. I enjoy exploring datasets to uncover trends, optimize business strategies, and support decision-making. This portfolio showcases my key projects, demonstrating skills in data cleaning, exploratory analysis, visualization, SQL, Python (Pandas, NumPy, Matplotlib, Seaborn), and data warehousing.

##  Skills

**Programming & Tools**: Python (Pandas, NumPy), SQL, MySQL, Jupyter Notebook, Matplotlib, Seaborn

**Data Analysis**: EDA, Feature Engineering, Descriptive Statistics, Correlation Analysis

**Data Engineering**: ETL Pipelines, Data Modeling (Star Schema), Data Cleaning & Imputation

**Visualization**: Bar Charts, Pie Charts, Line Plots, Boxplots, Count Plots

**Domains**: E-commerce Sales, Entertainment (Movies), Business Intelligence

## Projects
### 1. 📦 Data Warehouse Project
**Type:** Data Engineering + Analytics

**Tech Stack:** MySQL, SQL, Python (Pandas, NumPy), Jupyter Notebook, MySQL Workbench

**Repository:** https://github.com/Aimen-zikra/Data-Warehouse.git

**Description:**
Built a MySQL-based Data Warehouse integrating ERP and CRM sales data using a Medallion Architecture (Bronze, Silver, Gold layers).
Includes ETL, data modeling, and advanced SQL analytics to derive insights on sales, customers, and products.

#### 🏗️ Architecture Overview
🔹 Medallion Architecture (MySQL Schema Design)
| Layer      | Description                | Implementation                                             |
| ---------- | -------------------------- | ---------------------------------------------------------- |
| **Bronze** | Raw data ingestion         | Loaded via `LOAD DATA INFILE` from CSV/ERP/CRM exports     |
| **Silver** | Cleansed & integrated data | Removed duplicates, standardized formats, merged ERP & CRM |
| **Gold**   | Analytical layer           | Built a **Star Schema** for reporting and analytics        |

> **Schema naming convention:**
bronze_, silver_, and gold_ prefixes ensure clear data lineage and governance.


#### 🧩 Data Modeling
⭐ Star Schema Design

**Fact Table**
- gold_fact_sales — Central fact table containing transactional sales data.

**Dimension Tables**
- gold_dim_customer — Customer attributes and segments
- gold_dim_product — Product details, categories, and pricing

#### 📈 Analytical Highlights
- Built Star Schema for fast query performance.
- Delivered reports on:
  - Top 10 Products by Revenue
  - Monthly Sales & MoM Growth
  - Customer Lifetime Value (CLTV)
  - Regional Sales & Category Profitability

#### 🧮 Dual-Stack Analysis
- SQL queries in MySQL for production-grade analytics.
- Python validation using Pandas for visualization and automation.
  
#### 💼 Business Impact
- Unified ERP + CRM view of sales performance.
- Improved KPI tracking for marketing and operations teams.

---
## 📊 2. Blinkit Sales Data Analysis
**Type:** Exploratory Data Analysis (EDA)

**Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

**Repository:** https://github.com/Aimen-zikra/Blinkit-Analysis.git

#### Description
Analyzed Blinkit’s sales performance to identify key sales drivers across items, outlets, and customer ratings — enabling better inventory and outlet management decisions.

#### 🧩 Key Insights
*  Top Performers: Fruits & Vegetables and Snack Foods generate the highest revenue.
*  Outlet Insights: Tier 2 outlets and Supermarket Type 2 show strongest performance.
*  Customer Ratings: Have minimal impact on sales (r = 0.0113) — other factors dominate.
*  Fat Content: Sales are evenly split between Low Fat and Regular products.

#### 📈 Highlights
*  Cleaned and standardized over 8,500+ sales records for accuracy and consistency.
*  Engineered new sales-level features and performed statistical correlation analysis.
*  Developed visualizations to reveal insights on item performance, outlet type trends, and sales distribution.

#### 💡 Business Impact
*  Enhanced inventory and stocking strategies for high-performing categories.
*  Refined marketing and promotion plans based on data-driven insights.
*  Supported strategic decision-making for outlet expansion and product prioritization.

---
## 🎬 3. Netflix Movie Data Analysis
**Type:** Exploratory & Business Data Analysis

**Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

**Repository:** https://github.com/Aimen-zikra/Netflix-Analysis.git

#### Description
Explored a dataset of 9,826 Netflix movies to inform content strategy, focusing on genres, popularity, ratings, and release trends to reduce churn and optimize investments.

#### 🔍 Key Findings

| Question             | Answer                             |
| -------------------- | ---------------------------------- |
| Most Frequent Genre  | 🎭 Drama (3,744 titles)            |
| Most Popular Movie   | 🕷️ *Spider-Man: No Way Home*      |
| Highest Vote Average | *Spider-Man: No Way Home* (8.3/10) |
| Most Productive Year | 📅 2021 (714 releases)             |

#### 📊 Insights

* Drama dominates — ~38% of all Netflix movies.
* Popularity ≠ Ratings — some top-rated titles lack strong viewership.
* Action/Sci-Fi genres correlate with top popularity metrics.
* Post-2020 boom in releases shows content expansion after pandemic.

#### 🧠 Business Recommendations

- Increase investment in Drama + Action/Sci-Fi content.
- Use popularity-based targeting for recommendations.
- Leverage release-year patterns for production scheduling.

---
# Contact

**Email:** aimenzikraa@gmail.com
**GitHub:** yourusername
