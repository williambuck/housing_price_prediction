# [Predicting House Price with Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

The goal of this project is to use EDA, visualization, data cleaning, preprocesing, and linear models to predict home prices given the features of the home, and interpret these linear models to find out what features add value to a home.


## Dataset

From the Kaggle competition website:

"Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home."
    

## Project Details:

Included in this repository:
1. **housing_price_prediction.ipynb** - This shows the full process for analyzing the housing data.
1. **train.csv** - This is the data file from Kaggle
1. **data_description.txt** - Full description of all the housing features.


## Results:

After carefully cleaning the data, I was able to show that the most important features for sales price are:

**Top three value increasers:**
    * Neighborhhood_NridgHt
    * Neighborhood_NoRidge
    * Exterior1st_BrkFace
    
**Top three value reducers:**
    * Condition2_PosN
    * Neighborhood_Edwards
    * BdgType_Twnhs