# COVID-19 Prediction using Random Forest

This repository contains a Python-based Machine Learning script that preprocesses a dataset (`covid_toy.csv`) and trains a Random Forest Classifier to predict whether a patient has COVID-19 based on their symptoms and demographics.

## 🚀 Features & Workflow

The code executes a complete end-to-end Machine Learning pipeline:
1. **Data Loading:** Reads patient data using `pandas`.
2. **Missing Data Imputation:** Uses `SimpleImputer` from `scikit-learn` to handle missing values in the `fever` column.
3. **Categorical Encoding:** Converts text-based features (`gender`, `cough`, `city`, and `has_covid`) into numerical values using `LabelEncoder`.
4. **Data Splitting:** Segregates features ($X$) and target labels ($y$), splitting them into an 80% training set and a 20% testing set.
5. **Model Training:** Utilizes a `RandomForestClassifier` to learn patterns from the training data.
6. **Evaluation:** Measures and outputs the classification performance using `accuracy_score`.

## 🛠️ Tech Stack & Libraries

* **Python 3.x**
* **Pandas** & **NumPy** (Data manipulation and structured analysis)
* **Scikit-Learn** (Data preprocessing, model building, and evaluation)

## 📋 Prerequisites

Before running the script, make sure you have installed the required dependencies. You can install them via pip:

Bash-

pip install numpy pandas scikit-learn

## 🛠️ How to Run Locally
Clone the repository:

Bash-

git clone [https://github.com/Ashutoshgupta618/covid19-prediction-randomforest-classification.git](https://github.com/Ashutoshgupta618/covid19-prediction-randomforest-classification.git)
Navigate into the project folder:

Bash- 

cd covid19-prediction-randomforest-classification

Dataset Requirement: Ensure your source dataset is named covid_toy.csv and is placed in the root directory alongside your script.

## Execute the script:

Bash-

python app.py

## 📊 Expected Output
When you run app.py, it will print:

A snapshot of the raw data.

A snapshot of the data after label encoding.

The final model accuracy score (e.g., 0.815 or similar depending on the data)
