# 📊 End-to-End Telco Customer Churn Prediction & Analysis | Machine Learning Project

![Coverr (cover%20image.png)


---

## 🧠 Project Overview

This project aims to predict customer churn for a telecom company using machine learning models. It demonstrates the complete ML pipeline — from Data Cleaning, Exploratory Data Analysis (EDA), Feature Engineering, Model Building, Evaluation, to Business Recommendation.

---

## 📁 Dataset Summary

Source: Telco Customer Dataset (Kaggle)  
Records: 7043 Rows  
Features: 21 Columns  
Target Variable: Churn (Yes/No)

Features include:  
Customer Demographics | Contract Type | Internet Service | Payment Method | Monthly Charges | Total Charges | Churn Status  

---

## 🛠 Tools & Libraries Used

- Python  
- Pandas, NumPy — Data Manipulation  
- Matplotlib, Seaborn — Data Visualization  
- Scikit-learn — Machine Learning Models  
- VIF — Multicollinearity Check  
- GridSearchCV — Hyperparameter Tuning  

---

## 🔄 Workflow Summary

### 1. Data Preprocessing
- Checked for missing values — No missing data found.  
- Removed `TotalCharges` column due to high multicollinearity (VIF > 10).  
- Label Encoding for categorical features.  
- Feature Scaling applied to numerical features.  
- Train-Test Split (80:20).  

---

## 📊 Exploratory Data Analysis (EDA)

### Churn Distribution
Shows class imbalance.

![Churn Distribution](Churn%20distribution.png)

---

### Churn by Gender

![Churn by Gender](Churn%20by%20Gender.png)

---

### Churn by Contract Type
Month-to-Month customers churn more.

![Churn by Contract Type](Churn%20by%20Contract%20Type.png)

---

### Monthly Charges vs Churn (Boxplot)

![Monthly Charges vs Churn](Monthly%20Charges%20vs%20Churn%20(Boxplot).png)

---

### Correlation Heatmap

![Correlation Heatmap](Correlation%20Heatmap.png)

---

## 🤖 Machine Learning Models Applied

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)

Used Cross Validation and Hyperparameter Tuning for all models.

---

## 📈 Final Model Accuracy Comparison

Comparison of Accuracy Before and After CV & Tuning.

![Model Accuracy Comparison](model%20accuracy%20.png)

| Model                | Accuracy After CV & Tuning |
|---------------------|----------------------------|
| Logistic Regression | 79.63 %                   |
| Decision Tree       | 79.24 %                   |
| Random Forest       | 81.45 %                   |
| SVM                 | 82.31 %                   |
| KNN                 | 79.02 %                   |

---

## 📌 Business Insights & Recommendations

- Customers with low tenure churn more — Improve retention strategy.  
- Month-to-Month contract customers churn more — Offer long-term plans & benefits.  
- Fiber Optic Internet users churn more — Improve service quality.  
- Customers paying via Electronic Check churn more — Promote alternative payment methods.  

---

## 🎯 Key Learnings

- Built a complete end-to-end ML project pipeline.  
- Learned the importance of feature engineering and multicollinearity handling.  
- Cross Validation & Hyperparameter Tuning improved model stability.  
- Generated business-driven insights for customer retention strategies.  

---

## 👩‍💻 Author

Sanjana Thakur  
Aspiring Data Analyst | Data Science Enthusiast  

 
 
