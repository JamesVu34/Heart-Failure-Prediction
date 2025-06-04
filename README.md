# Heart-Failure-Prediction

## Overview
This project focuses on analyzing four different heart failure datasets using machine learning techniques. The objective is to predict heart failure events by identifying key patterns across all datasets.

## Datasets
**Bold text is the dependant outcome we are training on.**
1. `heart_dataset_1.csv`  - 918 observations, 11 features: age, sex, ChestPainType, RestingBP, Cholesterol, FastingBS, Resting ECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope, **HeartDisease**

2. `heart_dataset_2.csv` - 300 observations, 12 features: age, anaemia, creatinine_phosphokinase, diabetes, ejection_fraction, high_blood_pressure, platelets, serum_creatinine, serum_sodium, sex, smoking, time, **DEATH_EVENT**

3. `heart_dataset_3.csv` - 369 observations, 59 features: Age, Age.Group, Gender, Locality, Marital status, Life.Style, Sleep	Category, Depression, Hyperlipi, Smoking, Family.History, F.History, Diabetes, HTN, Allergies, BP, Thrombolysis, BGR, B.Urea, S.Cr, S.Sodium, S.Potassium	, S.Chloride, C.P.K, CK.MB, ESR, WBC, RBC, Hemoglobin, P.C.V, M.C.V, M.C.H, M.C.H.Cm PLATELET_COUNT, NEUTROPHIL, LYMPHO, MONOCYTE, EOSINO, Others, CO, Diagnosis, Hypersensitivity, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, num, SK, SK.React, Reaction, **Mortality**

4. `heart_dataset_4.csv` - 1000 observations, 30 features: id, **death**, los, age, gender, cancer, cabg, crt, defib, dementia, diabetes, hypertension, ihd, mental_health, arrhythmias, copd, obesity, pvd, renal_disease, valvular_disease, metastatic_cancer, pacemaker, pneumonia, prior_appts_attended, prior_dnas, pci, stroke, senile, quintile, ethnicgroup, fu_time

## Features
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Model Building: Logistic Regression & Random Forest
- Model Evaluation & Comparison
- Visualizations & Feature Importance

## Technologies
- Python
- Pandas, Numpy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebooks / VSCode
