
# Case Study: Predicting Customer Churn in a Telecom Company

This dataset focuses on individuals who either retain telecom services (Not Churn) or leave the telecom company (Churn) based on various inputs and services offered. The dataset consists of **7,043 observations** and **21 features**, with only one column containing missing values, which I addressed through imputation. There are no outliers present in the dataset.

I implemented three machine learning classification algorithms—**Random Forest Classifier**, **Naïve Bayes**, and **K-Nearest Neighbors (KNN)**—and compared their prediction outputs.

### Results:
- **Random Forest**: This model exhibited a higher overall accuracy of **80%**, demonstrating a balanced performance for Class 0. However, it struggled to detect churn (Class 1), resulting in low recall.
  
- **KNN**: This algorithm excelled at identifying churn, achieving a high recall for Class 1. However, it came at the expense of a higher false positive rate, misclassifying many non-churn instances as churn, which led to lower precision for Class 0.
  
- **Naïve Bayes**: This model performed the least effectively, with an accuracy of only **69%**, primarily due to the high cardinality of the dataset and the imbalance in the output feature related to churn.

