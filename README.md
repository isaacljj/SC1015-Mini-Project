# SC1015-mini-project

## About

This is a Mini-Project for SC1015 (Intro To Data Science and Artificial Intelligence) which uses the datasets from Kaggle to analyse how having stroke can be affected by different predictors and to find a set of predictors that can be used to predict stroke. We did data preparation and cleaning, data visualization and analysis as well as machine learning.

### 1. Data Preparation and Cleaning
- initial data exploration to prepare for cleaning
- extraction, preparation and cleaning of data

### 2. Data Visualisation and Analysis
- visualisation of differences in trends and distribution between stroke and other variables
- exploratory analysis and visualisation of all features over time
- visualisation and analysis of relationships between all metrics against stroke

### 3. Machine Learning
- making use of Naive Bayes to choose the variables that predicts stroke most accurately
- training and evaluation of decision trees and random forest models to predict stroke
- analysis of coefficients and importances of various features in different models

## Contributors

|  Name  |  Area of Focus  |  GitHub Account  |
|  ---  |  ---  | --- |
|  Suki Ng  |  Data Preparation, Data Visualisation, Machine Learning, Presentation, Github Respository  | @Sukingg
|  Issac Lim  |  Data Preparation, Data Cleaning, Data Visualisation, Presentation, Github Respository  |
|  Tay Shu Shuang  |  Data Preparation, Data Visualisation, Machine Learning, Presentation, Github Respository  | @shuangshuu

## Problem Definition
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
We want to use data science and ML to predict the occurrence of stroke for early detection and treatment. According to research, if stroke is detected or diagnosed early, the loss of death and severe damage to brain can be prevented in 85% cases

![Person with stroke](stroke.jpeg)

## Models Used

- Chi-Square Test
- Naive Bayes
- Decision Tree
- Random Forest Regression

## What we learned from this project
- How to make use of Chi-Square Test and Naive Bayes to select variables that can help us predict stroke
- How to use Random Forest Regression to plot a more accurate decision tree to help us predict stroke
- How to use Synthetic Minority Oversampling Technique (SMOTE) to oversample the data of people with stroke so that our dataset will be more balanced.
- How to handle multiple datasets with different formats and standardizing them
- Collaborating using Google Colab notebooks and Github
 
## Conclusion
We noticed that in general, the BMI is above 30 as seen in the box plot and that is abnormal as the average BMI is between 18.5 to 24.9. (box plot description) Thus a large number of the respondents are obese and this may make BMI seem like a negligible factor in predicting stroke, which is what we concluded. In order to overcome this, the data can be obtained from different geographical locations, to ensure that the BMI is more spreaded out. 
We also deduced from our findings that the risk of stroke is increased by the existence of heart disease, hypertension and high glucose levels. Additionally, there is a clear link between age and stroke, and this can be associated with the fact that older people are more susceptible to stroke. There is no clear link between stroke and work type, residence type, gender and smoking status. 
To answer our initial question on which factor is the most important to predict the occurrence of stroke, there is no one clear factor to predict stroke since the correlation between stroke and the other factors is 0.38 or less, which is not very accurate. Hence, the combination of the few factors which have been mentioned above are important factors which have to be considered concurrently when predicting the occurrence of stroke. Below we will be including some recommendations to reduce the risk of stroke based on our findings.

Some recommendations based on our findings:
1) Since age is an irreversible factor, we would recommend older patients to constantly monitor their health and visit doctors for health checkups regularly.
2) People with conditions such as hypertension, heart disease and diabetes should be encouraged to have their doctors monitor them, in order to better prevent stroke. 
3) The general public should be educated on the negative effects of excessive consumption of sugar to prevent high glucose levels.
4) Overweight people should be encouraged to put in efforts to lose some weight such that they are within the healthy bmi range, in order to reduce their chances of having a stroke. 


## Datasets used
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

## References

https://www.kaggle.com/code/neereshkumar/stroke-prediction-data-analysis/notebook#Rare-Labels
https://www.kaggle.com/code/marwanyasser/stroke-prediction
https://www.kaggle.com/code/olukayodeifeoluwapo/stroke-analysis
https://www.kaggle.com/code/monkeyhaha/stroke-prediction-eda-model-selectio
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9017592/

