# HASS-CONSULTING-COMPANY-REAL-ESTATE-ANALYSIS-AND-PREDICTIONS

## Links to the various tools used 

Dataset - [Source link](http://bit.ly/IndependentProjectWeek7Dataset)

Python Notebook - [Notebook](https://colab.research.google.com/drive/1OQvv2j5OQ9FyrYvx0k3j5FxVzOgxGjIW?usp=sharing)


## Dataset Description

As a Data Scientist, you work for Hass Consulting Company which is a real estate leader with over 25 years of experience. You have been tasked to study the factors that affect housing prices using the given information on real estate properties that was collected over the past few months. Later onwards, create a model that would allow the company to accurately predict the sale of prices upon being provided with the predictor variables. 

Within your deliverable you are expected to:

Define the question, the metric for success, the context, experimental design taken.
Read and explore the given dataset.
Define the appropriateness of the available data to answer the given question.
Find and deal with outliers, anomalies, and missing data within the dataset.
Perform univariate, bivariate and multivariate analysis recording your observations.
Performing regression analysis.
Incorporate categorical independent variables into your models.
Check for multicollinearity
Provide a recommendation based on your analysis. 
Create residual plots for your models, and assess heteroskedasticity using Barlett's test.
Challenge your solution by providing insights on how you can make improvements in model improvement.
While performing your regression analysis, you will be required to perform modeling using the given regression techniques then evaluate their performance. You will be then required to provide your observations and recommendation on the suitability of each of the tested models on their appropriateness of solving the given problem. 

 * Multiple Linear Regression
 * Quantile Regression
 * Ridge Regression
 * Lasso Regression
 * Elastic Net Regression

#### -- Project Status: [Completed]

## Project Intro/Objective

As a Data Scientist, you work for Hass Consulting Company which is a real estate leader with over 25 years of experience. You have been tasked to study the factors that affect housing prices using the given information on real estate properties that was collected over the past few months. Later onwards, create a model that would allow the company to accurately predict the sale of prices upon being provided with the predictor variables. 


### Methods Used
* Descriptive Statistics
* Data Visualization
* Data Analysis
* EDA Analysis
* Machine learning Algorithms
* Kfold cross-validation
* Multicollinearity tests
* Heteroskdasticity tests
* Multiple Linear Regression
 * Quantile Regression
 * Ridge Regression
 * Lasso Regression
 * Elastic Net Regression
   
### Technologies
* Python
* Pandas,Numpy,Gooogle Colab


```python
import pandas as pd # python library that import datasets into a working env and does so much more such as helping in cleaning datasets etc
import numpy as np # offers comprehensive mathematical functions etc
```

 * Data Preprocessing Methods used
    *  Boxplots to get rid of outliers in the data
    *  No null/missing values in the dataset 
    *  No duplicates in the dataset
    *  Concatinating and Merging of columns in the dataset
    *  Dropping of unnecessary columns in the dataset
    *  Creating Dummy variabels
    *  Label  Encoding 
    *  Changing of Date type columns 
    
 * Data Analysis used
      * Univariate Analysis 
          * Frequency Distibutions
          * Bar graphs
          * Descriptive Statistics
              * Standard deviation
              * Mean
              * Variance
              * Skewness
              * Kurtosis
       * Bivariate Analysis
           * line graphs
           * scatterplots
       * Multivariate Analysis 
           * Pair plots
  * Modelling
       * Multicollinearity  tests
           * Using VIF to check for multicollinearity in our dataset
       * Heteroskdestacity tests
            * Residual plots
            * Bartlett's test
       * Machine Learning algorithms
            * Polynomial Regression
            * Logistic Regression
       * K-fold cross validation
       * Grid-search 

   
## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning - involves taking care of missing data, outliers and duplicates before after merging the datasets
- Data Analysis 
- Modelling


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate

## License
[GPL](https://www.gnu.org/licenses/gpl-3.0.en.html)
