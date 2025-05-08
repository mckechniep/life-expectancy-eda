WHO Life Expectancy Analysis

### This project analyzes global life expectancy data using exploratory data analysis (EDA) and machine learning models. The goal is to uncover key factors influencing life expectancy across countries and predict outcomes using regression techniques.

Dataset

[Life Expectancy (WHO) ](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who/data)

* **Source**: World Health Organization (WHO)
  
* **Years**: 2000–2015
  
* **Observations**: 2,900+
  
* **Features**: Health, economic, demographic indicators
  

Requirements

* pandas
  
* numpy
  
* matplotlib
  
* seaborn
  
* scikit-learn
  
* scipy
  

Methodology

* Data cleaning and transformation (log scaling, outlier handling)
  
* Univariate and multivariate analysis
  
* Feature selection (top K)
  
* Model building: Linear, Ridge, Lasso, Random Forest
  
* Evaluation using R², RMSE, MAE
  

Results

Random Forest Regressor gave the best performance with highest R² and lowest error metrics.
