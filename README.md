Customer Churn Prediction Using Machine Learning

Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. This project aims to predict whether a customer is likely to leave the telecom service using Machine Learning techniques. By identifying customers who are at risk of churning, companies can take proactive measures to improve customer satisfaction and retention.

This project demonstrates the complete data analysis workflow, including data collection, data cleaning, exploratory data analysis (EDA), data preprocessing, feature engineering, machine learning model development, and performance evaluation.

---

Objective

- Predict customer churn using Machine Learning.
- Analyze customer behavior and subscription patterns.
- Identify the key factors influencing customer churn.
- Provide business recommendations to improve customer retention.

---

Dataset

Dataset: Telco Customer Churn Dataset

The dataset contains customer information such as:

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

---

Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

Project Workflow

1. Data Collection
2. Data Exploration
3. Data Cleaning
4. Data Preprocessing
5. Exploratory Data Analysis (EDA)
6. Feature Engineering
7. Train-Test Split
8. Logistic Regression Model
9. Model Evaluation
10. Business Recommendations

---

Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset using Pandas.
- Checked for missing values.
- Converted the TotalCharges column to numeric format.
- Removed missing records.
- Removed the customerID column.
- Converted categorical variables into numerical values using One-Hot Encoding.
- Split the dataset into training and testing sets.

---

Exploratory Data Analysis (EDA)

The following visualizations were created:

- Customer Churn Distribution
- Contract Type vs Customer Churn
- Payment Method vs Customer Churn
- Monthly Charges vs Customer Churn
- Correlation Heatmap

These visualizations helped identify important customer behavior patterns and the factors contributing to customer churn.

---

Machine Learning Model

Algorithm Used

- Logistic Regression

The model was trained using the training dataset and tested using the testing dataset to evaluate its predictive performance.

---

Model Performance

Model: Logistic Regression

Accuracy: 78.75%

The model achieved satisfactory performance in predicting customer churn and can assist businesses in identifying customers who are likely to leave.

---

Key Findings

- Customers with Month-to-Month contracts have the highest churn rate.
- Customers with higher Monthly Charges are more likely to churn.
- Customers using Electronic Check payment methods have a higher probability of churn.
- Long-term contracts significantly improve customer retention.

---

Business Recommendations

- Encourage customers to switch to long-term contracts.
- Offer loyalty rewards to existing customers.
- Provide personalized retention offers to high-risk customers.
- Improve customer support services.
- Monitor customers with high monthly charges and provide suitable plans.

---

Future Improvements

- Implement additional Machine Learning models such as Decision Tree, Random Forest, and XGBoost.
- Perform feature scaling and hyperparameter tuning.
- Improve model accuracy using ensemble learning techniques.
- Deploy the model as a web application for real-time churn prediction.

---

Project Structure

Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── Customer_Churn_Project_Report.pdf
├── Customer_Churn_Presentation.pptx
├── requirements.txt
└── images/

---

Requirements

Install the required libraries using:

pip install -r requirements.txt

---

Author

Joshna Maria Joseph

Data Analyst Intern

This project was completed as part of a Data Analyst internship to demonstrate practical skills in data cleaning, exploratory data analysis (EDA), data visualization, data preprocessing, and predictive analytics using Python and Machine Learning.