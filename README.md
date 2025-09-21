# Ad-Click-Prediction-Using-Machine-Learning
Ad Click Prediction Using Machine Learning A machine learning project to predict whether a user will click on an online advertisement. This project explores advertising data, performs exploratory data analysis (EDA), and builds a Logistic Regression model to predict ad click-through rates (CTR) based on user behavior and demographics.

Project Overview

The online advertisement industry has become a multi-billion-dollar sector, and predicting ad click-through rates (CTR) is central to maximizing revenue for advertisers and search engines.

In this project, we predict whether a user will click on an advertisement using machine learning techniques. We will focus on search ads, which are displayed when a user searches for a specific keyword, and apply Logistic Regression to predict ad clicks based on user features.

Predicting CTR helps search engines decide which ads to display, considering both the probability of a click and the advertiser's bid amount.

Problem Statement

This project uses advertising data from a marketing agency to develop a machine learning algorithm that predicts whether a particular user will click on an advertisement.

The dataset contains 10 variables:

Feature	Description
Daily Time Spent on Site	Consumer time on-site in minutes
Age	Customer age in years
Area Income	Average income of the consumer's geographical area
Daily Internet Usage	Average minutes a day consumer is on the internet
Ad Topic Line	Headline of the advertisement
City	City of consumer
Male	Whether the consumer is male (1) or female (0)
Country	Country of consumer
Timestamp	Time at which the consumer clicked on the ad or closed the window
Clicked on Ad	Target variable: 0 (not clicked) or 1 (clicked)

Objective: Use the other 9 variables to accurately predict whether a user clicks on an advertisement.

Relevance

CTR prediction is critical because:

Revenue for search engines like Google comes primarily from ads.

Advertisers pay only when users click on their ads (Pay Per Click).

Predicting CTR allows search engines to maximize revenue by displaying ads with high click probability multiplied by bid amount.

Example: If a user is highly likely to click on an ad with a high bid, that ad is prioritized.

Exploratory Data Analysis (EDA)

Analyze how Daily Time Spent on Site affects the likelihood of clicking an ad.

Explore the effect of Ad Topic Line on user behavior.

Understand demographic influence like Age, Gender, City, and Country.

Identify trends and patterns that inform the machine learning model.

Machine Learning Approach

We use Logistic Regression to:

Predict whether a user clicks on an ad (binary classification).

Calculate probabilities of clicks for each user.

Allow search engines to rank ads based on probability × bid amount.

Steps:

Load and clean the dataset.

Perform exploratory data analysis.

Encode categorical variables as needed.

Split data into training and test sets.

Train a Logistic Regression model.

Evaluate performance using accuracy, confusion matrix, and ROC-AUC.

Use model probabilities to predict ad clicks.
