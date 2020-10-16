# EDA-Titanic-survival-prediction-using-RandomForestClassifier
A project that predicts whether a passenger survived the Titanic accident or not.
# 1. Problem definition:
> using machine learning to create a model that predicts which passengers survived the Titanic shipwreck.
# 2. Data
The data for the project is gotten from the legendary Titanic ML competition on kaggle. check the link https://www.kaggle.com/c/titanic/data .
The data has been split into two group:
* training set (train.csv)
* test set (test.csv)

**Note:** The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

**Data dictionary**


Variable	Definition	Key
survival	Survival	0 = No, 1 = Yes
pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd
sex	Sex	
Age	Age in years	
sibsp	# of siblings / spouses aboard the Titanic	
parch	# of parents / children aboard the Titanic	
ticket	Ticket number	
fare	Passenger fare	
cabin	Cabin number	
embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton

# 3. Evaluation
The goal of this project is to predict if a passenger survived the sinking of the Titanic or not.
For each in the test set, you must predict a 0 or 1 value for the variable.

**Metric**
Your score is the percentage of passengers you correctly predict. This is known as ***accuracy.***

# 4. Features
This project is centered on using the given dependent variables on the data set say `X` to predict the independent variable (target variable) say `y`.

# 5. Modelling
For the purpose of this project since it is a classification problem that tells if a pessenger survives the shipwerk or not. Will be using a RandomForest Classifier from our trusted `ensemble` method from sklearn library.

# 6. Experimentation
Finally, we will carry out hyper parameter tuning on the RandomForest classifier to improve the accuracy score of the model.
