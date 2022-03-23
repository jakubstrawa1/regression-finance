This is a data science project with regression problem that predicts the amount based on cost centre, account type, date etc.
For this model i've also used the GridSearchCV pipeline trick with dictionary and hyperparameters, 
which immensely helps with tuning and finding the best optimal algorithm (in this case from randomforst, lasso, ridge, elasticnet and gradientboosting). In this case the best one turned out to be Random Forest. 

I found this technique to be amazing at finding the best algorithm, but im pretty sure as far as deep learning goes it would be pretty hard to do so, since one bigger model could be training for hours or days. But for regression or simpler tasks that's brilliant

This ipynb presents lots of data visualisation, correlations, violinplots and heatmaps. 
In this project i've used high level techniques for data processing such as one hot encoding with pd.get_dummies(), dropping/filling columns/rows,
changing dtypes.
