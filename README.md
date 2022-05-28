
# Fraud-Detection-using-Decision-Tree-and-Random-Forest-Classifier

Used both Decision Tree and Random Forest classifier to classify Fraudulent and non Fraudulent 
transactions of a Finance company. 
The dataset is highly imbalanced. Used SMOTE technique for 
oversampling . Used imblearn pipeline for applying SMOTE to the training set 
and fitting the classifier. 


##  Performance

Used both feature selected and the whole dataset for training
and testing. 
Both the F1 score and Recall value is better while using all 
of the features. 

#### Feature selected :
For random forest
F1 score = 0.65 and Recall = 0.89 for Fraud class. 

#### Using all of the features:
For random forest 
F1 score = 0.76 and Recall = 0.96 for Fraud class. 

For Decision Tree 
F1 score = 0.62 and Recall = 0.98 for Fraud class. 
