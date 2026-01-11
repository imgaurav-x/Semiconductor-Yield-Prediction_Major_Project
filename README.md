# Semiconductor Yield Prediction

This project focuses on predicting pass and fail outcomes in a semiconductor manufacturing process using machine learning techniques. The analysis is based on high-dimensional sensor data collected during different stages of the manufacturing process.

The objective of the project is to explore the dataset, handle preprocessing challenges such as missing values and class imbalance, and build classification models to accurately predict yield outcomes.

---

## Dataset

- The dataset consists of sensor measurements collected from a semiconductor manufacturing process.
- Each data point represents a single production unit.
- The target variable indicates:
  - `-1` → Pass
  - `1` → Fail

---

## Project Workflow

The project was carried out in the following steps:

1. Data import and initial exploration  
2. Missing value analysis and data cleaning  
3. Target variable identification and imbalance analysis  
4. Handling class imbalance using SMOTE  
5. Train–test split and feature scaling  
6. Model training and evaluation  
7. Model comparison and final selection  

---

## Models Used

The following machine learning models were implemented and evaluated:

- Logistic Regression (baseline model)
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## Final Model Selection

Among the evaluated models, the Support Vector Machine (SVM) was selected as the final model. Although Random Forest also showed strong performance, SVM achieved the highest accuracy while requiring significantly less training time, making it a more efficient choice for this dataset.

---

## Tools & Technologies

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn  
- **Environment:** Jupyter Notebook

---

## Conclusion

The results demonstrate that machine learning models can be effectively applied to semiconductor sensor data for yield prediction. Such models can support manufacturing engineers in monitoring processes and identifying potential yield issues at an early stage. Further improvements could be achieved through advanced feature selection and additional hyperparameter tuning.


Gaurav Aryan 
-Intern, Corizo Edutech Pvt. Ltd.
