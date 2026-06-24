# Iris Flower Classification Using Machine Learning

## Project Description and Motivation

The Iris Flower Classification project is a Machine Learning application that predicts the species of an Iris flower based on its physical characteristics. The model classifies flowers into one of three categories: Iris Setosa, Iris Versicolor, and Iris Virginica.

This project was developed to understand the complete Machine Learning lifecycle, including data preprocessing, exploratory data analysis, model training, evaluation, and prediction. It serves as a beginner-friendly introduction to supervised learning and classification problems.

### Motivation

Manual classification of flower species requires botanical expertise and can be time-consuming. Machine Learning can automate this process by learning patterns from historical data and making accurate predictions for new observations.

---

# Dataset Information

**Dataset Name:** Iris Flower Dataset

**Source:** Scikit-Learn Repository / UCI Machine Learning Repository

### Dataset Statistics

* Total Records: 150
* Features: 4
* Classes: 3
* Missing Values: 0

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target Classes

* Iris-setosa
* Iris-versicolor
* Iris-virginica

---

# Installation Guide

## Prerequisites

* Python 3.9+
* pip

## Clone Repository

```bash
git clone https://github.com/your-username/iris-flower-classification-ml.git
cd iris-flower-classification-ml
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

### Required Libraries

```txt
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

# Usage Instructions

## Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/iris_analysis.ipynb
```

## Run Model Training Script

```bash
python src/train_model.py
```

## Run Prediction Script

```bash
python src/prediction.py
```

## Example Prediction

Input:

```text
Sepal Length: 5.1
Sepal Width: 3.5
Petal Length: 1.4
Petal Width: 0.2
```

Output:

```text
Predicted Species: Iris-setosa
```

---

# Machine Learning Workflow

```text
IRIS Dataset
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Selection
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Species Prediction
```

---

# Model Performance Summary

## Algorithms Evaluated

1. K-Nearest Neighbors (KNN)
2. Decision Tree Classifier
3. Random Forest Classifier

## Benchmark Results

| Algorithm     | Accuracy |
| ------------- | -------- |
| KNN           | 96%      |
| Decision Tree | 95%      |
| Random Forest | 98%      |

### Best Model

**Random Forest Classifier**

Reasons:

* Highest Accuracy
* Better Generalization
* Reduced Overfitting

### Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

Expected Accuracy Range:

```text
95% - 98%
```

---

# Project Structure

```text
iris-flower-classification-ml
│
├── dataset
│   └── IRIS.csv
│
├── notebooks
│   └── iris_analysis.ipynb
│
├── src
│   ├── preprocessing.py
│   ├── train_model.py
│   └── prediction.py
│
├── models
│   └── iris_model.pkl
│
├── images
│
├── README.md
├── requirements.txt
└── presentation
```

---

# Future Enhancements

* Deploy using Streamlit
* Develop a Web Interface
* Add Real-Time Prediction
* Integrate Deep Learning Models
* Deploy to Cloud Platforms

---

# Contributors

| Name          | Role                                  |
| ------------- | ------------------------------------- |
| Srikar Samala | Project Developer                     |
| Team Members  | Data Analysis, Testing, Documentation |

---

# License

This project is licensed under the MIT License.

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files to use, copy, modify, and distribute the software for educational and research purposes.

---

# Acknowledgements

* Scikit-Learn Documentation
* UCI Machine Learning Repository
* Python Open Source Community
* Faculty Mentors and Project Reviewers
