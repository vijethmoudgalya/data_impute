# Data_impute 
## Data imputation library for pandas data-frame
Data_impute is a data imputation library which imputes the missing data in the data-frame.
# Overview
data_impute performs the following operations on the pandas data-frames

### Imputes contentious missing data 
- Mean Imputation
- Mode Imputation
- Median Imputation
- Random Sample Imputation
- end Of Distribution Imputation

### Imputes categorical missing data
- frequent Category Imputation
- capture NaN with Feature Imputation
- capture NaN with Category Imputation

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


