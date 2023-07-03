# Bulldozer_Prices_Prediction
Predicting the Auction Price of Bulldozers using Machine Learning¶ This project looks into various Python based machine learning and data science libraries in an attempt to build a machine learning model which is capable of predicting the auction sale price for a piece of heavy equipment
Predicting the Auction Price of Bulldozers using Machine Learning
This project looks into various Python based machine learning and data science libraries in an attempt to build a machine learning model which is capable of predicting the auction sale price for a piece of heavy equipment

Problem Definition
Predict the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozer The goal of the contest is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration. The data is sourced from auction result postings and includes information on usage and equipment configurations.

Data:
The data is downloaded from the Kaggle : Blue Book for Bulldozer Competition.

The data for this competition is split into three parts:

Train.csv: is the training set, which contains data through the end of 2011.
Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.
Evaluation:
The evaluation Metric for the competition is the RMSLE : Root Mean Squared Log Error between the actual and the predicted auction prices. To minimise this RMSLE error is the aim of this project

Features:
The key fields are in train.csv are:

SalesID: the uniue identifier of the sale
MachineID: the unique identifier of a machine. A machine can be sold multiple times
saleprice: what the machine sold for at auction (only provided in train.csv)
saledate: the date of the sale
Data Dictionary given by kagle gives us the list 53 different which can be found here: https://docs.google.com/spreadsheets/d/11Y32g_OIVqnj5U5Rn6hkro3juiK_LKWQWjjBChgXtMA/edit?usp=sharing
