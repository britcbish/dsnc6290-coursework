# Machine Learning

This repository contains course work for the Summer 2019 semester of <a href= "https://github.com/jphall663/GWU_data_mining" rel="nofollow">GWU's Machine Learning</a> class taught by Patrick Hall. The group worked together to enter two kaggle competitions: <a href="https://www.kaggle.com/c/digit-recognizer" rel="nofollow">Digit Recognizer</a> and <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques" rel="nofollow">House Prices: Advanced Regression Techniques</a> with the team name VBA^2.

## Digit Recognizer

This<a href= "https://github.com/britcbish/dsnc6290-coursework/blob/master/MNIST.ipynb" rel = "nofollow"> jupyter notebook</a> produced the predictions that we submitted for this competition. We use a convolutional neural network and data augmentation for a submission score of .99571 - this placed us at 485/3046 on the leaderboard at the time of our submission.

![Image of MNIST rank](https://github.com/britcbish/dsnc6290-coursework/blob/master/MNISTrank.jpg)
![Image of MNIST score](https://github.com/britcbish/dsnc6290-coursework/blob/master/MNISTscore.jpg)

## House Prices: Advanced Regression Techniques

### Using h2o.automl - StackEnsemble
This<a href= "https://github.com/britcbish/dsnc6290-coursework/blob/master/House Sale Prices - H2OAUTOMIL.ipynb" rel = "nofollow"> jupyter notebook</a> walks through our initial use of the h2o.automl feature, that resulted in a StackedEnsemble Model producing the best predictions and yielding a top submission score of .12170 - this placed us at 1289/4658 on the leaderboard at the time of our submission.
 
![Image of House Sale Prices Contest rank](https://github.com/britcbish/dsnc6290-coursework/blob/master/h2o_automl_rank.PNG)
![Image of House Sale Prices Contest score](https://github.com/britcbish/dsnc6290-coursework/blob/master/h2o_automl%20score.PNG)

### A closer look at data prep and using RF, XGB, GBM, LightGBM
This<a href= "https://github.com/britcbish/dsnc6290-coursework/blob/master/House%20Prices.ipynb" rel = "nofollow"> jupyter notebook</a> put more emphasis on the exploration and preparation of the data before attempting to model. We used Random Forest, XG Boost, Gradient Boost Regressor(GBM), and LightGBM. We submited the best model, LightGBM, and recceived a score of .12188 which placed us at 1313/4658 on the leaderboard at the time of our submission.
 
![Image of House Sale Prices Contest rank](https://github.com/britcbish/dsnc6290-coursework/blob/master/HousePricesRank.PNG)
![Image of House Sale Prices Contest score](https://github.com/britcbish/dsnc6290-coursework/blob/master/HousePricesScore.PNG)

### Top submission
This<a href= "https://github.com/britcbish/dsnc6290-coursework/blob/master/HPART.ipynb" rel = "nofollow"> jupyter notebook</a> combined our two efforts to create a submission that used some of our initial data preparation techniques and then h2o.automl for the modeling aspect. The averaged results of the top two models resulted in a submission score of .11768 and a ranking of 751/4577 on the leaderboard at the time of our submission.

![Image of House Sale Prices Contest rank](https://github.com/britcbish/dsnc6290-coursework/blob/master/HPARTrank.PNG)
![Image of House Sale Prices Contest score](https://github.com/britcbish/dsnc6290-coursework/blob/master/HPARTscore.PNG)
