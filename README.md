# Student Placement Prediction

## 📌 Overview

This is a beginner-friendly Machine Learning project based on student placement data.

The project contains two different prediction tasks:

1. **Placement Prediction** – Predict whether a student will get placed or not.
2. **Placement Package Prediction** – Predict the placement package of a student.

Both problems are solved using different machine learning algorithms depending on the type of prediction.

---

## 🎯 Projects

### 1. Placement Prediction

**Problem Type:** Classification

**Machine Learning Algorithm:** Logistic Regression

The goal of this project is to predict whether a student will get placed or not based on the available student-related features.

The target variable has two possible outcomes:

- `1` → Placed
- `0` → Not Placed

Since the target contains two categories, this is a **binary classification problem**.

📓 Notebook: `placement_prediction_logistic_regression.ipynb`

---

### 2. Placement Package Prediction

**Problem Type:** Regression

**Machine Learning Algorithm:** Linear Regression

The goal of this project is to predict the placement package of a student based on the available features.

Since the target variable is a continuous numerical value, this is a **regression problem**.

📓 Notebook: `Placement_prediction_linear_regression.ipynb`

---

## 🔄 Machine Learning Workflow

Both notebooks follow the basic Machine Learning workflow:

1. Importing required libraries
2. Loading the dataset
3. Understanding the data
4. Exploratory Data Analysis (EDA)
5. Data preprocessing
6. Splitting the data into training and testing sets
7. Model training
8. Making predictions
9. Evaluating the model

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📂 Project Structure

```text
student-placement-prediction/
│
├── placement_prediction_logistic_regression.ipynb
├── Placement_prediction_linear_regression.ipynb
│
├── dataset/
│   └── placement.csv
│
├── README.md
└── .gitignore
