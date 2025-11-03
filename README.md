# Employee Attrition & Workforce Analytics

Explore a comprehensive HR Analytics portfolio showcasing data analysis and visualization skills, featuring dashboards in Power BI, Excel, and Tableau, along with SQL queries for deeper insights. This project provides a holistic view of expertise in HR analytics, data visualization, and database management, offering valuable insights into workforce assessment, attrition analysis, and employee demographics.

---

## Preview of Projects

| Project | Preview | Description |
| --- | --- | --- |
| Power BI HR Analytics Dashboard | ![Power BI Dashboard](assets/powerBI_preview%20copy.png) | This dynamic and interactive dashboard emphasizes data integration and features visually appealing visualizations. |
| Tableau HR Analytics Project | ![Tableau Dashboard](assets/tableau_snapshot.png) | This Tableau dashboard showcases custom charts and provides insightful trend analyses. |
| SQL Queries | ![SQL Queries](assets/test_doc_powerBI.png) | Utilized SQL queries to extract key metrics for in-depth data analysis. |
| Excel HR Analytics Dashboard | ![Excel Dashboard](assets/excel_snapshot.png) | An interactive Excel dashboard with pivot tables and visually compelling charts. |

---

## Project Overview

This project undertakes a comprehensive analysis of HR workforce data, leveraging SQL for robust data querying and manipulation. The analysis is complemented by advanced visualization and further exploration using Power BI, Excel, and Tableau. The primary objective is to extract actionable insights concerning employee attrition, workforce demographics, job satisfaction, and departmental trends. The analysis spans various dimensions, including temporal patterns, departmental performance, demographic segmentation, and employee satisfaction metrics.

This project addresses critical HR challenges using Power BI, Tableau, SQL, and Excel, focusing on HR Data 2022 of a medical components manufacturing company.

## Objectives

- **Provide a comprehensive assessment** of the organization's workforce performance, identifying strengths and areas for improvement in employee retention and satisfaction.

- **Discover trends and patterns** in employee attrition across departments, gender, age groups, and job roles to optimize workforce strategies.

- **Evaluate key HR metrics** such as Attrition Rate, Average Age, Job Satisfaction, and Employee Count to gauge workforce stability and engagement.

- **Support strategic decision-making** for enhancing employee retention programs, ensuring alignment with organizational goals and employee needs.

## Data Source

The project is based on a comprehensive HR dataset stored in a PostgreSQL database, encompassing various aspects of employee data including demographics, department, job roles, education, attrition status, and job satisfaction ratings.

## Methodology

Our approach to analyzing the HR workforce data involved a multi-step, systematic process designed to ensure thorough data examination and insightful visualization:

### Data Ingestion and Database Creation

**Objective:** Establish a robust foundation for data storage and retrieval.

**Process:** A relational database was created in PostgreSQL to store comprehensive HR data, ensuring data integrity and accessibility for all analysis tools.

### Data Analysis and SQL Queries

**Objective:** Extract meaningful insights and key performance indicators (KPIs).

**Process:** SQL queries were meticulously developed to retrieve essential KPIs, including total employee count, attrition count and rate, active employees, and average age. This step facilitated the identification of critical trends and performance metrics across various dimensions.

### Data Processing in Excel

**Objective:** Perform initial data cleaning and preliminary analysis.

**Process:** The dataset underwent further cleaning and processing in Excel, which included data validation and the generation of preliminary insights using pivot tables. This step ensured the accuracy and reliability of the data before more advanced analysis.

### Multi-dimensional Analysis

**Objective:** Examine the data across various dimensions and categories.

**Process:** Detailed analysis was conducted based on multiple factors, including gender, age bands, department, job role, education field, marital status, and business travel frequency. This multifaceted analysis enabled a comprehensive understanding of the factors influencing employee attrition and satisfaction.

### Advanced Visualization

**Objective:** Transform data into actionable visual insights.

**Process:** The results from the SQL queries were visualized using Power BI, Excel, and Tableau. These visualizations were designed to ensure data consistency and to provide clear, graphical representations of the findings. This step was critical for communicating insights effectively to stakeholders.

## Key Insights and Findings

- **Total Employee Count:** Comprehensive breakdown of workforce size, providing baseline metrics for all HR analyses and organizational planning.

- **Attrition Analysis:** Detailed tracking of employee turnover including attrition count and rate, enabling identification of high-risk departments and demographic segments.

- **Active Employees:** Clear differentiation between active and departed employees, providing real-time workforce assessment.

- **Average Age:** Examination of workforce demographics to understand age distribution and support succession planning initiatives.

- **Attrition by Gender:** Gender-based analysis of attrition patterns to identify any imbalances and support diversity initiatives.

- **Department-wise Attrition:** Detailed breakdown of attrition rates across different departments to identify areas requiring targeted retention strategies.

- **Job Satisfaction Ratings:** Comprehensive analysis of employee satisfaction scores across job roles to gauge engagement levels and identify improvement opportunities.

