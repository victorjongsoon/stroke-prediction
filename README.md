# Stroke Prediction
This project explores binary classification algorithms such as **support vector classifier and random forest classifier.** The objective of this project is to identify patients with a stroke.

# Dataset
The dataset is downlaoded from Kaggle (https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

# Approach
The dataset will be process before it is used for training. The null values (bmi) in the dataset will be fill with the **mean values.** **One-hot encoding** will be used to encode the dataset so that the dataset is "readable" by the machine. StandardScaler will be used to remove the mean and scales each variable to unit variance. This processed dataset will then be split into training and testing for evaluation. After the training process, I choose the best performing algorithm for hyperparameter tuning using GridSearchCV. This is to find the best parameters for the algorithm so that we can have the highest accuracy model.

# Best Model (after hyperparameter tuning)
Model Name | Testing Accuracy
------------ | -------------
**Support Vector Classifier** | **95.40%**
Random Forest Classifier | 95.30%

From the result above, we can see that support vector classifier has a **0.01%** higher testing accuracy as compared to random forest classifier. 

# What can be improved in this project?
1. During the hyperparameter tuning process, I could tune more parameters (e.g. SVC kernel - linear, rbf, poly, sigmoid etc.)
2. I could try different binary classification algorithms such as naive bayes, nearest neighbor, neural networks etc.

# Skillset required for the project (Machine Learning)
* Python (Numpy, Pandas etc.)
* Data Structures and Data Modeling
* Machine learning algorithms (e.g. Support Vector Machine, Random Forest, Linear Regression, Logistic Regression, k- Nearest Neighbors, Decision Tree etc.)

