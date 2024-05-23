# AbaloneRingPred
Kaggle competition to predict rings on abalone.  Ended up in the top 10%.  

The goal of this competition was to predict the number of rings of an abalone based on features such as size, weight, sex

Two interesting techniques I used to get a good score:

1.  Combining features such as wight and length to make new features.
2.  Building ensemble prediction models.  Ensemble prediction models combine multiple models.  For example, you might use a Random tress model paired with lightGBM and use both of their predicitive capablities to get better predictions than what you could get from either model alone.

In this case, I experimented with a number of different models and settled on a model that used the following models:

-HistGradientBoostingRegressor
-MLPRegressor
-RandomForestRegressor
-'ExtraTreesRegressor'
