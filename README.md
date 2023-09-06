# Breast Cancer Wisconsin (Diagnostic) Dataset Analysis

This project involves the analysis of the Breast Cancer Wisconsin (Diagnostic) dataset available in Scikit-Learn. The dataset contains information about breast cancer tumor samples and their classification as malignant or benign. In this project we will train a few decision tree classifiers on the Breast cancer wisconsin
(diagnostic) dataset available on Scikit-Learn and compare their performances.

## Dataset Description

The Breast Cancer Wisconsin (Diagnostic) dataset consists of the following:

- Number of instances: 569
- Number of features: 30
- Classes:
  - Malignant (Class 0) - 212 instances
  - Benign (Class 1) - 357 instances

For more details about the dataset, you can refer to the [official documentation](https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-wisconsin-diagnostic-dataset).

## Tasks

1. **Data Preprocessing**:
   - Load the dataset using Scikit-Learn.
   - Explore and visualize the data to identify any features that can be dropped.
   - Split the data into training and testing sets (85/15 split).

2. **Decision Tree Classifiers**:
   - Train multiple decision tree classifiers with different hyperparameter values.
   - Evaluate the accuracy scores on both the training and test sets.
   - Investigate potential overfitting by analyzing decision tree structures.

3. **Hyperparameter Tuning**:
   - Use a 3-fold cross-validation and grid-search to find the best hyperparameters.
   - Compare the best hyperparameters obtained from cross-validation with previous settings.
   - Report the training and test set results, including confusion matrices and performance metrics.



