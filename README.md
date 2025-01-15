# 📚 Magazine Subscription Behavior Analysis Using Logistic Regression and SVM

![Magazine Subscription Behavior](https://github.com/SYEDFAIZAN1987/Magazine-Subscription-Behaviour-Analysis/blob/main/pic%202.png)

## 📘 About the Project

This project analyzes the behavior of magazine subscription customers, aiming to identify factors influencing subscription trends and provide actionable insights for marketing strategies. Using **Logistic Regression** and **Support Vector Machines (SVM)**, the project predicts customer responses to marketing campaigns, addressing critical challenges like class imbalance and feature selection.

The dataset contains 2,240 records with 29 attributes detailing customer demographics, purchasing behavior, and response to marketing campaigns.

---

## 🔑 Key Features

1. **Data Preprocessing**:
   - Addressed missing values, outliers, and class imbalance.
   - Converted categorical variables to numerical using label encoding.
   - Scaled numerical features for improved model performance.

2. **Modeling Techniques**:
   - **Logistic Regression** for interpretable, linear relationships.
   - **SVM** with grid search for hyperparameter tuning to capture nonlinear patterns.

3. **Evaluation Metrics**:
   - Accuracy, precision, recall, and F1-scores for robust model evaluation.
   - ROC curves to assess classification thresholds.

4. **Business Impact**:
   - Insights into marketing strategies and customer segmentation for targeted campaigns.

---

## 📊 Key Insights

- **Significant Predictors**:
  - **Marketing Campaigns**: AcceptedCmp3, AcceptedCmp4, and AcceptedCmp5 were the most influential predictors of subscription behavior.
  - **Recency**: Customers with recent purchases were more likely to subscribe.
  - **Total Children**: Families with fewer children showed higher subscription likelihood.

- **Model Comparison**:
  - **Logistic Regression** achieved an accuracy of 88.55%.
  - **SVM** demonstrated superior performance in handling class imbalance with optimized hyperparameters.

- **Business Recommendations**:
  - Focus marketing efforts on segments identified by key predictors.
  - Use targeted campaigns for customers with recent interactions and fewer dependents.

---

## 📜 Full Report

For a detailed analysis, including methodology, visualizations, and results, refer to the complete project report:  
[📄 Magazine Subscription Behavior Report](https://github.com/SYEDFAIZAN1987/Magazine-Subscription-Behaviour-Analysis/blob/main/Magazine%20Subscription%20Behaviour%20Report.pdf)

---

## 📂 Project Structure

```
.
├── Data/
│   ├── marketing_campaign.xlsx
├── Scripts/
│   ├── Magazine_Subscription_Behavior_Analysis.py
├── Reports/
│   ├── Magazine_Subscription_Behaviour_Report.pdf
├── README.md
```
## 🤝 Connect with Me

Feel free to reach out for feedback, questions, or collaboration opportunities:  
**LinkedIn**: [Dr. Syed Faizan](https://www.linkedin.com/in/drsyedfaizanmd/)

---

**Author**: Syed Faizan  
**Master’s Student in Data Analytics and Machine Learning**
