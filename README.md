# Deep Learning

In this assignment, I used deep learning recurrent neural networks to model bitcoin closing prices. One model uses the FNG indicators to predict the closing price while the second model uses a window of closing prices to predict the nth closing price.

I used the two models to answer the follwoing questions: 

>Which model has a lower loss?
>>The first model, using the FNG indicators to predict the closing price, had lower loss. 

>Which model tracks the actual values better over time?
>>The second model, using the closing prices to predict future closing prices, tracks better values over time. The predicted values seem to decrease and increase in correlation with the actual values more consistently than the first model. 

>Which window size works best for the model?
>>For the second model, using the window size of 1 improved the accuracy of predictions significantly. However, for the first model, it seemed to perform the best using the 10 day window size. 