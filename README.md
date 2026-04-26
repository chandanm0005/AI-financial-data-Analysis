# 💹 AI Financial Data Analysis  
### **By Chandan M**

An analytical exploration of financial and AI performance data for **OpenAI, Google, and Meta**, focusing on R&D spending, AI revenue, growth metrics, and stock impact trends from 2015–2024.

---

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on a synthetic-realistic financial dataset to uncover insights about:

- AI revenue growth  
- R&D investments  
- Event-driven stock movement  
- Year-wise financial performance  
- Correlations between spending, revenue & stock impact  

The dataset contains **10,959 records** of daily AI financial activity.

---

## 📁 Dataset Summary

- **Companies:** OpenAI, Google, Meta  
- **Years Covered:** 2015–2024  
- **Rows:** ~10k  
- **Key Columns:**  
  - Date  
  - Company  
  - R&D_Spending_USD_Mn  
  - AI_Revenue_USD_Mn  
  - AI_Revenue_Growth_%  
  - Event  
  - Stock_Impact_%  

---

## 🧹 Data Preparation

- Converted `Date` → datetime  
- Checked & visualized missing values (**Event column has many nulls**)  
- Created company-wise subsets  
- Extracted `year` for trend analysis  
- Cleaned for better time-series visualization  

---

## 📝 Key Analysis Performed

### **1️⃣ R&D Spending Comparison**  
Bar comparison of total spending by each company.

### **2️⃣ AI Revenue Generated**  
Visual comparison of total AI revenue (in billions).

### **3️⃣ Stock Impact Trend (2015–2024)**  
Line plots for overall & company-wise stock movement.

### **4️⃣ Event-Based Stock Impact**  
Sorted events where stock impact peaked (positive & negative).

### **5️⃣ AI Revenue Growth (%) Analysis**  
Scatter plot & company-wise growth patterns.

### **6️⃣ Correlation Study**  
Heatmap of relationships between R&D, revenue, growth & stock impact.

### **7️⃣ Yearly Spending vs Revenue**  
Two-line trend showing investment vs earnings.

### **8️⃣ Year-wise Stock Impact (Grouped by Company)**  
Bar visualization of yearly max/min stock impact.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
---

## 🎯 What I Learned

- **Cleaning & handling large datasets**
- **Using seaborn/matplotlib for financial visualizations**
- **Applying groupby, sorting, and time-series analysis**
- **Understanding AI industry financial patterns**
- **Correlation analysis between revenue, R&D & stock trends**
- **Building clean, structured EDA pipelines**




