# Customer-Churn-Prediction

 This project analyzes customer behavior and builds a machine learning model to predict whether a customer will churn (leave the service) or stay. The analysis is performed in Google Colab using the Telco Customer Churn dataset.

**Project Overview:**
The goal of this project is to understand what factors influence customer churn and to create a predictive model that helps identify customers at risk. This allows businesses to take proactive steps to improve retention.

**Key Steps:**
1. Data Cleaning & Preprocessing
2. Handled missing values, encoded categorical features, and scaled numerical columns.
3. Exploratory Data Analysis (EDA)
4. Visualized customer demographics, service usage patterns, and churn distribution.
5. Identified key patterns such as:
6. Month-to-month contract customers churn more.
7. Customers without tech support or online security show higher churn rates.
8. Higher monthly charges often correlate with churn.
9. Model Development
10. Trained a deep learning model (Keras) to predict churn using customer features.
11. Model Evaluation
12. Converted predicted probabilities into binary churn predictions and compared them with the actual labels.

**Results:**
The model can reliably distinguish between customers who are likely to stay and those who are likely to churn.
In the test sample, the majority of customers were predicted to stay, but a significant portion were predicted to churn, showing the model’s ability to detect risk.
📁 Technologies Used
Python
Google Colab
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
TensorFlow / Keras

**Conclusion:**
This project provides a complete workflow from data preprocessing to churn prediction using machine learning.
The model’s predictions can help companies reduce churn by targeting customers most at risk and improving service strategies.
