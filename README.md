# Titanic-Survival-Prediction
This is a Kaggle competition to predict the Titanic survivals.

The attributes are:
-PassengerId: a unique identifier for each passenger

-Survived: that's the target, 0 means the passenger did not survive, while 1 means he/she survived.
-Pclass: passenger class.
-Name, Sex, Age: self-explanatory
-SibSp: how many siblings & spouses of the passenger aboard the Titanic.
-Parch: how many children & parents of the passenger aboard the Titanic.
-Ticket: ticket id
-Fare: price paid (in pounds)
-Cabin: passenger's cabin number
-Embarked: where the passenger embarked the Titanic

We compare 3 machine learning classifiers to get the best result:
-Stochastic Gradient Descent (SGD) Classifier with 71.1% accuracy prediction
-A Grid search with K-Neighbors Classifier with 72.95% accuracy prediction
-Random Forest Classifier with 78.73% accuracy prediction

We generate the test prediction submitted to Kaggle competition. The score is 75.11% accuracy prediction.
