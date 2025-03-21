# Disease-diagnosis-and-recommendation-system
This web application provides a comprehensive health diagnostic tool that helps users identify potential health conditions based on symptoms and medical test results. Built with Streamlit, the system utilizes machine learning models to predict several common diseases and conditions.
Features
1. General Diagnosis
Predicts common conditions based on symptoms and vital signs:

Temperature
Pulse rate
Common symptoms (vomiting, yellowish urine, indigestion)

Conditions detected:

Heart Disease
Viral Fever/Cold
Jaundice
Food Poisoning

2. Diabetes Prediction
Predicts diabetes based on common risk factors:

Number of pregnancies
Glucose level
Blood pressure
Skin thickness
Insulin level
BMI
Diabetes pedigree function
Age

3. Heart Disease Prediction
Predicts heart disease risk based on multiple factors:

Age
Sex
Chest pain type
Resting blood pressure
Serum cholesterol
Fasting blood sugar
Resting ECG results
Maximum heart rate
Exercise-induced angina
ST depression induced by exercise
Slope of the peak exercise ST segment
Number of major vessels colored by fluoroscopy
Nuclear stress test results

4. Parkinson's Disease Prediction
Predicts Parkinson's disease based on biomedical voice measurements:

Various frequency and amplitude measurements
Jitter and shimmer values
Harmonics-to-noise ratio
Nonlinear dynamical complexity measures

5. BMI Calculator
Calculates Body Mass Index and provides categorization:

Underweight
Normal Weight
Overweight
Obese

Technology Stack

Frontend & Backend: Streamlit
Machine Learning: Scikit-learn (RandomForestClassifier)
Data Processing: Pandas, NumPy
Visualization: PIL

Models
The system uses pre-trained machine learning models:

diabetes_model.sav - Diabetes prediction model
heart_disease_model1.sav - Heart disease prediction model
parkinsons_model.sav - Parkinson's disease prediction model
A general diagnosis model trained on a custom dataset
