# AI-Based Heart Disease Prediction Using Machine Learning

## Project Overview

**AI-Based Heart Disease Prediction Using Machine Learning** is a machine learning project that predicts whether a person is likely to have heart disease based on different health-related parameters.

The project uses a heart disease dataset containing **303 patient records and 14 attributes**. Machine learning algorithms are trained on the dataset to identify patterns in the medical data and predict the target class.

This project was developed as part of an **AI/ML internship project** to understand data preprocessing, machine learning model training, evaluation, and prediction.

---

## Objectives

* To understand and preprocess healthcare data.
* To analyze important heart disease-related attributes.
* To train machine learning models for prediction.
* To compare different machine learning algorithms.
* To evaluate model performance using standard evaluation metrics.
* To build a foundation for a future web-based prediction system.

---

## Dataset

The project uses a heart disease dataset containing **303 records and 14 columns**.

### Important Features

| Feature    | Description                          |
| ---------- | ------------------------------------ |
| `age`      | Age of the patient                   |
| `sex`      | Gender of the patient                |
| `cp`       | Chest pain type                      |
| `trestbps` | Resting blood pressure               |
| `chol`     | Cholesterol level                    |
| `fbs`      | Fasting blood sugar                  |
| `restecg`  | Resting electrocardiographic results |
| `thalach`  | Maximum heart rate achieved          |
| `exang`    | Exercise-induced angina              |
| `oldpeak`  | ST depression                        |
| `slope`    | Slope of peak exercise ST segment    |
| `ca`       | Number of major vessels              |
| `thal`     | Thalassemia-related measurement      |
| `target`   | Heart disease prediction target      |

---

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**
* **Google Colab / Jupyter Notebook**
* **GitHub**

---

## Machine Learning Algorithms

The following machine learning algorithms are used:

### 1. Logistic Regression

Used as a classification model to predict the target class based on the input features.

### 2. Decision Tree

Uses a tree-based structure to make predictions by dividing the data according to different conditions.

### 3. Random Forest

Uses multiple decision trees together to improve prediction performance and reduce the limitations of a single decision tree.

---

## Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Prediction
   ↓
Model Evaluation
   ↓
Heart Disease Prediction
```

---

## Model Evaluation

The trained models can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help in understanding how well the machine learning models perform on unseen test data.

---

## Implementation

The project follows these main steps:

1. Import the required Python libraries.
2. Load the heart disease dataset.
3. Explore the dataset.
4. Check for missing or invalid values.
5. Separate input features and target values.
6. Split the dataset into training and testing data.
7. Train different machine learning models.
8. Make predictions using the trained models.
9. Calculate evaluation metrics.
10. Compare the model results.

---

## Future Scope

The project can be further improved by:

* Using larger healthcare datasets.
* Applying advanced machine learning algorithms.
* Performing hyperparameter tuning.
* Using cross-validation.
* Adding explainable AI techniques.
* Developing a web application using **Flask** or **Streamlit**.
* Creating a user-friendly interface where users can enter health parameters and receive a prediction.
* Deploying the application online.

---

## Disclaimer

This project is developed for **educational and academic purposes only**.

The prediction produced by the machine learning model should **not be considered a medical diagnosis**. Medical decisions should always be made by qualified healthcare professionals.

---

## Author

**Bharti Giram**

Student | AI/ML Enthusiast | Web Development Learner

---

## ⭐ Project Purpose

This project demonstrates how machine learning can be applied to healthcare-related datasets for predictive analysis and provides practical experience with **data preprocessing, model training, evaluation, and prediction**.
