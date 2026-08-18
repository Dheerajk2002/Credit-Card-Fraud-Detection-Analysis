# Credit Card Fraud Detection & Risk Analytics

## 📌 Project Overview
This project focuses on identifying fraudulent credit card transactions within a highly imbalanced dataset. The goal is to maximize the detection of true fraud (minimizing financial loss) while keeping false positives low (reducing customer friction). 

## 📊 The Dataset
* **Source:** European cardholder transactions (September 2013).
* **Scale:** 284,807 transactions.
* **Imbalance:** Only 0.172% of transactions are fraudulent. 
* *(Note: The dataset is too large to host on GitHub. It can be downloaded directly from Kaggle).*

## 🛠️ Technical Approach
1. **Data Preprocessing:** Addressed extreme class imbalance utilizing **SMOTE** (Synthetic Minority Over-sampling Technique) to ensure the model could accurately learn minority class patterns.
2. **Predictive Modeling:** Trained an **XGBoost Classifier** to detect fraudulent patterns.
3. **Evaluation Strategy:** Optimized for risk-adjusted performance using the **ROC-AUC** metric rather than simple accuracy.
4. **Business Intelligence:** Exported model predictions into **Tableau** to visualize the business impact of False Positives vs. False Negatives.

## 📈 Key Results
* Achieved an **ROC-AUC score of 0.97**, demonstrating highly effective separation between normal and fraudulent transactions.
* **[Link to Tableau Dashboard](https://public.tableau.com/app/profile/dheeraj.kumar4085/viz/CreditCardFraudDetection_17870928265860/Dashboard1?publish=yes)** 


## 💻 Technologies Used
* **Python** (pandas, scikit-learn, imbalanced-learn, XGBoost)
* **Tableau** (Data Visualization & Business Reporting)
