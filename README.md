# House-Price-Prediction_Kaggle

This is my first independent machine learning project focused on predicting house prices using regression techniques. Through this hands-on practice, I gained comprehensive experience in end-to-end data processing, feature engineering, and model optimization.

# Project Overview

With 79 various features (e.g., square footage, number of bedrooms, location, etc.) describing almost every aspect of residential homes in Ames, Iowa, the goal of this project is to build a predictive model that accurately estimates house prices. I worked with a housing dataset to develop a robust model that can generalize to unseen data.

# Key Workflow
### 1. Data Preprocessing

**Price Normalization**: Applied log transformation to normalize the target variable (house prices), which helped address the skewed distribution and improve model performance.

**Handling Missing Values**: Identified and imputed missing values using appropriate strategies (mean/median for numerical features, mode for categorical features).

**Outlier Detection & Treatment**: Detected outliers using IQR method and handled them to prevent skewed model training.

### 2. Feature Engineering
This phase significantly deepened my understanding of data transformation:

- Processed categorical features using one-hot encoding and label encoding

- Created meaningful interaction features (e.g., price per square foot, total rooms   per floor)

- Selected impactful features based on correlation analysis and feature importance

- Scaled numerical features to ensure consistent model input


### 3. Model Development & Tuning
- Implemented XGBRegressor as the primary model
  
- Performed grid search for hyperparameter optimization (tuned learning rate, max_depth, n_estimators, etc.)

- Compared performance with baseline models (linear regression, random forest)


# Result
Through systematic feature engineering and hyperparameter tuning, the final XGBoost model achieved a 20% reduction in prediction error (measured by RMSE).

# Technologies Used
- Python (Pandas, NumPy)
- Scikit-learn (preprocessing, model selection, metrics)
- XGBoost
- Matplotlib/Seaborn (visualization)

# Information Page & Dataset
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
