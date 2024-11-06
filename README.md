# Prediction-of-Breast-Cancer-Detection-Using-the-Decision-Tree-C4.5-Algorithm-Using-Phyton
This project focuses on the detection and classification of breast cancer, one of the most common cancers with a significant health risk. Using the Decision Tree C4.5 algorithm, this study aims to identify key factors that influence breast cancer classification and evaluate the algorithm's performance in distinguishing tumors as either malignant or benign.

## Background
Breast cancer poses a severe health threat, particularly for women. This disease develops when cells in the breast grow abnormally, potentially spreading to other parts of the body. To assist in faster and more accurate diagnosis, this study applies the Decision Tree C4.5 algorithm to predict tumor classification based on risk factors like age, menopause status, body mass index (BMI), and radiation exposure.

## Key Features
- Data Preparation: Extensive data preprocessing, including handling missing values, normalization, and outlier removal, to ensure high-quality input.
- Exploratory Data Analysis (EDA): Visualizes risk factor distributions and analyzes correlations to understand data patterns and feature relationships.
- Classification Modeling: Utilizes the Decision Tree C4.5 algorithm, comparing entropy and gini index criteria, and evaluates model performance with relevant metrics.
- Model Evaluation: Compares results between entropy and gini to select the best-performing model for classification.

## Results
- Accuracy: 83% for the gini criterion, slightly higher than entropy.
- F1 Score: Achieves 0.828 with gini, indicating an optimal balance between precision and recall.
- Confusion Matrix: The model with gini criterion is more accurate in distinguishing "benign" and "malignant" classes.

## Technologies and Tools
- Programming Language: Python
- Data Science Library: Scikit-Learn
- Data Visualization: Matplotlib, Seaborn
- Development Environment: Jupyter Notebook

## Dataset
- Age, Menopause Status, BMI, Radiation Exposure: Key risk factors influencing breast cancer development.
- Diagnosis Status: Classification of tumor type as benign or malignant.

## Methodology
- Business Understanding: Defining the goal of classification to provide insights for cancer prevention.
- Data Understanding: Analyzing data characteristics and preprocessing.
- Data Preparation: Normalization and outlier removal to enhance model performance.
- Modeling: Implementing Decision Tree C4.5 with both gini and entropy criteria.
- Evaluation: Using confusion matrix, F1 score, and accuracy to assess model results.
- Deployment Recommendations: Proposing a data-driven cancer risk monitoring application.

## Conclusion
The Decision Tree C4.5 algorithm with the gini criterion is more effective in predicting breast cancer type than entropy. These findings can help improve diagnostic accuracy and support more precise medical decision-making for breast cancer management.
