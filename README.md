
# 📊 Finance KPI Dashboard – Power BI

## 📌 Overview

This project is a **Finance KPI Dashboard** built using **Power BI** to analyze **Actual vs Target performance**, track **monthly trends**, and provide **executive-level insights** through interactive KPIs and visuals.
The dashboard focuses on **clear business storytelling**, **dynamic DAX calculations**, and **time-based performance analysis**.

---

## 🎯 Objectives

* Track **financial performance** against predefined targets
* Monitor **monthly trends** and **variance percentages**
* Provide **interactive insights** using slicers and KPIs
* Apply **best practices in DAX and data modeling**

---

## 🛠 Tools & Technologies Used

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Power Query**
* **Data Modeling (Star Schema concepts)**
* **GitHub (Version Control & Documentation)**

---

## 📈 Key Features of the Dashboard

* **KPI Tiles** for:

  * Total Sales
  * YTD Sales
  * Months Target Reached
  * Variance % with directional indicators
* **Trend Charts** to visualize monthly performance
* **Dynamic Titles** driven by DAX
* **Interactive Slicers** for filtering by time periods
* **Clean and executive-friendly layout**

---

## 🧮 DAX Concepts Learned & Used

This project strengthened my understanding of **core and advanced DAX concepts**, including:

* Measures vs Calculated Columns
* Filter Context vs Row Context
* Time Intelligence:

  * `DATESYTD()`
  * `DATESMTD()`
* Conditional logic using `IF()`
* Table functions:

  * `VALUES()`
  * `COUNTROWS()`
* Dynamic text measures for chart titles
* KPI variance and percentage calculations

**Example:**

```DAX
Months Target Reached =
COUNTROWS(
    FILTER(
        VALUES('Calendar'[MonthYear]),
        [Variance] > 0
    )
)
```

---

## 🗂 Data Modeling Approach

* Created a **Calendar (Date) table**
* Established relationships between **fact and dimension tables**
* Used the Calendar table for **time-based filtering and calculations**
* Ensured clean model design for better performance

---

## 🎛 Interactivity & User Experience

* Slicers dynamically update all KPIs and charts
* Measures automatically recalculate based on user selection
* Clear visual hierarchy for business users
* Minimal clutter with meaningful insights

---

## 📚 What I Learned From This Project

* How to design **business-oriented KPIs**
* Writing **clean and efficient DAX measures**
* Handling common DAX errors and context issues
* Building **dynamic dashboards** instead of static reports
* Presenting data in a way that supports **decision-making**
* Best practices for **Power BI dashboard design**

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open it in **Power BI Desktop**
3. Interact with slicers to explore trends and KPIs
4. Review DAX measures for learning and reference

---

## ⭐ Why This Project Matters

This dashboard demonstrates:

* Strong **analytical thinking**
* Practical **Power BI & DAX skills**
* Ability to convert raw data into **actionable insights**
* Readiness for **Data Analyst / BI Analyst** roles
