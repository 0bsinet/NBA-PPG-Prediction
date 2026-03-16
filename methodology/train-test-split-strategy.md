## Data Splitting Strategy
  - This model uses the standard X_train, y_train, X_test, y_test convention
  - A **time-based split** is used on the training set and test set to ensure the model is trained only on past data and evaluates on future data
    - Model is trained on data dating up to 2016
    - Model is evaluated on data from 2017 to 2022 
    - Features with very little feature importance are removed from the feature matrices prior to model training 
 