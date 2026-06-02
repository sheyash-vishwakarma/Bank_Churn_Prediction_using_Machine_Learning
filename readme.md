# Bank Churn Prediction using Machine Learning

## 📌 Project Overview
An end-to-end **Machine Learning classification project** focused on predicting customer churn in the banking sector. The project applies **EDA, data preprocessing, and multiple ML models** to identify customers likely to exit the bank, enabling proactive retention strategies.

---

## 🔍 Summary (2 Lines)
This project analyzes banking customer data and builds machine learning models to predict customer churn. The solution helps identify at-risk customers using behavioral and demographic patterns.

---

## 🎯 Problem Statement
Customer churn directly impacts a bank’s revenue and long-term growth. The objective of this project is to build a reliable machine learning model that predicts whether a customer is likely to leave the bank, enabling early intervention and improved customer retention. :contentReference[oaicite:0]{index=0}

---

## 🧰 Tools & Technologies
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Models Used:**  
  - Logistic Regression  
  - Decision Tree Classifier  
  - Random Forest Classifier  
  - K-Nearest Neighbors (KNN)  
- **Environment:** Jupyter Notebook / Google Colab
- **Dataset:** Bank Churn Prediction.csv

---

## 🏗️ Project Architecture
Raw Banking Dataset (CSV)
│
▼
Data Cleaning & Validation
│
▼
Exploratory Data Analysis (EDA)
│
▼
Feature Encoding & Scaling
│
▼
Train-Test Split (Stratified)
│
▼
Machine Learning Model Training
│
▼
Model Evaluation & Comparison
│
▼
Churn Prediction Insights

---

## 🔄 Project Workflow
1. **Data Ingestion**
   - Loaded a structured banking dataset with 10,000 customer records and 14 features.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions of numerical features such as credit score, age, balance, and salary.
   - Visualized categorical features including geography, gender, and activity status.
   - Used correlation heatmaps to understand feature relationships. :contentReference[oaicite:1]{index=1}

3. **Data Preprocessing**
   - Removed irrelevant identifier columns (RowNumber, CustomerId, Surname).
   - Encoded categorical variables using One-Hot Encoding.
   - Scaled numerical features using StandardScaler.
   - Applied stratified train-test split (80/20) to handle class imbalance.

4. **Model Building**
   - Trained multiple classification models including Logistic Regression, Decision Tree, Random Forest, and KNN.
   - Evaluated regression models for comparison purposes.

5. **Model Evaluation**
   - Compared models using Accuracy, Precision, Recall, F1-score, and AUC-ROC.
   - Visualized ROC curves and performance metrics for model comparison.

---

## 📊 Key Insights
- Around **20% of customers have churned**, indicating moderate class imbalance.
- Customers from **Germany show a higher churn rate** compared to other regions.
- **Inactive members are more likely to churn** than active customers.
- Age and account balance show a positive correlation with churn.
- **Random Forest Classifier performed best**, achieving approximately **85.8% accuracy**. :contentReference[oaicite:2]{index=2}

---

## 🚀 Future Scope
- Perform advanced feature engineering (e.g., balance-to-salary ratio).
- Experiment with Gradient Boosting models such as XGBoost or LightGBM.
- Deploy the model as a REST API for real-time churn prediction.
- Improve interpretability using SHAP or feature importance analysis.
- Integrate churn predictions with A/B-tested retention strategies. :contentReference[oaicite:3]{index=3}

---

## 👤 Author
**Shreyash Vishwakarma**

---

## 📬 Contact
📧 **shreyash.sk.sv@gmail.com**


---
