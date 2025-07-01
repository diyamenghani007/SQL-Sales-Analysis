# SQL Sales Analysis Project (End-to-End ETL + Business Insights)

This project showcases a complete **ETL pipeline** followed by business-focused **SQL analysis** to derive valuable sales insights. 
Starting from raw data extraction and cleaning in Python, the project ends with deep analytical querying using SQL on a structured database.



## Dataset Source

📂 [Kaggle: Retail Orders Dataset](https://www.kaggle.com/)  
*(https://www.kaggle.com/datasets/ankitbansal06/retail-orders)*



## Tech Stack & Tools

- **Python** (ETL & preprocessing)
  - 'pandas', 'numpy', 'sqlalchemy', 'sqlite3'
- **SQL** (Business Queries)
  - Window functions, CTEs, Aggregations
- **Jupyter Notebook**
- **Git & GitHub** (Version control)



## Project Workflow

### 1. Data Cleaning & Transformation
- Loaded Kaggle dataset using 'pandas'
- Cleaned missing values, handled data types, renamed columns
- Converted categorical formats for consistency
- Verified integrity and schema readiness

### 2. Database Setup & ETL
- Created a SQLite database
- Connected using 'SQLAlchemy'
- Pushed cleaned DataFrame into SQL using 'df.to_sql()'

### 3. SQL Business Analysis
Performed SQL queries to answer questions like:
- Top 10 highest revenue-generating products
- Top 5 best-selling products in each region
- Month-over-month growth comparison (2022 vs 2023)
- Highest sales month per category
- Sub-category with the highest growth in 2023 over 2022

### 4. Used techniques like:
- Common Table Expressions (CTEs)
- Window Functions ('ROW_NUMBER')
- 'CASE WHEN', 'GROUP BY', 'ORDER BY', 'LIMIT', and more



## Files in This Repo

|         File                          |                  Description                |
|---------------------------------------|---------------------------------------------|
|  'sqlproject.ipynb'                   | Full notebook: ETL + SQL queries documented |
|  'sql_project.sql'                    | Raw SQL queries for all business questions  |
|  'orders.csv'                         | Cleaned dataset for reproducibility         |
|  'Sales Analysis Project Output.docx' | Output Screenshots of SQL Queries           |
|  'README.md'                          | You’re reading it!                          |



## Skills Demonstrated

- Data Cleaning & Preprocessing
- SQL for Analytics & BI
- Database Integration with Python
- Writing efficient analytical queries
- Business-driven storytelling using data



## Connect With Me

**[LinkedIn](https://www.linkedin.com/in/diya-menghani-ab409031a/)** | **[GitHub](https://github.com/diyamenghani007)**



## If you liked this project:
- ⭐ Star the repo  
- 📩 Reach out to collaborate


