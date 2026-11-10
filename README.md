# Task 4: Classification with Logistic Regression

## Overview
This project implements a Binary Classification Model using Logistic Regression on the Breast Cancer Wisconsin Dataset. The objective is to classify tumours as Benign or Malignant using machine learning techniques.

The project demonstrates data preprocessing, feature standardization, model training, performance evaluation, and classification threshold tuning.

## Objectives
- Build a binary classification model using Logistic Regression.
- Understand and implement feature standardization.
- Evaluate model performance using classification metrics.
- Visualize the Sigmoid Function and ROC Curve.
- Experiment with different classification thresholds.

## Dataset
**Breast Cancer Wisconsin Dataset**

- Source: Scikit-learn built-in dataset.
- Total Records: 569
- Input Features: 30
- Target Classes:
  - 0 – Benign
  - 1 – Malignant

The dataset contains numerical features describing characteristics of cell nuclei in breast mass samples.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

1. **Data Loading:** Loaded the Breast Cancer Wisconsin dataset using Scikit-learn.
2. **Exploratory Data Analysis:** Examined class distribution, tumour radius distribution, and feature correlations.
3. **Train-Test Split:** Divided the dataset into 80% training data and 20% testing data.
4. **Feature Standardization:** Applied StandardScaler to bring numerical features to a common scale.
5. **Model Training:** Trained a Logistic Regression classifier.
6. **Prediction:** Generated class predictions and malignant class probabilities.
7. **Model Evaluation:** Evaluated performance using Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC.
8. **ROC Curve:** Visualized the model's classification performance.
9. **Sigmoid Function:** Visualized the sigmoid activation function used in Logistic Regression.
10. **Threshold Tuning:** Experimented with a classification threshold of 0.3 instead of the default 0.5.

## Evaluation Metrics

| Metric | Purpose |
|---|---|
| Accuracy | Measures overall prediction correctness |
| Precision | Measures correctness of positive predictions |
| Recall | Measures how many actual positive cases are detected |
| F1-score | Balances precision and recall |
| ROC-AUC | Measures the model's ability to distinguish between classes |
| Confusion Matrix | Displays correct and incorrect classifications |

## Visualizations

The project includes the following visualizations:

- Cancer Class Distribution
- Mean Radius Distribution
- Feature Correlation Heatmap
- Confusion Matrix
- ROC Curve
- Sigmoid Function
- Tuned Threshold Confusion Matrix

## Threshold Tuning

The default classification threshold of 0.5 was compared with a lower threshold of 0.3.

A lower threshold makes the classifier more sensitive to malignant cases, potentially increasing recall while also increasing false positives.

## Project Structure

```text
Task-4-Logistic-Regression/
│
├── screenshots/
│   ├── class_distribution.png
│   ├── radius_distribution.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── sigmoid_function.png
│   └── tuned_confusion_matrix.png
│
├── logistic_regression.py
└── README.md
```


## Learning Outcomes

- Understanding binary classification using Logistic Regression.
- Learning the importance of feature standardization.
- Understanding the Sigmoid Function.
- Evaluating classification models using multiple performance metrics.
- Understanding ROC curves and ROC-AUC.
- Learning how classification thresholds influence model predictions.

## Internship Task
**Elevate Labs – AI & ML Internship**

**Task 4:** Classification with Logistic Regression.