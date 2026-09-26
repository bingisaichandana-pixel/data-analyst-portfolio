# Data Analyst Portfolio | SQL Data Cleaning Project

Welcome to my portfolio repository! This website showcases an end-to-end data cleaning project executed in SQL (MySQL), featuring real-world data transformation workflows.

## 🌐 Live Portfolio Website
👉 **[Click here to view my Live Portfolio](https://bingisaichandana-pixel.github.io/data-analyst-portfolio/)**

---

## 🛠️ Project Featured: World Layoffs Data Cleaning

### 🎯 Objective
Transform raw, unformatted world layoffs data into a structured, reliable dataset ready for Exploratory Data Analysis (EDA).

### ⚙️ Key Data Cleaning Steps Applied
1. **Duplicate Removal:** Used `ROW_NUMBER()` over CTEs to identify and remove duplicate records.
2. **Data Standardization:** Trimmed unwanted whitespaces, unified industry/country naming conventions, and converted string fields to standardized `DATE` values using `STR_TO_DATE`.
3. **Null & Blank Value Handling:** Populated missing values using self-joins on matching company entries and removed irrelevant records.
4. **Column Cleanup:** Dropped temporary calculation columns and staging tables to optimize database performance.

---

## 📁 Repository Structure
* `index.html` — Portfolio layout and presentation
* `data_cleaning.sql` — SQL queries and pipeline scripts
* `layoffs.csv` — Raw dataset used for analysis
* `images/` — Screenshots and visual query results

---

## 📬 Contact & Connect
* **GitHub:** [@bingisaichandana-pixel](https://github.com/bingisaichandana-pixel)
*
