# Human Action Detection

A machine learning project for classifying human actions using classical ML algorithms on structured tabular data.

## Overview

This project applies a variety of supervised machine learning models to detect human actions from a labeled dataset. It includes preprocessing, class balancing, feature scaling, training multiple classifiers, and comparing their performance using evaluation metrics such as accuracy, confusion matrix, and classification report.

## Project Structure

- HumanActionDetection.ipynb — Main notebook with end-to-end pipeline   
- README.md — Project documentation

## Features

- Handles class imbalance using upsampling
- Feature scaling with RobustScaler and StandardScaler
- Label encoding of categorical target variables
- Trains and evaluates various machine learning models:
  - Logistic Regression
  - Lasso Regression
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Gaussian Naive Bayes
  - Decision Tree Classifier
  - Random Forest Classifier
- Model evaluation using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

## Results

Each model's performance is evaluated and compared using accuracy, confusion matrices, and classification reports. Visualizations are included in the notebook.

## Possible Improvements

- Add k-fold cross-validation
- Introduce feature selection or dimensionality reduction (e.g., PCA)
- Use advanced models like XGBoost or LightGBM
- Deploy the best model using Streamlit or Flask

## License

This project is licensed under the MIT License.

## Author

Pree Om  
GitHub: [https://github.com/Pree-om](https://github.com/Pree-om)  
LinkedIn: [https://linkedin.com/in/pree-om](https://linkedin.com/in/pree-om)
