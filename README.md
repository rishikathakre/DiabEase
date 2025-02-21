# DiabEase
Diabetes Prediction and Analysis

## 📌 Project Overview
This project explores diabetes prediction based on a dataset containing health indicators such as:

1) Age
2) BMI (Body Mass Index)
3) HbA1c Level
4) Blood Glucose Level
5) Hypertension, Heart Disease & Smoking History
   
### The workflow involves:

✔ Data Cleaning & Preprocessing (handling missing values, feature encoding)

✔ Exploratory Data Analysis (EDA) (statistical analysis & visualization)

✔ Handling Class Imbalance (SMOTE oversampling, class weighting)

✔ Machine Learning Models (Logistic Regression, Random Forest)

✔ Evaluation Metrics (Accuracy, Precision, Recall, F1-score, ROC-AUC)

## 📂 Dataset
The dataset is sourced from Kaggle.
To download, run:

kaggle datasets download -d iammustafatz/diabetes-prediction-dataset
unzip diabetes-prediction-dataset.zip

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction

### 2️⃣ Install Dependencies

pip install -r requirements.txt

### 3️⃣ Run the Script

python diabetes_prediction.py


## 🛠️ Machine Learning Models Used

The project implements two classifiers:

Logistic Regression (Baseline model)
Random Forest Classifier (Improved performance)

## Handling Class Imbalance:

Class Weights in models
SMOTE (Synthetic Minority Over-sampling Technique)

### Evaluation Metrics:

Accuracy
Precision, Recall, F1-score
ROC-AUC Score

## 📊 Data Visualization & Insights

### 1️⃣ Age vs. Blood Glucose Level
Diabetic patients tend to have higher blood glucose levels.
Older individuals have a higher risk of diabetes.

### 2️⃣ HbA1c Levels by Diabetes Status
HbA1c levels are significantly higher for diabetic patients.

### 3️⃣ BMI vs. Diabetes
Higher BMI is slightly correlated with diabetes.

### 4️⃣ Smoking History & Diabetes
Smoking history has a notable influence on diabetes risk.


## 🔍 Results & Conclusion

Random Forest outperforms Logistic Regression in terms of accuracy and F1-score.
Feature Importance: Blood glucose level and HbA1c are the most significant indicators of diabetes.
SMOTE improved recall for diabetic class, ensuring fewer false negatives.

## 📜 License
This project is licensed under the MIT License – you are free to use and modify it with attribution.
