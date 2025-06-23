# Credit Risk Predictor – End-to-End Credit Default Classification Model

## Project Summary

This project delivers a credit risk prediction model that classifies loan applicants into defaulters and non-defaulters. The model is based on Logistic Regression, balancing predictive accuracy and interpretability, which is crucial for transparent credit decision-making. It leverages key features such as Credit Amount, Duration in Months, and Age to make informed predictions, and has been evaluated using multiple classification algorithms to ensure robustness.

---

## Project description

Built a machine learning pipeline to predict credit default risk using the German Credit Data from UCI. The model predicts whether a borrower will repay or default, helping lenders mitigate financial risk.

- Conducted exploratory data analysis (EDA), preprocessing, and feature engineering on real-world credit dataset
- Trained and compared multiple classifiers, selecting Logistic Regression for its strong performance and interpretability
- Evaluated model with detailed classification reports and confusion matrices
- Saved final model pipeline for deployment and future use 

This project showcases the complete workflow from data exploration to model tuning and deployment, emphasizing threshold adjustment for real-world risk management.

---

## Problem

Financial institutions require accurate tools to assess borrower risk. Misclassifying a defaulter as trustworthy can lead to significant losses, while false positives may reject good clients. This project uses historical credit data to build a model optimizing this trade-off.

---

## My Role

Led the entire process from data preparation to model selection and evaluation, including:

- Data cleaning, feature preprocessing, and exploratory analysis
- Training and comparing multiple models, choosing Logistic Regression for interpretability and performance
- Implementing custom classification threshold tuning to improve recall of defaulters
- Creating evaluation reports and visualizations
- Saving the trained model pipeline for deployment

---

## Confusion Matrix Analysis

Most good borrowers correctly identified (True Positives = 119/139).
False Positives remain significant (24 cases), likely due to class imbalance and default threshold.
Feature importance analysis showed Age as a key factor, with model often misclassifying older applicants—this motivated adjusting the decision threshold.
Lowering threshold to 0.4 improved recall of defaulters, balancing false positives and false negatives.
Prioritizing recall in credit risk helps reduce costly missed defaulters.

--- 

## Tools & Technologies

Python, Pandas, Matplotlib, Jupyter Notebook, scikit-learn 

---

## Outcome

Delivered an interpretable and well-tuned credit risk prediction model with enhanced detection of defaulters by adjusting classification threshold. The solution balances minimizing financial risk with fair client assessment, ready for integration in lending workflows.

---


## Key Insights
- The top three most important features influencing credit risk prediction were:
    - Credit amount
    - Duration in months
    - Age in years
- A moderate positive correlation of 0.62 was observed between Duration in months and Credit amount, which is logical since higher credit amounts usually imply longer repayment periods.
- No other strong correlations were detected, indicating features mostly contribute independently.
- Logistic Regression, Random Forest, and Gradient Boosting models were evaluated for predicting defaulters (class 2):
  - Logistic Regression showed the best balance for identifying defaulters (recall 0.61, precision 0.65).
    - Random Forest had higher precision (0.72) but lower recall (0.43), missing more defaulters.
    - Gradient Boosting had moderate recall (0.52) and precision (0.65).
- Lowering the classification threshold to 0.4 for Logistic Regression significantly improved recall of defaulters to 0.72, enhancing risky client detection without sacrificing precision.
- Despite being an important feature, age caused prediction errors in certain groups, suggesting further feature engineering or additional demographic data may be needed.

---

## Limitations & Future Work

- Current model trained on a single dataset
- Broader validation on diverse credit portfolios is recommended to ensure generalizability.
- The model exhibits weaknesses in accurately predicting defaults related to certain age groups
- Future work could include more detailed age-related features or demographic data.
- Potential to explore advanced models or ensemble techniques to improve predictive performance further.


## [View notebook on GitHub](https://github.com/kamilak5/Credit-Risk-Predictor/blob/main/german_bank.ipynb)

