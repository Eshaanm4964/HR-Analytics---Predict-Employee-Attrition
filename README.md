# HR Analytics — Predict Employee Attrition

## 🔍 Objective

Use data analytics and machine learning to:

- Understand key factors behind employee resignations
- Predict future attrition using classification models
- Explain model predictions using SHAP analysis
- Suggest actionable steps to reduce attrition

---

## 🛠️ Tools & Technologies

- **Python**: Data analysis, model building  
  Libraries used: `pandas`, `seaborn`, `sklearn`, `matplotlib`, `shap`, `imblearn`
- **Power BI**: Interactive dashboard visualizing attrition insights
- **Jupyter Notebook / VS Code**: For Python scripting and model development

---

## 📊 Process Overview

### 1. Exploratory Data Analysis (EDA)
- Attrition by department, gender, education, and job role
- Salary bands, performance ratings, and promotion frequency
- Work-life balance, job satisfaction, and overtime trends

### 2. Model Building
- Built classification models: **Logistic Regression**, **Decision Tree**, and **Random Forest**
- Addressed class imbalance using **SMOTE**
- Evaluated models using F1-score, recall, and accuracy

### 3. Explainability with SHAP
- Visualized feature importance (beeswarm, force plots, summary)
- Identified key drivers of attrition

---

## 📁 Deliverables

| File | Description |
|------|-------------|
| `HR_ANALYTICS_DASHBOARD.pbix` | Power BI dashboard |
| `predict_employee_attrition_model.py` | Model training & prediction code |
| `best_attrition_model.pkl` | Saved best model |
| `WA_Fn-UseC_-HR-Employee-Attrition[1].csv` | HR dataset |
| `Shap-analysis/` | SHAP explanation plots (`beeswarm`, `force`, `summary`) |
| `Suggestions to reduce attrition rate.pdf` | Actionable HR strategy PDF |
| `README.md` | This documentation file |

---

## ✅ Results Summary

- Achieved ~80–85% model accuracy
- Identified top factors influencing attrition:
  - **OverTime**
  - **YearsSinceLastPromotion**
  - **JobSatisfaction**
- Suggested HR strategies for retention (in PDF)

---

## 📌 Suggestions to Reduce Attrition

- Improve work-life balance by limiting mandatory overtime
- Implement structured internal promotion policies
- Increase job engagement via satisfaction surveys & feedback
- Full report: See `Suggestions to reduce attrition rate.pdf`

---

## 🚀 How to Use

1. Clone this repo  
   `git clone https://github.com/yourusername/HR-Analytics---Predict-Employee-Attrition.git`
2. Run the model training script:  
   `python predict_employee_attrition_model.py`
3. View Power BI dashboard with `.pbix` file
4. Explore SHAP plots in `/Shap-analysis/`

---

## 📬 Contact

Created by **Eshaanm4964**  
Feel free to connect or raise issues for feedback or improvements.
