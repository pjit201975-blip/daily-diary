# AI & Machine Learning Training

## Day 15
*Date:* 20 July 2026

### Topics Covered
- Linear Regression
- Ridge Regression
- Lasso Regression
- Regularization Techniques
- Model Evaluation
- R² Score
- Mean Squared Error (MSE)
- Model Comparison

### Summary

On this day, I learned about different regression algorithms and regularization techniques used in machine learning. I understood that **Linear Regression** is used to predict continuous numerical values by finding the relationship between input features and the target variable. I also learned that **Ridge Regression** and **Lasso Regression** are improved versions of Linear Regression that use regularization to reduce overfitting and improve the model's ability to generalize to new data.

I studied the concept of **regularization**, where a penalty is added to the model to prevent it from becoming too complex. Ridge Regression uses **L2 regularization**, which reduces the magnitude of feature coefficients, while Lasso Regression uses **L1 regularization**, which can reduce some coefficients to zero and automatically perform feature selection.

I also learned how to evaluate regression models using **R² Score** and **Mean Squared Error (MSE)**. The **R² Score** measures how well the model explains the variation in the target variable, whereas **MSE** measures the average squared difference between the predicted and actual values. Finally, I learned how to compare different regression models using these evaluation metrics to identify the most suitable model for a given dataset.

### Key Learning
- Understanding Linear, Ridge, and Lasso Regression.
- Learning the difference between L1 and L2 regularization.
- Reducing overfitting using regularization techniques.
- Performing feature selection with Lasso Regression.
- Evaluating regression models using R² Score and MSE.
- Comparing the performance of different regression algorithms.


## Day 16
*Date:* 21 July 2026

### Topics Covered
- Feature Selection
- Variance Threshold
- Correlation-based Feature Selection
- Chi-Square Test
- ANOVA (F-Test)
- Mutual Information
- Recursive Feature Elimination (RFE)
- Feature Importance

### **Feature Selection**

Feature Selection is the process of selecting the most relevant features from a dataset while removing less important ones. It helps reduce model complexity, improves prediction accuracy, and decreases training time. In my **Student Lifestyle and Stress Prediction** project, feature selection was used to identify the lifestyle factors that have the greatest impact on predicting students' stress levels.

### **Variance Threshold**

Variance Threshold is a filter-based feature selection technique that removes features with very low variance because they provide little or no useful information for prediction. It is a simple preprocessing method used before model training. In my project, it can help eliminate features that remain almost constant across all student records.

### **Correlation-based Feature Selection**

Correlation-based Feature Selection identifies features that have a strong relationship with the target variable while removing weakly related or redundant features. Features with higher correlation are considered more useful for prediction. In my project, this method was used to find the lifestyle factors that are most closely associated with students' stress levels.

### **Chi-Square Test**

The Chi-Square Test is a statistical feature selection method used for categorical data. It measures the dependency between each feature and the target variable, selecting features with higher Chi-Square scores. In my project, it can be applied after encoding categorical features to identify the most relevant variables for stress prediction.

### **ANOVA (F-Test)**

ANOVA (Analysis of Variance) is a statistical method used to determine whether there are significant differences between groups. In feature selection, it evaluates how strongly each numerical feature is related to the target variable using the F-score. In my project, ANOVA can help identify which numerical lifestyle features contribute most to predicting stress levels.

### **Mutual Information**

Mutual Information measures the amount of information a feature provides about the target variable. It can capture both linear and non-linear relationships, making it useful for selecting informative features. In my project, Mutual Information helps identify lifestyle features that have the strongest influence on stress prediction.

### **Recursive Feature Elimination (RFE)**

Recursive Feature Elimination (RFE) is a wrapper-based feature selection technique that repeatedly trains a model and removes the least important feature until the desired number of features remains. It ranks features based on their contribution to the model. In my project, RFE was used to select the most important features for predicting students' stress levels.

### **Feature Importance**

Feature Importance is an embedded feature selection method that measures the contribution of each feature to a machine learning model's predictions. Algorithms such as Random Forest calculate importance scores for all features. In my **Student Lifestyle and Stress Prediction** project, Feature Importance helped identify the top lifestyle factors influencing stress levels, and these features were used to build the final prediction model.


## Day 17
*Date:* 22 July 2026

### Topics Covered
- Wrapper Method
- Validation Test
- Forward Selection
- Backward Selection
- RFECV

### Wrapper Method

The Wrapper Method is a feature selection technique that evaluates different combinations of features by training and testing a machine learning model. It selects the subset of features that gives the best prediction performance. In my Student Lifestyle Stress Prediction project, I used wrapper methods such as Forward Selection, Backward Selection, and RFECV to identify the most relevant features for predicting students' stress levels and to improve the model's efficiency.

### Validation Set (Validation Test)

A validation set is a portion of the dataset used during model development to evaluate and fine-tune the model before testing it on unseen data. It helps in selecting the best model, tuning hyperparameters, and reducing the risk of overfitting. In my Student Lifestyle Stress Prediction project, the validation process helped compare different machine learning models and feature selection techniques to identify the model that performed best before final evaluation.

### Forward Selection

Forward Selection is a wrapper-based feature selection technique that starts with no features and adds one feature at a time based on model performance. At each step, the feature that improves the model the most is selected until the desired number of features is reached. In my **Student Lifestyle Stress Prediction** project, I applied Forward Selection to identify the most important lifestyle-related features for predicting students' stress levels.

### Backward Selection

Backward Selection is a wrapper-based feature selection technique that starts with all available features and removes the least important feature one by one. The process continues until the optimal subset of features remains. In my project, Backward Selection helped eliminate less relevant features while maintaining good prediction performance.

### RFECV (Recursive Feature Elimination with Cross-Validation)

RFECV is an advanced wrapper method that recursively removes the least important features while using cross-validation to determine the optimal number of features automatically. It selects the feature subset that provides the best model performance. In my project, RFECV selected the most suitable features for predicting student stress and helped compare model accuracy before and after feature selection.

### **Key Learning**

* Understood the working of wrapper-based feature selection techniques.
* Applied Forward Selection, Backward Selection, and RFECV on the **Student Lifestyle Stress Prediction** dataset.
* Compared the features selected by different wrapper methods.
* Evaluated model performance before and after feature selection.
* Learned that RFECV automatically determines the optimal number of features using cross-validation.
* Identified the most relevant features to improve the efficiency and performance of the machine learning model.

## Day 18
*Date:* 23 July 2026

### Topics Covered
- Parameters
- Hyperparameters


### **Parameters**

Parameters are the values that a machine learning model learns automatically from the training data during the training process. They define how the model makes predictions and are updated to minimize prediction errors. In my **Student Lifestyle Stress Prediction** project, model parameters were learned from students' lifestyle features to predict their stress levels.

### **Hyperparameters**

Hyperparameters are the settings that are defined before training a machine learning model and control how the model learns from the data. They are not learned automatically and must be chosen or tuned by the user. In my project, hyperparameters such as the number of trees in Random Forest (`n_estimators`) and the number of neighbors in KNN (`n_neighbors`) influenced the model's performance and prediction accuracy.


### **Key Learning**

* Understood the difference between parameters and hyperparameters.
* Learned that parameters are learned automatically during model training.
* Explored how hyperparameters are set before training and affect model performance.
* Recognized the importance of selecting appropriate hyperparameters to improve prediction accuracy in the **Student Lifestyle Stress Prediction** project.

