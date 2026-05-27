# Customer Churn Prediction

## Project Overview

This project focuses on predicting customer churn in a telecommunications company using machine learning techniques.

Customer churn prediction is a critical business problem because identifying customers at risk of cancellation allows companies to implement retention strategies and reduce financial losses.

The project follows a complete end-to-end data science workflow, including:

- Data understanding
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Machine learning modeling
- Model evaluation and interpretation

---

# Dataset

Source:
IBM Telco Customer Churn Dataset

The dataset contains demographic, contractual and service-related information for 7,043 customers, including the target variable:

- Churn → Indicates whether the customer canceled the service.

Main features include:

- tenure
- MonthlyCharges
- TotalCharges
- Contract
- InternetService
- PaymentMethod
- OnlineSecurity
- TechSupport
- Streaming services

---

# Project Structure

project 1/

│
├── Data/
│   ├── Raw/
│   ├── Interim/
│   └── Processed/
│
├── notebooks/
│   ├── 01_Telco_Customer_Churn_data_understanding.ipynb
│   ├── 02_Telco_Customer_Churn_EDA.ipynb
│   ├── 03_Telco_Customer_Churn_preprocessing.ipynb
│   ├── 04_Telco_Customer_Churn_modeling.ipynb
│   └── 05_Telco_Customer_Churn_model_evaluation.ipynb
│
├── images/
│
├── Results/
│
└── README.md

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

# Exploratory Data Analysis

The exploratory analysis revealed several important patterns associated with customer churn:

- Customers with lower tenure show higher churn rates.
- Monthly contracts are strongly associated with customer cancellation.
- Customers with higher monthly charges tend to churn more frequently.
- Fiber optic internet service appears associated with higher churn probability.
- Long-term contracts reduce churn risk significantly.

---

# Data Preprocessing

The preprocessing stage included:

- Handling missing values
- Converting data types
- Encoding categorical variables
- Feature scaling
- Train-test split
- Multicollinearity analysis

---

# Machine Learning Models

The following classification models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

# Model Performance

| Model | Accuracy | ROC AUC |
|------|------|------|
| Logistic Regression | 0.811 | 0.855 |
| Decision Tree | 0.795 | 0.843 |
| Random Forest | 0.805 | 0.857 |
| XGBoost | 0.809 | 0.858 |

---

# Key Findings

The models consistently identified the following variables as the most important factors associated with churn:

- tenure
- Contract type
- MonthlyCharges
- TotalCharges
- InternetService
- PaymentMethod

Main business insights:

- New customers are more likely to churn.
- Long-term contracts improve customer retention.
- Higher monthly charges are associated with increased churn risk.
- Certain internet services and payment methods influence customer cancellation behavior.

---

# Conclusions

This project demonstrates how machine learning techniques can be applied to predict customer churn and support business decision-making.

Among the evaluated models, Random Forest and XGBoost achieved the highest predictive performance, while Logistic Regression provided a strong balance between interpretability and accuracy.

The project highlights the importance of combining technical modeling with business-oriented insights to improve customer retention strategies.

---

# Author

Juan Fernández Serichol

Master in Data Science & Business Analytics

LinkedIn: linkedin.com/in/juan-serichol

GitHub: github.com/Jfserichol