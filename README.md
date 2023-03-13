<div style="color:#483838; padding:0px 10px; border-radius:5px; font-size:18px; text-align:center"><h1 style='margin:10px 5px'>Data Prepration</h1>
</div>
### Motivation
- This repository is going to explain Data Prepration step by step. The First step is finding missing values and then how to replace them using mean, median or a constant. The next step is to scale out data and how to change categorical data into numerical data. All these has been said in order, I hope to be a goof refrence for data prepration.
### Requirements
##### The major libraries used in these projects are :

- 1.numpy
- 2.pandas
- 3.scickitlearn
### Repository structure
- I used a dataset called heart which contains some data about heart diseas and related body parameters.
- :::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
- __01)Missing Value__

       - 01) Kinds of missing values
       - 02)import data and EDA
       - 03)Extarcting missing values
       - 04)Replacing missing values
       
- __02)Misiing Values and scikit-learn__

        - 01)What is scikit-learn
        - 02)import dataset
        - 03)Extarcting missing values
        - 04)Replacing missing valuse using Scikit-Learn.SimpleImputer
- __03)Categorical Values__

        - 01)import data and EDA
        - 02)Data separation
        - 03)apply Label encoder on caregorical data
        - 04)apply one_hot_encoding
- __04)Scaling__

        - 01) Scaling Definitions
        - 02) Normalize
            - a)min_max_normalization
            - b)max_normalization
        - 03)Standardization
        - 04)Binarizer
