# 🏦 Smart Banking Analytics: Loan Approval & Risk Prediction Engine

## 📌 Project Overview

This project focuses on building an AI-driven system to predict loan approval and assess credit risk using machine learning techniques. It helps financial institutions make data-driven decisions for approving or rejecting loan applications.

## 🎯 Objective

* Predict whether a loan will be approved or rejected.
* Analyze key factors influencing loan approval.
* Provide insights for risk assessment in banking.

## 🛠️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Seaborn & Matplotlib 📊
* Scikit-learn (Machine Learning)
* Jupyter Notebook
* Power BI

## 📊 Dataset Information

* Total Records: 4269
* Features include:

  * Income
  * Loan Amount
  * CIBIL Score
  * Assets (Residential, Commercial, Luxury)
  * Employment Status
  * Education
  * Loan Status (Target)

## ⚙️ Data Preprocessing

* Removed unnecessary columns (loan_id).
* Converted categorical data into numerical format.
* Cleaned and standardized string values.
* Checked and handled missing values.

## 🤖 Machine Learning Model

* Model Used: Random Forest Classifier.
* Train-Test Split: 80% Training, 20% Testing.

## 📈 Model Performance

* Accuracy: **97.7%**
* Evaluated using Precision, Recall, F1-score.
* Confusion Matrix used for performance analysis.

## 🔍 Key Insights

* Higher CIBIL score increases chances of loan approval.
* Higher income applicants are more likely to get approved.
* Asset values play a significant role in risk assessment.
* Self-employed applicants show varied approval trends.

## 📊 Visualization

* Loan approval distribution
* Feature importance graph
* Confusion matrix heatmap

## 🚀 Future Enhancements

* Deploy model using Flask / Streamlit
* Add real-time prediction system
* Integrate Power BI dashboard
* Improve model using advanced algorithms (XGBoost)

## 🙌 Conclusion

This project demonstrates how machine learning can be applied in the banking sector to automate loan approval and reduce financial risk effectively.

## 🔗 Author

**Manikanta Puppala**
