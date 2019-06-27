# Machine Learning

This repo contains course work for the Summer 2019 semester of <a href= "https://github.com/jphall663/GWU_data_mining" rel="nofollow">GWU's Machine Learning</a> class taught by Patrick Hall. The group worked together to enter two kaggle competitions: <a href="https://www.kaggle.com/c/digit-recognizer" rel="nofollow">Digit Recognizer</a> and <a href="https://www.kaggle.com/c/house-prices-advanced-regression-techniques" rel="nofollow">House Prices: Advanced Regression Techniques</a>.

## Digit Recognizer

This<a href= "https://github.com/britcbish/dsnc6290-coursework/blob/master/MNIST.ipynb" rel = "nofollow"> jupyter notebook</a> produced the predictions that we submitted for this competition. We use a convolutional neural network and data augmentation for a submission score of .99571 - this placed us at 485/3046 on the leaderboard at the time of our submission.

![Image of MNIST rank](https://github.com/britcbish/dsnc6290-coursework/blob/master/MNISTrank.jpg)
![Image of MNIST score](https://github.com/britcbish/dsnc6290-coursework/blob/master/MNISTscore.jpg)

## House Sale Prices

### Using h2o.automl - StackEnsemble
This<a href= "https://github.com/britcbish/dsnc6290-coursework/blob/master/House Sale Prices - H2OAUTOMIL.ipynb" rel = "nofollow"> jupyter notebook</a> produced the predictions that we submitted for this competition. We use a the h2o.automl feature, that resulted in a StackedEnsemble Model for a submission score of .12170 - this placed us at 1289/4658 on the leaderboard at the time of our submission.
 
![Image of House Sale Prices Contest rank](https://github.com/britcbish/dsnc6290-coursework/blob/master/h2o_automl_rank.PNG)
![Image of House Sale Prices Contest score](https://github.com/britcbish/dsnc6290-coursework/blob/master/h2o_automl%20score.PNG)


## House Sale Prices

### RF, XGB, GBM, LightGBM
This<a href= "https://github.com/britcbish/dsnc6290-coursework/blob/master/House%20Prices.ipynb" rel = "nofollow"> jupyter notebook</a> produced the predictions that we submitted for this competition. We used Random Forest, XG Boost, Gradient Boost Regressor(GBM), and LightGBM. We submited the best model, LightGBM, and recceived a score of .12188 - this placed us at 1313/4658 on the leaderboard at the time of our submission.
 
![Image of House Sale Prices Contest rank](https://github.com/britcbish/dsnc6290-coursework/blob/master/HousePricesRank.PNG)
![Image of House Sale Prices Contest score](https://github.com/britcbish/dsnc6290-coursework/blob/master/HousePricesScore.PNG)
