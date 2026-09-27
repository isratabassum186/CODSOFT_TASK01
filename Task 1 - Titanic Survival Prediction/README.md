# Task 1 - Titanic Survival Prediction

## Project Overview

This project is part of the **CodSoft Data Science Internship**. The objective is to predict whether a passenger survived the Titanic disaster using Machine Learning.

## Objective

To build a Machine Learning model that predicts passenger survival based on features such as:

* Passenger class
* Sex
* Age
* Number of siblings/spouses
* Number of parents/children
* Fare
* Port of embarkation

## Dataset

The dataset used is **Titanic-Dataset.csv**.

It contains information about Titanic passengers, including:

* **PassengerId**
* **Survived**
* **Pclass**
* **Name**
* **Sex**
* **Age**
* **SibSp**
* **Parch**
* **Ticket**
* **Fare**
* **Cabin**
* **Embarked**

The dataset contains **891 passenger records**.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Google Colab
* Jupyter Notebook

## Steps Performed

1. Imported the required Python libraries.
2. Loaded the Titanic dataset.
3. Examined the dataset using `df.info()`.
4. Checked for missing values.
5. Cleaned missing values in the dataset.
6. Selected the required features and target variable.
7. Converted categorical values into numerical values using one-hot encoding.
8. Split the dataset into training and testing data.
9. Built a Logistic Regression model.
10. Trained the model using the training data.
11. Predicted passenger survival using the test data.
12. Evaluated the model using accuracy.
13. Created a confusion matrix.
14. Compared actual and predicted values using visualizations.

## Machine Learning Model

**Logistic Regression** was used to predict whether a passenger survived or did not survive.

## Result

The model achieved an accuracy of approximately:

**81.01%**

## Visualizations

The project includes:

* Confusion Matrix
* Actual vs Predicted Survival graph

## Files

* `Titanic_Survival_Prediction.ipynb` – Complete Jupyter/Google Colab notebook.
* `Titanic-Dataset.csv` – Dataset used for the project.
* `README.md` – Project documentation.

## Conclusion

A Logistic Regression model was successfully developed to predict Titanic passenger survival. The model achieved approximately **81.01% accuracy** on the test dataset.

