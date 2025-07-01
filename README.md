# 🧠 Regression and Classification with Python

This project demonstrates the application of supervised machine learning techniques on two real-world datasets using Python and Scikit-learn. It includes regression and classification tasks, complete with preprocessing, model building, and evaluation using cross-validation.

## 📁 Project Overview

We worked on two separate datasets:

### 1️⃣ Regression Task - COVID-19 Dataset
- **Goal**: Predict total deaths using COVID-19 statistics.
- **Rows**: 232
- **Columns**: 13
- **Missing Values**: 879
- **Target Variable**: `Total Deaths`

### 2️⃣ Classification Task - Asthma Dataset
- **Goal**: Predict asthma diagnosis based on health metrics.
- **Rows**: 2,392
- **Columns**: 29
- **Missing Values**: 0
- **Target Variable**: `Diagnosis`

## 🛠️ Preprocessing Steps
- Handled missing values (dropped columns with >40% missing).
- One-hot encoded categorical variables (classification task).
- Min-Max scaled all numerical features.

## 🤖 Models Used

### Regression Models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor (SVR)
- K-Nearest Neighbors (KNN)

### Classification Models:
- Logistic Regression
- Support Vector Machine (SVC)
- K-Nearest Neighbors
- Decision Tree Classifier
- Random Forest Classifier
- Naïve Bayes

## 📊 Evaluation Metrics

### Regression (R² Scores):
| Model                 | Test R² | Cross-Validation R² |
|----------------------|---------|----------------------|
| Linear Regression     | 1.0     | 1.0                  |
| Decision Tree         | 0.493   | -0.5507              |
| Random Forest         | 0.606   | -11.25               |

### Classification (Accuracy Scores):
| Model                 | Test Accuracy | Cross-Validation Accuracy |
|----------------------|----------------|----------------------------|
| Logistic Regression   | 95.8%          | 94.8%                      |
| SVM                   | 95.82%         | 94.8%                      |
| KNN                   | 95.6%          | 94.6%                      |

## 🧠 Insights

- **Regression**: Linear Regression performed perfectly, while tree-based models overfitted.
- **Classification**: Logistic Regression and SVM gave strong and consistent results.
- **Cross-validation**: Helped reveal overfitting in some models, especially in regression.

## 🔗 Colab Notebooks

- [Asthma Classification Model](https://colab.research.google.com/drive/1h6CCehtIw2vktLDyfbT1HhkeFzjBAFad?usp=sharing)
- [COVID-19 Regression Model](https://colab.research.google.com/drive/1FqMxzHnKtOzw7lITS47re8bq3bf4OnyQ?usp=sharing)

## 🧑‍💻 Contributors
- Mahmoud Tarbolsi
- Ahmed Abduljawad
- Othman Al-Omari

---

## 🚀 Skills Demonstrated

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Overfitting detection using cross-validation
- Scikit-learn pipeline creation
