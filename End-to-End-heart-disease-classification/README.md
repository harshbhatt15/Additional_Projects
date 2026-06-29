## 🫀 End-to-End Heart Disease Classification  
*A Research-Oriented Machine Learning Project*

---

## 📌 Abstract

Heart disease is one of the leading causes of mortality worldwide. Early and accurate prediction can significantly improve clinical outcomes by identifying high-risk patients and prioritizing timely medical intervention.

This project implements an **end-to-end machine learning pipeline** to predict the presence of heart disease using clinical data and supervised classification techniques. The study focuses on data preprocessing, model development, evaluation, and comparative analysis of algorithms to assess their effectiveness in a real-world healthcare scenario.

---

## 🎯 Problem Statement

The objective of this project is to build a predictive model that determines whether a patient has **heart disease** based on clinical and demographic features such as age, sex, blood pressure, cholesterol levels, and other medical indicators.

### Input:
Multiple clinical features related to heart health.

### Output:
- **0** → No heart disease  
- **1** → Heart disease present  

This is a **binary classification problem**.

---

## 📂 Dataset Overview

The dataset consists of the following attributes:

1. **age** – Age of the patient (in years)

2. **sex** – Gender  
   - 1 = Male  
   - 0 = Female  

3. **cp** – Chest pain type  
   - 0: Typical angina (reduced blood supply to the heart)  
   - 1: Atypical angina (not related to heart)  
   - 2: Non-anginal pain (e.g., esophageal spasms)  
   - 3: Asymptomatic  

4. **trestbps** – Resting blood pressure (mm Hg)

5. **chol** – Serum cholesterol (mg/dl)  
   - Serum = LDL + HDL + 0.2 × triglycerides  
   - Values above 200 are a cause for concern  

6. **fbs** – Fasting blood sugar > 120 mg/dl  
   - 1 = True  
   - 0 = False  
   - Values above 126 mg/dl may indicate diabetes  

7. **restecg** – Resting electrocardiographic results  
   - 0: Normal  
   - 1: ST-T wave abnormality  
   - 2: Left ventricular hypertrophy  

8. **thalach** – Maximum heart rate achieved

9. **exang** – Exercise-induced angina  
   - 1 = Yes  
   - 0 = No  

10. **oldpeak** – ST depression induced by exercise relative to rest  
    - Indicates cardiac stress during exercise  

11. **slope** – Slope of the peak exercise ST segment  
    - 0: Upsloping  
    - 1: Flat  
    - 2: Downsloping  

12. **ca** – Number of major vessels (0–3) colored by fluoroscopy  
    - Higher blood flow generally indicates better heart health  

13. **thal** – Thalium stress test result  
    - 1, 3: Normal  
    - 6: Fixed defect  
    - 7: Reversible defect  

14. **target** – Heart disease diagnosis  
    - 1 = Disease present  
    - 0 = No disease  

---

## 🧠 Exploratory Data Analysis (EDA)

EDA includes:
- Checking for missing values and handling them appropriately  
- Evaluating feature distributions and class imbalance  
- Visualizing relationships between features and the target variable  
- Using plots such as histograms, correlation heatmaps, and scatter plots  

EDA helps uncover patterns and prepare the data for modeling.

---

## ⚙️ Preprocessing and Feature Engineering

Typical preprocessing steps include:
- Handling missing or invalid values  
- Encoding categorical features  
- Feature scaling (Standard Scaling or Min-Max Scaling)  
- Splitting the dataset into training and testing sets  

Proper preprocessing ensures that models receive **clean and well-conditioned input data**.

---

## 🛠 Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  

---

## 👨‍🎓 Author

**Harsh Bhatt**  

---
