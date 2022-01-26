This project applies a Random Forest model to classify fraudulent transactions.
We used an anonymized and normalized dataset provided from Kaggle: https://www.kaggle.com/mlg-ulb/creditcardfraud 

Dealing with unbalanced data (fraud classification accounts for only 0.172% of transactions) has been a challenge and we considered different 
sampling methods to counter act it. We also use Area Under the Precision-Recall Curve (AUPRC) as an evaluation metric and trying to maximize the recall as we try to be aggressive in capturing each fraudulent transaction.
