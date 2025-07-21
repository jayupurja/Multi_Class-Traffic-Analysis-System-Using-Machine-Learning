DATASET: CICDS2017
Dataset Description
Realistic network traffic dataset with over 2.5 million records and 53 features.
Preprocessed and cleaned for immediate use.
Captures both normal traffic and multiple network attack types.

Features
Network flow metrics: packet counts, byte sizes, flags, and timing statistics.
Numerical features ideal for machine learning.
Examples: Flow Duration, Packet Length Mean, ACK Flag Count, Idle Times



Supervised Models:
 - Random Forest 
 - Decision Tree
 - Naive Bayes

Unsupervised Models:
 - Isolation Forest Model
 - Minibatch K-means



EVALUATION METRICS
Accuracy: Overall percentage of correctly classified instances.
Precision: How many predicted attacks are actually attacks (minimizes false alarms).
Recall (Sensitivity): How many actual attacks are correctly detected (minimizes missed attacks).
F1-Score: Balance between precision and recall, useful for imbalanced classes.
Confusion Matrix: Detailed breakdown of correct and incorrect predictions per class.
ROC Curve & AUC: Shows model’s ability to distinguish classes; higher AUC means better performance.
Precision-Recall Curve & Average Precision: Illustrates trade-off between precision and recall, especially for imbalanced data.
Adjusted Rand Index (ARI): Measures how well unsupervised clustering matches true labels.
