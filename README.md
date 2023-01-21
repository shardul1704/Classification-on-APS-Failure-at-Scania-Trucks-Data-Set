# Classification-on-APS-Failure-at-Scania-Trucks-Data-Set
Machine Learning project using Random Forests, XGBoost, SMOTE on the APS Failure at Scania Trucks Data Set


Contributor - Shardul Nazirkar

Data Set source - https://archive.ics.uci.edu/ml/datasets/APS+Failure+at+Scania+Trucks

The dataset consists of data collected from heavy Scania
trucks in everyday usage. The system in focus is the
Air Pressure system (APS) which generates pressurised
air that are utilized in various functions in a truck,
such as braking and gear changes. The datasets'
positive class consists of component failures
for a specific component of the APS system.
The negative class consists of trucks with failures
for components not related to the APS. The data consists
of a subset of all available data, selected by experts.

The training set contains 60000 examples in total in which
59000 belong to the negative class and 1000 positive class.
The test set contains 16000 examples.

Jupyter notebook is present in the Code directory and the data set is present in the Data directory.

Jupyter Notebook Contents:

1.(a) Loading the Data Set


1.(b) Data Preparation

  i.   Data imputation to deal with missing values
  
  ii.  Coefficient of variation of each feature
  
  iii. Correlation matrix
  
  iv.  Scatter plots and box plots of features with high Coefficient of variation
  
  v.   Checking data imbalance
  
  
1.(c) Random Forests model, Out-of-bag error estimate


1.(d) Random Forests model with balanced classes


1.(e) XGBoost using L-1 Logistic regression with imbalanced classes, 5-fold cross validation


1.(f) Data preprocessing using SMOTE, XGBoost using L-1 Logistic regression with balanced classes


-----------------------------THANK YOU-----------------------------
