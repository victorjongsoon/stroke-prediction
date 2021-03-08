# Stroke Prediction
This project explores binary classification algorithms such as **support vector classifier and random forest classifier.** The objective of this project is to identify patients with a stroke.

# Dataset
The dataset is downlaoded from Kaggle (https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

# Approach
The dataset will be process before it is used for training. The null values in the dataset will be fill with the **mean values.** **One-hot encoding** will be used to encode the dataset so that the dataset is "readable" by the machine. This processed dataset will then be split into training and testing for evaluation. After the training process, I choose the best performing algorithm for hyperparameter tuning using GridSearchCV. This is to find the best parameters for the algorithm so that we can have the highest accuracy model.

# Best Model
Model Name | Testing Accuracy
------------ | -------------
Support Vector Classifier | 95.40%
**Random Forest Classifier** | **95.60%**


