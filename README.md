
#ML_Assignments_Demo
#1. House Price Prediction with Linear Regression

This notebook demonstrates a simple linear regression model to predict house prices using the California Housing dataset. 

## Project Overview

This project aims to predict the median house value (`MedHouseVal`) based on various features of housing districts in California. The process involves:

1.  **Loading Data**: Fetching the California Housing dataset.
2.  **Data Exploration**: Understanding the dataset's structure, types, and summary statistics.
3.  **Feature and Target Definition**: Separating the dataset into features (input variables) and the target variable (what we want to predict).
4.  **Train/Test Split**: Dividing the data into training and testing sets to evaluate model performance.
5.  **Feature Scaling**: Applying standardization to features for optimal model training.
6.  **Model Training**: Training a Linear Regression model.
7.  **Prediction**: Making predictions on the test set.
8.  **Model Evaluation**: Assessing the model's performance using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared.
9.  **Visualization**: Plotting actual vs. predicted values.
10. **Sample Prediction**: Demonstrating how to predict the value for a single house.

#2. Random Forest – Customer Churn Prediction

## 📌 Project Overview

This project demonstrates the use of the **Random Forest Classifier** to predict whether a customer is likely to **churn (leave a service)** or **stay**.

The project is implemented using **Python and Google Colab/Jupyter Notebook** and focuses on understanding how Random Forest can be applied to a binary classification problem.

---

## 🎯 Objective

The objective is to build a machine learning model that predicts customer churn based on customer characteristics such as:

* Age
* Tenure
* Monthly Charges
* Number of Support Calls
* Contract Duration

The target variable is:

* `0` → Customer stays
* `1` → Customer churns

---

## 🤖 Machine Learning Algorithm

### Random Forest Classifier

Random Forest is an ensemble machine learning algorithm that combines predictions from multiple decision trees.

In this project:

```text
Customer Data
      ↓
Train/Test Split
      ↓
Random Forest Classifier
      ↓
Churn Prediction
      ↓
Model Evaluation
```

The model uses **100 decision trees** to make predictions.

---

## 📊 Dataset

A synthetic customer dataset containing **1,000 customer records** was generated using Python.

### Features

| Feature        | Description                      |
| -------------- | -------------------------------- |
| Age            | Customer age                     |
| Tenure         | Number of months as a customer   |
| MonthlyCharges | Monthly service charges          |
| SupportCalls   | Number of customer support calls |
| ContractMonths | Contract duration                |
| Churn          | Target variable                  |

The dataset was generated specifically for demonstrating the Random Forest algorithm.

---

## ⚙️ Methodology

The project follows these steps:

1. Import required Python libraries
2. Create the customer dataset
3. Explore the dataset
4. Separate features and target
5. Split the data into training and testing sets
6. Train the Random Forest Classifier
7. Generate predictions
8. Evaluate model performance
9. Analyze the confusion matrix
10. Analyze feature importance
11. Predict churn for a new customer

---

## 📈 Evaluation Metrics

The model is evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1 Score**
* **Confusion Matrix**

Feature importance is also analyzed to understand which customer characteristics contribute most to the model's predictions.

---

## 🔍 Key Demonstrations

The notebook demonstrates:

* Binary classification
* Ensemble learning
* Decision-tree-based modeling
* Model evaluation
* Confusion matrix analysis
* Feature importance
* Prediction for a new customer

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## 📁 Project Files

```text
02_Random_Forest_Customer_Churn.ipynb
README.md
```

---

## 🚀 How to Run

1. Open the Jupyter Notebook or Google Colab notebook.
2. Run the cells sequentially.
3. The dataset will be generated automatically.
4. Train the Random Forest model.
5. Review the evaluation metrics and visualizations.
6. Test the model using a new customer example.

---

## 📌 Conclusion

This project demonstrates how the **Random Forest Classifier** can be used for customer churn prediction. It provides a practical introduction to classification, ensemble learning, model evaluation, and feature importance using Python and Scikit-learn.

> **Note:** The dataset is synthetic and is intended for educational and algorithm demonstration purposes.

