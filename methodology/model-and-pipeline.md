## Model and Pipeline 

### Model:
  - Random forest regressor excels because of the nonlinearity and irregular patterns in player stats
  - random_state is set to 1 to ensure reproducible results


### Numeric pipeline:
  - Impute missing values with median; robust to skewed player statistics
  - Features standardized to prevent bias towards larger values (e.g. superstar stats)

### Categorical pipeline: 
  - Team abbreviation is the only categorical feature
  - One-hot encoded to convert categories into numeric format