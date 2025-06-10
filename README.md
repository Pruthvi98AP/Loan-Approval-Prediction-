#  Loan Approval Prediction

A Machine Learning project that predicts whether a loan application will be **Approved** or **Rejected** based on applicant information. This helps financial institutions make data-driven decisions.

---

##  Project Overview

This project uses historical loan application data to build a classification model that can predict the approval status of future loan applications. It includes thorough data preprocessing, feature engineering, model training, and deployment using **Flask**.

---

##  Dataset

- **Source**: Kaggle – Loan Prediction Dataset  
- **Format**: CSV file  
- **Features**:
  - Gender, Marital Status, Education
  - ApplicantIncome, CoapplicantIncome
  - LoanAmount, Loan_Amount_Term, Credit_History
  - Property_Area
- **Target**: Loan_Status (Y = Approved, N = Rejected)

---

##  Technologies Used

- Python 🐍  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Flask (for deployment)  
- HTML/CSS (for front-end)

---

##  ML Workflow

1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize/scale numerical features  
2. **Model Building**  
   - Logistic Regression / Random Forest / XGBoost  
3. **Model Evaluation**  
   - Accuracy, Confusion Matrix, ROC-AUC  
4. **Deployment**  
   - Flask app with user input form

---

# Results
Model accuracy: ~85-90% (varies by algorithm)

Most important features: Credit History, Applicant Income, Loan Amount

