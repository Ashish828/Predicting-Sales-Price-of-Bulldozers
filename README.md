# Predicting Sales Price of Bulldozers

**Description:**
The goal of this project is to predict the sale price of a particular piece of heavy equipment at auction based on it's usage, equipment type, and configuration. The data is sourced from auction result postings and includes information on usage and equipment configurations.

**The key fields are in train.csv are:**
* SalesID: the uniue identifier of the sale.
* MachineID: the unique identifier of a machine. A machine can be sold multiple times.
* saleprice: what the machine sold for at auction (only in train.csv).
* saledate: the date of the sale.

**The data is split into three parts:**
* **Train.csv** is the training set, which contains data through the end of 2011.
* **Valid.csv** is the validation set, which contains data from January 1, 2012 - April 30, 2012. Make predictions on this set.
* **Test.csv**  contains data from May 1, 2012 - November 2012.

*Dataset: https://www.kaggle.com/c/bluebook-for-bulldozers/data*

**Model Used:** RandomForestRegressor
 
# Final Result:

**Model Accuracy:** 87.56%,
**Mean Absolute Error:** 6026.27,
**Root Mean Squared Log Error:** 0.2459
