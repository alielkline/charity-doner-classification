📊 Charity Donor Income Prediction

This project applies supervised machine learning algorithms to predict whether an individual earns more than $50,000 per year using data from the 1994 U.S. Census (Adult dataset, UCI Machine Learning Repository).

The motivation for this task is inspired by a non-profit context:

Understanding income brackets can help organizations make informed decisions about donor outreach strategies — such as estimating the likelihood of receiving a donation or deciding the scale of contribution to request.

🔍 Project Overview

Implement and compare several supervised learning algorithms (e.g., Logistic Regression, Decision Trees, Random Forests, SVM, Naïve Bayes).

Select the best candidate model from preliminary results.

Optimize the chosen algorithm with hyperparameter tuning.

Evaluate performance using metrics like accuracy, precision, recall, and F1-score.

📂 Dataset

Source: UCI Machine Learning Repository – Adult Dataset

Originally published in “Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid” by Ron Kohavi and Barry Becker.

Modifications:

Removed the fnlwgt feature.

Dropped entries with missing or ill-formatted values.

🎯 Goal

The final model predicts whether an individual’s income is:

≤ $50,000

> $50,000

This notebook demonstrates the complete ML pipeline: data preprocessing, feature engineering, model training, evaluation, and optimization.
