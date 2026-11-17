# Iris Flower Classification

## Project Overview

This project focuses on classifying Iris flowers into three different species: **Setosa, Versicolor, and Virginica** using Machine Learning techniques in Python.

The project uses the built-in Iris dataset from Scikit-learn. It contains measurements of different flowers, which are analysed to understand patterns and train classification models that can predict the species of a flower based on its measurements.

## Objective

The main objective of this project is to:
- Explore and understand the Iris dataset.
- Perform basic data analysis and visualization.
- Train different machine learning classification models.
- Compare model performance and identify the best-performing model.

## Dataset Description

The Iris dataset contains **150 samples** belonging to three flower species.

Each sample has four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable represents the species of the flower.

**Dataset Source:** Built-in Iris dataset from `sklearn.datasets`.

## Technologies and Libraries Used

- **Python** – Programming language
- **Google Colab** – Development environment
- **Pandas** – Data handling and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Scikit-learn** – Machine learning models and evaluation

## Project Workflow

The project was completed through the following steps:

### 1. Data Loading and Exploration
- Loaded the Iris dataset using Scikit-learn.
- Converted the dataset into a Pandas DataFrame.
- Checked the dataset shape, data types, missing values, and statistical summary.
- Examined the distribution of the three flower species.

### 2. Data Visualization
Different visualizations were created to understand the dataset:

- **Pair Plot:** To observe relationships between different flower measurements and species.
- **Box Plots:** To compare the distribution of sepal and petal measurements across species.
- **Correlation Heatmap:** To understand the correlation between numerical features.

### 3. Model Training

Three classification algorithms were trained:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

The dataset was divided into training and testing sets using an 80:20 split. Feature scaling was applied for the KNN model.

### 4. Model Evaluation

The models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, and F1-Score)

## Model Performance

The accuracy of the three classification models is shown below:

| Model | Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| KNN | 93.33% |
| Decision Tree | 93.33% |

## Best Performing Model

**Logistic Regression** was the best-performing model, achieving an accuracy of **96.67%** on the test dataset.

It correctly classified 29 out of 30 test samples, giving it the highest accuracy among the three models.

## Conclusion

The Iris Flower Classification project provided practical experience in data analysis, visualization, and machine learning.

After comparing three classification models, Logistic Regression achieved the highest accuracy of 96.67% and was selected as the best-performing model for this task.

---

**Project:** Iris Flower Classification  
**Internship Track:** Data Science  
**Internship Organization:** Oasis Infobyte
