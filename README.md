# Logistic-Regression
Logistic Regression applied on DonorsChoose Dataset

Even though the name contain Regression it ia not a regression model,its a classification model.
In Logistic Regression we finding a plain wich seperate two class which minimize log-loss .
we can prove Logistic Regression by considering the featuers follows gaussian Naive base  and target variable follows Binomial distribution

The ipynb shows the implimentation of Logistic Regression on DonorsChoose Dataset and how to tune Hyper paramater alpha which is multiplied with regulizer .
The AUC for different alpha value is plotted and we can see how AUC changes as alpha changes.
* alpha is low model overfits (high variance)
* alpha high model underfits (high Bias)

The data has been prerocessed like removel of duplicate ,stop words, special character and hyper txt links etc

The processed Data have been analysed - univarient analysis to know more about the data .

Metric used to find best model was AUC (Area under ROC).

# Facing error while loading IPYNB "Sorry, something went wrong. Reload?"
please click the following link
https://nbviewer.jupyter.org/github/prassena/Logistic-Regression/blob/master/Logistic%20Regression.ipynb
