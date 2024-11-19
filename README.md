# Email Spam Classification with Machine Learning
## Project Overview
The goal of this project is to classify emails as phishing (malicious) or legitimate based on their text content. The project explores the performance of different machine learning models, including Logistic Regression, Random Forest, XGBoost, and Naive Bayes, using TF-IDF vectorization for feature extraction.

## Dataset
The dataset contains a text_combined column representing the text content of the emails and a label column with binary labels:
0: Legitimate email
1: Phishing email

The dataset is split into:
Training set: 80%
Test set: 20%

## Model Architecture
TF-IDF Vectorizer is used to transform the text data into numerical features.
### Machine Learning Models
#### Logistic Regression
A linear classifier that predicts the probability of a binary outcome.
#### Random Forest
An ensemble learning method using decision trees for classification.
#### XGBoost
An optimized gradient boosting method designed for speed and performance.
#### Naive Bayes
A probabilistic classifier based on Bayes' Theorem with strong independence assumptions.

## Evaluation Metrics
Accuracy: Proportion of correctly classified samples.
Precision: Correctly predicted positive observations out of all predicted positives.
Recall: Correctly predicted positive observations out of all actual positives.
F1-Score: Harmonic mean of precision and recall.
Confusion Matrix: Distribution of true positive, true negative, false positive, and false negative predictions.

## Results
### Logistic Regression
![image](https://github.com/user-attachments/assets/a4661466-a17d-464a-a3e0-f6e2ab853154)

### Random Forest
![image](https://github.com/user-attachments/assets/eab2d852-597d-424d-b99b-96ebad9aef67)

### XGBoost
![image](https://github.com/user-attachments/assets/26973522-7fda-4e66-80e7-77f711fd77e8)

### Naive Bayes
![image](https://github.com/user-attachments/assets/5ab421c1-5faa-4abb-b8d8-67f4789c9d05)

## Conclusion
Logistic Regression achieved the highest accuracy with 98.45% and robust performance across precision, recall, and F1-score. Logistic Regression is suitable for deployment due to its simplicity, interpretability, and strong results compared to other models.
