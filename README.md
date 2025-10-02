# Optimizing Iron Concentrate Yield with Machine Learning

# 🔧 Optimization of Iron Concentrate Percentage using Machine Learning

## 📌 Project Description

This project applies advanced data analysis and machine learning techniques to optimize the **% Iron Concentrate** in a mineral flotation process. By analyzing operational variables such as pH, reagent flow rates, and feed composition, the goal is to improve decision-making in process control and maximize the quality of the concentrate.

Este proyecto aplica técnicas avanzadas de análisis de datos y aprendizaje automático para optimizar el **% de Hierro en el Concentrado** en un proceso de flotación minera. A través del análisis de variables operativas como el pH, el flujo de reactivos y la composición de alimentación, se busca mejorar la toma de decisiones en el control del proceso y maximizar la calidad del concentrado.

---

## 🎯 Objectives / Objetivos

- Predict and optimize the % Iron Concentrate based on process variables.  
- Detect anomalies that may indicate operational inefficiencies or faults.  
- Identify key variables influencing the quality of the concentrate.  
- Build a machine learning model to simulate and optimize process conditions.

- Predecir y optimizar el % de hierro en el concentrado según variables del proceso.  
- Detectar anomalías que puedan indicar ineficiencias o fallos operativos.  
- Identificar las variables clave que influyen en la calidad del concentrado.  
- Construir un modelo de aprendizaje automático para simular y optimizar condiciones del proceso.

---

## 🧰 Technologies & Tools Used / Tecnologías y Herramientas

- Python: `Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`, `XGBoost`, `Scipy`
- Jupyter Notebook
- Exploratory Data Analysis (EDA)
- Machine Learning Models: Random Forest, Gradient Boosting
- Bayesian Optimization (for hyperparameter tuning)

---

## 📊 Dataset

- Real-world operational data from a mineral flotation process.  
- Data includes variables such as:
  - % Iron Feed
  - % Silica Feed
  - pH, Reagent Flows (Starch, Amina)
  - Ore Pulp Density
  - Flotation Column Air Flow
  - Output: % Iron Concentrate & % Silica Concentrate

---

## 🔍 Methodology / Metodología

1. **Data Cleaning & Preprocessing**  
   - Conversion of numerical data from string to float (handling commas, missing values).
   - Normalization and anomaly detection using Isolation Forest.

2. **Exploratory Data Analysis**  
   - Correlation analysis
   - Feature importance evaluation
   - Heatmaps and pairplots

3. **Predictive Modeling**  
   - Training regression models (Random Forest, XGBoost).
   - Evaluating using MSE and R² Score.
   - Final model R²: **0.9574**

4. **Optimization**  
   - Bayesian optimization to find input conditions that maximize % Iron Concentrate.
   - Best predicted output: **66.52% Iron Concentrate**

5. **Anomaly Detection**  
   - 7,264 anomalies detected out of 736,282 records.
   - Useful for process diagnostics and preventive maintenance.

---

## ✅ Results / Resultados

- 📈 **Model Performance**  
  - Mean Squared Error (MSE): `0.0532`  
  - R² Score: `0.9574` — Excellent predictive performance.

- 🔍 **Key Variables Influencing Output**  
  - % Silica Feed, Ore Pulp pH, % Iron Feed, Amina Flow

- 🔧 **Optimized Conditions** (Bayesian Optimization)  



