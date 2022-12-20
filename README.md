# Card-Fraud-Detect
To recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.


Dataset was taken from kaggle.
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original 
features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been 
transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 
'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 
in case of fraud and 0 otherwise.
