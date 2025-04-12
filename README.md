# Telco Customer Churn Prediction and Analysis Project

![Cover Image](cover%20image.png)

---

## Project Overview

This project aims to predict customer churn for a telecom company using machine learning techniques. The objective is to identify customers who are likely to leave the company and provide business insights for retention.

---

## Problem Statement

Customer churn causes a significant loss to businesses. Early prediction of churn customers helps in taking preventive actions and improving customer satisfaction.

---

## Dataset Details

- Dataset: Telco Customer Dataset  
- Records: 7043 Rows  
- Features: 21 Columns  
- Target Variable: Churn (Yes/No)

---

## Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## End-to-End Workflow Followed

1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Outlier & Multicollinearity Check (VIF)  
5. Model Building  
6. Cross Validation (CV)  
7. Hyperparameter Tuning  
8. Model Evaluation  
9. Business Insights & Recommendations  

---

## Exploratory Data Analysis (EDA)

### Churn Distribution
Shows how many customers churned vs stayed.

![Churn Distribution](Churn%20distribution.png)

---

### Churn by Gender
![Churn by Gender](Churn%20by%20Gender.png)

---

### Churn by Contract Type
Month-to-Month customers churn the most.

![Churn by Contract Type](Churn%20by%20Contract%20Type.png)

---

### Monthly Charges vs Churn (Boxplot)
Higher charges → Higher churn probability.

![Monthly Charges vs Churn](Monthly%20Charges%20vs%20Churn%20(Boxplot).png)

---

### Correlation Heatmap
Feature relation analysis.

![Correlation Heatmap](Correlation%20Heatmap.png)

---

## Machine Learning Models Applied

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)

---

## Final Model Accuracy Comparison

Comparison of accuracy before and after Cross Validation & Hyperparameter Tuning.

![Model Accuracy Comparison](model%20accuracy%20.png)

---

## Final Results

| Model                | Accuracy After CV & Tuning |
|---------------------|----------------------------|
| Logistic Regression | 79.63 %                   |
| Decision Tree       | 79.24 %                   |
| Random Forest       | 81.45 %                   |
| SVM                 | 82.31 %                   |
| KNN                 | 79.02 %                   |

---

## Business Insights & Recommendations

- Focus on retaining new customers (low tenure).  
- Convert Month-to-Month customers to long-term contracts.  
- Improve service for Fiber Optic Internet users.  
- Offer better deals to customers using Electronic Check.

---

## Conclusion

This project helped me implement the complete machine learning project pipeline and solve a real-world business problem using data science techniques.

---

## Author

- Sanjana Thakur  
- Aspiring Data Analyst | Data Science Enthusiast  
