# Ted-Talk-Views-Prediction

## Regression Model for Predicting Ted Talk Views

![1](https://user-images.githubusercontent.com/89520031/172645572-8290b2e4-6cf6-4416-a227-c153aaa86fa1.jpg)

# Summary:

The task was to explore and analyze the data and to build a regression model for Ted Talk Videos Views Prediction.

Challenge was to perform imputation in the ‘occupations’ column as the observations were python dictionary. Did imputation with ‘{0:[]}’ Used the idea of common terms between occupations and topics column to extract the main topics.

Employed some of the most widely used regression algorithms for this project namely;

**1.	Random Forest**

**2.	Ridge**

**3.	SVR**

Final model was Support Vector Regressor selected from Random Forest, Ridge and SVR for predicting ted_talk views, having lowest variance in prediction (0%) and highest r2_score (66%) among all three models . Used RandomizedSearchCV for hyperparameter tuning.
