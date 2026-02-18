# Insurance Cost Prediction using Machine Learning
This project analyzes and predicts medical insurance charges using demographic and health-related features such as age, BMI, smoking status, and number of children. The goal is to understand key factors influencing insurance costs and build regression models to predict charges.

Dataset source: [Prediction of Insurance Charges using Age & Gender](https://www.kaggle.com/datasets/thedevastator/prediction-of-insurance-charges-using-age-gender)

## Project Objectives
- Perform Exploratory Data Analysis (EDA) to identify patterns and relationships
- Understand how features like age, BMI, and smoking affect insurance charges
- Prepare and preprocess data for machine learning
- Train regression models to predict insurance charges
- Evaluate model performance and identify important predictors
## Key Insights from EDA
- Smoking status has the strongest impact on insurance charges
- Age shows a moderate positive correlation with insurance costs
- BMI has a moderate influence on charges
- Number of children has minimal impact on insurance cost
### Key ML concepts demonstrated:
- Exploratory Data Analysis (EDA)
- Feature preprocessing using ColumnTransformer
- Pipeline implementation
- OneHotEncoding categorical variables
- Hyperparameter tuning
- Cross-validation
- Model evaluation and comparison

## Final Model Summary

Two regression models were trained and evaluated to predict insurance charges:

Models tested:
- Decision Tree Regressor
- Random Forest Regressor

Hyperparameter tuning was performed using:
>max_leaf_nodes

Best model:
> Random Forest Regressor (max_leaf_nodes=30)

Performance:
> Mean Absolute Error (MAE): 2503.61

 Cross-validation results confirmed that Random Forest provided more stable and reliable predictions compared to Decision Tree.

### Conclusion:
-----
Random Forest Regressor was selected as the final model due to its lower error and better generalization performance.

