# MLB Pitch Type Classification ⚾

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/status-academic%20project-green)

Supervised machine learning project for classifying MLB pitch types using Statcast postseason pitch-by-pitch data.

---

## Overview

This project applies supervised machine learning techniques to classify the type of pitch thrown in MLB postseason games. Using Statcast pitch-by-pitch data, multiple machine learning models are trained and evaluated to predict the target variable **`pitch_type`**.

The project includes data preprocessing, feature selection, model training, and performance evaluation.

---

## Key Objective

The main objective of this project is to evaluate the performance of different supervised machine learning models in predicting MLB pitch types using Statcast postseason data.

---

## Dataset

The dataset contains pitch-by-pitch information from MLB postseason games. Each row represents a single pitch and includes features related to:

- pitch velocity
- pitch movement
- release position
- batter and pitcher characteristics
- strike zone location
- game context and baserunner configuration

The goal of the project is to predict the **pitch type** using these features.

---

## Dataset Source

The dataset used in this project was obtained from Kaggle:

MLB Postseason 2025 Pitch-by-Pitch Data  
https://www.kaggle.com/datasets/janus137/mlb-postseason-2025-pitch-by-pitch-data

---

## Methodology

The machine learning workflow includes the following steps:

1. Data loading and preprocessing
2. Feature selection and sampling
3. Exploratory analysis of the target variable
4. Training multiple supervised learning models
5. Model evaluation using classification metrics
6. Comparison of model performance

---

## Models Used

The following machine learning models were implemented and evaluated:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression
- Decision Tree Classifier

---
## Model Performance

| Model | Accuracy |
|------|------|
| K-Nearest Neighbors | 0.71 |
| Logistic Regression | 0.74 |
| Decision Tree | 0.69 |
| Support Vector Machine | 0.76 |

---

## Project Structure
```text
mlb-pitch-type-classification
│
├── data/
│ └── Data_MLB_2025_StatcastPostseason_PitchByPitch_20251102a.csv
│
├── notebooks/
│ └── mlb.ipynb
│
├── docs/
│ ├── Memoria_AA.pdf
│ └── Presentacion_AA.pdf
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```
## Running the Notebook
Launch Jupyter Notebook and open:
```bash
notebooks/mlb.ipynb
```
---

## Results

The models were trained and evaluated to predict the pitch type using Statcast data.  
Performance metrics such as accuracy and classification reports were used to compare the models.

The results show how different machine learning algorithms perform when classifying pitch types based on pitch characteristics and game context.

Among the evaluated models, **Support Vector Machine (SVM)** achieved the best performance with an accuracy of **0.76**, making it the strongest classifier in this comparison.

---

## Documentation

Additional project documentation is available in the **docs/** folder:

- Project report (`Memoria_AA.pdf`)
- Presentation slides (`Presentacion_AA.pdf`)

---

## Authors

This project was developed as part of a university assignment by:

- Diego José García Callejas
- Héctor Fernández Cano

---

## Acknowledgements

Dataset provided by Kaggle user **janus137**.
