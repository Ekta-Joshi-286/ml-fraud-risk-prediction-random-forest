# Fraud Check Data – Random Forest Classification

## 📌 Project Overview
This project focuses on identifying **Risky** and **Good** customers using a **Random Forest classification model**.  
Customers with **taxable income ≤ 30,000** are classified as *Risky*, while others are classified as *Good*.

The objective is to perform proper **EDA**, build a **machine learning model**, and evaluate its performance.

---

## 🎯 Problem Statement
Use Random Forest to prepare a model on fraud data by:
- Treating customers with taxable income **≤ 30,000** as **Risky**
- Treating customers with taxable income **> 30,000** as **Good**

Once the data is prepared:
1. Perform Exploratory Data Analysis (EDA)
2. Build and evaluate a Random Forest model
3. Submit the model output and analysis

---

## 📊 Dataset Description
The dataset contains customer demographic and financial information.  
The key variable **Taxable_Income** is used to create the target variable.

### Target Variable
- **Risk_Status**
  - `Risky` → Taxable_Income ≤ 30,000
  - `Good` → Taxable_Income > 30,000

---

## 🔍 Exploratory Data Analysis (EDA)
The following EDA steps were performed:
- Checked data types and missing values
- Analyzed class distribution (Risky vs Good)
- Visualized categorical and numerical variables
- Converted categorical variables using encoding

---

## ⚙️ Data Preprocessing
- Created a new target variable `Risk_Status`
- Removed `Taxable_Income` after classification
- Applied one-hot encoding to categorical features
- Split data into training and testing sets

---

## 🤖 Model Building
- Algorithm Used: **Random Forest Classifier**
- Multiple decision trees were used to improve accuracy and reduce overfitting
- Model trained using training dataset

---

## 📈 Model Evaluation
The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

These metrics help assess how well the model identifies risky customers.

---

## 🛠 Tools & Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

---


---

## ✅ Conclusion
The Random Forest model successfully classifies customers into **Risky** and **Good** categories.  
This analysis can help organizations identify potential fraud risks and make better decisions.

---

## 📌 Author
Ekta Joshi

