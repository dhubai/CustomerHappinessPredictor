# Customer Happiness Predictor Using Machine Learning

This project aims to predict customer satisfaction levels using various machine learning models. The objective is to identify the key factors driving customer satisfaction and provide actionable insights to enhance service quality.

## Project Overview

- **Goal**: Predict customer satisfaction and identify key factors.
- **Highest Accuracy Achieved**: **77.27%** using the **LGBMClassifier**.
- **Data**: Customer survey data containing 126 records with 7 features (after cleaning, 110 records).

## Key Features and Techniques

### 1. Data Cleaning and Preprocessing
- **Duplicates**: Removed 16 duplicate rows.
- **Outliers Handling**: Applied the Interquartile Range (IQR) method, reducing the dataset from **126** to **109** records.

### 2. Feature Selection
- Used **Recursive Feature Elimination (RFE)** and **Recursive Feature Elimination with Cross-Validation (RFECV)** to identify important features.
- **Key Features**: 'X6', 'X5', 'X4' were identified as the most significant.
- Recommended removal of less informative features ('X1' and 'X2') to streamline future surveys.

### 3. Model Development
- Tested multiple algorithms, including:
  - **Logistic Regression, Decision Trees, RandomForest, ExtraTrees, KNeighbors, SVM, XGBoost,** and **LightGBM (LGBM)**.
- **LGBMClassifier** achieved the highest accuracy of **77.27%**, exceeding the project's success criteria.

## Results

- **Accuracy Achievement**: **LGBMClassifier** reached an accuracy of **77.27%** on the test set.
- **Feature Importance**: 'X6' was the most critical feature in predicting customer satisfaction.
- **Data Refinement**: Improved data quality by removing duplicates and handling outliers.

## Tools and Libraries

- **Programming Language**: Python
- **Libraries Used**:
  - Data Manipulation and Visualization: `numpy`, `pandas`, `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `lightgbm`, `xgboost`

## Conclusion

The project successfully utilized machine learning models to predict customer satisfaction, providing valuable insights for optimizing future surveys and enhancing overall service quality.

