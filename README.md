# Brain Stroke Prediction
This project implements machine learning models to predict the likelihood of stroke occurrence based on various risk factors. It explores techniques for data exploration, pre-processing, model development, and hyperparameter tuning.
![image](https://github.com/sarax0/brain-stroke-prediction/assets/122404545/7378db45-6702-4580-9634-2cec7edc2ff5)

## Exploratory Data Analysis (EDA)
Implements binning for numerical variables.
Performs feature encoding for categorical data.
Visualizes data distributions using kernel density estimation (KDE).
Applies data transformations like MinMaxScaler and log scaling for improved modeling.

## Data Preprocessing ( Data Preparation)
Addresses class imbalance issues to optimize model performance.

## Model Development ( Machine Learning Models)
**Implements and compares various classification models including:**
- Logistic Regression
- Random Forest Classifiers
- Decision Tree Classifiers
- KNeighbors Classifiers
- XGBoost Classifier
- Gaussian Naive Bayes
**Utilizes GridSearchCV for hyperparameter tuning to optimize model performance.**

## Ensemble Learning ( Combining Models for Strength)
Implements Voting Classifier to leverage the strengths of multiple models for a more robust prediction.
## Models' Performance Comparison
| --- | RUS | ROS | SMOT| Original|
| --- | --- |---|---|---|
| Logistic Regression | 75% | 74% | 74% | - |
| KNeighbors Classifiers | 66% | 84% | 78% | - |
| XGBoost Classifier | 75% | 91% | 92% | - |
| ANN |72%|-|88%|`93.9%`|
