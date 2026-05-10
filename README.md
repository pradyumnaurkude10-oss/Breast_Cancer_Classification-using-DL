# Breast Cancer Classification using DL

## Overview:
This project focuses on breast cancer prediction using Deep Learning and Machine Learning techniques. The model is trained on the Breast Cancer Wisconsin Dataset provided by Scikit-learn to classify tumors as either:

* **Benign (1)**
* **Malignant (0)**
The project demonstrates the complete workflow of a Deep Learning pipeline including:

* Data loading
* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature and target separation
* Train-test splitting
* Model training
* Model evaluation
The project is implemented using Python in a Jupyter Notebook environment and can also be executed on platforms such as Databricks.
---

# Dataset Information:

The dataset used in this project is the **Breast Cancer Wisconsin Diagnostic Dataset** available in Scikit-learn.

---

# Technologies Used:

## Programming Language: Python
## Platform: Databricks
## Libraries: NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow / Keras

---

# Workflow:

## 1. Import Libraries

The required Python libraries are imported for data handling, visualization, preprocessing, and model building.

## 2. Load Dataset

The breast cancer dataset is loaded using:

```python
from sklearn.datasets import load_breast_cancer
```

## 3. Data Preprocessing

* Convert dataset into Pandas DataFrame
* Add target labels
* Check missing values
* Perform statistical analysis

## 4. Exploratory Data Analysis

* Dataset shape
* Feature information
* Distribution of target labels
* Group analysis

## 5. Train-Test Split

The dataset is divided into training and testing sets.

```python
from sklearn.model_selection import train_test_split
```

## 6. Model Training

A Deep Learning model is trained using TensorFlow/Keras.

## 7. Model Evaluation

The model performance is evaluated using:

* Accuracy Score
* Loss Function
* Prediction Result
---

# Results

The model successfully predicts whether a tumor is:

* Benign
* Malignant

The performance depends on:

* Data preprocessing
* Neural network architecture
* Hyperparameter tuning

---

# Future Improvements

* Add CNN models for medical image classification
* Hyperparameter tuning
* Model deployment using Flask or Streamlit
* Integration with Databricks MLflow
* Improve visualization dashboards
  
