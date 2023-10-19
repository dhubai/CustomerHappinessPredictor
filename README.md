# g2cvbOwSL3HPXugV

# Predictive Modeling for Customer Feedback

## Overview

- Developed a model to predict binary outcomes based on survey responses.
- Utilized Python and several machine learning libraries to preprocess the data, train models, and evaluate performance.

## Dataset

- The dataset contains survey responses related to a service's quality attributes.
- Each response ranges from 1 to 5, indicating the level of agreement/disagreement with a statement.
- The target variable is binary, indicating two possible outcomes.

## Approach

1. **Data Preprocessing**:
   - Loaded the dataset.
   - Split the data into training and validation sets.
   
2. **Model Training**:
   - Trained multiple models, including Random Forest, XGBoost, and Decision Tree classifiers.
   - Evaluated models based on their accuracy on the validation set.
   - Selected the Decision Tree classifier as the best-performing model.
   
3. **Feature Importance**:
   - Utilized the trained Decision Tree model to determine the importance of each feature in prediction.
   - Used Recursive Feature Elimination (RFE) to identify the most influential features.

## Results

- The Decision Tree model achieved an accuracy of over 73% on the validation set.
- Feature importance analysis revealed the most critical questions in determining the outcome.

## Bonuses:

1. **Important Features**: 
   - Based on our feature selection, the question associated with X1 was identified as the most important feature, having the highest importance score of 0.28.

2. **Minimal Set of Attributes**: 
   - To preserve the most information about the problem while maximizing the predictability of our data, we would prioritize the questions associated with attributes X1, X5, and X6 given their higher importance scores.

3. **Survey Refinement**: 
   - The question corresponding to X2 has a negative importance score of -0.024. This suggests that it may not be contributing positively to our model's predictions and could be a candidate for removal in our next survey to streamline the process.
