# 🧠 HR Analytics - Predict Employee Attrition

This project analyzes employee attrition using HR data, visualizes insights using Power BI, and applies machine learning to predict potential attrition cases. SHAP analysis is used to explain model decisions.

## 📌 Project Objective

Understand key reasons for employee attrition and build a model to predict future attrition, helping HR teams take preventive actions.

## 🛠️ Tools & Technologies Used

- Python (Pandas, Seaborn, Scikit-learn)
- Power BI
- SHAP for model explainability
- Jupyter Notebook
- Git & GitHub

## 🧭 Folder Structure

```
HR-Analytics-Attrition-Project/
├── Dataset/
│   ├── HR_Employee_Attrition.csv       ← Raw data
│   └── hr_cleaned.csv                  ← Cleaned dataset used in modeling
│
├── Notebook/
│   └── hr_eda_model.ipynb              ← EDA + ML model + SHAP analysis
│
├── PowerBI_Dashboard/
│   ├── HR_Attrition_Dashboard.pbix     ← Power BI dashboard file
│   ├── final_dashboard_layout.pdf      ← Full dashboard layout as PDF
│   └── Screenshots/
│       ├── Attrition_By_Department.png
│       ├── Attrition by Gender.png
│       ├── Attrition by Job Role.png
│       ├── Attrition by Overtime.png
│       ├── Attrition_by_agegroup.png
│       └── Attrition_by_education_field.png
│
├── shap_analysis/
│   ├── shap_summary_plot.png           ← SHAP summary plot
│   ├── shap_feature_importance.png     ← SHAP feature importance
│
├── models/
│   └── attrition_model.pkl             ← Trained model (Logistic Regression or Decision Tree)
│
├── report/
│   └── Hr Attrition Report.pdf         ← Final 2-page project report
│
├── README.md                           ← Project overview and structure
└── requirements.txt                    ← Python dependencies (optional)
```

## 📊 Dashboard Insights

Power BI was used to visualize key attrition patterns:
- Attrition by Department, Gender, Age Group
- Attrition by Job Role, Education Field
- Attrition vs. Overtime

## 🔍 Machine Learning Model

- Classification Models: Logistic Regression and Decision Tree
- Evaluation Metrics: Accuracy Score and Confusion Matrix
- SHAP used to explain which features most influenced model predictions

## ✅ How to Run

1. Clone this repository
2. Open `hr_eda_model.ipynb` in Jupyter Notebook or Google Colab
3. Run all the cells
4. Ensure `hr_cleaned.csv` is inside the `Dataset/` folder
5. Power BI visuals can be viewed from the `.pbix` file and screenshots in the `PowerBI_Dashboard/`

## 📄 Report

The final 2-page PDF report includes:
- Introduction & Abstract
- Tools Used
- Steps Followed
- Insights & Conclusion

It's available under the `report/` folder as `Hr Attrition Report.pdf`.

## 🤝 Acknowledgments

This project was done as part of a Data Analyst Internship under the topic **"HR Analytics – Predict Employee Attrition"**, covering:
- Data Analysis
- Machine Learning
- Dashboard Creation
- SHAP Model Explainability
- PDF Report Preparation

