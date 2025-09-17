# Customer-Churn-Prediction

# Customer Churn Prediction Using Machine Learning

## 📌 Overview
This project predicts customer churn using supervised machine learning models.  
Customer churn refers to when a customer stops doing business with a company. By predicting churn early, businesses can take proactive actions to retain customers.

## 🎯 Objectives
- Identify customers likely to churn based on demographic and service-usage features.
- Build predictive models to classify churn vs. non-churn customers.
- Provide business insights through visualizations and feature analysis.

## 🗂️ Dataset
- Source: Publicly available churn dataset (e.g., Kaggle / Telco Customer Churn).  
- Features include customer demographics, account information, and service usage.  
- Target variable: `Churn` (Yes/No).

## ⚙️ Methodology
1. **Data Preprocessing**
   - Handled missing values and categorical encoding.
   - Performed feature scaling for numerical columns.
   - Split dataset into training and testing sets.

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution using bar charts and heatmaps.
   - Identified correlations and key churn indicators.

3. **Model Training**
   - Implemented multiple models:
     - Logistic Regression
     - Decision Trees
     - Random Forest
     - XGBRF Classifier
   - Applied hyperparameter tuning for performance improvement.

4. **Model Evaluation**
   - Accuracy: **87% (Random Forest, XGBRF)**
   - Recall improvement: **+15%** after feature selection.
   - Visualized feature importance to highlight top churn drivers.

## 📊 Results
- Random Forest and XGBRF models performed the best.  
- Key churn factors included contract type, tenure, and monthly charges.  
- Dashboards created with heatmaps and feature importance plots.

## 🛠️ Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost  

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-prediction.git
   cd customer-churn-prediction
