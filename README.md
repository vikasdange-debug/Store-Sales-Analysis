# Store-Sales-Analysis

A complete end-to-end data analytics project that analyzes a retail superstore dataset to uncover business insights, sales trends, customer behavior, and product performance using Python, MySQL, SQL, and Power BI.

---

## 📌 Project Overview

This project focuses on analyzing superstore sales data to identify key business trends and support data-driven decision making. The workflow includes data cleaning, database integration, SQL analysis, and interactive dashboard creation.

The analysis answers questions such as:

- Which product categories generate the highest sales?
- Which sub-categories are most profitable?
- Which regions and states perform best?
- What are the monthly and yearly sales trends?
- Which customer segments contribute the most revenue?
- Which products should be promoted or optimized?

---

## 🎯 Objectives

- Clean and preprocess raw sales data
- Store cleaned data in a MySQL database
- Perform business analysis using SQL
- Create an interactive Power BI dashboard
- Generate actionable business insights

---

## 🛠️ Tech Stack

- Python
- Pandas
- MySQL
- SQL
- Power BI

---

## 📂 Project Structure

```
Superstore-Sales-Analysis/
│
├── Cleaned Data.csv
├── Data Cleaning.py
├── Import CSV to MySQL.py
├── Presentation.pbix
├── Raw Data.csv
├── SQL Sales Queries.sql
└── README.md
```

---

## 📁 Files Description

| File | Description |
|------|-------------|
| **Raw Data.csv** | Original sales dataset |
| **Data Cleaning.py** | Python script for data preprocessing and cleaning |
| **Cleaned Data.csv** | Final cleaned dataset used for analysis |
| **Import CSV to MySQL.py** | Imports cleaned dataset into MySQL |
| **SQL Sales Queries.sql** | SQL queries used for business analysis |
| **Presentation.pbix** | Interactive Power BI dashboard |

---

## 🔄 Project Workflow

### 1. Data Collection

- Loaded the raw Superstore sales dataset.

### 2. Data Cleaning

Performed data preprocessing using Python:

- Removed duplicate records
- Handled missing values
- Corrected data types
- Standardized column names
- Improved data consistency

Output:

```
Cleaned Data.csv
```

---

### 3. Database Integration

- Imported the cleaned dataset into MySQL.
- Created tables for SQL-based analysis.

Python Script:

```
Import CSV to MySQL.py
```

---

### 4. SQL Analysis

Performed various business queries including:

- Total Sales
- Sales by Category
- Sales by Sub-Category
- Regional Sales Analysis
- State-wise Performance
- Customer Segment Analysis
- Top Selling Products
- Monthly Sales Trends
- Profit Analysis

SQL File:

```
SQL Sales Queries.sql
```

---

### 5. Dashboard Development

Designed an interactive Power BI dashboard featuring:

- KPIs
  - Total Sales
  - Total Profit
  - Total Orders

- Sales by Category

- Sales by Sub-Category

- Sales by Region

- Monthly Sales Trend

- State-wise Sales

- Customer Segment Distribution

- Interactive Filters (Slicers)

---

## 📈 Key Insights

Some important insights obtained from the analysis include:

- Technology products generated the highest sales.
- Sales varied significantly across regions.
- Certain product sub-categories contributed high sales but relatively lower profit.
- Consumer customers generated the largest share of revenue.
- Seasonal trends revealed peak sales during specific months.

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/vikasdange-debug/Store-Sales-Analysis.git
```

### Install Python Libraries

```bash
pip install pandas mysql-connector-python
```

### Run Data Cleaning

```bash
python Data Cleaning.py
```

### Import Data into MySQL

```bash
python Import CSV to MySQL.py
```

### Execute SQL Queries

Open MySQL Workbench and run:

```
SQL Sales Queries.sql
```

### Open Dashboard

Open:

```
Presentation.pbix
```

using Microsoft Power BI Desktop.

---

## 📊 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- SQL Querying
- Database Integration
- Business Intelligence
- Data Visualization
- Dashboard Design
- Retail Sales Analytics

---

## 📚 Future Improvements

- Sales forecasting using Machine Learning
- Customer segmentation
- Profit prediction models
- Inventory optimization
- Interactive web dashboard using Streamlit
- Automated ETL pipeline

---

## 👨‍💻 Author

**Vikas Dange**

---

## 🌐 Connect With Me

**GitHub:**  https://github.com/vikasdange-debug

**LinkedIn:**  https://www.linkedin.com/in/vikas-dange-b9327b349/

Feel free to connect with me for collaborations, project discussions, or opportunities in Data Analytics, AI, and Software Development.

---
If you found this project helpful, consider giving it a ⭐ on GitHub.
