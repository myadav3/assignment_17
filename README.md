# Practical Application Assignment 17.1: Comparing Classifiers 

Overview:

In this third practical application assignment, your goal is to compare the performance of the classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines) you encountered in this section of the program. 

# Data:
The dataset used comes from the UCI Machine Learning repository. The data is from a Portuguese banking institution and is a collection of the results of multiple marketing campaigns. 

# Data clean up and processing
- Outlier treatment, Missing value treatment
- Delete features
- Convert data type
- Split into training (0.7) and test (0.3)

# Modeling
- Logistic regression
- K-nearest neighbors
- Decision tree

# Deliverable

prompt_III[1].ipynb

# Colcusion

KNN Report:
              precision    recall  f1-score   support

           0       0.91      0.99      0.95     10829
           1       0.61      0.19      0.29      1270

    accuracy                           0.90     12099
   macro avg       0.76      0.59      0.62     12099
weighted avg       0.88      0.90      0.88     12099

Decision Tree Report:
              precision    recall  f1-score   support

           0       0.92      0.98      0.95     10829
           1       0.57      0.28      0.37      1270

    accuracy                           0.90     12099
   macro avg       0.74      0.63      0.66     12099
weighted avg       0.88      0.90      0.89     12099
