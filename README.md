# layoffs-data-analysis
Data cleaning and analysis project using SQL
# Layoffs Data Cleaning and Exploration Project

## 📂 Project Overview
This project focuses on cleaning and analyzing a dataset containing layoffs information from various companies, industries, and regions. The goal was to remove duplicates, standardize data, handle missing values, and explore patterns such as trends by industry, company, and time.

The project demonstrates how to work with messy real-world data using SQL and extract actionable insights through exploratory data analysis.

---

## ✅ Tools & Technologies Used
- **SQL (MySQL/PostgreSQL)**
  - Window functions (`ROW_NUMBER()`, `DENSE_RANK()`)
  - `JOIN`, `GROUP BY`, `ORDER BY`
  - String functions (`TRIM`, `LIKE`)
  - Date formatting (`STR_TO_DATE`)
  - Handling NULLs and inconsistent values

- **Data Cleaning**
  - Removing duplicate records
  - Handling missing or blank data
  - Standardizing text fields (company names, industries, countries)
  - Formatting date fields for accurate analysis

- **Exploratory Data Analysis (EDA)**
  - Aggregating layoffs by company, industry, and year
  - Time-series analysis and cumulative trends
  - Ranking and identifying top affected companies

---

## ✅ Skills Demonstrated
✔ Data preprocessing and cleaning  
✔ Handling NULL values and inconsistent datasets  
✔ String manipulation and formatting in SQL  
✔ Performing aggregations and deriving insights  
✔ Using advanced window functions for ranking and rolling totals  
✔ Extracting trends from time-series data

---


---

## 📊 Sample Insights
- Top companies impacted by layoffs
- Layoffs trends by industry over the years
- Monthly and yearly aggregation of layoffs
- Rolling total layoffs to track changes over time
- Identifying companies with the highest layoffs per year

---

## 📂 How to Run This Project
1. Load the `layoffs_raw.csv` into your MySQL database.
2. Execute the queries from `data_cleaning.sql` in sequence to clean the data.
3. Export the cleaned data as `layoffs_cleaned.csv`.
4. Run the queries from `data_exploration.sql` to derive insights.
5. Refer to `reports.xlsx` to view documented results and interpretations.

---
