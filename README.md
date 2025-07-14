# BaceClassification
Beta secretase Classification

1. Required libraries:
    - deepchem
    - sklearn
    - rdkit
    - lightgbm
    - xgboost
    - numpy
    - seaborn
    - matplotlib
    - pandas
    - tensorflow

2. Trained models:
    - Logistic Regression
    - SVC
    - Random Forest Classification
    - LGBM Classifier
    - XGB Classifier
    - Neural network
    - GraphConvModel


3. Best Model:
    LGBMClassifier(boosting_type='gbdt',n_jobs=-1, verbose=-1,
                   n_estimators=100, learning_rate=0.1,
                   num_leaves=32, reg_alpha=0, reg_lambda=0.1)
   
5. Test score on best model:
    Best model's roc-auc on test set: 0.9174614184151205


6. Project potential extension:
    - Test other featurizers
    - Printing validation loss for Graph

    
