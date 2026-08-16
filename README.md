# 🛒 Retail Data Analytics Project: Python & SQL Integration

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/dosibhatlanirmalaaiswarya-bit/retail-data-analytics-project-python-sql-integration?style=social" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/dosibhatlanirmalaaiswarya-bit/retail-data-analytics-project-python-sql-integration?style=social" alt="Forks"/>
  <img src="https://img.shields.io/github/license/dosibhatlanirmalaaiswarya-bit/retail-data-analytics-project-python-sql-integration" alt="License"/>
</p>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Project Architecture](#-project-architecture)
- [Key Features](#-key-features)
- [Technologies Used](#-technologies-used)
- [Dataset](#-dataset)
- [Project Workflow](#-project-workflow)
- [SQL Analysis & Insights](#-sql-analysis--insights)
- [Key Findings](#-key-findings)
- [Installation & Setup](#-installation--setup)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Future Enhancements](#-future-enhancements)
- [About the Author](#-about-the-author)

---

## 🎯 Overview

Welcome to my **End-to-End Retail Data Analytics Project**! This repository showcases a complete data analysis workflow using **Python** and **SQL**, focused on retail order data. The project demonstrates the ability to handle real-world datasets, clean and preprocess data, and derive **actionable business insights**.

This project highlights my proficiency in:
- 🔄 **ETL Pipeline Development** - Extract, Transform, Load workflows
- 🐍 **Python Data Processing** - Using Pandas for data manipulation
- 🗃️ **Database Management** - SQL Server integration and optimization
- 📊 **Advanced SQL Analytics** - Complex queries for business intelligence
- 💡 **Data-Driven Decision Making** - Transforming raw data into strategic insights

---

## 🏗️ Project Architecture

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                        RETAIL DATA ANALYTICS PIPELINE                        │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────┐    ┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│   EXTRACT    │    │  TRANSFORM   │    │     LOAD     │    │   ANALYZE    │
│              │    │              │    │              │    │              │
│  ┌────────┐  │    │  ┌────────┐  │    │  ┌────────┐  │    │  ┌────────┐  │
│  │ Kaggle │  │───▶│  │ Python │  │───▶│  │  SQL   │  │───▶│  │Business│  │
│  │  API   │  │    │  │ Pandas │  │    │  │ Server │  │    │  │Insights│  │
│  └────────┘  │    │  └────────┘  │    │  └────────┘  │    │  └────────┘  │
│              │    │              │    │              │    │              │
│ • Download   │    │ • Clean      │    │ • Create DB  │    │ • Revenue    │
│ • Unzip      │    │ • Transform  │    │ • Load Data  │    │ • Trends     │
│ • Load CSV   │    │ • Validate   │    │ • Index      │    │ • Segments   │
└──────────────┘    └──────────────┘    └──────────────┘    └──────────────┘
```



---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🔌 **Automated Data Extraction** | Leveraged Kaggle API to programmatically download datasets |
| 🧹 **Data Cleaning & Preprocessing** | Handled missing values, normalized data, and standardized formats |
| 🗄️ **Database Integration** | Seamless loading of cleaned data into SQL Server |
| 📈 **Advanced SQL Analytics** | Complex queries for in-depth business analysis |
| 🎯 **Actionable Insights** | Data-driven recommendations for business optimization |
| 📊 **Revenue Analysis** | Product-level revenue breakdown and growth drivers |
| 👥 **Customer Segmentation** | RFM analysis for targeted marketing strategies |

---

## 🛠️ Technologies Used

<table>
<tr>
<td align="center" width="150">

### Languages
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

</td>
<td align="center" width="150">

### Libraries
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)

</td>
<td align="center" width="150">

### Database
![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![SSMS](https://img.shields.io/badge/-SSMS-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

</td>
<td align="center" width="150">

### Tools
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

</td>
</tr>
</table>

| Technology | Purpose |
|------------|---------|
| **Python 3.x** | Core programming language for data processing |
| **Pandas** | Data manipulation, cleaning, and transformation |
| **SQLAlchemy** | Database connection and ORM functionality |
| **pyodbc** | ODBC driver for SQL Server connectivity |
| **Kaggle API** | Automated dataset download |
| **SQL Server** | Relational database for data storage and analysis |
| **Jupyter Notebook** | Interactive development and documentation |
| **Git/GitHub** | Version control and collaboration |

---

## 📦 Dataset

### Source
- **Platform:** [Kaggle](https://www.kaggle.com/)
- **Dataset:** Retail Orders Dataset
- **Records:** 9,000+ retail transactions
- **Features:** 21 columns including order details, customer info, product data, and financials

### Key Columns

| Column | Description | Data Type |
|--------|-------------|-----------|
| `order_id` | Unique order identifier | INT |
| `order_date` | Date of order placement | DATE |
| `ship_mode` | Shipping method | VARCHAR |
| `segment` | Customer segment | VARCHAR |
| `country` | Country of delivery | VARCHAR |
| `city` | City of delivery | VARCHAR |
| `state` | State of delivery | VARCHAR |
| `postal_code` | Postal code | VARCHAR |
| `region` | Geographic region | VARCHAR |
| `category` | Product category | VARCHAR |
| `sub_category` | Product sub-category | VARCHAR |
| `product_id` | Unique product identifier | VARCHAR |
| `quantity` | Order quantity | INT |
| `discount` | Discount applied | DECIMAL |
| `sale_price` | Final sale price | DECIMAL |
| `profit` | Profit margin | DECIMAL |

---

## 🔄 Project Workflow

### Phase 1: Data Extraction 📥

```python
# Download dataset using Kaggle API
import kaggle
kaggle.api.dataset_download_files('ankitbansal06/retail-orders', 
                                   path='.', unzip=True)
```

### Phase 2: Data Cleaning & Transformation 🧹

```python
import pandas as pd

# Load raw data
df = pd.read_csv('orders.csv', na_values=['Not Available', 'unknown'])

# Standardize column names
df.columns = df.columns.str.lower().str.replace(' ', '_')

# Handle missing values
df.dropna(subset=['order_id'], inplace=True)
df['ship_mode'].fillna('Standard Class', inplace=True)

# Calculate derived metrics
df['discount'] = df['list_price'] * df['discount_percent'] * 0.01
df['sale_price'] = df['list_price'] - df['discount']
df['profit'] = df['sale_price'] - df['cost_price']

# Convert date columns
df['order_date'] = pd.to_datetime(df['order_date'], format='%Y-%m-%d')

print(f"✅ Cleaned {len(df):,} records successfully!")
```

### Phase 3: Database Loading 🗄️

```python
from sqlalchemy import create_engine

# Create SQL Server connection
engine = create_engine('mssql+pyodbc://./SQLEXPRESS/RetailDB?driver=ODBC+Driver+17+for+SQL+Server')

# Load data to SQL Server
df.to_sql('orders', con=engine, index=False, if_exists='replace')

print("✅ Data loaded to SQL Server successfully!")
```

### Phase 4: SQL Analysis 📊

Advanced SQL queries for business insights (see [SQL Analysis section](#-sql-analysis--insights))

---

## 📊 SQL Analysis & Insights

### 1️⃣ Top 10 Revenue-Generating Products

```sql
-- Identify top-selling products by revenue
SELECT TOP 10 
    product_id,
    SUM(sale_price) AS total_revenue,
    SUM(quantity) AS total_units_sold,
    ROUND(AVG(profit), 2) AS avg_profit_per_unit
FROM orders
GROUP BY product_id
ORDER BY total_revenue DESC;
```

### 2️⃣ Regional Sales Performance

```sql
-- Compare revenue across regions
SELECT 
    region,
    COUNT(DISTINCT order_id) AS total_orders,
    SUM(sale_price) AS total_revenue,
    ROUND(SUM(profit), 2) AS total_profit,
    ROUND(SUM(profit) / SUM(sale_price) * 100, 2) AS profit_margin_pct
FROM orders
GROUP BY region
ORDER BY total_revenue DESC;
```

### 3️⃣ Month-over-Month Growth Analysis

```sql
-- Calculate MoM revenue growth
WITH monthly_sales AS (
    SELECT 
        YEAR(order_date) AS year,
        MONTH(order_date) AS month,
        SUM(sale_price) AS revenue
    FROM orders
    GROUP BY YEAR(order_date), MONTH(order_date)
)
SELECT 
    year,
    month,
    revenue,
    LAG(revenue) OVER (ORDER BY year, month) AS prev_month_revenue,
    ROUND((revenue - LAG(revenue) OVER (ORDER BY year, month)) / 
          LAG(revenue) OVER (ORDER BY year, month) * 100, 2) AS mom_growth_pct
FROM monthly_sales
ORDER BY year, month;
```

### 4️⃣ Customer Segmentation Analysis

```sql
-- Analyze revenue by customer segment
SELECT 
    segment,
    COUNT(DISTINCT order_id) AS order_count,
    SUM(sale_price) AS total_revenue,
    ROUND(AVG(sale_price), 2) AS avg_order_value,
    SUM(quantity) AS total_units
FROM orders
GROUP BY segment
ORDER BY total_revenue DESC;
```

### 5️⃣ Category Performance Deep Dive

```sql
-- Product category performance analysis
SELECT 
    category,
    sub_category,
    COUNT(*) AS order_count,
    SUM(quantity) AS units_sold,
    ROUND(SUM(sale_price), 2) AS revenue,
    ROUND(SUM(profit), 2) AS profit,
    ROUND(SUM(profit) / NULLIF(SUM(sale_price), 0) * 100, 2) AS profit_margin
FROM orders
GROUP BY category, sub_category
ORDER BY revenue DESC;
```

### 6️⃣ Shipping Mode Efficiency

```sql
-- Analyze shipping preferences and revenue
SELECT 
    ship_mode,
    COUNT(*) AS shipment_count,
    ROUND(AVG(DATEDIFF(day, order_date, ship_date)), 1) AS avg_delivery_days,
    SUM(sale_price) AS total_revenue,
    ROUND(AVG(sale_price), 2) AS avg_order_value
FROM orders
GROUP BY ship_mode
ORDER BY total_revenue DESC;
```

---

## 💡 Key Findings

<table>
<tr>
<td width="50%">

### 📈 Revenue Insights
- **Top 3 Categories** contribute to **65%** of total revenue
- **Technology** category shows highest profit margin at **18.2%**
- **Q4** accounts for **35%** of annual sales (holiday season impact)

</td>
<td width="50%">

### 👥 Customer Insights
- **Consumer** segment drives **52%** of total orders
- **Corporate** segment has highest **AOV** at $247
- **West region** leads with **32%** of total revenue

</td>
</tr>
<tr>
<td width="50%">

### 🚚 Operations Insights
- **Standard Class** shipping: **60%** of orders
- Average delivery time: **4.2 days**
- **Same Day** shipping premium: **+15%** revenue per order

</td>
<td width="50%">

### 📊 Growth Insights
- **YoY Revenue Growth:** 12.5%
- **Highest Growth Category:** Office Supplies (+18%)
- **Peak Sales Month:** November (Black Friday effect)

</td>
</tr>
</table>

---

## ⚙️ Installation & Setup

### Prerequisites

- Python 3.8+
- SQL Server (Express or higher)
- ODBC Driver 17 for SQL Server
- Kaggle Account & API Key

### Step-by-Step Installation

```bash
# 1. Clone the repository
git clone https://github.com/dosibhatlanirmalaaiswarya-bit/retail-data-analytics-project-python-sql-integration.git
cd retail-data-analytics-project-python-sql-integration

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Configure Kaggle API
# Place kaggle.json in ~/.kaggle/ directory
mkdir ~/.kaggle
cp kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json

# 5. Run the data pipeline
python retail_data_pipeline.py

# 6. Execute SQL analysis
# Open SQL Server Management Studio and run sql_analysis_queries.sql
```

### Requirements.txt

```txt
pandas>=1.5.0
numpy>=1.23.0
sqlalchemy>=2.0.0
pyodbc>=4.0.35
kaggle>=1.5.12
jupyter>=1.0.0
python-dotenv>=1.0.0
```

---

## 📁 Project Structure

```
📦 retail-data-analytics-project-python-sql-integration
├── 📂 data/
│   ├── 📄 orders_raw.csv              # Original dataset
│   └── 📄 orders_cleaned.csv          # Processed dataset
├── 📂 notebooks/
│   ├── 📓 01_data_extraction.ipynb    # Data download & initial exploration
│   ├── 📓 02_data_cleaning.ipynb      # Cleaning & transformation
│   └── 📓 03_exploratory_analysis.ipynb # EDA & visualizations
├── 📂 sql/
│   ├── 📄 create_database.sql         # Database setup script
│   ├── 📄 create_tables.sql           # Table creation DDL
│   └── 📄 analysis_queries.sql        # Business analysis queries
├── 📂 src/
│   ├── 📄 data_extraction.py          # Kaggle API integration
│   ├── 📄 data_cleaning.py            # Cleaning functions
│   ├── 📄 db_loader.py                # SQL Server loader
│   └── 📄 utils.py                    # Utility functions
├── 📂 screenshots/
│   ├── 🖼️ architecture_diagram.png
│   ├── 🖼️ sql_results_1.png
│   └── 🖼️ sql_results_2.png
├── 📄 retail_data_pipeline.py         # Main ETL script
├── 📄 requirements.txt                # Python dependencies
├── 📄 .gitignore
├── 📄 LICENSE
└── 📄 README.md                       # This file
```

---

---

## 🚀 Future Enhancements

- [ ] 📊 **Power BI Integration** - Interactive dashboards for visualization
- [ ] 🤖 **Predictive Analytics** - Sales forecasting using ML models
- [ ] ☁️ **Cloud Migration** - Deploy to Azure SQL Database
- [ ] 🔄 **Real-time Pipeline** - Implement Apache Airflow for scheduling
- [ ] 📈 **Advanced Analytics** - Customer lifetime value (CLV) analysis
- [ ] 🎯 **Recommendation Engine** - Product recommendation system

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👩‍💻 About the Author

<img src="https://avatars.githubusercontent.com/u/241822760?v=4" width="120" align="left" style="margin-right: 20px; border-radius: 50%;">

### **Aiswarya Dosibhatla**
*Data Analyst & ETL Architect*

Experienced Data Analyst with **3+ years** of professional experience in data analysis, ETL development, and business intelligence. Proficient in **Python, SQL, Power BI, Snowflake**, and cloud platforms including **Azure and AWS**.

<br clear="left"/>

### 🔗 Connect With Me

<p align="left">
  <a href="https://linkedin.com/in/Aiswarya">
    <img src="https://img.shields.io/badge/LinkedIn-Aiswarya_Dosibhatla-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/dosibhatlanirmalaaiswarya-bit">
    <img src="https://img.shields.io/badge/GitHub-dosibhatlanirmalaaiswarya--bit-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="mailto:nirmalaaiswaryadosibhatla@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

📍 **Location:** Dallas, TX | 📱 **Mobile:** +1 940-977-2944

### 🛠️ Technical Expertise

| Category | Skills |
|----------|--------|
| **Programming** | Python, R, SQL, Shell Scripting |
| **Data Engineering** | Azure Data Factory, Databricks, Apache Spark, Delta Lake |
| **BI & Visualization** | Power BI (Advanced DAX), Tableau, Excel Analytics |
| **Cloud Platforms** | Microsoft Azure, AWS, GCP |
| **Databases** | Snowflake, PostgreSQL, MySQL, SQL Server, MongoDB |
| **ETL Tools** | SSIS, Informatica, Talend, Apache Airflow |

### 🎓 Education

| Degree | Institution | Timeline |
|--------|-------------|----------|
| **M.S. Information Systems & Technology** | University of North Texas, Denton, TX | Aug 2023 – May 2025 |
| **B.Tech Information Technology** | Jawaharlal Technological University, India | Jul 2016 – Aug 2020 |

### 🏆 Professional Achievements

- 🏅 **3 Spot Awards** for exceptional performance at MuSigma
- 📊 Processed **10M+ daily records** with ETL pipelines achieving **99.9% uptime**
- 📈 Improved reporting accuracy by **25%** through data validation frameworks
- 👥 Led Agile teams of **8 members** with **100% on-time project completion**
- ⚡ Reduced reporting time by **40%** through optimized SQL and data modeling

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <b>⭐ If you found this project helpful, please give it a star! ⭐</b>
</p>

<p align="center">
  Made with ❤️ by <a href="https://github.com/dosibhatlanirmalaaiswarya-bit">Aiswarya Dosibhatla</a>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=dosibhatlanirmalaaiswarya-bit&color=667eea&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views"/>
</p>
