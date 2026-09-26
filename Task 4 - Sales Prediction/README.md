# Task 4 - Sales Prediction

## Project Overview

This project is part of the **CodSoft Data Science Internship**. The objective is to predict product sales based on advertising expenditure using Machine Learning.

## Objective

To build a Linear Regression model that predicts sales using advertising data from:

* TV
* Radio
* Newspaper

## Dataset

The dataset used is **Advertising.csv**.

It contains the following columns:

* **TV** – Advertising expenditure on TV
* **Radio** – Advertising expenditure on Radio
* **Newspaper** – Advertising expenditure on Newspaper
* **Sales** – Sales generated

The dataset contains **200 records**.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Google Colab
* Jupyter Notebook

## Steps Performed

1. Imported the required Python libraries.
2. Loaded the Advertising dataset.
3. Checked the dataset information.
4. Checked for missing values.
5. Separated the input features and target variable.
6. Split the dataset into training and testing data.
7. Built a Linear Regression model.
8. Trained the model using the training data.
9. Predicted sales using the testing data.
10. Evaluated the model using Mean Squared Error and R² Score.
11. Created graphs to compare actual and predicted sales.

## Machine Learning Model

**Linear Regression** was used to predict Sales based on TV, Radio, and Newspaper advertising expenditure.

## Results

The model achieved the following results:

* **Mean Squared Error (MSE):** 2.9078
* **R² Score:** 0.9059

The R² score indicates that the model explains approximately **90.6% of the variation in Sales** on the test dataset.

## Visualization

The project includes visualizations for:

* Actual vs Predicted Sales
* TV Advertising vs Sales

## Files

* `Sales_Prediction.ipynb` – Jupyter/Google Colab notebook containing the complete implementation.
* `README.md` – Project documentation.

## Conclusion

A Linear Regression model was successfully developed to predict sales from advertising expenditure. The model was evaluated using MSE and R² Score and produced the above results on the test dataset.
