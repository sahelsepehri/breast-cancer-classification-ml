# Breast Cancer Tumor Classification

An end-to-end machine learning project to classify breast tumors as malignant or benign using the Wisconsin dataset. This project focuses on model comparison, performance evaluation, and interpretability using SHAP.

## Highlights
- **Models:** Logistic Regression, SVM, KNN, Random Forest.
- **Evaluation:** Precision, Recall, F1-Score, ROC-AUC, Confusion Matrices.
- **Interpretability:** SHAP analysis & Random Forest feature importance.
- **Insights:** Identified key geometric features (size, perimeter) influencing tumor malignancy.

## Workflow
1. **EDA & Preprocessing:** Data cleaning, class balance inspection, and feature scaling.
2. **Dimensionality Reduction:** PCA to visualize class separability in lower dimensions.
3. **Modeling:** Training and comparing four classification models.
4. **Interpretation:** Analyzing model decisions with SHAP to ensure medical relevance.

## Key Results
Logistic Regression and SVM emerged as the top-performing models, effectively distinguishing between malignant and benign cases with high reliability. Analysis confirms that tumor morphology features (size, texture, concavity) are the primary predictors, aligning with clinical findings.

## Limitations & Future Work
While effective on this dataset, the models are based on pre-engineered features. Future work will focus on testing on more diverse, larger datasets and exploring deep learning on raw imaging data.

## Technologies
Python | Pandas | Scikit-learn | SHAP | Matplotlib/Seaborn | Jupyter

---
*Developed for educational purposes in computational biology.*
