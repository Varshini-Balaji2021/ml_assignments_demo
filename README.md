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

# Gradient Boosting – Loan Approval Prediction

## 📌 Project Overview

This project demonstrates the use of the **Gradient Boosting Classifier** to predict whether a loan application is likely to be **approved or rejected**.

The project is implemented using **Python and Google Colab/Jupyter Notebook** and focuses on understanding how Gradient Boosting can be applied to a binary classification problem.

---

## 🎯 Objective

The objective is to build a machine learning model that predicts loan approval based on applicant and financial characteristics such as:

* Applicant Income
* Loan Amount
* Credit Score
* Employment Years
* Existing Loans

The target variable is:

* `0` → Loan Rejected
* `1` → Loan Approved

---

## 🤖 Machine Learning Algorithm

###3. Gradient Boosting Classifier

Gradient Boosting is an ensemble machine learning algorithm that builds decision trees sequentially. Each new tree attempts to improve the errors made by the previous trees.

The workflow is:

```text
Loan Application Data
        ↓
Train/Test Split
        ↓
Gradient Boosting Classifier
        ↓
Loan Prediction
        ↓
Model Evaluation
```

The model is configured with:

* `n_estimators = 100`
* `learning_rate = 0.1`
* `max_depth = 3`

---

## 📊 Dataset

A synthetic dataset containing **1,000 loan applications** was generated using Python.

### Features

| Feature         | Description              |
| --------------- | ------------------------ |
| ApplicantIncome | Applicant's income       |
| LoanAmount      | Requested loan amount    |
| CreditScore     | Applicant's credit score |
| EmploymentYears | Years of employment      |
| ExistingLoans   | Number of existing loans |
| LoanApproved    | Target variable          |

The dataset was generated specifically for educational and algorithm demonstration purposes.

---

## ⚙️ Methodology

The project follows these steps:

1. Import required Python libraries
2. Generate the loan application dataset
3. Explore the dataset
4. Visualize loan approval distribution
5. Separate features and target
6. Split data into training and testing sets
7. Train the Gradient Boosting Classifier
8. Generate predictions
9. Evaluate model performance
10. Analyze the confusion matrix
11. Analyze feature importance
12. Predict the result for a new loan application

---

## 📈 Evaluation Metrics

The model is evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1 Score**
* **Confusion Matrix**

Feature importance is also analyzed to understand which applicant characteristics contribute most to the model's predictions.

---

## 🔍 Key Demonstrations

This project demonstrates:

* Binary classification
* Ensemble learning
* Gradient boosting
* Sequential decision-tree learning
* Model evaluation
* Confusion matrix analysis
* Feature importance
* Prediction for a new loan application

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
03_Gradient_Boosting_Loan_Approval.ipynb
README.md
```

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run the cells sequentially.
3. The synthetic dataset will be generated automatically.
4. Train the Gradient Boosting model.
5. Review the evaluation metrics and visualizations.
6. Test the model using a new loan application.

---

## 📌 Conclusion
-------------------
# 4. K-Means Clustering – Customer Segmentation

## 📌 Project Overview

This project demonstrates the use of the **K-Means Clustering algorithm** for customer segmentation.

Unlike supervised machine learning, K-Means is an **unsupervised learning algorithm**, meaning there is no predefined target variable. The algorithm identifies groups of customers based on similarities in their characteristics.

The project is implemented using **Python and Google Colab/Jupyter Notebook**.

---

## 🎯 Objective

The objective is to divide customers into meaningful groups based on:

* Age
* Annual Income
* Spending Score
* Purchases Per Year

These groups can help businesses understand different customer segments and develop targeted marketing strategies.

---

## 🤖 Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised clustering algorithm that divides observations into a predefined number of clusters.

The algorithm works by:

1. Selecting the number of clusters (`K`)
2. Initializing cluster centroids
3. Assigning customers to the nearest centroid
4. Recalculating centroids
5. Repeating the process until the clusters stabilize

The workflow is:

```text
Customer Data
      ↓
Feature Selection
      ↓
Feature Scaling
      ↓
Elbow Method
      ↓
Select K
      ↓
K-Means Clustering
      ↓
Customer Segments
      ↓
