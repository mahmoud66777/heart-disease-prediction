# heart-disease-prediction
Predicting heart disease using Logistic Regression, SVM, KNN – with EDA, outlier removal, and feature selection.
# ❤️ Heart Disease Prediction Project

This project aims to predict the likelihood of heart disease in patients based on clinical and lifestyle features using multiple machine learning models.

## 📊 Dataset
- Source: [Kaggle - Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- Columns: Age, Sex, Chest Pain Type, RestingBP, Cholesterol, FastingBS, RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope, HeartDisease

## 🔍 Exploratory Data Analysis (EDA)
- Bar plots showing relationships between **Chest Pain Type**, **Sex**, and **Age** with heart disease.
- Histogram for **Cholesterol** distribution.
- Correlation heatmap to identify feature importance.

## 🧼 Data Preprocessing
- **Encoding** of categorical columns (`Sex`, `ChestPainType`, etc.).
- **Outlier removal** using IQR for all numerical columns.
- Feature selection based on correlation threshold.

## 🧠 Models Used
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**

Each model was trained and tested using:
- `train_test_split`
- `StandardScaler` for normalization
- Confusion matrix visualization
- Accuracy evaluation

## 📈 Performance
| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | ~84%     |
| SVM                 | ~82%     |
| KNN (k=3)           | ~81%     |

