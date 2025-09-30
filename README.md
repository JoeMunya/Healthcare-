# Healthcare- EDA & Model development
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  This repository showcases my ability to handle healthcare data, apply preprocessing and feature engineering, train advanced models, and interpret outcomes. It reflects practical skills in building data-driven solutions for healthcare management and predictive analytics.
## 🗂 Dataset
Key columns include:
- **Age, Gender, Blood Type**
- **Medical Condition, Admission Type, Medication, Test Results**
- **Admission Date, Discharge Date**
- **Billing Amount (Target)**

Dropped: Name, Doctor, Hospital, Insurance Provider, Age Group.

Engineered Features:
- `Length of Stay` = Discharge Date – Admission Date  
- `Admission Month` = Month extracted from admission date

  
  ## 🔎 Exploratory Data Analysis
- Billing amounts are centered and are widely distribute evenly.  
- No strong correlation between any single feature and billing amount.  
- Some conditions (e.g., Cancer, Hypertension) show slightly higher median costs.  

## 🤖 Model Development
Two machine learning models were trained:  
- **Random Forest Regressor**  
- **XGBoost Regressor**  
Both models struggle to captre the patterns in billing amounts.

This project enhanced my ability to manage real-world healthcare data by applying effective cleaning, feature engineering, and exploratory analysis techniques. I developed and evaluated predictive models (Random Forest, XGBoost) to estimate billing amounts, improving my understanding of regression workflows. The experience strengthened my skills in turning complex datasets into actionable insights and practical machine learning solutions.
