Prediction of Hypertension using Machine Learning and Correlation with Stroke
This repository contains the implementation and findings of a study focused on predicting hypertension using various machine learning algorithms. Additionally, it analyzes the statistical correlation between hypertension and the incidence of stroke.

📜 Abstract
Hypertension, or high blood pressure, is a major global health issue affecting over a billion people and is a leading risk factor for cardiovascular diseases, including stroke. This project leverages machine learning to build predictive models for early hypertension detection, which can facilitate timely interventions and reduce the risk of severe complications. We trained and evaluated several ML algorithms, including Logistic Regression, Decision Trees, Random Forest, and K-Nearest Neighbors (KNN), using key health indicators. Furthermore, we employed statistical methods like the Chi-Square test and logistic regression to quantify the strong correlation between hypertension and stroke. Our results demonstrate the high efficacy of ML models in this domain and underscore the critical need for proactive hypertension management to mitigate stroke risk.

📊 Dataset
The data for this study was sourced from the Behavioral Risk Factor Surveillance System (BRFSS) 2015, a health-related survey conducted by the Centers for Disease Control and Prevention (CDC) in the United States.

We utilized two primary datasets:

Hypertension Dataset: Contained 26,083 instances with attributes such as age, sex, chest pain type, cholesterol, blood pressure, heart rate, and more.

Stroke Dataset: Contained 40,910 instances with attributes including sex, age, hypertension status, heart disease, BMI, and smoking status.

⚙️ Methodology
The project followed a structured machine learning workflow:

1. Model Training
The dataset was split into 80% for training and 20% for testing. The following models were implemented:

Logistic Regression: A statistical model for binary classification.

Decision Tree: A supervised learning model that classifies data by splitting it based on feature importance.

Random Forest: An ensemble method using multiple decision trees to improve generalization and reduce overfitting.

K-Nearest Neighbours (KNN): A distance-based algorithm that classifies based on the majority class of its nearest neighbors (k=3).

2. Performance Evaluation
Model performance was assessed using standard classification metrics:

Accuracy: The proportion of correctly classified instances.

Precision: The proportion of true positive predictions among all positive predictions.

Recall (Sensitivity): The model's ability to identify all actual positive cases.

F1-Score: The harmonic mean of precision and recall.

3. Statistical Analysis
To validate the link between hypertension and stroke, we used:

Chi-Square Test: To determine if there is a significant association between the two conditions.

Logistic Regression Analysis: To calculate the odds ratio, quantifying how much more likely hypertensive patients are to experience a stroke.

📈 Results
Machine Learning Model Performance
The Decision Tree and Random Forest models demonstrated nearly perfect accuracy, significantly outperforming the other models.

Model

Training Accuracy

Testing Accuracy

Logistic Regression

68.35%

68.24%

Decision Tree

100%

99.94%

Random Forest

100%

99.71%

KNN

92.28%

85.11%

Hypertension and Stroke Correlation
The statistical analysis confirmed a strong and significant relationship:

Chi-Square Test: The p-value was < 0.0001, indicating a statistically significant correlation.

Odds Ratio: 2.95. This crucial finding implies that hypertensive patients are nearly 3 times more likely to experience a stroke compared to non-hypertensive individuals.

🎯 Conclusion
This study successfully demonstrates that machine learning models, particularly Decision Trees and Random Forest, can predict hypertension with exceptional accuracy. The strong, statistically significant correlation found between hypertension and stroke highlights the critical importance of early detection and management of high blood pressure as a preventative measure against stroke.

🚀 Future Work
Future research can extend this work in several exciting directions:

Deep Learning: Integrate more complex models like LSTMs or CNNs to a potentially capture more intricate patterns in the data.

Explainable AI (XAI): Use techniques like SHAP or LIME for advanced feature engineering and to better understand the model's decision-making process.

Real-Time Monitoring: Develop a system that integrates data from wearable devices for real-time risk prediction and health monitoring.

✍️ Authors
Dr. Subhashini R

Utkarsh Mishra

Lakshita Setia

(Based on the paper: "Prediction of Hypertension using Machine Learning Algorithms and Correlation with Stroke")
