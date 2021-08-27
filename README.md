# On_Airbnb_data_analysis

## About the project

This project is part of the Data Scientist nanodegree from udacity, the objetive is to answer 3 questions from data of free choice and making use of descriptive, inferential statistics or machine learning.

The chosen data for the project was airbnb's data available in Kaggle for [Seattle](https://www.kaggle.com/airbnb/seattle/data,"kaggle") and [Boston](https://www.kaggle.com/airbnb/boston/data,"kaggle"). 

## Files

For each city folder you will find three `.csv` files, calendar, listings and reviews.

### calendar.csv
 Contains full one year availability info for all the listings in the city.

### listings.csv
 Contains all the listing details like location, property details, policies details, amenities and review score.

### reviews.csv
 Contains multiple comments for all the listings.

## The analysis

The questions of interest were the following:

### 1. When are the busiest times of each city?

Here we calculate the average availability for month for city and in a time graph we analize how it evolves whitin a year.

For **Seattle** we see a clear decay in availability in the last semester of the year, reaching it's lowest by **December**, Whereas for **Boston**, which has an overall higher availability than Seattle, reaches it's lowest average availability by **February**. 

### 2. Which listing characteristics affect prices the most?

We try different regression methods for later deciding to use the feature_importance_ attribute from a Random Forest Regressor to find the most relevant features for the prediction. 

The most important features for predicting the price are location related features, which might not be very surprising, also the number of bedrooms affects prices the most, was a surprise not seeing very relevant the square footage of the stay.

### 3. What are the most negative comments about?
For this questions we use sentiment analysis, more specific sentiment polarity for ranking the comments for the worst rated listing.

The main complaint in this negative comments, misleading publications, dirty stays and miscommunication with the hosts.

## Airbnb data analysis.ipynb
 Jupyter notebook containing the process for answering the questions of interest.

## Libraries Used

You can find de libraries used for the project in the **requirements.txt** file.

## Acknowledgements

Getting to do many things for the first time in this project was challeging, but the content found in [Chris Albon's Site](https://chrisalbon.com/,"chrisalbon") 
took some of the weight off.

Also was very helpfull the take from Abhishek kumar in [How to create a Readme.md file?](https://medium.com/analytics-vidhya/how-to-create-a-readme-md-file-8fb2e8ce24e3,"medium")

And special thanks to the udacity team! remarkable learning in their [Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025,"udacity")! 
