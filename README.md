# 📊 Data Professional Survey – Power BI Dashboard

## 🔍 Project Overview

This project presents an **end-to-end Power BI dashboard** built using a *Data Professional Survey* dataset. The goal is to analyze survey responses from data professionals across the globe and uncover insights related to **job roles, salaries, programming preferences, demographics, and job satisfaction**.

The project demonstrates my ability to:

* Clean and transform raw data using **Power Query**
* Build meaningful **DAX measures**
* Design an **interactive, insight-driven dashboard** following data storytelling best practices

This dashboard is suitable for portfolio presentation on **GitHub and LinkedIn**.

---

## 🧾 Dataset Details

* **Source**: Data Professional Survey (CSV file included in this repository)
* **Rows**: 504 survey responses
* **Columns**: 26 fields
* **Key Attributes**:

  * Job Title
  * Country
  * Salary
  * Programming Language Preference
  * Gender
  * Work-Life Balance Happiness
  * Salary Satisfaction

---

## 🧹 Data Cleaning & Transformation (Power Query)

The raw dataset required significant preprocessing before analysis. Below are the key steps performed in **Power Query**:

### 🔧 Cleaning Steps

* Removed irrelevant and duplicate columns
* Promoted headers and corrected data types
* Handled missing values by replacing nulls with meaningful labels (e.g., "Unknown")
* Split multi-value columns (Country, Job Title, Programming Language)
* Standardized categorical values for consistency
* Removed errors and ensured clean joins

### 🛠 Feature Engineering

* Created calculated columns for:

  * Survey time spent
  * Standardized job titles
  * Grouped countries (Top countries vs Others)

> 📸 *Screenshot of Power Query cleaning steps is included in the repository*

---

## 📈 Dashboard Overview

The final Power BI dashboard provides a **comprehensive breakdown of the data professional landscape**.

### 🔑 Key Metrics (KPIs)

* **Total Survey Responses**: 504
* **Youngest Survey Taker**: 18 years
* **Average Happiness with Work-Life Balance**: 12 / 24
* **Average Happiness with Salary**: 12 / 24

### 📊 Visualizations Included

* **Country-wise Distribution of Survey Takers** (Treemap)
* **Average Salary by Job Title** (Bar Chart)
* **Favorite Programming Languages** (Stacked Column Chart)
* **Average Salary by Gender** (Donut Chart)
* **Job Satisfaction Gauges** (Salary & Work-Life Balance)

> 📸 *Dashboard screenshot is included in the repository*

---

## 🧠 Key Insights

* **Data Scientists** report the highest average salaries
* **Python** is the most preferred programming language across roles
* Survey participation is highest from **Canada, India, the US, and the UK**
* Salary satisfaction and work-life balance show **moderate happiness levels** overall
* A noticeable salary difference exists across job roles and gender groups

---

## 🛠 Tools & Technologies Used

* **Power BI** – Data modeling & dashboard creation
* **Power Query (M)** – Data cleaning and transformation
* **DAX** – Measures and KPIs
* **CSV Dataset** – Source data

---

## 📂 Repository Structure

```
├── Data_Professional_Survey.csv
├── PowerBI_Dashboard.pbix
├── Screenshots/
│   ├── Power_Query_Cleaning.png
│   └── Final_Dashboard.png
├── README.md
```

---

## 🚀 How to Use This Project

1. Download or clone this repository
2. Open the `.pbix` file using **Power BI Desktop**
3. Explore interactive visuals and filters
4. Review Power Query steps to understand data preparation

---

## 🎯 Learning Outcomes

* Hands-on experience with real-world survey data
* Improved Power Query and DAX proficiency
* Strong understanding of dashboard layout and storytelling
* Portfolio-ready Power BI project

---

## 👤 Author

**Naveen Kumar K**
Aspiring Data Analyst

### 🔗 Connect With Me

* **LinkedIn**: https://www.linkedin.com/in/naveen840/
* **GitHub**: https://github.com/NaveenKumar1822
* **Email**: sknaveen148@gmail.com

---
