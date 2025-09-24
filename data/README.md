Customer Churn Prediction Model — MTN Nigeria

🔹 Overview

This project builds a machine learning prediction model to identify telecom customers at risk of churning. Using the MTN Nigeria customer dataset, the analysis explores key churn drivers and applies TensorFlow to predict churn probability, enabling targeted retention strategies.

🔹 Objectives

Analyze customer behavior to identify factors driving churn.

Build a baseline model (Logistic Regression) for comparison.

Develop a TensorFlow Neural Network to improve prediction accuracy.

Apply SHAP explainability to understand feature importance.

Deliver actionable business insights for churn reduction.

🔹 Dataset

Source: Kaggle – MTN Nigeria Customer Churn Dataset
 (https://www.kaggle.com/datasets/oluwademiladeadeniyi/mtn-nigeria-customer-churn)

Size: ~974 customers

Features: Age, Gender, Device, Subscription Plan, Tenure, Satisfaction Rate, Revenue, Data Usage, etc.

Target: Customer Churn Status (1 = churned, 0 = stayed)

🔹 Methodology
1) Data Cleaning & Preprocessing

    Standardized target labels (0/1).

    Dropped IDs and free-text columns.

    Handled missing values with imputation.

    One-hot encoded categorical variables.

2) Exploratory Data Analysis (EDA)

    Distribution of churn (29% churned, 71% retained).

    Boxplots and bar charts showing churn differences across revenue, tenure, satisfaction, and subscription plans.

    Correlation heatmaps for numeric features.

3) Modeling

    Baseline: Logistic Regression (ROC-AUC ~0.75).

    Neural Network: TensorFlow MLP with early stopping (ROC-AUC ~0.86).

4) Model Evaluation

    Accuracy, ROC-AUC, Confusion Matrix.

    Precision-Recall curve for threshold tuning.

5) Explainability

    SHAP analysis confirmed key drivers: short tenure, low satisfaction rate, subscription type, revenue/usage levels.

🔹 Results

    Baseline (Logistic Regression): ROC-AUC = ~0.75

    TensorFlow Model: ROC-AUC = ~0.86

    Key Insight: Short-tenure, low-satisfaction, and prepaid customers have the highest churn risk.

🔹 Business Takeaways

    Focus retention efforts on new customers within their first months.

    Improve customer satisfaction (support, pricing fairness, network quality).

    Redesign or incentivize high-churn plans (e.g., prepaid).

    Retain high-value customers with loyalty rewards.

🔹 Tech Stack

    Languages & Libraries: Python, Pandas, NumPy, Scikit-learn, TensorFlow/Keras, SHAP, Matplotlib, Seaborn

    Tools: Google Colab, Kaggle, GitHub

🔹 How to Run

1) Clone the repository:

    git clone https://github.com/joshuaaokocha/customer-churn-ml-prediction.git
    cd customer-churn-ml-prediction


2) Install requirements:

    pip install -r requirements.txt


3) Open the notebook:

    jupyter notebook notebooks/churn_mtn.ipynb



🔹 Author

👤 Your Name

LinkedIn - www.linkedin.com/in/joshuaaokocha

Kaggle - 

Portfolio - 

    
