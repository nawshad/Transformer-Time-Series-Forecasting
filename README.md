
# Attention Mechanisms for Time Series Forecasting

Article: https://natasha-klingenbrunn.medium.com/transformer-implementation-for-time-series-forecasting-a9db2db5c820

#### The prediction task is to Predict P(T_(n+k) | T_1 ... T_n), so the classifier will be provided features T_1 ... T_n and labels T_1 ... T_(n+k) for training. K is the forecast window. 

### Todo:
* Identify how depression symptoms scores and depression scores over two weeks
episode can be incorportated in this code, possibly by using some dummy representation
of such data. Also, how sequential order is maintained?
* This code sequence to sequence, while this is useful for another task, how to edit this code for
doing sequence to single task.
* How to incorporate Time related constraint, one way is to model the time-gap 
in the data, so that the model implicitly takes care of it. Other way is to 
explicitly regularize for it? What about other signals that can be incorporated 
through regularization.
* Try the performance for both CLPsych-2015 and IJCAI-2017.
