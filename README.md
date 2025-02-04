# Breast Cancer Detection Using Machine Learning

This project aims to build a machine learning model to classify breast cancer as malignant or benign using the **Wisconsin Diagnostic UCI dataset**. The model utilizes feature selection, hyperparameter tuning, and SMOTE for class balancing to improve performance.

## Dataset
- **Source**: [Kaggle Datasets](https://www.kaggle.com/datasets/abhinavmangalore/breast-cancer-dataset-wisconsin-diagnostic-uci?select=breast-cancer-wisconsin-data.csv)
- **Features**: 30 numerical features extracted from digitized images of breast mass
- **Target**: Diagnosis (Malignant or Benign)

## Model Development
1. **Data Preprocessing**: 
   - Handling missing values, duplicates, and outliers
   - Feature selection using Recursive Feature Elimination (RFE)
2. **Machine Learning Models**:
   - Random Forest Classifier (optimized with hyperparameter tuning)
   - XGBoost Classifier
3. **Class Balancing**:
   - Applied **SMOTE (Synthetic Minority Over-sampling Technique)**
4. **Evaluation Metrics**:
   - Accuracy, Precision, Recall, F1-Score, and Confusion Matrix

## Final Model Performance
- **Optimized Random Forest with SMOTE**:
  - **Accuracy**: 0.9737
  - **Precision**: 0.97
  - **Recall**: 0.99

## Results & Insights
- Feature selection improved model efficiency with minimal accuracy loss.
- SMOTE improved model performance by addressing class imbalance.
- Random Forest performed better than XGBoost in this dataset.
