## Assessment of predictions

### Yearly error function details
  - test_set parameter is for any made test set that will be used as a benchmark
  - pred_df parameter is for a dataframe that holds model predictions
  - prediction_years parameter is for an array that holds the years the model will predict
  - RMSE metric is used to evaluate how far off predictions were
  - RMSE evaluates to {2017: 1.1683941526346235, 2018: 3.378358986544249, 2019: 4.397192277063395, 2020: 4.622316574843429, 2021: 5.487476775038701}

### Limitations of program
  - Errors compound yearly
  - Predictions are limited to players who were active during the 2015-2016 season
  - There are many cases where first-year and second-year predictions are greatly off because due to erratic behavior of injuries that were not a feature