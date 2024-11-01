# Stroke Prediction Project

### Project Motivation: 
The goal of this project is to create a tool that can predict who is likely to have a stroke. By looking at things like age, high blood pressure, heart disease, and body mass index, the tool aims to help doctors find people who are at high risk. Early detection can help reduce the number of strokes and lessen the severity of the effects.

---
### Libraries Used:
1. pandas: For data manipulation and analysis.
2. matplotlib: For creating visualizations to illustrate trends and analysis results.
3. seaborn: For creating visualizations
4. scikit-learn: For model building, data preprocessing, and evaluation metrics.

---
### Repository Files:
- healthcare-stroke-analysis.ipynb: Jupyter notebook containing all code for data exploration, preprocessing, trend analysis, and model building. This notebook demonstrates the entire workflow, including visualization of trends between age and health indicators, and the predictive modeling steps.
- healthcare-dataset-stroke-data.csv: The dataset used for this project, containing individual health information including age, BMI, hypertension status, heart disease status, average glucose level, and stroke status. This dataset is the basis for both trend analysis and model training.

---
## Summary of Analysis Results:

---
### 1. Trends Between Health Indicators:
- Age and Hypertension: Hypertension prevalence increases with age, highlighting the importance of blood pressure monitoring in older age groups.
- Age and Heart Disease: Similar to hypertension, heart disease incidence rises with age, underscoring the need for cardiovascular health monitoring as people get older.
- BMI and Hypertension: Higher BMI is associated with an increased likelihood of hypertension, suggesting that weight management could be an effective preventive measure.
- Hypertension and Heart Disease: Individuals with hypertension show a higher prevalence of heart disease, reinforcing the correlation between blood pressure and cardiovascular health.

### 2. Predictive Modeling:
- The model achieved a satisfactory level of accuracy in predicting stroke risk. The primary predictive features identified by the model are age, hypertension, heart disease, and BMI. The model allows for risk categorization:
- High-Risk Individuals: Those with hypertension, heart disease, higher BMI, or advanced age.
- Low-Risk Individuals: Those without these factors, indicating a lower probability of stroke.

---
