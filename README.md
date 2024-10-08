# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## Adjustments from the previous script to acclimatize to new python version

- Added a fetch_housing_data function call to fetch the data. This was not present in the previous version.Line 29
- Corrected the instantiation of the loading function. Line 32
- Corrected the subsetting of the loc. Line 52 to Line 54
- Added correct usage of the corr method. Line 83
- Adjusting any missing columns in the test / train. Line 198 to 209

## To excute the script
- conda env create -f env.yml
- conda activate mle-dev
- python nonstandardcode.py
