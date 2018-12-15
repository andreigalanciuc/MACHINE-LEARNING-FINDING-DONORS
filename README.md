# MACHINE-LEARNING-FINDING-DONORS


## SOFTWARE REQUIREMENTS
Python
NumPy
pandas
scikit-learn (v0.17)
Matplotlib

## PROJECT MOTIVATION
CharityML is a fictitious charity organization located in the heart of Silicon Valley that was established to provide financial support for people eager to learn machine learning. In this project, I build and evaluate several supervised learning models that will identify potential donors to the charity.

## RESULTS
I tested 3 different learners: *Support Vector Classifier*, *AdaBoostClassifier*, *RandomForestClassifier*.
I chose the AdaboostClassifier because the F score on the testing data set is the highest for Adaboost. Besides that, there is not a big difference in F-scores between the training and testing sets like with RandomForest. This matters because we do not want our model to overfit on the training set and return us an inflated F score. The accuracy score and F score are highest for Adaboost at all training set sizes. The training and testing times are very low, which means that the model is computationally fast. The iterative aspect of the model makes it handle well a high number of attributes like in our case. Its accuracy score was 0.8651 and its F-score was 0.7396.
