# Breast Cancer Classification using Machine Learning

## Project Overview

- This project applies machine learning techniques to classify breast tumors as benign or malignant using the Breast Cancer Wisconsin dataset. 
- The goal is to build predictive models and identify the most important cellular features contributing to the classification.
- Several machine learning models were trained and compared to evaluate their performance. 
- Model interpretation techniques were also used to understand how different features influence predictions.

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin Diagnostic dataset available in Scikit-learn.

It contains 569 samples and 30 numerical features extracted from digitized images of breast cell nuclei.

Target classes:

- Malignant (cancerous tumors)
- Benign (non‑cancerous tumors)

## Methods

The following models were implemented:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- K-Nearest Neighbors (KNN)

The workflow includes:

- Data exploration
- Data preprocessing
- Feature scaling
- Model training and evaluation
- Model comparison
- Feature importance analysis
- SHAP model interpretation

## Results

All models achieved high classification performance. Logistic Regression and SVM produced the highest accuracy among the tested models.

Feature importance analysis indicates that characteristics related to cell size, perimeter, and concavity play a significant role in identifying malignant tumors.

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SHAP

## Project Structure

breast-cancer-classification-ml
breast_cancer_classification.ipynb  
README.md  
requirements.txt

## References

Scikit-learn Breast Cancer Dataset  
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

Scikit-learn Documentation  
https://scikit-learn.org

SHAP Documentation  
https://shap.readthedocs.io
