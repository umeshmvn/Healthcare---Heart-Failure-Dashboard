# Healthcare - Heart Failure Dashboard 🩺❤️

Dive into critical insights about heart failure with this interactive Tableau dashboard. Explore key factors such as age, sex, blood pressure, and other health metrics to understand their relationship with survival status in patients with heart failure.

🔗 [Explore the Dashboard](https://public.tableau.com/app/profile/venkata.naga.umesh.munagala/viz/Healthcare-HeartFailure_17265441426990/Dashboard1)

![image](https://github.com/user-attachments/assets/790963cd-854c-4043-9d9f-38184f69538a)


## 🎉 Key Highlights:
- **Diabetes & Survival Status:** Understand how diabetes affects survival outcomes.
- **High Blood Pressure Insights:** Explore the survival status in patients with high blood pressure.
- **Gender & Survival:** Compare survival rates across males and females.
- **Age Distribution:** See how age correlates with survival status in heart failure patients.
- **Ejection Fraction & Survival:** Gain insights into how heart function affects survival rates.
- **Smoking Habits:** Understand the impact of smoking on patient survival.
- **Serum Sodium & Creatinine Levels:** Explore the importance of serum sodium and creatinine levels in predicting survival.

This dashboard provides an in-depth look into the major health factors that influence heart failure outcomes, helping medical professionals and researchers make data-driven decisions.

## 💻 Code Overview: Heart Failure Prediction

This project builds a predictive model for heart failure using patient health data.

### Key Features of the Code:
- **Data Preprocessing:**
   - Cleaned and normalized the dataset to ensure high-quality inputs for machine learning models.
   - Conducted feature selection to focus on critical health metrics like age, ejection fraction, and serum sodium.

- **Model Training:**
   - Implemented multiple models, including **Logistic Regression**, **Random Forest**, and **XGBoost**.
   - Hyperparameter tuning was applied for each model to achieve optimal performance using techniques like cross-validation.

- **Model Evaluation:**
   - Evaluated the models using accuracy, precision, recall, and F1 score.
   - Created confusion matrices and ROC curves for performance visualization.

- **Feature Importance:**
   - Generated feature importance scores to identify key factors influencing heart failure predictions.
   - Major contributing factors include ejection fraction, serum creatinine, and patient age.

- **Prediction Pipeline:**
   - Built a robust pipeline for training and testing the heart failure prediction model.
   - Designed for scalability and integration with future patient data for ongoing predictions.
