CSE6363: Machine Learning - Final Project

There are 2 notebooks 
1. Classification 
2. Plotting_Graph

Important Instructions for Classification 
-> Run Files in one by one or in batch.

-> Datasets have been given a unique ID.
	Example: Credit Card Clients Data - CP_2

-> Section 4. Code Cell will train all models one by one on all the dataset with a call of classification() method.

-> It will train DEFAULT SKLEARN MODELS - use hs = False along with other parameter.
	Example: classification(X_train, X_test, y_train, y_test, parity, hs = False)
	

-> Extensive Analysis Result can be found in ClassifiationAnalysis.XLS
 
-> For HyperParameter Search - USE hs=True along with other parameters.
	Example: classification(X_train, X_test, y_train, y_test, parity, hs = True)

-> HyperParameter Search option will give best estimators using both GridSearchCV and RandomizedSearchCV for each models.

-> Some Results of the Exhaustive Hyperparameter Search can be found in RP_Data or CP_Data folders under Hyperparameter Search Results for all the datasets.

-> For the Best Result find the parameters we found from the Config.XLS File and follow the instructions in the last cell block.
	Example: ABC(X_train, X_test, y_train, y_test, parity, hs, n_estimators=50, learning_rate=1)
	Values like n_estimators, learning_rate in this case for CP_2 Dataset (Credit Card Clients Data) are taken from Config.XLS


-> In Classifiation, parity handles different evaluation metrics. 

-> For any query, please mail me at harish.pumbhadia@mavs.uta.edu






