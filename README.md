# Data_impute - Data imputataion library for pandas dataframes
Data_impute is a data imputataion library which imputes the missing data in the dataframe.
# Overview
data_impute performs the following operations on the pandas dataframes

- imputes contionous missing data
\n a. Mean Imputataion
\n b. Mode Imputataion
\n c. Median Imputation
\n d. RandomSampleImputation
\n e. endOfDistributionImputation

- imputes categorical missing data
-a. frequentCategoryImputation
-b. captureNaNwithFeatureImputation
-c. captureNaNwithCategoryImputation

# Usage
In the following paragraphs, I am going to describe how you can get and use Data Impute for your own projects.

# Getting it
To download Data Impute, either fork this github repo or simply use Pypi via pip.
```sh
$ pip install data_impute
```
# Using it
data_impute was programmed with ease-of-use in mind. First, import null_imputer from data_impute

```sh
from data_impute import null_imputer
```

#Run it
Run the App by calling null_imputer.run() and providing the Data Frame 
```sh
null_imputer.run(<DataFrame Name>)
```


