# Head Size vs Brain Weight Prediction

This project builds a simple machine learning model to predict brain weight based on head size using Linear Regression. 

## Dataset
The model is trained on the `headbrain.csv` dataset[cite: 1]. It isolates two primary variables:
* **Feature (X):** `Head Size(cm^3)`[cite: 1]
* **Target (y):** `Brain Weight(grams)`[cite: 1]

## Technologies Used
This project is built with Python and utilizes the following data science libraries[cite: 1]:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

## Model Performance
The dataset was divided into a 90% training set and a 10% testing set. The Scikit-Learn Linear Regression model achieved an R-squared ($R^2$) score of approximately 0.812, indicating a strong predictive fit.

## Installation
To run this notebook locally, ensure you have the required packages installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
