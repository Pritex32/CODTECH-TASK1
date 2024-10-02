
# Name: Ukanwa Prisca Oluomachi
# Comapany: CODTECH IT SOLUTIONS
# ID: COD67690
# Domain: Data Science
# Mentor: Muzammil


# Diabeties Analysis and prediction

## Data Overview: 
The dataset used contains 2768 rows and 10 columns, including features like 'Pregnancies,' 'Glucose,' 'BloodPressure,' 
'Insulin,' 'BMI,' 'Age,' and the target variable 'Outcome' (indicating diabetic vs. non-diabetic).

## Exploratory Data Analysis:
Visualizations include count plots of diabetic vs. non-diabetic patients and age distribution.
The dataset had no missing values, but duplicate entries (1990) were identified and removed.
Outliers were handled using the IQR method for columns like 'Insulin,' 'BMI,' 'BloodPressure,' and 'Age.'
Statistical Analysis: Summary statistics and correlations between features were computed. 'Glucose' showed the strongest correlation with diabetes outcome (0.46).

## Model Building [Download here](diabetes-1.pdf)
Five models were tested:
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
  
## Data Processing:
The data was split into training and testing sets (80% training, 20% testing).
Standard scaling was applied to the feature variables.

## Model Evaluation:
- SVM performed the best with an accuracy of 79.48%.
- KNN and Random Forest had similar accuracy (76.28%), while Logistic Regression performed slightly lower (75.64%).
- Decision Tree was the least accurate (69.23%).
  
## Conclusion:
[](https://github.com/Pritex32/CODTECH-TASK1/blob/main/diabetic.jpg)
SVM was selected as the best model based on its accuracy.
The conclusion highlighted the growing trend of diabetes and recommended regular health checkups, personalized health devices, and consulting healthcare professionals.

