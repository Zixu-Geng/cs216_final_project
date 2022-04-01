# cs216_final_project
This is CS216 final project 

Data source: Zixu
- data dictionary (indicator, meaning, unit, datatype, range?)
- merge data into one table (which year to use? take average across all in a year? predict?)
- drop na

Exploratory Data Analysis: Islina
- shape, variable, datatype
- distribution: histograms, scatterplot, heatmap

Decide on which variables to use to predict: Xinyu
- 39 variables down to 20 after data cleaning
- ~10? + happiness report?
- do we have enough data for prediction?

Apr 1 meeting with KSM
- if we are trying to predict trend by year:
  - split test-train sets by year e.g. all values in 2016 as testing data, all values in 2010, 2015, etc. as training data
  - if we are missing values of some years, we can use time series analysis to fill in some missing data e.g. use trends across three years as an individual set of values
  - if we are using linear regression: no need for cross-validation (why ?)
  - think aobut how to interpret r^2 and rmse?

Prototype
- loaded and cleaned data, graphs, summary statistics
- answered at least one research question, or have written some code
