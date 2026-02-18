# 🌡️ Temperature Prediction Using Humidity (Regression Project)

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-lightgrey)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-9cf)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Google%20Colab](https://img.shields.io/badge/Google-Colab-yellow)
![License](https://img.shields.io/badge/License-MIT-brightgreen)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 Project Summary
This project predicts **temperature** based on **humidity sensor readings** using a machine learning regression approach.  
It demonstrates a complete **data analytics workflow** including:

- Data Loading & Cleaning  
- Exploratory Data Analysis (EDA)  
- Regression Model Training  
- Performance Evaluation using MSE and R²  
- Visualization of predictions  

This is a **Data Analyst portfolio project** and focuses on clean analysis, interpretable modeling, and strong documentation.

---

## 🎯 Objective
To build a regression model that predicts:

✅ **Temperature** (Target Variable)  
Using:

✅ **Humidity** (Feature Variable)

---

## 📂 Dataset Information
The dataset contains sensor-based readings with the following columns:

- `sensor_id`
- `lat`
- `lon`
- `pressure`
- `temperature`
- `humidity`

---

## 🧠 Approach
### ✔ Step 1: Data Cleaning
- Checked missing values
- Checked duplicate rows
- Handled missing values before modeling

### ✔ Step 2: Exploratory Data Analysis (EDA)
- Temperature distribution
- Humidity distribution
- Humidity vs temperature scatter plot
- Correlation heatmap
- Pairplot

### ✔ Step 3: Model Training
- Trained a **Linear Regression model**
- Used Train-Test split (80/20)

### ✔ Step 4: Model Evaluation
Evaluated model using:
- Mean Squared Error (MSE)
- R² Score
- Actual vs Predicted plot

---

## 📈 Model Used
### ✅ Linear Regression
Linear Regression was used as a baseline model to understand how humidity influences temperature.

---

## 📊 Evaluation Metrics
- **Mean Squared Error (MSE)**
- **R² Score**

---

## 🧾 Model Equation
After training, the regression equation is:

\[
Temperature = Intercept + (Coefficient \times Humidity)
\]

This helps interpret the impact of humidity on temperature.

---

## 🖼️ Output Screenshots

### 📍 Temperature Distribution
### 📍 Humidity Distribution
### 📍 Humidity vs Temperature
### 📍 Correlation Heatmap
### 📍 Actual vs Predicted Temperature


---

## 🧪 How to Run This Project

### ✅ Option 1: Run in Google Colab (Recommended)
1. Open Google Colab : [https://colab.research.google.com/drive/1yc6LKpJB2evWeZr9GTi8BOjkPS8hgPsl?usp=sharing](https://colab.research.google.com/drive/1yc6LKpJB2evWeZr9GTi8BOjkPS8hgPsl?usp=sharing)
