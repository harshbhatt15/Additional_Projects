# 📊 Banking Term Deposit Prediction

## 📌 Project Overview

This project focuses on predicting whether a customer will subscribe to a term deposit based on banking marketing campaign data. The dataset is derived from a Portuguese banking institution and includes customer demographics, financial details, and campaign-related attributes.

The goal is to build a machine learning model that can accurately classify customer responses (Yes/No).

---

## 📁 Dataset Information

* Total Records: **41,188**
* Total Features: **21**
* Target Variable: **y (0 = No, 1 = Yes)**

### Key Features:

* Age
* Job
* Marital Status
* Education
* Loan Status
* Contact Type
* Campaign Details
* Economic Indicators

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn (Visualization)
* Scikit-learn (Machine Learning)

---

## 🔍 Workflow

### 1. Data Preprocessing

* Removed missing values
* Grouped education categories
* Converted categorical variables using dummy encoding

### 2. Exploratory Data Analysis (EDA)

* Distribution of target variable
* Relationship between features and target
* Visualizations using bar plots and histograms

### 3. Feature Selection

* Used **Recursive Feature Elimination (RFE)**
* Selected most important predictors

### 4. Model Building

* Logistic Regression (with GridSearchCV)
* Random Forest Classifier

### 5. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve

---

## 📈 Results

* Logistic Regression Accuracy: ~**88%**
* Random Forest Accuracy: Comparable performance
* Cross-validation used for robustness

---

## 🧠 Key Insights

* Customers with lower `pdays` are more likely to subscribe
* Job type and education significantly influence outcomes
* Campaign frequency has an inverse effect on success

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/banking-term-deposit.git

# Navigate to project folder
cd banking-term-deposit

# Install dependencies
pip install -r requirements.txt

# Run the script
python main.py
```

---

## 📊 Sample Code Reference

The implementation includes:

* Data preprocessing
* Feature engineering
* Model training and tuning
* Evaluation metrics

(Refer to the main Python file for complete code) 

---

## 📌 Future Improvements

* Use advanced models like XGBoost
* Deploy model using Flask/Django
* Real-time prediction dashboard
* Handle class imbalance more effectively

---

## 🤝 Contributing

Feel free to fork this repository and submit pull requests.

---

## 📜 License

This project is open-source and available under the MIT License.

---

Author

Harsh Bhatt
BCA Student