- **Education Field Analysis:** Examination of attrition patterns by education field to understand the relationship between educational background and retention.

- **Age Group Trends:** Analysis of attrition rates across different age bands to understand generational patterns and support targeted retention programs.

## Problem Statement

The HR department faces challenges in monitoring and analyzing key HR metrics. The project aims to provide insights and hands-on experience to address these challenges, enabling data-driven decision-making in workforce management.

## Tools and Technologies Used

### SQL (PostgreSQL)
Used for database management, querying, and data analysis. SQL queries were crucial in extracting key metrics and insights from the HR dataset.

### Excel
Utilized for data cleaning, processing, and conducting preliminary analyses. Excel provided a platform for validating data integrity, performing calculations, and creating pivot table visualizations.

### Power BI
Employed for data visualization and dashboard creation. Power BI enabled the creation of interactive dashboards that visualize workforce performance and trends with dynamic filtering capabilities.

### Tableau
Utilized for advanced data visualization and building interactive dashboards. Tableau's capabilities were leveraged to explore complex data relationships and provide deeper insights into HR analytics.

## Future Work

- **Predictive Modeling:** Implement machine learning models to forecast employee attrition based on historical data patterns and employee characteristics.

- **Sentiment Analysis:** Conduct advanced analysis on employee feedback and engagement surveys to better understand drivers of satisfaction and retention.

- **Compensation Analysis:** Perform deeper analyses on the relationship between compensation, job satisfaction, and attrition rates to optimize pay structures.

- **Real-time Dashboards:** Develop live dashboards that update automatically with real-time HR data to support proactive workforce management.

---

## 🚀 Getting Started

### Prerequisites

- **SQL Management Server** (PostgreSQL recommended) - To manage and query the database
- **Excel** - For data processing and analysis
- **Power BI Desktop** - For creating and viewing dashboards
- **Tableau Desktop** - For advanced data visualization and interactive dashboards
- **Git LFS** - Already included in the repository for large file storage

### Installation and Setup

**Clone the Repository:**

```bash
git clone https://github.com/ShubhamKapopara/Employee-Attrition-Workforce-Analytics.git
cd Employee-Attrition-Workforce-Analytics
```

The Power BI and Tableau files are stored using Git LFS. If you don't have Git LFS installed:

```bash
git lfs install
git lfs pull
```

**Database Setup:**

1. Use the provided SQL script (`sql/HR_analytics.sql`) to set up the database in PostgreSQL.
2. Import the HR dataset (`sql/hrdata.csv`) into the created database.

**Excel Setup:**

Open the provided Excel file (`excel/HR_Report.xlsx`) to review preliminary analyses and data processing steps.

**Power BI Setup:**

Open the provided Power BI file (`powerBI/HR_Analysis.pbix`). Connect the BI file to your SQL database.

**Tableau Setup:**

Open the provided Tableau workbook (`tableau/HR_DataViz.twbx`). Connect the Tableau workbook to your SQL database.

### Running the Analysis

**SQL Queries:**

Run the SQL queries provided in the `HR_analytics.sql` file to extract key metrics and KPIs.

**Excel Analysis:**

Review and utilize the analysis provided in the `HR_Report.xlsx` file for initial insights.

**Power BI Dashboards:**

Open Power BI and refresh the data connections. Navigate through the dashboards to explore various insights and visualizations.

**Tableau Dashboards:**

Open Tableau and refresh the data connections. Navigate through the dashboards for interactive visualizations.

---

## 📊 Project Contents

- **`data/`** - Raw HR datasets (Excel and CSV formats)
- **`sql/`** - SQL analytics queries and documentation
- **`powerBI/`** - Power BI dashboard (`.pbix` file via Git LFS)
- **`tableau/`** - Tableau visualization (`.twbx` file via Git LFS)
- **`excel/`** - Excel pivot tables and analysis
- **`assets/`** - Screenshots and documentation images

---

## 🛠️ Tech Stack

- **Data Analysis:** SQL, Excel, PostgreSQL
- **Visualization:** Power BI, Tableau
- **Languages:** SQL, DAX
- **Large File Storage:** Git LFS

---

## 💬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/yourprofile/) [![Tableau Public](https://img.shields.io/badge/Tableau%20Public-Shubham%20Kapopara-%23003366?logo=tableau)](https://public.tableau.com/app/profile/shubham.kapopara/viz/EmployeeAttritionWorkforceAnalytics/Dashboard1)    [![Clone](https://img.shields.io/badge/Clone-Repository-brightgreen)](https://github.com/ShubhamKapopara/Employee-Attrition-Workforce-Analytics.git)    [![Pull Requests](https://img.shields.io/badge/Pull%20Requests-Welcome-blue)](https://github.com/ShubhamKapopara/Employee-Attrition-Workforce-Analytics/pulls)    [![Issues](https://img.shields.io/badge/Report-Issues-red)](https://github.com/ShubhamKapopara/Employee-Attrition-Workforce-Analytics/issues)


