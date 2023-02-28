# Credit-Card-Fraud-Detection

- This is a classification problem with highly unbalanced dataset. 
- The dataset contains 492 fraud transactions out of total 284,807 transactions.
- The positive class (fraud transactions) account for only 0.172% of all the transactions.
- The dataset includes 30 features.

### Key learning from this project
- Area Under the Precision-Recall Curve (AUPRC) should be used instead of the ROC curve for model selection.
    - The False Positive Rate (False Positives/Total Real Negatives) does not drop drastically when the Total Real Negatives is huge.
    - Precision (True Positives/(True Positives+False Positives)) is highly sensitive to False Positives and is not impacted by a large total real negative denominator.

Link to the dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
