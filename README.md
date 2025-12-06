# Exploring Heart Diseases – Data Analysis 

This project analyzes a heart disease dataset containing **1000+ records and 17 health-related attributes**, focusing on identifying risk factors, demographic patterns, lifestyle impact, symptom distribution, and predictive modeling using **Python, Pandas, Matplotlib, Seaborn & Scikit-Learn**.

---

This repository contains a complete data analysis project on **Exploring Heart Diseases – Data Analysis**, including:

- **CSV dataset**
- **Excel (XLSX) dataset**
- **Power BI dashboard**
- **Presentation (PPTX)**
- **Python notebook to perform operations**

## 📁 Project Structure


---

# 📌 Dataset Overview

The dataset consists of **1000 synthetic patient records**, created for analysis and research demonstration.

### 🔢 Total Features: **17**
### 🔍 Key Attributes:
- **Age**
- **Gender**
- **BMI**
- **Cholesterol level**
- **Sugar Level**
- **Diet (Healthy / Unhealthy)**
- **Hypertension**
- **Chest Pain type**
- **Heart Rate**
- **Exercise Induced Angina (Exang)**
- **Smoking or Alcohol habit**
- **Disease (Positive / Negative)**

### ✔ Dataset Quality
- No missing values  
- No duplicate rows  
- Clean, analysis-ready data  

---

# 📊 Exploratory Data Analysis (EDA)

### **1️⃣ Age Distribution**
Age groups **40–49**, **50–59**, **70–79** show the highest frequency of heart-related issues.

### **2️⃣ Gender Distribution**
- Males: ~52%
- Females: ~48%
- Males show slightly higher heart disease occurrence.

### **3️⃣ BMI Analysis**
- Highest BMI values appear in **50–59** age group.

### **4️⃣ Cholesterol Levels**
- Females show more **borderline cholesterol**.
- Males show slightly more **high cholesterol**.

### **5️⃣ Lifestyle Risk Factors**
- Sugar levels higher in females  
- Smoking/Alcohol habits higher in males  
- Unhealthy diet more common in males  

These lifestyle factors contribute significantly to cardiovascular risk.

---

# 🩺 Symptoms & Clinical Patterns

### **Chest Pain vs Disease**
Some types of chest pain strongly correlate with positive heart disease.

### **Exercise Induced Angina (Exang)**
Higher counts show discomfort during exertion.

### **BMI vs Heart Rate**
Patients with BMI **18–22** show unexpectedly high heart rate levels — possible early risk category.

---

# 🤖 Machine Learning Model

### **Model Used:** Linear Regression  
### **Input Features:**
- Age  
- BMI  
- Impluse  

### **Output:** Predicted Heart Rate

### **Evaluation Metric:** Mean Squared Error (MSE)

The model showed a **moderate prediction accuracy**, and the scatter plot indicates close alignment between predicted and actual heart rate values.

---

# 📈 Sample Visualizations

📌 *These charts are included in the `/results` folder*

- Age Distribution Histogram  
- Gender Distribution Pie Chart  
- BMI vs Age Group Bar Chart  
- Cholesterol Level vs Gender Countplot  
- Disease Result (Positive vs Negative) Bar Chart  
- Chest Pain vs Disease Distribution  
- Scatter Plot: BMI vs Heart Rate  
- Choropleth Map: Global Sample Distribution  
- Actual vs Predicted Heart Rate (Regression)

---

# 🧠 Key Insights Summary

- Heart disease risk rises sharply after **age 45**.
- **Lifestyle habits** (diet, smoking, alcohol) play a major role.
- BMI and cholesterol patterns align with global risk data.
- Males are slightly more prone to positive results.
- Symptom patterns (chest pain, angina) show strong correlations.
- Machine learning can predict heart rate trends effectively.

---

# 🧩 How to Run the Code

### 1. Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn
jupyter notebook notebook.ipynb
