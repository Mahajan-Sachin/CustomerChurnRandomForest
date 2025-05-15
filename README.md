# 📊 Customer Churn Prediction - Telco Dataset

## 🔍 Project Overview
This project aims to predict whether a customer will churn (i.e., leave the company) based on their usage patterns and contract details.  
It’s a binary classification problem solved using **Random Forest Classifier** with advanced techniques like **SMOTE**, **Threshold Tuning**, and **Hyperparameter Optimization**.

---

## 🧪 Tools & Libraries Used
- Python, Pandas, NumPy
- Scikit-learn (Random Forest, SMOTE, GridSearchCV)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📊 Key Steps in the Workflow
1. **Data Cleaning**
   - Handled missing values (blank strings in object columns)
   - Converted data types
2. **EDA & Visualization**
   - Explored churn distribution, categorical vs numerical features
3. **Balancing with SMOTE**
   - Applied SMOTE to handle class imbalance (target = churn)
4. **Modeling**
   - Trained a base Random Forest Classifier
   - Performed **RandomizedSearchCV** for tuning
5. **Evaluation**
   - Used metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
   - Tuned threshold using ROC curve

---

## ✅ Final Results
- ROC-AUC Score: **0.82**
- F1-Score (Churn): **0.61**
- SMOTE improved minority class recall

---

## 📷 Screenshots
_Add confusion matrix, ROC curve, etc._

---

## 🧠 What I Learned
- Accuracy is not always the best metric
- Importance of balancing datasets using SMOTE
- How hyperparameters affect tree-based models
- Real-world challenges in classification

---

## 🔗 GitHub
If you found this useful, give it a ⭐️ and feel free to fork!

