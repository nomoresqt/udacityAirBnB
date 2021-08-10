# SEATTLE AIR BNB DATA ANALYSIS


## Project Motivation 

This blog post is the first project of Udacity Data Scientists Nanodegree Program. 

In this project, I used Seattle Air BNB open data set, the dataset was downloaded via link https://www.kaggle.com/airbnb/seattle/data

In case you are interested in AirBnB data of other popular cities around the world, go to the following page 

http://insideairbnb.com/index.html


This project follows the guide line of CRISP-DM (Cross-industry standard process for data mining). The details of this process can be found via this Wikipedia link: https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining


[My blog post is HERE](https://lululastudio.com/data)


## Python Libraris that I used in this analysis

* numpy 
* pandas
* sklearn
* seaborn
* xgboost
* math


## Description of this repository

* Three datasets: Listing, Review and Calendar 
* one notebook file that contians all the python code
* Saved Plots and files 


## In this project, I mainly want to investigate the following questions:

##### 1. Does the location of the Air BNB listings have impact on the price of the listing?  Which neighborhood has the highest average price?

  Answer: Yes. The listing price is influenced by the location. The Top 10 neighbourhood with the highest average price are:
 -Southeast Magnolia: 231.71
 - Portage Bay: 227.86
 - Westlake: 194.47
 - West Queen Anne: 187.77
 - Montlake: 182.789474
 - Briarcliff: 176.571429
 - Sunset Hill: 176.055556
 - Industrial District :173.333333
 - Alki: 171.62 

##### 2. Is there any seasonal fluctuation of listing prices? For example, the summer months and high seasons such as end of year around Christmas and new year.

   Answer: Yes, the listing prices are higher during summer vacation season.

##### 3. What are the factors/features that significantly influence the price of the listings?

   Answer: Yes!  As we can see from the Correlation matrix and feature impertinence, number of bedrooms, accommodates and number of bathrooms are good predictor of the listing price
