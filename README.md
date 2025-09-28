# 👩‍💼 HR Dashboard (Tableau)

## 📌 Overview
This project develops an **interactive Tableau HR Dashboard** to help HR managers and executives analyze workforce data.  
It provides **summary-level insights** on hiring, demographics, and income trends, along with a **detailed employee records view** for drill-down analysis.  

🔗 **Live Dashboard Link:** [View on Tableau Public](https://public.tableau.com/views/HRDashboard_17587543406260/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  

---

## 🗂 Dataset
- **File:** `HumanResources.csv`  
- **Generated Using:** Python (`Generate Data.py`)  
- **Key Columns:**  
  - `EmployeeID`, `Name`, `Department`, `JobTitle`, `Gender`, `Age`, `Education`, `PerformanceRating`, `HireDate`, `TerminationDate`, `Salary`, `City`, `State`  

---

## ❓ Business Questions Addressed by the Dashboard

### 1. **Overview**
- **How many employees have been hired, are currently active, and have been terminated?**  
  → KPI cards display total hires, actives, and terminations.  

- **What are the hiring and termination trends over the years?**  
  → Line charts show year-over-year hiring and exit trends.  

- **Which departments and job titles have the most employees?**  
  → Bar charts break down employees by department and role.  

- **How does the workforce compare between HQ (New York) and branches?**  
  → Side-by-side comparison between HQ and regional offices.  

- **Where are employees distributed across cities and states?**  
  → Map visualization highlights employee geographic distribution.  

---

### 2. **Demographics**
- **What is the gender ratio of the workforce?**  
  → Pie chart shows male-to-female distribution.  

- **How are employees spread across different age groups and education levels?**  
  → Histograms and bar charts display age and education splits.  

- **Which age groups or education levels dominate the workforce?**  
  → Totals are aggregated by demographic categories.  

- **Does education level impact performance ratings?**  
  → Scatterplot/correlation charts link education with performance.  

---

### 3. **Income Analysis**
- **Are there salary differences across genders and education levels?**  
  → Comparative box/violin plots highlight pay disparities.  

- **How does age correlate with salary across departments?**  
  → Trend lines within each department analyze age-salary relationships.  

---

### 4. **Employee Records View**
- **Can I access detailed information on every employee?**  
  → A filterable employee table shows Name, Department, Position, Gender, Age, Education, and Salary.  

- **Can I drill down to specific departments, roles, or cities?**  
  → Filters allow slicing by any available column.  

---

## 🎨 Design & Interactivity
- Dynamic filters by department, education, age, and city  
- Interactive charts for drill-down insights  
- Seamless navigation between **Summary View** and **Employee Records View**  

---

## 🛠️ Tech Stack
- Tableau Public (dashboard design & interactivity)  
- Python (dataset generation)  
- CSV (final dataset)  

---

## 📂 Repository Structure
