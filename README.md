# 📊 Public School Characteristics (2022-2023) Dashboard 
**Excel-Based Data Analysis & Visualization Project**

## 📌 Overview
This project analyzes public school characteristics for the **2022-2023 academic year** using **Excel pivot tables, charts, and dashboards**. The goal is to explore key metrics such as:  
- 🏫 **School size distribution**  
- 👩‍🏫 **Student-to-teacher ratios**  
- 📈 **Enrollment trends by grade level**  
- 🍱 **Free/Reduced Lunch eligibility**  
- 🎨 **Demographic breakdown (Ethnicity & Gender ratios)**  

The final product includes an **interactive Excel dashboard** that visualizes these trends various graphs and slicers.

---

## 📖 Data Definitions & Terminology  
This dataset includes various categorical variables. Below are key definitions to help interpret the data:  

- **ULOCALE (Urban Locale Classification)**  
  - `11` → **City: Large** (Large metro areas)  
  - `12` → **City: Mid-size** (Mid-sized urban areas)  
  - `13` → **City: Small** (Smaller cities)  
  - `21` → **Suburb: Large** (Suburbs near large cities)  
  - `22` → **Suburb: Mid-size** (Suburbs near mid-sized cities)  
  - `23` → **Suburb: Small** (Suburbs near small cities)  
  - `31` → **Town: Fringe** (Close to urban areas)  
  - `32` → **Town: Distant** (Further from urban areas)  
  - `33` → **Town: Remote** (Far from urban areas)  
  - `41` → **Rural: Fringe** (Near a town or city)  
  - `42` → **Rural: Distant** (Further from towns/cities)  
  - `43` → **Rural: Remote** (Isolated areas)  

- **SIZE (School Size Category Based on the Boxplot)**  
  - **Huge** → 1204+ Students 
  - **Large** → 630 - 1203 Students
  - **Medium** → 417 - 629 Students 
  - **Small** → 247 - 416 Students
  - **Tiny** → 1 - 247 Students

- **CHARTER_TEXT (School Type)**  
  - `Traditional` → Regular public schools  
  - `Charter` → Schools operating under a charter agreement  
  - `Non-Traditional` → Other alternative school types  

- **S/T Ratio (Student-Teacher Ratio)**  
  - Number of students per teacher in a given school  

- **M/F Ratio (Male/Female Ratio)**  
  - Ratio of male to female students in a school  

---

## 📂 File Structure
This repository contains:

### 🔹 **Main Excel File (Complete Analysis & Dashboards)**
- 📄 **[`Public_School_Characteristics_Analysis.xlsx`](./Public_School_Characteristics_Analysis.xlsx)**  
  _This file contains all sheets, pivot tables, and working dashboards._

### 🔹 **Raw Data & Pivot Tables (Separated)**
📂 **data/**  
- 📄 [`original_dataset.xlsx`](./data/original_dataset.xlsx) → The raw public school dataset  
- 📄 [`working_sheet.xlsx`](./data/working_sheet.xlsx) → Cleaned and processed data  

📂 **pivot-tables/**  
- 📄 [`pivot_v1.xlsx`](./pivot-tables/pivot_v1.xlsx) → Initial pivot table   
- 📄 [`pivot_v2.xlsx`](./pivot-tables/pivot_v2.xlsx) → Improved pivot tables with better organization and insights  
- 📄 [`pivot_v3.xlsx`](./pivot-tables/pivot_v3.xlsx) → Pivot tables optimized specifically for dashboard charts  

### 🔹 **Dashboards (PDF Versions for Easy Viewing)**
📂 **dashboards/**  
- 📄 [`dashboard_v1.pdf`](./dashboards/dashboard_v1.pdf) → Original version of the dashboard  
- 📄 [`dashboard_v2.pdf`](./dashboards/dashboard_v2.pdf) → Refined version with better formatting, colors, and layout  

---

## 🔍 Key Insights & Findings
### School Size Distribution & Enrollment Trends
- **Most schools fall into the "Tiny," "Small," or "Medium" size category (each with ~24000 schools out of ~97000).**
- **Majority of Elementary students are from Small-Large schools.**
- **Majority of Middle-School students are from Large schools.**
- **Majority of High-School students are from Huge schools.**
- **From Kindergarten to Grade 12, the distribution of students is pretty even.**
### Student-to-Teacher Ratios
- **Student-Teacher Ratios vary significantly by locale, with rural areas tending to have lower ratios.**
- **Student-Teacher Ratios are tend to be significantly higher in larger school types.**
### Demographic Breakdown
- **About 45% of students are white, with Hispanic or Latino students being the second-largest group at ~29%.**  
- **Charter schools tend to have different gender ratios compared to traditional schools (more females to males).**
### Free/Reduced Lunch Eligibility
- **Free/Reduced Lunch eligibility is highest in certain urban areas, indicating economic disparities.**
- **Free/Reduced Lunch eligibility varied extremely between different states highlighting differing policies.** 

---

## ⚡ Skills Demonstrated
✅ **Data Cleaning & Preprocessing**  
✅ **Pivot Table Creation & Optimization**  
✅ **Advanced Excel Chart Formatting**  
✅ **Dashboard Design & Data Storytelling**  

---

## 🔄 Future Improvements & Lessons Learned
While this dashboard is **one of my first Excel data projects**, there are areas I might refine in future versions:  
- 📌 Improve readability of certain charts (better axis labeling & spacing).  
- 📌 Further refine color choices for better data distinction.

The project was ambitious to say the least. With over 100000 records of schools each with 77 fields, there was a plethora of information to work with. This resulted in data wrangling taking a long time: both due to needing to think about how to clean and work with the data, and waiting for the Excel software to update everything. With so many categories to work with, it was hard to pinpoint which ones to focus on especially when trying to compare information between states. Needless to say, I significantly improved my understanding of the data analyst process and familiarity with the Excel software. 

In the future, I hope to leverage my familiarity with different softwares and methods and experiment on ways to streamline the process such as using other data processing tools utilizing SQL or Python, or creating dashboards with different software like Tableau or Power BI. 

---

## 🚀 How to Use This Project
1. Download the **[`Public_School_Characteristics_Analysis.xlsx`](./Public_School_Characteristics_2022-2023_Analysis.xlsx)** file to view the full dashboard.  
2. Explore **pivot tables** (`pivot_v2.xlsx` and `pivot_v3.xlsx`) to see how the data was structured.  
3. View **dashboard PDFs** (`dashboard_v1.pdf` and `dashboard_v2.pdf`) if you don’t have Excel installed.  

---

## 🎯 Acknowledgments
This project was inspired by my **interest in data visualization and analysis**. It serves as a foundation for future, more advanced dashboards.  

