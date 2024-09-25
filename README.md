### Title:Bio-signal Smoking Classification  
### Author: Alpesh Chovatiya

### Problem Statement:
Smoking is a significant public health concern, contributing to various chronic diseases and mortality worldwide. Identifying individuals likely to smoke based on health and physiological indicators can help in developing targeted interventions and healthcare programs. This study aims to predict whether an individual is a smoker using health examination data, which includes a variety of physiological measurements and health-related information.

### Objective:
The objective of this project is to develop a machine learning model that can accurately predict whether an individual is a smoker based on their physiological and health data. By analyzing factors such as age, height, weight, cholesterol levels, and other clinical measures, the model aims to assist in early detection and intervention efforts for smoking-related health risks.

### Dataset Overview:

#### This dataset is a collection of basic health biological signal data which contains around 55K record with 27 attributes.

- ID --> index
- gender --> gender of a person (M or F)
- age --> age of a person (5-years gap)
- height(cm)--> height of a person
- weight(kg) --> weight of a person
- waist(cm) --> waist circumference length
- eyesight(left) --> left eyesight
- eyesight(right) --> right eyesight
- hearing(left) --> hearing pulse in left ear
- hearing(right) --> hearing pulse in right ear
- systolic --> Blood pressure
- relaxation --> Blood pressure
- fasting blood sugar --> Blood test
- Cholesterol --> total
- triglyceride --> Lipid found in blood
- HDL --> cholesterol type
- LDL  --> cholesterol type
- hemoglobin --> Transporting oxygen in blood
- Urine protein --> Excess of bloodborne proteins in urine
- serum creatinine --> Amount of creatinine in blood
- AST --> glutamic oxaloacetic transaminase type
- ALT --> glutamic oxaloacetic transaminase type
- Gtp γ-GTP
- oral --> Oral Examination status
- dental caries --> Tooth decay
- tartar --> tartar status
- smoking --> Smoker (0 or 1)

### Summary of Results:
**Random Forest:** 0.83     
**Decision Tree:** 0.79   
**XGB:** 0.77    
**SVM:** 0.75   
**Logistic Regression:** 0.73   


#### Best performing model for current dataset is Random Forest  with accuracy of 83%.
