# Timeseries classification - Conv1D NN solution

Solution to [the competition](https://www.kaggle.com/c/adsc-2018-timeseries-classification) based on:
* extensive EDA,
* synthetic intermediate task of finding certain artifacts in time series - which is solved by 1d-convolutional neural network,
* aggregated predictions of NN for raw time series and predictions of a linear model trained on simple statistical features - stacked via LightGBM.

Please download competition data into the [input](input/) directory and see the [working](working/) directory for notebooks.
