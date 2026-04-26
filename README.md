# Heart Disease Prediction (PRCP-1016)

## Problem Statement
Developing a robust machine learning classification model to predict the presence of heart disease based on clinical data. The goal is to provide a reliable digital triaging tool for hospitals to identify high-risk individuals and minimize diagnostic errors.

## Domain Analysis
This project utilizes a clinical dataset of 180 patients. Each feature represents a critical physiological or diagnostic marker:
  - **Age/Sex:** Demographic data used to establish baseline risk profiles.
  - **Chest_paint_type:** Categorized into 4 types (Typical Angina, Atypical, Non-anginal, Asymptomatic).
  - **Resting_bps:** Resting blood pressure (in mm Hg on admission).
  - **Cholesterol:** Serum cholesterol in mg/dl; a primary indicator of arterial health.
  - **Fasting_blood_sugar:** Indicator of diabetes (> 120 mg/dl).
  - **Resting_ecg:** Electrocardiographic results (Normal, ST-T wave abnormality, Left ventricular hypertrophy).
  - **Max_heart_rate:** Maximum heart rate achieved during stress testing.
  - **Exercise_induced_angina:** Binary indicator of chest pain during physical exertion.
  - **Oldpeak:** ST depression induced by exercise relative to rest.
  - **Slope:** The slope of the peak exercise ST segment.
  - **Vessels_count:** Number of major vessels (0-3) colored by fluoroscopy; a high-impact predictor.
  - **Thal:** Results of the Thallium stress test (Normal, Fixed defect, Reversible defect).
  - **Target:** Binary classification indicating the presence or absence of heart disease.
## Key Takeaways
- Clinical imaging and stress EKG data were identified as the most vital predictors.
- Standardizing medical metrics like blood pressure vs. EKG results was critical for model balance.

## Future Scope
- Developing a real-time API dashboard for clinicians.
- Implementing SHAP interpretability to explain "High Risk" flags.

## Technologies Used
- Python, Pandas, Scikit-learn
- Data Visualization (Seaborn)
