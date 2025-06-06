# sql_clean_data_project


# 🧹 SQL Data Cleaning & Analysis Project

## 📌 Project Overview:
This project focuses on cleaning and analyzing a real-world layoff dataset using **MySQL**. The goal is to improve data quality by handling duplicates, null values, inconsistent formatting, and irrelevant columns — making the dataset ready for advanced analysis or visualization.

---

## 🛠 Tools Used:
- MySQL
- SQL (CTEs, Window Functions, Filtering, ALTER TABLE)
- DB Browser / MySQL Workbench (Optional)

---

## 🔧 Key Steps:
- Created **staging tables** for structured data flow (`layoffs_staging`, `layoffs_staging2`)
- Used **ROW_NUMBER()** with **CTE** to identify and remove duplicate records
- Cleaned and standardized inconsistent data (like spacing, city names)
- Removed blank/null values to ensure data accuracy
- Dropped unnecessary columns using `ALTER TABLE` to simplify the schema

---

## 📁 Files Included:
- `layoff_cleaning.sql` → Full SQL script with all data cleaning steps

---

## ✨ Outcomes:
- Improved and structured dataset ready for analysis
- Applied advanced SQL techniques like **window functions** and **CTEs**
- Simulated real-world business case of data preprocessing in a data project

---

## 👩‍💻 Created By:
**R. Jeevitha**  
_BCA Student | Aspiring Data Analyst & Web Developer_  
📧 jeevithamalar2004@gmail.com  
📍 Chennai, India  
