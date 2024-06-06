# edx-capstone-CYO-LOL
This repository documents an ML approach to predict the winner of League of Legends matches based on data on the first 10 minutes of each match. 

In this project, we build a machine learning classifier that helps us to predict the winner in an online game called "League of Legends." League of Legends (LoL) is one of the most popular online games in which professional Esports players regularly compete for high monetary prizes. The goal of our analysis is not only to predict the winner but also to understand which features help predict the win and learn about strategies that increase the chances of winning the game. Such insights are valuable for professional players who play the game to win prize money in competitions but can also inform casual players on how to do better. 

The data we use is a sample of almost 10,000 competitive games. The features in our data set are different performance indicators measured after 10 minutes. Therefore, our analysis seeks to reveal what players need to do in the first 10 minutes to increase their chance of winning the game. 

After exploring the data in a short exploratory data analysis, we build different models and compare their performance based on their prediction accuracy and the F1 score they can achieve on a test set not used for training. We will use a simple logistic regression as a based line and among others a naive bayes classifier, a k-nearest-neighbor classifier, a support vector machines, a random forest classifier, an ensemble method, and xgboosting. 

The final outcome reveals that a **xgboost** classifier yields the best accuracy and F1 score. 

The data we use is downloaded from: https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min/data
