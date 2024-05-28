# Ames Housing Price Prediction

## Overview
The goal is to predict the final sales price of residential homes in Ames, Iowa, using a rich dataset with 79 explanatory variables. This project is part of a competition.

## Dataset
The dataset was compiled by Dean De Cock for educational purposes and serves as a modernized alternative to the classic Boston Housing dataset. It comprises 79 variables describing various aspects of residential homes, which influence the final sales prices beyond the simple number of bedrooms or location attributes.

### Files
- `train.csv` - the training set with 79 features plus the target price
- `test.csv` - the testing set where participants make predictions
- `sample_submission.csv` - a sample of the expected submission format

## Evaluation
Predicting the sales price for each house in the test set. The metric for evaluation is the Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted values and the logarithm of the observed sales prices. This approach helps in treating prediction errors of expensive and cheap houses equally.
