# SC1015-mini-project

## About

This is a Mini-Project for SC1015 (Intro To Data Science and Artificial Intelligence) which uses the datasets from Kaggle to analyse how having stroke can be affected by different predictors and to find a set of predictors that can be used to predict stroke. We did data preparation and cleaning, data visualization and analysis as well as machine learning.

### 1. Data Preparation and Cleaning
- initial data exploration to prepare for cleaning
- extraction, preparation and cleaning of data

### 2. Data Visualisation and Analysis
- visualisation of differences in trends and distribution between LE and HALE
- exploratory analysis and visualisation of all features over time
- visualisation and analysis of relationships between all metrics against HALE

### 3. Machine Learning
- training and evaluation of linear regression, regression tree and random forest models to predict HALE and LE
- analysis of coefficients and importances of various features in different models

## Contributors
Name	Area of Focus	GitHub Acount
Leong Kit Ye	Data Preparation, Data Cleaning, Data Visualisation, Machine Learning, Presentation, Github Repository	@Sherylleong
Khant Zayar	Data Preparation, Data Visualisation, Machine Learning, Github Repository	@KZY201101
Bruce Li Luyun	Data Preparation, Data Cleaning, Data Visualisation, Presentation	@BruceLee7

## Problem Definition

Can we predict the Life Expectancy (LE) and Health-Adjusted Life Expectancy (HALE) of a country based on other data such as its population, GDP etc?
Which set of data are the most useful in predicting the HALE and Life Expectancy?
Which model would provide the most accurate results?

## Models Used

Multivariate Linear Regression
Regression Trees
Random Forest Regression

## What we learned from this project

Handling multiple datasets with different formats and standardizing them
Merging multiple dataframes into a single dataframe with a convenient format for analysis
Linear Regression from sklearn.linear_model
Regression Trees from sklearn.tree
Random Forest Regression from sklearn.ensemble
Collaborating using Google Colab notebooks and Github
Concept about feature importances

## Conclusion

The random forest model was the best at predicting life expectancy and HALE out of all the 3 models. It seems that both life expectancy and HALE had slightly nonlinear relationships with the data, but a sufficiently robust model such as random forest is able to capture these relationships. It seems that overall, the metrics chosen were able to btter predict life expectancy than HALE, but they can still predict HALE with high accuracy.

Both access to basic sanitation services and GDP per capita are the most important metrics across all the models, as well as having positive correlations with HALE. However, we must also keep in mind that correlation does not imply causation. For example, population density had a positive correlation with HALE, but logically a high population density would put a strain on current healthcare services. Instead, this could be explained by areas with high population densities also tending to be centres of economic activity, with richer citizens.

It can also be seen that current health expenditure brings significant benefits to HALE, but domestic private health expenditure has negligible impact on HALE, implying that government expenditure in the healthcare sector is what causes HALE to rise. Furthermore, age dependency ratio has more influence than CO2 emissions on life expectancy, but they have equal influence on HALE.

Given limited resources, our model can inform which areas countries can shift their limited resources in order to increase HALE to ensure everyone lives long, healthy lives.

## Datasets used


## References

https://neptune.ai/blog/random-forest-regression-when-does-it-fail-and-why
https://towardsdatascience.com/random-forest-regression-5f605132d19d
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
https://en.wikipedia.org/wiki/Random_forest
https://www.analyticsvidhya.com/blog/2020/05/decision-tree-vs-random-forest-algorithm/
https://www.keboola.com/blog/random-forest-regression
https://levelup.gitconnected.com/random-forest-regression-209c0f354c84
https://builtin.com/data-science/regression-tree
https://medium.com/analytics-vidhya/regression-trees-decision-tree-for-regression-machine-learning-e4d7525d8047
https://towardsdatascience.com/comparative-study-on-classic-machine-learning-algorithms-24f9ff6ab222#:~:text=When%20there%20are%20large%20number,are%20better%20than%20linear%20regression
https://ourworldindata.org/life-expectancy#:~:text=The%20United%20Nations%20estimate%20a,life%20expectancy%20of%2072.3%20years
https://www.who.int/data/gho/indicator-metadata-registry/imr-details/66
