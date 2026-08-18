# -HR-Analytics-Dashboard-
An interactive HR Analytics Dashboard developed using Microsoft Power BI as part of Task 2 at SAM AI Technologies. The project analyzes employee attrition, salary distribution, departmental insights, attendance, performance, and hiring trends through interactive visualizations and KPI metrics. 
# HR Analytics Dashboard | Power BI

## 📌 Project Overview

The **HR Analytics Dashboard** is an interactive Business Intelligence project developed using **Microsoft Power BI** as part of **Task 2 at SAM AI Technologies**.

The project focuses on analyzing Human Resources data and converting it into meaningful, interactive visual insights. The dashboard helps understand employee attrition, salary distribution, departmental trends, attendance, performance, and hiring patterns.

---

## 🎯 Objectives

* Analyze employee attrition and identify key trends.
* Understand salary distribution across departments.
* Analyze employee attendance and performance.
* Visualize hiring trends over time.
* Create meaningful HR-related KPIs.
* Develop an interactive and user-friendly dashboard.
* Support data-driven HR decision-making.

---

## 📊 Dashboard Features

### 1. Employee Attrition Analysis

* Overall attrition rate
* Employee attrition trends
* Department-wise attrition
* Employee demographics and attrition patterns

### 2. Salary & Department Insights

* Salary distribution
* Department-wise salary analysis
* Comparison of employee compensation
* Department-level workforce insights

### 3. Attendance & Performance Analysis

* Attendance trends
* Employee performance analysis
* Performance comparison across departments
* Identification of important workforce patterns

### 4. Hiring Trends

* Hiring trends over time
* Department-wise recruitment analysis
* Workforce growth patterns
* Year/month-wise hiring insights

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **DAX**
* **Power Query**
* **Data Analysis**
* **Data Visualization**
* **KPI Design**
* **Business Intelligence**

---

## 🔄 Project Workflow

```text
HR Dataset
    ↓
Data Cleaning & Transformation
    ↓
Data Modeling
    ↓
DAX Calculations
    ↓
KPI Development
    ↓
Data Visualization
    ↓
Interactive HR Analytics Dashboard
    ↓
Business Insights
```

---

## 📈 Key KPIs

The dashboard includes important HR performance indicators such as:

* Total Employees
* Total Attrition
* Attrition Rate
* Average Salary
* Average Attendance
* Average Performance
* Total Hires
* Department-wise Employee Count

---

## 🧮 DAX

DAX was used to create calculated measures and support HR analytics.

Example:

```DAX
Total Employees = COUNTROWS(HR_Data)
```

```DAX
Total Attrition = 
CALCULATE(
    COUNTROWS(HR_Data),
    HR_Data[Attrition] = "Yes"
)
```

```DAX
Attrition Rate =
DIVIDE(
    [Total Attrition],
    [Total Employees],
    0
) * 100
```

*Note: Column and table names may vary depending on the dataset used.*

---

## 🎨 Dashboard Design

The dashboard was designed with a focus on:

* Clean and professional layout
* Interactive filters and slicers
* KPI cards
* Charts and visualizations
* Easy-to-understand insights
* Consistent visual formatting
* User-friendly navigation

---

## 💡 Key Insights

The dashboard enables users to identify:

* Departments with higher employee attrition.
* Salary differences across departments.
* Relationships between attendance and performance.
* Hiring patterns and workforce growth.
* Important HR trends that may require further analysis.

---

## 📂 Project Structure

```text
HR-Analytics-Dashboard/
│
├── Dataset/
│   └── HR_Data.xlsx
│
├── Dashboard/
│   └── HR_Analytics_Dashboard.pbix
│
├── Images/
│   └── HR_Analytics_Dashboard.png
│
└── README.md
```

---

## 🚀 Learning Outcomes

Through this project, I gained practical experience in:

* Building interactive Power BI dashboards.
* Cleaning and transforming data using Power Query.
* Creating DAX measures.
* Designing meaningful KPIs.
* Performing HR data analysis.
* Creating effective data visualizations.
* Presenting business insights through dashboards.

---

## 👩‍💻 Project Information

**Project:** HR Analytics Dashboard
**Task:** Task 2
**Organization:** SAM AI Technologies
**Tool:** Microsoft Power BI
**Domain:** Human Resources Analytics
**Focus:** Data Analytics & Business Intelligence

---

## 📌 Conclusion

The **HR Analytics Dashboard** demonstrates how Power BI can be used to transform HR data into interactive visualizations and actionable business insights. The project strengthened my practical knowledge of **Data Analytics, DAX, Power BI, and Business Intelligence**.

---

### 🔖 Tags

`Power BI` `HR Analytics` `Data Analytics` `Business Intelligence` `DAX` `Data Visualization` `Dashboard` `Human Resources` `SAM AI Technologies`
