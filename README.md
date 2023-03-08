# Homogeneous-ensemble
A Random forest operation using homogenous ensemble 
focuses on two dataset; churn_modelling.csv and Insurance.csv 
Varius libraries are uploaded inclusive of pandas, RandomForestClassifier, and numpy
Dataset is first loaded and checked for missing values; in this case, no missing values are identified for both datasets. 
Dataset is the preprocesssed by removing unwanted columns, in this case CustomerId in churn and children in insurance, because it plays no significant role in the analysis of the data. 
Data is the split in to test and training sets under the 0.2 test fraction 
A homogenous ensemble random forest classifier is created by creating a base classifier; rf = RandomForestClassifier(n_estimators=100)  
The models are put under prediction using the test set and checked for accuracy, precision, recall, and f1 score 
Higher accuracy value indicate the model works efficiently on the dataset while lower accuracy indicates poor ensemble on the dataset. 
With churn model, the varous results came out high, meaning a good ensemble was achieved while insurance produced aerage values.
