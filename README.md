# 📊 HR_Employee_Data_Analysis using Excel

## 🧾 Project Overview
This project focuses on analyzing employee-related data to uncover key workforce insights using **Microsoft Excel**.  
It demonstrates end-to-end **HR analytics** — from data cleaning and transformation to visualization and insight generation.  

The goal of this analysis is to help HR teams understand employee demographics, retention trends, salary distribution, and departmental diversity to make informed workforce decisions.

---

## 🎯 Objectives
- Clean and structure raw HR employee data for analysis  
- Calculate employee tenure and performance-based insights  
- Identify top earners and salary trends across departments  
- Analyze gender diversity and departmental workforce distribution  
- Create meaningful Excel visualizations and dashboards for HR decision-making  

---

## 📂 Dataset Description
The dataset contains information about employees such as:

| Column Name | Description |
|--------------|-------------|
| Employee ID | Unique identifier for each employee |
| Employee Name | Full name of the employee |
| Gender | Male / Female |
| Department | Employee’s department (HR, IT, Finance, etc.) |
| Job Role | Designation or role of the employee |
| Salary | Current salary in INR |
| Joining Date | Date when the employee joined the company |
| Performance Rating | Rating (1–5) based on recent evaluation |

---

## 🧮 Key Excel Operations Performed

### 🔹 Data Cleaning
- Removed blank rows, duplicate entries, and formatted inconsistent dates  
- Standardized department names and job titles  
- Applied **Data Validation** for consistent gender and department entries  

### 🔹 Data Transformation
- Created new calculated columns:  
  - `Years with Company = DATEDIF([@[Joining Date]], TODAY(), "Y")`  
  - `Profit Margin` or `Tenure Band` for segmentation  

### 🔹 Analysis Performed
1. **Top 5 Highest-Paid Employees**  
   - Used sorting and ranking to identify top earners  

2. **Gender Distribution Across Departments**  
   - Created PivotTable and visualized with a clustered column chart  

3. **Average Salary by Department**  
   - Used PivotTable aggregation and conditional formatting  

4. **Employee Tenure Analysis**  
   - Calculated years of experience and categorized tenure levels  

5. **Monthly Joining Trend**  
   - Used `MONTH()` and `COUNTIFS()` to observe seasonal hiring patterns  

---

## 📊 Visualizations Created
- **Clustered Column Chart** → Gender vs Department  
- **Bar Chart** → Top 5 Highest Paid Employees  
- **Pie Chart** → Department-wise Employee Count  
- **Line Chart** → Monthly Joining Trend  
- **Interactive Dashboard** → Combined visuals with slicers for department and gender filters  

---

## 💡 Insights Derived
- IT and Finance departments have the highest average salaries  
- HR has a balanced gender ratio, while IT is male-dominated  
- Most employees have been with the company for **3–5 years**  
- Hiring peaked in **2021–2022**, showing recent growth trends  
- Long-serving employees show higher performance ratings  

---

## 🧠 Skills Demonstrated
- Advanced Excel formulas (`IF`, `DATEDIF`, `VLOOKUP`, `COUNTIFS`, `AVERAGEIFS`)  
- PivotTables and PivotCharts  
- Conditional Formatting  
- Data Cleaning & Transformation  
- Dashboard Design and Visualization  

---

## 🛠️ Tools Used
- **Microsoft Excel**
- **Power Query (optional)**
- **Excel Charts & PivotTables**
- **Data Validation and Formatting**

---

## 📁 File Structure
