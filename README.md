We build a model that predicts if a credit card transaction is fraudulent or not. We model the problem as a binary classification problem. A transaction belongs to the positive class (1) if it is a fraud, otherwise it belongs to the negative class (0).

with an access to transactions that occured over a certain period of time. The majority of the transactions are normally legitimate and only a small fraction are non-legitimate. Thus, typically the dataset that is highly unbalanced. This is also the case of the current dataset: only 492 transactions out of 284,807 are fraudulent (the positive class - the frauds - accounts for 0.172% of all transactions).

This is a Kaggle dataset. We can find this "Credit Card Fraud Detection" dataset from the following link: Credit Card Fraud Detection.

To train the model, we use part of the input dataset, while the remaining data is used utilized to assess the quality of the trained model. First, let's import the necessary libraries and download the dataset. 
