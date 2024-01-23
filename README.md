# Credit Risk Classification Project

## Background

In this challenge, the goal is to employ various techniques to train and evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company will be used to build a model capable of identifying the creditworthiness of borrowers.

## Before You Begin

1. Create a new repository for this project called `credit-risk-classification`. Do not add this homework to an existing repository.
2. Clone the new repository to your computer.
3. Inside your `credit-risk-classification` repository, create a folder titled "Credit_Risk."
4. Add the `credit_risk_classification.ipynb` and `lending_data.csv` files found in the "Starter_Code.zip" file to the "Credit_Risk" folder.
5. Push your changes to GitHub.

## Files

Download the following files to help you get started:
[Module 20 Challenge files](#) (Link not provided, replace with actual link)

## Instructions

### Split the Data into Training and Testing Sets (30 points)

To receive all points, you must:
1. Read the `lending_data.csv` data from the Resources folder into a Pandas DataFrame. (5 points)
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns. (10 points)
3. Split the data into training and testing datasets by using `train_test_split`. (15 points)

### Create a Logistic Regression Model (30 points)

To receive all points, you must:
1. Fit a logistic regression model by using the training data (`X_train` and `y_train`). (10 points)
2. Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model. (5 points)
3. Evaluate the model’s performance by doing the following:
   - Generate a confusion matrix. (5 points)
   - Generate a classification report. (5 points)
   - Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels? (5 points)

### Write a Credit Risk Analysis Report (20 points)

To receive all points, you must:
1. Provide an overview that explains the purpose of this analysis. (5 points)
2. Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model. (5 points)
3. Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. (10 points)

### Coding Conventions and Formatting (10 points)

To receive all points, you must:
1. Place imports at the top of the file, just after any module comments and docstrings and before module globals and constants. (3 points)
2. Name functions and variables with lowercase characters, with words separated by underscores. (2 points)
3. Follow DRY (Don’t Repeat Yourself) principles, creating maintainable and reusable code. (3 points)
4. Use concise logic and creative engineering where possible. (2 points)

### Code Comments (10 points)

To receive all points, your code must:
1. Be well commented with concise, relevant notes that other developers can understand. (10 points)

