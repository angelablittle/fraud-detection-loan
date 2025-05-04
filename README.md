# fraud-detection-loan
Detect fraudulent loan applications with ML + GPT-powered explanations

## 🧐 Loan Application Fraud Detector: LLM Auditor Summary

This project implements a machine learning model to predict fraudulent loan applications based on applicant data (loan amount, credit score, income, age, etc.). Using a logistic regression classifier, the model analyzes patterns from historical data to flag potentially fraudulent applications.

### 🔍 Model Approach:
- Data preprocessed by encoding categorical variables
- Features selected based on correlation with fraud label
- Trained using logistic regression for binary classification
- Evaluated using accuracy, precision, recall, and ROC AUC

### 🤖 How the LLM Auditor Works:
An LLM (Large Language Model) like GPT was used to explain the model’s logic in natural language. For example:

> “An application is flagged as fraud if certain patterns—such as unusually high loan amounts with low credit scores or mismatched income levels—match historical fraud profiles.”

This explanation layer is meant to assist non-technical stakeholders in understanding why an application may be flagged, improving transparency and interpretability.

---
# Loan Application Fraud Detector + LLM Auditor

## 📂 Project Structure
- `fraud_detection_model.joblib`: Saved machine learning model
- `loan_fraud_sample.csv`: Sample dataset used for training
- `fraud_detection_notebook.ipynb`: Jupyter Notebook with all code
- `README.md`: Project documentation

## 🚀 How to Run
1. Clone the repo
2. Open the notebook in Colab or Jupyter
3. Run cells to reproduce training
4. Load saved model with `joblib.load()`

The project includes:
- A trained fraud detection model
- Exploratory data analysis and visualizations
- A saved model file for deployment
- This README file documenting the process

