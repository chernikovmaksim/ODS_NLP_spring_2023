# Toxic comments classification
## Project description
The store needs a tool that will search for toxic comments and submit them for moderation.
## Status
Done
## Goals
It is necessary to train the model to classify comments into positive and negative.
## Required libraries
pandas, numpy, scikit learn, torch, tqdm, sys, os, time, transformers, nltk, matplotlib, seaborn
## Conclusion
The general information about the obtained data was examined. The data was also checked for duplicates and omissions. Text data was stripped of stop words, symbols and texts were lemmatized. Then the texts were transformed into vector representations for solving the problem of binary classification using 2 methods: TF_IDF and BERT. To solve the classification problem, 2 models were chosen: logistic regression and gradient boosting. The best hyperparameters were selected for these models. To combat class imbalance, the "balanced" hyperparameter was applied. The chosen logistic regression model shows a high accuracy - 94.37%, the level of class prediction is also high and amounted to F1 = 0.7569, which is at the level of 0.75 from the condition of the problem. The ROC curve demonstrates a good quality of the model (the proportion of truly positive responses is greater than the proportion of false positives). The area of the figure under the ROC curve was 0.97, which is an excellent indicator.
## Data
The following datasets were used:
* data with comment texts
