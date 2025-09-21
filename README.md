Ad Click Prediction Using Machine Learning
Project Overview

The online advertisement industry is a multi-billion-dollar sector, and predicting ad click-through rates (CTR) is central to maximizing revenue for advertisers and search engines.

In this project, we predict whether a user will click on an advertisement using machine learning. We focus on search ads (displayed when a user searches for a keyword) and apply Logistic Regression to predict ad clicks based on user behavior and demographics.

Predicting CTR helps search engines decide which ads to display based on both:

Probability of a click

Advertiser's bid amount

Problem Statement

We use advertising data from a marketing agency to develop a model that predicts whether a particular user will click on an advertisement.

The dataset contains 10 features:

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

Objective: Predict the Clicked on Ad variable using the other 9 features.

Relevance of CTR Prediction

Revenue for search engines like Google primarily comes from ads.

Advertisers pay only when users click on their ads (Pay Per Click).

Predicting CTR allows search engines to maximize revenue by ranking ads based on probability × bid amount.

Example: A high-probability click on a high-bid ad is prioritized.

Exploratory Data Analysis (EDA)

We explore the data to identify patterns and trends:

How Daily Time Spent on Site affects ad clicks.

The influence of Ad Topic Line on user behavior.

Demographic effects: Age, Gender, City, Country.

Patterns that inform the machine learning model.

Machine Learning Approach

We use Logistic Regression to:

Predict ad clicks (binary classification).

Calculate click probabilities for each user.

Rank ads for search engines using probability × bid.

Workflow:

Load and clean the dataset.

Perform exploratory data analysis (EDA).

Encode categorical variables as needed.

Split data into training and test sets.

Train Logistic Regression model.

Evaluate performance using accuracy, confusion matrix, ROC-AUC.

Use model probabilities to predict ad clicks.
