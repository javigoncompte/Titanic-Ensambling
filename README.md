
# Titanic Ensambling

predict survivors. Basic Data exploratory done.
Correlation heatmap done on features to understand how each feature behaves with each other.

# Basic Gist of project model used results
Basic Titanic Ensambling Model Used in the Kaggle competition to predict Survivors in the Titanic
Were a pipeline was created to clean the dataset and created features to pass through a 3 models which was later implemented into another model
The three models were RandomForest, SVC, Logistic Regression
Then these models applied their statistical algorithms to present predictions on the survival of passengers
which later a GradientBoostingClassifier used the predictions of the model and predicted based on the stacked models
Gave a score of 79% 
