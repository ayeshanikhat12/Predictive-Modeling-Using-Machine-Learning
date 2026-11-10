# Predictive Modeling Using Machine Learning

**Project Type:** Machine Learning  
**Industry:** Thiranex
**Contribution:** Individual Project  
**Project Domain:** Iris Classification 
**Name:** Ayesha Nikhat

## 1. Project Overview

This project focuses on building a supervised Machine Learning model to predict Iris flower species based on their physical measurements.

A Decision Tree Classifier is used to train the model and predict three types of Iris flowers: Setosa, Versicolor, and Virginica.

The model is evaluated using accuracy score, classification report, and confusion matrix.

## 2. Project Objectives

- Understand supervised Machine Learning.
- Load and inspect the dataset.
- Divide data into training and testing sets.
- Build a Decision Tree Classification model.
- Predict Iris flower species.
- Evaluate model performance using different metrics.
- Visualize predictions using a confusion matrix.

## 3. Dataset Description

The Iris dataset contains 150 records and 5 columns.

| Column | Description |
|---|---|
| SepalLength | Length of the sepal |
| SepalWidth | Width of the sepal |
| PetalLength | Length of the petal |
| PetalWidth | Width of the petal |
| Species | Target variable representing flower species |

**Species Categories:**
- Iris-setosa
- Iris-versicolor
- Iris-virginica

**Dataset Information:**
- Total Records: 150
- Total Columns: 5
- Missing Values: 0
- Duplicate Records: 3

## 4. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Project Workflow

1. Imported the required Python libraries.
2. Loaded the Iris dataset.
3. Inspected the dataset structure and data types.
4. Checked missing values and duplicate records.
5. Separated input features (X) and target variable (y).
6. Split the dataset into 80% training data and 20% testing data.
7. Trained a Decision Tree Classifier.
8. Predicted Iris flower species using testing data.
9. Evaluated the model using accuracy and classification report.
10. Visualized the results using a confusion matrix.

## 6. Model Used

**Decision Tree Classifier**

A Decision Tree Classifier is a supervised Machine Learning algorithm used for classification tasks. It learns patterns from the training data and uses decision rules to predict the target category.

## 7. Model Performance

The model was evaluated using 30 testing records.

| Evaluation Metric | Result |
|---|---:|
| Training Records | 120 |
| Testing Records | 30 |
| Model Accuracy | 93.33% |
| Correct Predictions | 28 |
| Incorrect Predictions | 2 |

### Classification Results

| Species | Precision | Recall | F1-Score |
|---|---:|---:|---:|
| Iris-setosa | 1.00 | 1.00 | 1.00 |
| Iris-versicolor | 0.90 | 0.90 | 0.90 |
| Iris-virginica | 0.90 | 0.90 | 0.90 |

### Confusion Matrix

The confusion matrix shows that:
- All 10 Iris-setosa records were correctly classified.
- 9 out of 10 Iris-versicolor records were correctly classified.
- 9 out of 10 Iris-virginica records were correctly classified.

## 8. Key Features

- Supervised Machine Learning classification.
- Decision Tree model training.
- Iris flower species prediction.
- Model accuracy calculation.
- Classification report.
- Confusion matrix visualization.

## 9. Project Structure

```text
Predictive-Modeling-Using-Machine-Learning/
│
├──Dataset
|    └──iris.csv
├── Predictive_Modeling.ipynb
└── README.md
```

## 10. Installation and Execution

The project can be executed using Google Colab.

**Required Libraries:**

```python
pip install pandas numpy matplotlib seaborn scikit-learn
```

Import the required libraries:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import accuracy_score, classification_report, confusion_matrix
```

Upload the dataset and run the notebook cells in sequence.

## 11. Conclusion

In this project, a Decision Tree Classifier was developed to predict Iris flower species using supervised Machine Learning.

The dataset was divided into training and testing sets, and the model achieved an accuracy of 93.33%.

This project provided practical understanding of data inspection, training and testing, classification, prediction, and model evaluation.

## 12. Author

**Ayesha Nikhat**

GitHub: https://github.com/ayeshanikhat12

LinkedIn: https://www.linkedin.com/in/ayesha-nikhat-12a4aa305/