Cluster Analysis
```

---

## 📊 Dataset

A synthetic dataset containing **500 customer records** was generated using Python.

### Features

| Feature          | Description                           |
| ---------------- | ------------------------------------- |
| Age              | Customer age                          |
| AnnualIncome     | Customer's annual income              |
| SpendingScore    | Customer spending tendency from 1–100 |
| PurchasesPerYear | Number of purchases made per year     |

There is **no target variable** because this is an unsupervised learning problem.

---

## ⚙️ Methodology

The project follows these steps:

1. Import required Python libraries
2. Generate the customer dataset
3. Explore the dataset
4. Visualize customers before clustering
5. Select clustering features
6. Standardize the features
7. Apply the Elbow Method
8. Select the number of clusters
9. Train the K-Means model
10. Assign customers to clusters
11. Visualize the customer segments
12. Analyze cluster centers
13. Create customer segment profiles
14. Assign a new customer to a cluster

---

## 📈 Elbow Method

The **Elbow Method** is used to help determine an appropriate number of clusters.

The method calculates the **inertia** for different values of K.

The value of K is selected by examining where the decrease in inertia begins to slow down significantly.

For this demonstration, **4 clusters** are used.

---

## 🔍 Customer Segmentation

After applying K-Mea


This project demonstrates how the **Gradient Boosting Classifier** can be used for loan approval classification. It provides a practical introduction to ensemble learning, sequential tree-based modeling, classification evaluation, feature importance, and prediction using Python and Scikit-learn.

> **Note:** The dataset is synthetic and is intended for educational and algorithm demonstration purposes only.
-------------------------------------
PROJECT 5:
Artificial Neural Network – Credit Card Default Prediction
📌 Project Overview

This project demonstrates the use of an Artificial Neural Network (ANN) for predicting whether a credit card customer is likely to default on their next payment.

The project is implemented in Python using Google Colab and follows a supervised machine learning classification workflow.

🎯 Objective

To build an Artificial Neural Network classification model that predicts:

0 → No Default
1 → Default

The model is trained using customer credit-related information and evaluated using standard classification metrics.
📊 Dataset

Dataset: UCI Default of Credit Card Clients Dataset

The dataset contains information about credit card customers, including demographic and credit/payment-related variables.

Target variable:

default payment next month

The dataset contains 30,000 customer records and 24 input features.
🤖 Algorithm
Artificial Neural Network (ANN)

The project uses MLPClassifier from Scikit-learn.

Neural network configuration:

Hidden Layer 1: 32 neurons
Hidden Layer 2: 16 neurons
Activation Function: ReLU
Solver/Optimizer: Adam
Maximum Iterations: 100
Random State: 42
🔄 Machine Learning Workflow
Dataset
   ↓
Data Understanding
   ↓
Exploratory Data Analysis
   ↓
Feature & Target Separation
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Build ANN
   ↓
Train Model
   ↓
Make Predictions
   ↓
Model Evaluation
   ↓
New Customer Prediction
🛠️ Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Scikit-learn
Joblib
📈 Model Evaluation

The ANN model is evaluated using:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix

A training loss curve is also generated to visualize the learning behaviour of the neural network.
🔮 New Customer Prediction

After training, the ANN is used to predict whether a new customer is likely to default.

The model also provides the predicted probability for:

No Default
Default
💾 Model Saving

The trained ANN model and feature scaler are saved using Joblib:
ann_credit_default_model.pkl
ann_scaler.pkl

📚 Key Learning

Through this project, the following concepts were demonstrated:

Preparing a credit default dataset.
Performing basic exploratory data analysis.
Separating features and target variables.
Splitting data into training and testing sets.
Applying feature scaling.
Building an Artificial Neural Network.
Training a classification model.
Evaluating model performance.
Interpreting a confusion matrix.
Visualizing the ANN training loss.
Making predictions for a new customer.
Saving the trained model.

🏁 Conclusion
This project demonstrates how an Artificial Neural Network can be applied to a supervised classification problem for credit card default prediction. The workflow covers data preparation, feature scaling, neural network training, model evaluation, and prediction on new customer data. This project corresponds to the Artificial Neural Networks topic included in the Machine Learning course syllabus.

⚠️ Disclaimer
This project is intended for educational and demonstration purposes. Model predictions should not be used as the sole basis for real-world credit decisions.

