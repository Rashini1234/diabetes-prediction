# 🩺 Diabetes Prediction Using Logistic Regression

This project uses machine learning to predict whether a patient is diabetic based on various health indicators. The model is trained on the **Pima Indians Diabetes Dataset** and applies a simple logistic regression approach to make predictions.

## 📊 Dataset

The dataset includes medical details for female patients aged 21 and above of Pima Indian heritage. 

## Features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)

## Target:

Outcome: Class variable (0 = Non-diabetic, 1 = Diabetic)

## 🔍 Exploratory Data Analysis (EDA)

- Visualized class distribution
- Checked feature distributions via histograms
- Identified and handled outliers using boxplots
- Analyzed feature correlation using a heatmap

## 🧹 Data Cleaning

- Replaced invalid zero entries with NaN for relevant clinical columns
- Filled NaN values with the **median** of each column

## ⚙️ Preprocessing

- Split the data into training (80%) and test (20%) sets
- Standardized features using StandardScaler

## 🧠 Model Used

- **Logistic Regression** from scikit-learn
  
## 📈 Results

- **Accuracy**: ~75%
- **Confusion Matrix**:
  - True Negatives: 82
  - False Positives: 17
  - False Negatives: 21
  - True Positives: 34
- **Classification Report**:
  - Precision: 0.80 (Class 0), 0.67 (Class 1)
  - Recall: 0.83 (Class 0), 0.62 (Class 1)
- **ROC-AUC Score**: ~0.82


