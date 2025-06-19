# Validation-Framework-for-Credit-Risk-Models
# Model Risk Management: Validation Framework for Credit Risk Models

This repository demonstrates an end-to-end model risk management (MRM) workflow, focusing on the validation of a Probability of Default (PD) model built using logistic regression on consumer credit data. The project is designed to simulate regulatory best practices (e.g., SR 11-7) and includes performance evaluation, population stability testing, and governance documentation.

---

## 📊 Project Overview

- **Objective**: Predict loan default (credit risk) using consumer lending data and implement a robust model validation framework.
- **Model**: Logistic Regression
- **Validation**: PSI, ROC-AUC, confusion matrix, classification report
- **Tools**: Python, scikit-learn, pandas, SHAP, joblib
- **Regulatory Framework**: SR 11-7

---

## 📁 Folder Structure

```
model-risk-management/
├── data/                         # (if applicable) Raw or cleaned data files
├── notebooks/                   # Jupyter Notebooks (development, validation)
├── scripts/                     # Python scripts (PSI calculator, helpers)
├── outputs/                     # Model metrics, plots, reports
├── README.md                    # Project overview and setup
├── validation_report.md         # Model governance summary
├── validated_logistic_model.pkl # Trained and validated model
```

---

## 🧪 Model Development Steps

1. Data Cleaning & Preprocessing  
2. Feature Engineering & Scaling  
3. Model Training (Logistic Regression)  
4. Performance Evaluation (ROC-AUC, confusion matrix)  
5. PSI Calculation for Stability Testing  
6. Model Documentation & Governance Report

---

## 📌 Key Validation Metrics

| Metric                | Value      |
|----------------------|------------|
| ROC-AUC              | ~0.78      |
| PSI (first feature)  | ~0.03      |
| Confusion Matrix     | Included   |
| Classification Report| Included   |

---

## 🛡️ Governance & Compliance

This project mimics model validation practices recommended in the **SR 11-7** guidance:
- **Model Development and Assumptions**
- **Performance Monitoring**
- **Data Stability (PSI)**
- **Audit-Ready Documentation**

---

## 🚀 How to Run

1. Clone the repo
2. Install dependencies from `requirements.txt`
3. Run the script or Jupyter Notebook to train and validate the model

```bash
pip install -r requirements.txt
python model_risk_validation.py
```

---

## 📝 Deliverables

- `validated_logistic_model.pkl`: Saved model object  
- `validation_report.md`: Summary of model performance and governance notes  
- `README.md`: Project documentation

---

## 📬 Contact

**Devi Prasana Kumar Siyyadri**  
Email: [deviprasanakumar.siyyadri@gmail.com](mailto:deviprasanakumar.siyyadri@gmail.com)

Feel free to reach out if you'd like to collaborate or have questions about model risk governance in finance.
