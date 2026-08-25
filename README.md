# Semiconductor Yield Prediction Using Machine Learning

## Project Description

Semiconductor manufacturing involves various process and sensor parameters that can affect the quality and yield of semiconductor products. This project uses machine learning classification techniques to predict whether a semiconductor sample belongs to the High Yield or Low Yield category.
The project analyzes semiconductor manufacturing data, performs data preprocessing and feature standardization, and applies three machine learning classification algorithms: Random Forest, Support Vector Machine (SVM), and Logistic Regression.
Among the evaluated models, Support Vector Machine achieved the highest accuracy of approximately 93.63% and was selected as the best-performing model.

## Objectives

- To analyze semiconductor manufacturing data.
- To preprocess and standardize the dataset.
- To train different machine learning classification models.
- To compare Random Forest, SVM, and Logistic Regression.
- To identify the best-performing model.
- To predict High Yield and Low Yield semiconductor samples.
- To provide prediction probabilities for new samples.

## Dataset

The dataset contains semiconductor manufacturing process and sensor-related features. Each record represents a semiconductor sample and contains multiple numerical features used for yield classification.

### Target Classes

- High Yield
- Low Yield

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook
- VS Code

## Machine Learning Models

The following classification algorithms were implemented:

1. Random Forest
2. Support Vector Machine (SVM)
3. Logistic Regression

## Data Processing

The following preprocessing steps were performed:

- Data cleaning
- Missing value checking
- Feature and target separation
- Train-test splitting
- Feature standardization
- Preparation of data for machine learning models

## Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the dataset and identify patterns in the semiconductor manufacturing features.

The analysis included:

- Histogram analysis
- Box plot analysis
- Correlation heatmap
- Target class distribution

## Model Performance

The machine learning models were evaluated using classification metrics such as accuracy, precision, recall, and F1-score.

Among the evaluated models, Support Vector Machine achieved the highest accuracy.

| Model | Accuracy |
|---|---:|
| Random Forest | Add actual value |
| Support Vector Machine (SVM) | 93.63% |
| Logistic Regression | Add actual value |

SVM was selected as the best-performing model for semiconductor yield prediction.

## Prediction

The trained Support Vector Machine model is used to predict new semiconductor samples as:

- High Yield
- Low Yield

The system also provides prediction probabilities for the predicted classes.
The trained model is saved using Joblib and can be reused for predicting new samples.

## Project Structure

```text
Semiconductor-Yield-Prediction/
│
├── dataset/
├── notebooks/
├── model/
├── app/
├── requirements.txt
├── README.md
└── Project_Report.pdf

