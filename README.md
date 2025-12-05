# Employee Attendance Data Analytics (Python + Power BI)

A beginner-friendly *Employee Attendance Analytics* project using *Python, Pandas, and Power BI*.  
This project analyzes employee InTime & OutTime data to calculate *Working Hours, detect **Late Arrivals, and generate a **visual dashboard* for HR insights.

---

## 📌 Project Objectives
- Calculate *daily working hours* for each employee  
- Identify *late arrivals* (after 09:30 AM)  
- Analyze *productivity trends*  
- Build an *interactive Power BI dashboard*  
- Provide actionable insights for HR/Management  

---

## 🛠 Tools & Technologies Used
- *Python (Pandas, NumPy, Matplotlib)*
- *Google Colab / Jupyter Notebook*
- *Power BI Desktop*
- *CSV dataset*

---

## 📂 Dataset Columns
- EmployeeID  
- Name  
- Date  
- InTime  
- OutTime  
- WorkingHours (calculated in Python)  
- IsLate (1 = late, 0 = on-time)  

---

## 📊 Python Analysis Performed
- Converted InTime & OutTime to datetime  
- Calculated WorkingHours = OutTime - InTime  
- Detected Late Arrivals  
- Grouped data to find:
  - Average working hours per employee  
  - Late arrival frequency  
  - Day-wise trends  

---

## 📈 Power BI Dashboard Highlights
- *Bar Chart* – Average Working Hours by Employee  
- *Column Chart* – Late Arrivals by Employee  
- *Line Chart* – Daily Working Hours Trend  
- *Table View* – Complete attendance summary  

📷 (Add screenshots here)  
You can upload dashboard images in the repo and insert them like:  
![Dashboard Screenshot](dashboard.png)

---

## 📢 Key Insights
- Most employees work ~8 hours on average  
- Some employees arrive late more frequently  
- Daily trend shows consistent working hours  
- HR can use these insights for attendance review  

---

## 🚀 How to Use This Project
1. Download the dataset employee_attendance.csv  
2. Open the Jupyter Notebook for Python analysis  
3. Open the .pbix file in Power BI to view the dashboard  

---

## ✨ Author
*Samiksha Shivsamb Mukhede*  
Aspiring Data Analyst | Python | Power BI | Pandas  
GitHub: [Samiksha4827](https://github.com/Samiksha4827)
