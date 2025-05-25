# 🏥 Improving Hospital Operations Using Data-Driven Decision Making

**Course:** BDA 640 – Data Driven Decision Making & Optimization  
**Project Title:** Operational Efficiency in Hospital Observation Units  
**Team Members:** Srikar Nadimpalli, Joyce Talluri, Aakanksha Singh 
**Tools Used:** R, Excel, Statistical Modeling, Data Visualization  

---

## 📌 Overview

This project uses a **data-driven approach** to improve the operations of a hospital’s **Observation Unit (OU)**, addressing inefficiencies in patient flow and resource utilization. By analyzing historical patient data, we developed **predictive models** to improve decision-making and reduce unnecessary inpatient admissions.

Our objective was to optimize **bed occupancy**, reduce **flipping rates** (patients moved unnecessarily to inpatient care), and ultimately improve both **patient outcomes** and **hospital revenue**.

---

## 📊 Project Highlights

- Hospital: 260-bed facility in Montanaro with a 23-bed OU
- Issue: 45% of OU patients were unnecessarily transferred to inpatient units
- Goal: Reduce this "flipping rate" to 20% using data analysis

---

## 🧠 Methodology

### 1. 📂 Data Processing & Cleaning
- Missing values handled using mean/median
- Correlated variables removed (e.g., `Flipped` and `OU_LOS_Hours`)
- Standardization of formats, normalization

### 2. 📊 Exploratory Data Analysis
- Bed occupancy and staff workload visualized by time of day
- Patient flow and treatment patterns analyzed

### 3. 🤖 Predictive Modeling
We built multiple models and compared performance:
- **Logistic Regression** (Best model – 62.05% accuracy)
- **Decision Tree**
- **Random Forest**

The logistic regression model identified that **bed availability** and **staff shortage** were the top factors behind unnecessary patient transfers.

---

## 💡 Key Results

- **Model Accuracy:**
  - Logistic Regression: 62.05%
  - Decision Tree: 61.04%
  - Random Forest: 61.04%
- **Estimated Impact:**
  - Reduce flip rate to 20%
  - Serve 570 more patients annually
  - Generate additional **$400,400 revenue/year**
  - Optimize over **3,300 inpatient beds** usage

---
