Customer_Churn_Prediction
Project Overview

This project aims to develop machine learning models to predict customer churn based on historical data. The dataset, churn.csv, contains customer demographic, account, and service usage information that can help determine whether a customer is likely to churn.

Customer churn refers to when a customer stops using a company's service. Accurately predicting churn can help companies implement strategies to retain customers.

Dataset Description

The dataset, churn.csv, includes the following columns:

CustomerID: Unique identifier for each customer.

Gender: The gender of the customer.

Age: The age of the customer.

Tenure: The number of months the customer has stayed with the company.

Phone Service, Multiple Lines, Internet Service, etc.: Various subscription features used by customers.

Monthly Charges: The monthly fee charged to the customer.

Total Charges: Total amount billed to the customer.

Churn: Binary target variable (1 = Churn, 0 = No Churn).

Objective

The main goal of this project is to:

Predict whether a customer will churn based on their subscription details, demographic information, and service usage.

Use this information to implement proactive strategies for customer retention.

Machine Learning Pipeline

Data Preprocessing:

Handle missing values in Total Charges column. Encode categorical variables such as Gender and Internet Service. Normalize numerical features like Monthly Charges and Total Charges.

Model Training:

Train models such as Logistic Regression, Random Forest, and Gradient Boosting. Perform cross-validation to assess model performance.

Model Evaluation:

Evaluate using accuracy, precision, recall, F1-score, and AUC-ROC curve. Compare different models and choose the best-performing one based on evaluation metrics.

Steps to Run the Project

Clone the repository:

git clone https://github.com/Swasthi-2/Activity1_customer_churn.git

cd Customer_Churn_Perdiction

Install dependencies:

pip install -r requirements.txt

Run the churn prediction script:

python churn_prediction.py The script will output the model's performance and visualizations to help evaluate churn prediction.

Evaluation Metrics

The model will be evaluated using the following metrics:

Accuracy: Measures the overall correctness of the model.

Precision: Measures the correctness of positive predictions (churn).

Recall: Measures the ability of the model to find all positive cases.

F1-Score: Harmonic mean of precision and recall.

ROC-AUC: The area under the ROC curve, assessing the model's ability to distinguish between classes.

Conclusion

By predicting customer churn, businesses can take proactive measures to reduce churn rates and improve customer retention. This project demonstrates the importance of data-driven strategies in customer management.

License

This project is licensed under the MIT License. See the LICENSE file for more details.
