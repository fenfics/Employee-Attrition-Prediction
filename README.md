# Employee Attrition Prediction

An employee attrition prediction project using machine learning to analyze factors related to employee turnover and predict employee attrition.

## Project Overview

This project analyzes employee-related data and develops machine learning models to predict whether an employee is likely to leave the organization.

The project includes:

* Data checking and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Model evaluation and comparison
* Power BI dashboard

## Dataset

The project uses the **Employee Attrition in the AI & Hybrid-Work Era** dataset from Kaggle.

The original dataset is not included in this repository.

See [`data/README.md`](data/README.md) for more information about the dataset and data source.

## Project Structure

```text
Employee-Attrition-Prediction/
│
├── data/
│   └── README.md
│
├── notebooks/
│   ├── 01_data_checking.ipynb
│   ├── 02_data_visualization.ipynb
│   ├── 03_knn_model.ipynb
│   └── 04_naive_bayes_model.ipynb
│
├── results/
│   ├── knn/
│   └── naive_bayes/
│
├── visualizations/
│   └── powerbi/
│
├── README.md
└── requirements.txt
```

## Machine Learning Models

### K-Nearest Neighbors (KNN)

KNN is used to classify employees into:

* `0` = No Attrition
* `1` = Attrition

The optimal value of K is selected using 5-Fold Cross-Validation.

### Naive Bayes

Naive Bayes is used as another classification model for predicting employee attrition and comparing its performance with KNN.

## Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## Visualization

Power BI is used to present the model results and key findings in an interactive dashboard.

## Tools and Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook
* Power BI

## Team

This project was developed as a group machine learning project.

Each member was responsible for different parts of the project, including data preprocessing, exploratory data analysis, KNN, Naive Bayes, model comparison, and visualization.
