# Iris Flower Classification Using Machine Learning

## Project Overview

This project focuses on classifying Iris flowers into three different species using Machine Learning techniques. The Iris dataset is one of the most popular datasets for classification problems and contains measurements of sepal length, sepal width, petal length, and petal width.

The objective of this project is to build, train, and evaluate multiple machine learning models and identify the best-performing model for flower species classification.

---

## Dataset Information

**Dataset Name:** Iris Flower Dataset

**Dataset Source:**
https://www.kaggle.com/datasets/uciml/iris

### Features

* SepalLengthCm
* SepalWidthCm
* PetalLengthCm
* PetalWidthCm

### Target Variable

* Iris-setosa
* Iris-versicolor
* Iris-virginica

---

## Project Workflow

### 1. Data Loading and Exploration

* Loaded the Iris dataset using Pandas.
* Examined dataset shape, columns, and data types.
* Checked for missing values and duplicates.

### 2. Data Preprocessing

* Removed the Id column as it is not useful for prediction.
* Encoded the Species column into numerical values.
* Split the dataset into training and testing sets (80:20 ratio).

### 3. Feature Engineering

* Performed correlation analysis using a heatmap.
* Identified relationships between flower measurements and species classification.

### 4. Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest Classifier

### 5. Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

A comparison table was created to compare the performance of all three models.

### 6. Best Model Analysis

The best-performing model was selected based on evaluation metrics.

A confusion matrix was generated to visualize the classification performance of the selected model.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* GitHub

---

## Results

The machine learning models successfully classified Iris flower species with high accuracy.

After comparing all models, the best-performing model was selected based on evaluation metrics and confusion matrix analysis.

---

## How to Run the Project

1. Download the Iris dataset.
2. Upload the dataset (Iris.csv) to Google Colab.
3. Open the notebook file.
4. Run all cells sequentially.
5. View model evaluation results and predictions.

---

## Author

Pramod Gouda

AI & Machine Learning Internship Project – Pluto Academy
