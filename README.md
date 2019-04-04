# feature-selection
Description: Using Scikit and mlxtend, we test different ML algorithms and see how they behave when trying with them several feature selection techniques.

Dataset must be unzipped prior to running the code.

In this Python 3 Jupyter notebook, we compare several ML algorithms: KNN, Decision Tree, Random Forest, Gradient Boosting and Catboost. Their hyper-parameter are optimized using Bayesian Optimization, Grid Search and Random Search. 

Later, we perform attribute selection using the SelectKBest and Pipeline functions from Scikit, SFS from mlxtend, selecting the features by hand and using the Rando Forest Predictor Importance. 

Libraries: 
 + matplotlib v 3.0.2
 + numpy v 1.15.4
 + pandas v 0.24.1
 + scikit-learn v 0.20.2
 + scikit-optimize v 0.5.2
 + mlxtend v 0.14.0
 + kneed v 0.1.1
