# 📊 Data Analytics Dashboards

This repository contains two interactive and insightful dashboards focused on real-world business use cases — **HR Analytics** and **Retail Performance & Profitability Analysis**. Both dashboards leverage powerful data visualization tools and provide stakeholders with actionable insights to make data-driven decisions.

---

## 🧑‍💼 HR Analytics Dashboard

A comprehensive dashboard built to provide deep insights into an organization’s HR data. It visualizes key human resources metrics, including workforce composition, employee well-being, compensation, and attrition trends.

### 🔍 Key Features

- **Work-Life Balance Ratings**: Analyze how employees perceive their work-life balance.
- **Job Role Distribution**: Visual overview of the spread of job roles within the company.
- **Monthly Income by Job Role**: Compare compensation across departments.
- **Attrition Analysis**: Monitor turnover rate and identify high-risk groups.
- **Employee Demographics**: Get an overview of job levels, education, satisfaction, and income.
- **Interactive Filters**: Drill down into attrition by age range and job level.

### 📊 Dashboard Sections & Metrics

#### 🔝 Top-Level KPIs
- **Sum of Job Level**
- **Sum of Education**
- **Sum of Job Satisfaction**
- **Sum of Monthly Income**

#### 😊 Employee Well-being
- **Donut Chart – Work-Life Balance Ratings**  
  Majority of employees (60.41%) report a rating of ‘3’, suggesting a balanced work-life environment.

#### 👥 Workforce Demographics & Compensation
- **Bar + Line Chart – Employees & Income by Job Level**  
  Job Level '2' has the highest headcount and income share.
- **Treemap – Job Role Distribution**  
  Most common roles: Sales Executive and Research Scientist.
- **Bar Chart – Monthly Income by Role**  
  Sales Executives earn the most, followed by Managers and Manufacturing Directors.

#### 📉 Attrition Analysis
- **Pie Chart – Overall Attrition Rate**  
  16.12% of employees have left the organization.
- **Filters**:  
  - Attrition (Yes/No)  
  - Age Range (18–60)  
  - Job Level (1–5)

### 🧭 How to Use

- Interact with charts and filters for detailed insights.
- Use the Age and Job Level sliders to refine attrition analysis.
- Toggle Attrition filter to compare current vs. exited employees.

### 🔐 Data Source

Confidential HR database (internal use only).

### 🚀 Future Enhancements

- Real-time data integration
- Historical trends and forecasting
- Department/location-level drilldowns
- Predictive attrition modeling

---

## 🛍️ Retail Business Performance & Profitability Analysis

An end-to-end project analyzing online retail transactional data to uncover trends in revenue, returns, customer behavior, and product profitability.

### 📈 Project Highlights

- Cleaned and transformed a raw dataset using Python and Pandas.
- Developed an interactive Power BI dashboard to explore revenue, returns, product trends, and geography-based performance.
- Delivered insights to guide inventory optimization and marketing focus.

### 📁 Dataset Overview

- **Source**: Online Retail Dataset
- **Size**: ~500,000 records
- **Key Columns**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country
- **Cleaned Output**: `cleaned_retail_data.csv`

### 🛠️ Tools & Technologies

| Tool       | Purpose                            |
|------------|------------------------------------|
| Python     | Data cleaning, transformation      |
| Pandas     | Data analysis                      |
| Power BI   | Dashboard design and visualization |
| DAX        | Calculated columns & KPIs          |

### 📊 Power BI Dashboard Visuals

- **Line Chart** – Monthly Revenue Trend
- **Bar Chart** – Top 10 Most Profitable Products
- **Map** – Country-wise Revenue Distribution
- **Bar Chart** – Most Returned Products
- **Stacked Column Chart** – Sales vs. Returns Over Time
- **KPI Cards** – Total Revenue, Returns, Net Profit
- **Slicers** – Filter by Country, Month, Return Status

### 📄 Deliverables

- ✅ Cleaned dataset
- ✅ Power BI dashboard
- ✅ Summary report with insights

---

