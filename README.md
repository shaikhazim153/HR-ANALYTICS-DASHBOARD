# 📊 HR Analytics & Employee Attrition Dashboard | Power BI

<div align="center">

### Turning Workforce Data into Actionable HR Insights

**POWER BI · DATA ANALYTICS · DAX · POWER QUERY · BUSINESS INTELLIGENCE**

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-Data%20Preparation-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Analytics](https://img.shields.io/badge/HR-Analytics-0A66C2?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Portfolio%20Project-6C63FF?style=for-the-badge)

*A data-driven HR analytics project designed to explore employee attrition, workforce distribution, compensation patterns, job satisfaction, and retention opportunities through interactive Power BI dashboards.*

</div>

---

## 📌 Project Overview

Employee attrition is an important workforce challenge that can affect productivity, recruitment costs, team stability, and organizational performance.

The **HR Analytics & Employee Attrition Dashboard** transforms employee-level data into interactive visual reports that help HR teams and business stakeholders explore workforce patterns, identify employee groups with higher observed attrition, and investigate factors associated with employee turnover.

Built with **Microsoft Power BI**, this project focuses on KPI monitoring, interactive filtering, comparative analysis, and clear business-focused data visualization.

### 🎯 Project Objectives

- Monitor total employees and employee attrition.
- Analyze attrition patterns across departments, age groups, and job roles.
- Explore relationships between overtime, job satisfaction, work-life balance, and attrition.
- Examine monthly income and compensation patterns.
- Support data-driven workforce planning and retention discussions.

---

## 🖥️ Dashboard Preview

### 01. Workforce Overview

Explore workforce composition and key HR indicators through a high-level dashboard.

**Key analytical areas**
- Total employee count
- Attrition count and attrition rate
- Department-wise workforce distribution
- Average monthly income
- Workforce demographics
- Interactive department, gender, and marital-status filters

![Workforce Overview Dashboard](assets/Workforce_Overview.png)

### 02. Attrition Deep-Dive Analysis

Investigate how employee turnover varies across job roles, age groups, satisfaction levels, and overtime categories.

**Key analytical areas**
- Attrition by age group and job role
- Department-wise attrition comparison
- Overtime vs. non-overtime attrition
- Job satisfaction and work-life balance analysis
- Compensation-related patterns
- Interactive filtering for detailed exploration

![Attrition Deep-Dive Dashboard](assets/Attrition_DeepDive.png)

> **Screenshot setup:** Save your actual Power BI dashboard screenshots in the `assets` folder using the filenames shown above. If your filenames differ, update the image paths.

---

## 📈 Key Performance Indicators

| KPI | Business Purpose |
|---|---|
| Total Employees | Measures the size of the workforce represented in the dataset. |
| Attrition Count | Tracks the number of employees who left the organization. |
| Attrition Rate | Measures employee turnover as a proportion of the workforce. |
| Average Monthly Income | Helps explore compensation patterns across employee groups. |
| Department-wise Attrition | Compares turnover across organizational departments. |
| Overtime Analysis | Examines differences in attrition between overtime categories. |
| Job Satisfaction | Supports analysis of employee satisfaction and turnover patterns. |

### Attrition Rate

A standard calculation for an employee dataset with an `Attrition` field containing `Yes` and `No` values is:

```DAX
Attrition Count =
CALCULATE(
    COUNTROWS('HR Data'),
    'HR Data'[Attrition] = "Yes"
)
```

```DAX
Attrition Rate =
DIVIDE(
    [Attrition Count],
    COUNTROWS('HR Data'),
    0
)
```

Format the `Attrition Rate` measure as a percentage in Power BI. Replace `'HR Data'` with the actual name of your table.

---

## 💡 Business Questions Explored

This dashboard helps investigate questions such as:

- Which departments have the highest observed attrition?
- Which age groups and job roles experience more employee turnover?
- How does attrition differ between employees who work overtime and those who do not?
- Are compensation levels associated with different attrition patterns?
- How do job satisfaction and work-life balance vary across employee groups?
- Which workforce segments may deserve further investigation by HR teams?

**Analytical note:** These are exploratory questions. Associations in the dataset do not, by themselves, establish causation or predict the likelihood that a particular employee will resign.

---

## 🧠 Power BI Features & Analytical Approach

### Data Preparation — Power Query
- Inspect column types and data quality.
- Handle missing values and inconsistent categories where appropriate.
- Prepare employee attributes for analysis.
- Build a clean, consistent data model.

### Data Modeling & DAX
- Create measures for employee count, attrition count, and attrition rate.
- Calculate average income and other workforce KPIs.
- Use measures that respond to report filters.
- Validate totals and percentages against the underlying dataset.

### Interactive Data Visualization
- KPI cards for executive-level monitoring.
- Bar and column charts for category comparisons.
- Matrix visuals for detailed breakdowns.
- Slicers for interactive filtering.
- Conditional formatting where it improves readability.

### Advanced Power BI Analytics
Power BI also provides visuals such as **Key Influencers**, **Decomposition Tree**, and **Smart Narrative** that can be incorporated when present in the actual report. Their findings should be documented only after validating the visual configuration and results.

---

## 🛠️ Tools & Technologies

| Technology | Application |
|---|---|
| Microsoft Power BI Desktop | Dashboard development and interactive reporting |
| Power Query | Data cleaning and transformation |
| DAX | Measures, KPI calculations, and filter-aware analysis |
| Data Visualization | KPI cards, charts, matrices, and slicers |
| HR Analytics | Attrition, demographics, income, and satisfaction analysis |
| GitHub | Project versioning and portfolio documentation |

---

## 📂 Repository Structure

```text
HR-Workforce-Analytics/
│
├── datasets/
│   └── HR_Employee_Data.csv
│
├── assets/
│   ├── Workforce_Overview.png
│   └── Attrition_DeepDive.png
│
├── HR_Predictive_Analytics.pbix
└── README.md
```

*The structure above is a recommended layout. Keep the filenames aligned with the files actually uploaded to your repository.*

---

## ▶️ How to Open the Project

1. Download or clone the repository.
2. Install and open **Microsoft Power BI Desktop**.
3. Open `HR_Predictive_Analytics.pbix`.
4. If Power BI requests a data source, open **Transform data → Data source settings** and update the source path as needed.
5. Refresh the data and review the dashboard pages, filters, and KPI calculations.

**Privacy reminder:** Before publishing employee datasets, confirm that you have permission to share them and remove personal or confidential information.

---

## 📊 Skills Demonstrated

- Data cleaning and transformation
- Exploratory Data Analysis
- KPI development and DAX measures
- Interactive dashboard design
- HR metrics and attrition analysis
- Data storytelling and business communication
- Data validation and analytical interpretation
- GitHub project documentation

---

## 👨‍💻 About the Author

**Abdul Azim**  
*Aspiring Data Analyst | Power BI | SQL | Python | Excel*

I am developing practical data analytics skills by working on projects that turn raw data into meaningful insights and interactive reports. My focus is on analytical problem-solving, data visualization, and communicating findings that support better business decisions.

- 💻 **GitHub:** [shaikhazim153](https://github.com/shaikhazim153)
- 📂 **Project Repository:** [HR-Workforce-Analytics](https://github.com/shaikhazim153/HR-Workforce-Analytics)
- 💼 **LinkedIn:** [Shaikh Azim](https://www.linkedin.com/)

---

<div align="center">

### ⭐ Explore the Dashboard · Understand the Data · Discover the Insights

*Built with Power BI and a data-driven mindset.*

</div>
