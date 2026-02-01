# 📊 Employee Attrition Analysis Dashboard  
**IBM HR Analytics Dataset**

---

1. Project Overview
Employee attrition is a critical business challenge that directly impacts productivity, team stability, and hiring costs.  
This project analyzes employee-level HR data to understand **attrition patterns**, identify **high-risk employee segments**, and support **data-driven retention decisions**.

The project combines **Python-based data analysis** with an **interactive Power BI dashboard** to deliver actionable HR insights.

---

## 🎯 Business Objective
The objectives of this project are to:
- Measure the overall employee attrition rate  
- Identify departments and job roles with high attrition  
- Analyze attrition trends by tenure and age group  
- Understand the relationship between job satisfaction and attrition  
- Enable proactive identification of at-risk employees  

---

## 🗂 Dataset
- **Source:** IBM HR Analytics Dataset (Kaggle)  
- **Total Records:** ~1,470 employees  
- **Features:** Employee demographics, department, job role, salary, tenure, overtime status, satisfaction scores, and attrition status  

---

## 🛠 Tech Stack
- **Python:** Pandas, NumPy  
- **Google Colab:** Data analysis environment  
- **Power BI:** Dashboard creation and visualization  
- **Power Query:** Data transformation  
- **DAX:** KPI and metric calculations  

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation (Python)
- Loaded and explored dataset structure and data types  
- Verified data quality and confirmed absence of missing values  
- Removed non-informative columns  
- Prepared attrition variable for analysis  

### 2️⃣ Exploratory Data Analysis
- Analyzed attrition trends by department, job role, age group, and tenure  
- Studied the impact of job satisfaction on attrition  
- Identified early-tenure and role-specific attrition risks  

### 3️⃣ Dashboard Development (Power BI)
- Built an interactive dashboard with filters and visualizations for HR stakeholders  

---

## 📊 Dashboard Components

### 🔹 KPI Cards
- **Total Employees:** 1.47K  
- **Attrition Count:** 237  
- **Attrition Rate:** 16.1%  

---

### 🔹 Filters (Slicers)
- Department  
- Job Role  
- Gender  
- Overtime  

These slicers allow HR teams to analyze attrition across specific employee segments.

---

### 🔹 Visualizations
- **Attrition Rate % by Department**  
  Highlights departments with higher attrition, with Sales showing the highest rate.

- **Attrition Rate % by Job Role**  
  Identifies high-risk roles such as Sales Representative and Laboratory Technician.

- **Attrition by Years at Company**  
  Shows attrition is highest during the early years of employment and decreases with tenure.

- **Attrition Count by Age Group**  
  Indicates the 26–35 age group experiences the highest attrition.

- **Job Satisfaction Factors vs Attrition**  
  Compares job satisfaction levels across roles to identify non-financial attrition drivers.

---

## 📈 Key Insights
- Overall attrition rate observed at **16.1%**  
- Employees with **lower tenure** account for the majority of attrition  
- **Sales department and sales-related roles** exhibit the highest attrition  
- Employees aged **26–35** are the most affected age group  
- Lower job satisfaction levels are associated with higher attrition  

---

## 💡 Business Recommendations
- Strengthen **early-tenure onboarding and engagement programs**  
- Focus retention efforts on **sales and other high-attrition roles**  
- Monitor **job satisfaction indicators** alongside performance metrics  
- Use dashboard filters to proactively identify and track at-risk employees  

---

## 📁 Repository Structure
