Diabetes Classification Project

Predicting whether a patient has diabetes using machine learning.

## Dataset
- 768 patients, 9 columns
- Source: Pima Indians Diabetes Dataset
- Target: 0 = No Diabetes, 1 = Diabetes


## Tools
Python, Pandas, Matplotlib, Seaborn, Scikit-learn

## Steps

**1. Load Data**
768 patient records loaded directly from URL.

**2. Fix Missing Values**
Glucose, BMI, BloodPressure, Insulin and SkinThickness had 0 values — medically impossible. Replaced with column averages.

**3. Visualize Data**
- Heatmap → Glucose strongest predictor (0.47 correlation)
- Bar chart → 500 non-diabetic vs 268 diabetic patients

**4. Train Model**
Split data 70/30. Applied StandardScaler. Trained Logistic Regression model.

**5. Evaluate**
Accuracy improved from 73.59% to 74.02% after fixing missing values.
