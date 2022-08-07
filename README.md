# Credit-Card-Fraud-Detection

## Data

"The dataset contains transactions made by credit cards in September 2013 by European cardholders. We have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions."

The data is a Kaggle dataset. You can get it from [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
> **Random Under-Sampling was used to handle the unbalanced data.**

## Algorithms Used & Models Evaluation 

The first model, I used the k-Neighbors classifier algorithm and got an accuracy of around 62%.

The second model, I applied the Min Max scaler to the data and used the SVC algorithm. This model has 91% accuracy and 89% recall.
