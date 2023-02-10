# About

## Summary 
This is my first personal GitHub project, so any feedback would be much appreciated. The files I've included are from a data mining project I worked on in 2018/19. I aimed to compare the performance of Linear Regression and Support Vector /machines using an f-score as my point of comparison. The data I used to train the models with were the 2015-2017 NFL regular season results and the dataset to be predicted was the 2018 NFL regular season results. My target/label was whether the home team won the match or not. For a longer explanation, please see below :)

## File Summary
I ran the Python programs using Jupyter Notebook. eeCode.ipynb is the main file for calculating the f-score - and eeCodeScatterGraph.ipynb creates a scatter graph that visualises the correlations within the attribute of the dataset. Finally, nflData.csv is the dataset used to train the model.

## Experimental Overview
In order to test the accuracy of different methods of data mining, I will be
making use of a dataset based on NFL Play-by-Play data between 2009 and 20185. Using this data I will construct a logistic regression algorithm and a support vector machine that will produce a binary response on the probability of the home team winning (1 being a win and 0 being a loss). When doing this, the training data will only consist of the games from 2015 to 2017. Next, I will use the 2018 regular season data as test data and input it into the model to see the probability of the home team winning; which will also be a binary response. Since the 2018 NFL season results are available the algorithm will compare its predictive results to the actual results as provided by the dataset. By making use of the F1 Score, I will be able to perform a comparative analysis on which algorithm was more accurate in predicting the winners and losers of the 2018 NFL regular season.

The initial step of the procedure was to clean the dataset by opening it with
spreadsheet software. This consisted of removing any null values to ensure the dataset only contained values that could be calculated with and avoid errors when read into the program. Following this, the ‘home_win’ label was created in another column to give the logistic regression and SVM models (classifier programs) a label to predict. F2 and G2 contain the total home score and total away score respectively​.