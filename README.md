#Provider Fraud Detection in the Healthcare Domain

The goal of this project is to “predict the potentially fraudulent providers” based on the claims filed by them.

#Source of Data
The dataset for this problem statement is taken from Kaggle. Follow the link to download the dataset.

#Mapping to machine learning problem
This is a two-class classification problem with data imbalance. We need to classify providers as frauds and genuine.
#Business constraints:-
No strict latency constraints.
2. Prediction of fraud should be correct, no fraud should be predicted as genuine

#Performance Metrics:-
One of the important things to keep in mind when dealing with imbalanced datasets is performance metrics. If we used metrics that are not robust against the imbalance of data then we can come to outcomes that are not true.
Precision/Specificity: Precision for positive class means how many points that are predicted positive actually belongs to the positive class, same for the negative class
Recall/Sensitivity: Recall for positive class means how many points that actually belong to a positive class are predicted as positive, same for the negative class
F1 Score: Harmonic mean of precision and recall.
Confusion Matrix
