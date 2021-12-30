
# Motivation

Assuming a model is just a bunch of rules to predict an outcome, I built some models to see if there are any patterns in the thousands of variables collected in the census. ML models are particularly useful over optimization when the rules that determine the outcome aren't quite clear.

# summary

A Gradient Boosting Machines (GBM) model was built for each of the "no internet" and "no computer" outcomes. All variables relating to having/not having internet and computers was removed to avoid outcome leakage. We are essentially predicting whether a group block has a high rate (one SD above the median) of either no internet or computer access. Five fold cross validation was used with a sixth fold reserved for evaluating performance. Performance for both models was in the mid to high 90s.

# Data/models location
https://www.dropbox.com/sh/n6fryd8j62b0a0w/AADeu1OAcJu3H2eIwg4UzNHda?dl=0

## Contains

* models
* figures
* variable importance
* raw and transformed datasets
