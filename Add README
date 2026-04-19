Credit Card Customer Churn Prediction

1. Project Overview

This project predicts which credit card customers are likely to churn (stop using their card). The goal is to help bank marketing and customer relationship management (CRM) teams identify high-risk customers early and take proactive retention actions.

Problem Definition: To predict whether a bank credit card customer will churn using their demographic and transaction data.

Target Variable: Attrition_Flag
- Attrited Customer = churned customer (labeled as 1)
- Existing Customer = active customer (labeled as 0)


2. Dataset

Source: Kaggle – Credit Card Bank Churn dataset
Access Date: 15 April 2026
Size: 10,127 rows, 23 columns

Features include:
- Demographics: age, gender, income, education, marital status
- Account information: credit limit, months on book, card category
- Behavioural metrics: transaction counts, transaction amounts, inactive months, contact counts


3. Business Value

- Cost Optimisation: Acquiring new customers costs more than retaining existing ones.
- Revenue Protection: Customer churn directly leads to revenue decline.
- Customer Experience Improvement: Identifying pain points helps improve satisfaction and loyalty.


4. Methods Used

Data Preprocessing:
- Stripped whitespace from column names and object-type columns
- Median imputation for numerical columns
- One-hot encoding for categorical variables
- Removed ID column (CLIENTNUM)

Feature Engineering:
- avg_transaction_amount = Total_Trans_Amt / Total_Trans_Ct
- credit_usage_ratio = Avg_Utilization_Ratio

Models Used:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

Evaluation Metrics:
- Accuracy, Precision, Recall, F1 Score, ROC AUC


5. Key Findings

- The dataset is imbalanced, with far fewer churned customers.
- Churned customers tend to have lower total transaction counts.
- Gradient Boosting achieved the highest F1 score and recall.
- Tree-based models showed signs of overfitting.
- Logistic Regression produced realistic results (accuracy ~92.5%, F1 ~0.74).


6. Limitations

- Tree-based models show signs of overfitting.
- The dataset is relatively small and from a single source.
- Feature engineering was limited to two derived features.


7. How to Run

Prerequisites: Python 3.8 or above

Install required packages:
pip install pandas matplotlib scikit-learn

Run the Notebook:
1. Download dataset from Kaggle
2. Place credit_card_churn.csv in the same folder
3. Run Credit_Card_Bank_Churn.ipynb


8. Author

Name: [Wantong.Zhao]
Student ID: [2468516]
Course: ACC102 – Mini Assignment
Track: Track 2 – GitHub Data Analysis Project


9. AI Disclosure

AI tools (ChatGPT, GitHub Copilot) were used for code debugging and drafting this README. All core analytical decisions are my own.


10. References

- Kaggle Credit Card Churn Dataset
- scikit-learn documentation
