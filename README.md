![26361](https://github.com/user-attachments/assets/99cc1f9b-0ed8-4ef2-bf72-29adc7966c8a)



# ❤️ Heart Disease Prediction Using Machine Learning

## Project Overview
Cardiovascular disease (CVD) remains a leading cause of global mortality, emphasizing the importance of early detection and prevention.  
This project integrates **statistical analysis** and **machine learning algorithms** to predict cardiovascular disease risk using patient clinical features.  
Although CVD includes multiple conditions, this study focuses specifically on **coronary artery disease (heart disease)**, using the UCI Cleveland Heart Disease dataset.

## Objectives
- Analyze relationships between clinical features and the presence of heart disease.  
- Evaluate and compare multiple supervised machine learning algorithms.  
- Identify significant predictors contributing to disease risk.  
- Demonstrate the value of combining statistical and machine learning methods for clinical prediction.

## Dataset Description
- **Source:** UCI Machine Learning Repository (Cleveland Heart Disease Dataset)  
- **Records:** 303 patient observations  
- **Features:** 13 clinical variables including age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, maximum heart rate, exercise-induced angina, ST depression (oldpeak), slope, number of major vessels (ca), and thalassemia (thal).  
- **Target Variable:** Presence (1) or absence (0) of heart disease.

## Methodology
### 1. Statistical Analysis
Descriptive statistics, correlation analysis, and hypothesis testing (t-tests, Chi-square, and ANOVA) were performed to identify significant clinical predictors.

### 2. Machine Learning Models
Five supervised algorithms were implemented and optimized using cross-validation:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)

### 3. Evaluation Metrics
Model performance was compared using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

## Results
| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| KNN | 0.9180 | 0.8965 | 0.9286 | 0.9122 | 0.9681 |
| Logistic Regression | 0.8688 | 0.8125 | 0.9286 | 0.8666 | 0.9599 |
| Random Forest | 0.8852 | 0.8387 | 0.9286 | 0.8813 | 0.9426 |


KNN achieved the best overall performance, demonstrating high discriminative ability.  
Key predictors identified included **chest pain type (cp)**, **ST depression (oldpeak)**, **number of major vessels (ca)**, and **thalassemia (thal)**.

## Key Insights
- Structural and exercise-related indicators (e.g., oldpeak, ca) were strong predictors of heart disease.  
- Statistical methods enhanced interpretability, while machine learning improved prediction accuracy.  
- The integration of both approaches provides a comprehensive framework for data-driven clinical diagnostics.

## Tools and Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## Conclusion
Machine learning models especially KNN proved effective in predicting heart disease from routine clinical data.  
Combining statistical inference with machine learning enhances both interpretability and performance, offering practical value for early detection and healthcare decision-making.
