# Semiconductor Yield Prediction Using Machine Learning

## Project Description

Semiconductor manufacturing is a complex process that involves various process and sensor parameters. These parameters can significantly affect the quality and yield of the final semiconductor products. Therefore, predicting semiconductor yield is important for identifying potential low-yield conditions and improving manufacturing quality.
This project uses machine learning classification techniques to analyze semiconductor manufacturing data and predict whether a semiconductor sample belongs to the High Yield or Low Yield category.
The project includes data preprocessing, exploratory data analysis, feature standardization, machine learning model training, model evaluation, and prediction. Three classification algorithms, namely Random Forest, Support Vector Machine (SVM), and Logistic Regression, are implemented and compared.
Among the evaluated models, Support Vector Machine achieved the highest accuracy of approximately 93.63% and was selected as the best-performing model for prediction.

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
- 
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
Semiconductor_Yield_Prediction/
│
├── models/
│   ├── best_model.pkl
│   ├── best_svm_model.pkl
│   └── scaler.pkl
│
├── Semiconductor_Yield_Prediction.ipynb
├── signal-data (1).csv
└── requirements.txt
````


Then:

```markdown
### File Description

- `Semiconductor_Yield_Prediction.ipynb` – Contains data analysis, preprocessing, model training, evaluation, and prediction.
- `signal-data (1).csv` – Semiconductor manufacturing dataset used in the project.
- `models/best_model.pkl` – Saved machine learning model.
- `models/best_svm_model.pkl` – Saved Support Vector Machine model.
- `models/scaler.pkl` – Saved feature scaler used during preprocessing.
- `requirements.txt` – Contains the Python libraries required to run the project.
```

## Requirements

The following Python libraries are required to run the project:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib
- jupyter

## Project Report

The complete project report is available in the repository as:

`Corizo Major Project.pdf`

## Author

**Yeeshigaa H R**

B.E. Computer Science and Engineering  
Arunachala College of Engineering for Women
