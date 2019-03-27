# Naive-Beyesian-Classifier-implementation
Implementation of  Naive Bayesian from scratch.
Data set used is - Census income or adult dataset available at http://archive.ics.uci.edu/ml/datasets/Adult
The missing values are handled in 2 ways : 1. Replacing it with mode of the attribute
                                           2. Ignoring records with missing values 
                                           
Continuous attributes are handled in 2 ways: 1. Transform the attribute into categorical using equal-width binning method
                                             2. Assume the attribute follows Gaussian Distribution 
                                             
                                             
Implemented the K-fold cross validation.
Evaluation strategies:
1. Accuracy
2. Precision
3. Recall
4. F1-score
5. Matthew's Co-relation Coefficient
 
