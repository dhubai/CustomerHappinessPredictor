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

1. **Data Exploration**
   
2. **Data Preprocessing**:
   
4. **Model Training**:
   - Trained multiple models, including Logistic regression, XGBoost, and KNN.
   - Evaluated models based on their accuracy on the validation set.
   - Selected the XGboost as the best-performing model.

5. **Hyperparameter Tuning**
   - Utilized hyperparameter tuning techniques like GridSearchCV and RandomizedSearchCV to search for optimal hyperparameters.
   - The goal was to find the best combination of hyperparameters to improve model performance.

6. **Feature Importance**
   - Conducted feature importance analysis to identify which survey questions had the most significant impact on predictions.
   - Gained insights into which survey responses played a crucial role in determining whether someone is "happy" or not.

7. **Reporting and Results**
   - Reported the best hyperparameters and corresponding accuracy for each model post-hyperparameter tuning.
   - Presented the results of different models, including their accuracy percentages, for clear comparison.
  
## Results

- The XGboost w/tuning achieved an accuracy of over 70% on the validation set.
- Feature importance analysis revealed the most critical questions in determining the outcome.

## Bonuses:

1. **Important Features**: 
   - Based on our feature selection, the question associated with X1 was identified as the most important feature, having the highest importance score of 0.28.

2. **Minimal Set of Attributes**: 
   - To preserve the most information about the problem while maximizing the predictability of our data, we would prioritize the questions associated with attributes X1, X5, and X6 given their higher importance scores.

3. **Survey Refinement**: 
   - The question corresponding to X2 has a negative importance score of -0.024. This suggests that it may not be contributing positively to our model's predictions and could be a candidate for removal in our next survey to streamline the process.
