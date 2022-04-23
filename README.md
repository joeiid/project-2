# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2 - Ames Housing Data and Kaggle Challenge

## Problem Statement 
---

The problem statement was to help inverstors to help generate a profit on their homes by analysing the characters of their homes and relating them to homes near by.

## Background
--- 

The model and project are going to analyze the data and determine the Mean Squared Error (MSE). The way we determained this by analyzing the null score using the sale price values and running againts our test score that we used to run models like lasso and ridge. The project will show a proper test when the model created is lowe than the null.

## Datasets
---

1. train.csv
    This dataset contained features of propeties that are in Ames, Iowa.
2. test.csv
    This dataset also cotains the same features as the train data set but was only used in the final step to determine the accuracy score.

## Data Dictionary
---

|Feature|Type|Dataset|                                 
|---|---|---|
|**ID**|*int*|train|
|**PID**|*int*|train|
|**MS Subclass**|*int*|train| 
|**MS Zoning**|*obj*|train| 
|**Lot Frontage**|*float*|train| 
|**Lot Area**|*int*|train| 
|**Street**|*obj*|train|
|**Alley**|*obj*|train|
|**Lot Shape**|*obj*|train| 
|**Land Contour**|*obj*|train| 
|**Utilies**|*obj*|train| 
|**Lot Config**|*obj*|train| 
|**Land Slopes**|*obj*|train|
|**Neighborhood**|*obj*|train|
|**Condition 1**|*obj*|train| 
|**Condition 2**|*obj*|train| 
|**Bldg Type**|*obj*|train| 
|**House Style**|*obj*|train|
|**Overall Qual**|*int*|train|
|**Overall Cond**|*int*|train|
|**Year Built**|*int*|train| 
|**Year Remod/Add**|*int*|train| 
|**Roof Style**|*obj*|train| 
|**Roof Matl**|*obj*|train| 
|**Exterior 1st**|*obj*|train|
|**Exterior 2nd**|*obj*|train|
|**Mas Vnr Type**|*obj*|train| 
|**Mas Vnr Area**|*float*|train| 
|**Exter Qual**|*obj*|train| 
|**Exter Cond**|*obj*|train| 
|**Foundation**|*obj*|train|
|**Bsmt Qual**|*obj*|train|
|**Bsmt Cond**|*obj*|train| 
|**Bsmt Exposure**|*obj*|train| 
|**BsmtFin Type 1**|*obj*|train| 
|**BsmtFin SF 1**|*float*|train| 
|**BsmtFin Type 2**|*obj*|train|
|**BsmtFin SF 2**|*float*|train|
|**Bsmt Unf SF**|*float*|train| 
|**Total Bsmt SF**|*float*|train| 
|**Heating**|*obj*|train| 
|**Heating QC**|*obj*|train| 
|**Central Air**|*obj*|train|
|**Electrical**|*obj*|train|
|**1st Flr SF**|*int*|train| 
|**2nd Flr SF**|*obj*|train| 
|**Low Qual Fin SF**|*float*|train| 
|**Gr Liv Area**|*int*|train| 
|**Bsmt Full Bath**|*int*|train|
|**Bsmt Half Bath**|*int*|train|
|**Full Bath**|*int*|train| 
|**Half Bath**|*obj*|train| 
|**Bedroom AbvGr**|*float*|train| 
|**Kitchen AbvGr**|*int*|train|
|**Kitchen Qual**|*int*|train|
|**TotRms AbvGrd**|*int*|train|
|**Functional**|*int*|train| 
|**Fireplaces**|*obj*|train| 
|**Fireplaces Qu**|*float*|train| 
|**Garage Type**|*int*|train| 
|**Garage Yr Blt**|*obj*|train|
|**Garage Finish**|*int*|train|
|**Garage Cars**|*int*|train| 
|**Garage Area**|*obj*|train| 
|**Garage Qual**|*float*|train| 
|**Garage Cond**|*int*|train| 
|**Pave Drive**|*int*|train|
|**Wood Deck SF**|*int*|train|
|**Open Porch SF**|*int*|train| 
|**Enclosed Porch**|*obj*|train| 
|**3Ssn Porch**|*float*|train| 
|**Screen Porch**|*int*|train| 
|**Pool Area**|*obj*|train| 
|**Pool QC**|*float*|train| 
|**Fence**|*int*|train| 
|**Misc Feature**|*int*|train|
|**Misc Val**|*int*|train|
|**Mo Sold**|*int*|train| 
|**Yr Sold**|*obj*|train| 
|**Sale Type**|*float*|train| 
|**SalePrice**|*int*|train| 

## Conclusion
---

With this project we were able to predict the housing prices by analysing the dataset given to us. We were able to deterrming the values in the dateset that were important to determain the best model.
This model was made to help determain the best profit for real estate investment in Ames, Iowa. The model has a 86% variance with the data and the MSE was 21916. This means that our model had an error of $21916 when trying to determine the price of a home. This means that their model has a high error rate and could use more data or outside research when trying to determine an accurate price.


