# Prediction of Hypertension using Machine Learning Algorithms and Correlation with Stroke

## Project Overview
Hypertension (high blood pressure) is one of the most common and serious medical conditions, strongly linked with cardiovascular diseases (CVDs) such as heart failure and stroke.  
This project applies **Machine Learning algorithms** to predict hypertension and studies its **correlation with stroke**.  

Our findings demonstrate that ML-based approaches can achieve high accuracy in hypertension prediction, and statistical methods confirm a strong association between hypertension and stroke.

---

## Dataset
We used datasets from the **Behavioral Risk Factor Surveillance System (BRFSS) 2015** (CDC, USA):

1. **Hypertension Dataset** (26,083 instances)  
   - Features: Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, ECG, Max Heart Rate, Exercise Angina, ST Depression, Slope, Major Vessels, Thalassemia.  

2. **Stroke Dataset** (40,910 instances)  
   - Features: Age, Sex, Hypertension, Heart Disease, Marital Status, Residence, Avg. Glucose, BMI, Smoking Status.  

---

## Machine Learning Models
We trained and evaluated the following models:

- **Logistic Regression**  
- **Decision Tree**  
- **Random Forest**  
- **K-Nearest Neighbors (KNN)**  
- **Naïve Bayes**

### Training & Testing
- Train/Test split: **80/20**  
- Evaluation Metrics: **Accuracy, Precision, Recall, F1-score**

---

## Results

| Model               | Train Accuracy | Test Accuracy |
|---------------------|----------------|---------------|
| Logistic Regression | 68.35%         | 68.24%        |
| Decision Tree       | 100%           | 99.94%        |
| Random Forest       | 100%           | 99.71%        |
| KNN                 | 92.28%         | 85.11%        |

 **Decision Tree and Random Forest achieved the highest accuracy**.

---

## Correlation Analysis (Hypertension ↔ Stroke)

- **Chi-Square Test**  
  - χ² = 2704.63  
  - p-value = 0.0001 (**significant correlation**)  

- **Logistic Regression Analysis**  
  - Odds Ratio = **2.95**  
  - Hypertensive patients are nearly **3x more likely** to experience a stroke.

---

## Conclusion
- ML models (especially **Decision Tree** and **Random Forest**) can accurately predict hypertension.  
- Strong statistical evidence shows a **significant correlation** between hypertension and stroke.  
- Early prediction can guide **preventive measures** and reduce stroke risk.  

---

## Future Work
- Integrating **Deep Learning models (LSTM, CNN)**  
- Feature engineering with **Explainable AI (SHAP, LIME)**  
- **Real-time monitoring** with wearable devices  

---

