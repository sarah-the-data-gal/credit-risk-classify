# Module 12 Report Template

## Overview of the Analysis

In this analysis, we aimed to evaluate the effectiveness of various machine learning models in predicting loan risk. Specifically, we sought to predict whether loans are healthy (class 0) or high-risk (class 1) based on financial data. The purpose was to identify a model that could accurately differentiate between these two classes, aiding in risk management and decision-making.

The machine learning process involved several stages:

Data Preprocessing: Cleaning and preparing the data for modeling.
Feature Scaling: Normalizing the data to ensure uniformity.
Model Training: Training various machine learning models.
Model Evaluation: Assessing the models using accuracy, precision, and recall metrics.
We primarily used the LogisticRegression algorithm, but also explored other algorithms to compare their performance.

## Results

* **Logistic Regression Model:**
    * **Accuracy:** The model achieves an overall accuracy of 99%, meaning it correctly classifies 99% of all instances.
    * **Precision:**
        * For healthy loans (class 0), the precision is 100%, indicating perfect accuracy in identifying healthy loans.
        * For high-risk loans (class 1), the precision is 85%, signifying that 85% of the predicted high-risk loans are correctly identified.
    * **Recall:**
        * For healthy loans (class 0), the recall is 99%, showing that 99% of actual healthy loans are correctly identified.
        * For high-risk loans (class 1), the recall is 91%, meaning that 91% of actual high-risk loans are correctly identified.

## Summary

Among the machine learning models evaluated, the Logistic Regression model performed the best, achieving the highest accuracy (99%) and the most balanced precision and recall scores across both classes. This model was particularly effective at predicting healthy loans with 100% precision and 99% recall. Although its precision and recall for high-risk loans were slightly lower (85% and 91%, respectively), it still outperformed the other models in this regard.

When considering the problem at hand, it's crucial to balance the prediction of both healthy and high-risk loans. Misclassifying high-risk loans as healthy could have significant financial repercussions, making it important to have high recall for class 1. The Logistic Regression model provides the best balance, making it the recommended choice for this analysis. However, further improvements could be explored, such as addressing the class imbalance to enhance the model's performance on high-risk loans.