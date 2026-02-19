# 📊 Customer Churn Prediction -- BCG X Data Science Simulation

## 🔍 Project Overview

This project is based on the BCG X Data Science Virtual Experience
Program (Forage). The objective was to analyze customer and pricing data
to identify key drivers of customer churn and build a machine learning
model to predict churn risk.

This project demonstrates: - Business problem solving - Exploratory Data
Analysis (EDA) - Feature Engineering - Machine Learning Modeling -
Business recommendations

------------------------------------------------------------------------

## 🏢 Business Problem

A utility company was experiencing customer churn, meaning customers
were discontinuing their service.

The goal was to: - Identify customers likely to churn - Understand key
churn drivers - Provide data-driven business recommendations to reduce
churn

------------------------------------------------------------------------

## 📂 Dataset

The dataset consisted of:

-   Customer information (consumption, contract details, tenure, etc.)
-   Pricing data
-   Churn labels

Both datasets were merged to create a unified analytical dataset.

------------------------------------------------------------------------

## 🧠 Project Workflow

### 1️⃣ Exploratory Data Analysis (EDA)

-   Missing value analysis
-   Churn distribution analysis
-   Correlation analysis
-   Pricing sensitivity investigation

### 2️⃣ Feature Engineering

-   Price difference features
-   Consumption ratio features
-   Categorical encoding
-   Removal of irrelevant variables

### 3️⃣ Model Building

Model Used: Random Forest Classifier

Why Random Forest? - Handles non-linearity - Captures feature
interactions - Reduces overfitting through ensemble learning - Provides
feature importance insights

------------------------------------------------------------------------

## 📈 Model Performance

-   Accuracy: \~85%
-   Evaluation Metrics:
    -   Confusion Matrix
    -   Precision
    -   Recall
    -   Feature Importance

The confusion matrix helped analyze false positives and false negatives
to understand business trade-offs.

------------------------------------------------------------------------

## 💡 Key Insights

-   Pricing differences were a major churn driver
-   Customers sensitive to price increases had higher churn probability
-   Tenure and consumption patterns influenced retention

------------------------------------------------------------------------

## 📌 Business Recommendations

-   Improve pricing strategy
-   Offer targeted discounts to high-risk customers
-   Implement early intervention retention campaigns
-   Focus on price-sensitive customer segments

------------------------------------------------------------------------

## 🛠 Tech Stack

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Scikit-learn

------------------------------------------------------------------------

## 📎 Project Structure

BCG-Customer-Churn-Prediction/ │ ├── notebooks/ │ └──
churn_analysis.ipynb ├── images/ │ └── confusion_matrix.png ├──
README.md └── requirements.txt

------------------------------------------------------------------------

## 📜 Disclaimer

This project is based on the BCG X Data Science Virtual Experience
Program and is intended for educational and portfolio purposes.

## 👩‍💻 Author :)
   SHALINI SAURAV 
  [CSE_DS_Student]
