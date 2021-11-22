# Customer Product holding pattern prediction

## Hackathon held by Analytics Vidhya and American Express.
## In this project Customer product holding pattern should be predicted.
## The dataset is containing customer details and their current product holding pattern using which the product holdings for next 6 months have to be predicted.
## This is a multi-class multi-output problem.
## The output variable is converted into sparse matrix so that it can be used for prediction.
## A fine-tuned XGBClassifier is combined with OneVsRestClassifier to tackle this problem.
## Finally map(mean average precision) is used to evaluate the model.
## I finished in top 100 in this Hackathon
