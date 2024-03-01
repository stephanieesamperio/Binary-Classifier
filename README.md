# Deep Learning Challenge: Binary Classifier
by: stephanie samperio

Background:

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organization classification

USE_CASE—Use case for funding

ORGANIZATION—Organization type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special considerations for application

ASK_AMT—Funding amount requested

IS_SUCCESSFUL—Was the money used effectively


# Report
Deep Learning Project

Stephanie Samperio

Feb. 29th, 2024

BACKGROUND

This project entailed deep learning project and neural networks to create a binary classifer for a charity dataset to predict whether applicants would be successful if funded by the Alphabet Soup.

PURPOSE & DATA PRE-PROCESSING

The purpose of the analysis was to clean it and remove unnecessary information such as EIN; and the data was split into training and testing datasets. Since the goal was to create a binary classifier, 'IS_SUCCESSFUL' is determined by the value 0 which means no while 1 means yes. 'CLASSIFICATION' was used for binning and was checked to see if it was successful or not which will also get encoded by the dummies module.

COMPILING, TRAINING, AND EVALUATING MODEL

It took 2 layers for my neural network. Layer 1 with 8 while the second one had 5 The amount of layers did not allow me to reach my target model performance, increasing the cut off of my bins such as 'NAME' and adding 21 to layer 1 and 15 to layer 2 I was able to reach my desired accuracy.

RESULTS

I did reach the desired accuracy of 75% even after optimizing. I believe maybe adding another layer would've helped with that; I had an accuracy of 57% and after optimizing my accuracy went up by 18% which was my desired accuracy.
