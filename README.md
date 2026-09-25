# Mini Project on Student Pass/Fail Prediction using Logistic Regression

## 📌 Project Overview

This mini project uses **Logistic Regression** to predict whether a student will **Pass or Fail** based on their study and academic information.

## 📊 Dataset

The dataset contains the following features:

* `study_hours` – Number of hours studied
* `attendance` – Student attendance percentage
* `previous_score` – Previous academic score
* `assignments_completed` – Number of assignments completed
* `pass_fail` – Target variable

  * `0` = Fail
  * `1` = Pass

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🤖 Machine Learning Model

**Logistic Regression** was used for this binary classification problem.

The dataset was divided into training and testing sets using `train_test_split`.

## 📈 Model Accuracy

The Logistic Regression model achieved an accuracy of:

**76.7%**

## 🔍 Project Steps

1. Load the dataset
2. Understand the data
3. Perform Exploratory Data Analysis (EDA)
4. Visualize the data
5. Select features and target
6. Split the dataset into training and testing data
7. Train the Logistic Regression model
8. Make predictions
9. Evaluate model accuracy

## 📁 Project Files

```text
student-logistic-regression/
│
├── data/
│   └── student_data.csv
│
├── student_logistic_regression.ipynb
│
└── README.md
```

## 🎯 Conclusion

This project demonstrates how **Logistic Regression** can be used to predict a binary outcome such as student **Pass/Fail** based on academic features.
