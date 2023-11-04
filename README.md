# SGD-LoglossClassifier

## Overview

This README provides an overview of the project where I implemented a Stochastic Gradient Descent (SGD) Classifier with Logloss and L2 regularization from scratch, without using scikit-learn. The project was carried out in a Jupyter Notebook and involved several tasks as outlined below.

## Project Tasks

1. Importing packages: We started by importing necessary Python libraries and modules, such as NumPy, Pandas, and scikit-learn, to facilitate data handling and machine learning.

2. Creating a custom dataset: Using the `make_classification` function from scikit-learn, a custom dataset was generated with 50,000 samples and 15 features.

3. Splitting data into train and test sets: The dataset was divided into training and testing sets with a 75% - 25% split. Additionally, data standardization was performed to ensure uniform scaling of the features.

4. Implementing the SGD Classifier: The SGD Classifier with Logloss and L2 regularization was implemented from scratch. Specific functions were provided and had to be filled in, such as `initialize_weights`, `logloss`, `gradient_dw`, and `gradient_db`.

5. Training the model: The logistic regression model was trained using the training data, and the weights and intercept were updated using stochastic gradient descent.

6. Evaluating the model: The model's performance was assessed by computing the log loss on both the training and test datasets.

7. Comparing with scikit-learn: To validate the implementation, the weights and intercept from the custom implementation were compared to the scikit-learn SGD Classifier.

## Project Output

Here are the key results and findings from the project:

- The implementation of the SGD Classifier with Logloss and L2 regularization closely matched the results obtained from the scikit-learn's SGD Classifier, with a difference in terms of 10^-3.

- The number of epochs versus the training and test log loss was visualized, showing how the loss changed during the training process.

- The model achieved an accuracy of approximately 95% on both the training and test datasets, indicating good performance.
