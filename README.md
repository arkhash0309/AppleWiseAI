<h1 style="text-align:center">AppleWiseAI</h1>
<!-- </br> -->

#### Predicting the prices of Apple stocks using census data from the past 44 years.

## Dataset

#### The dataset provides a detailed record of Apple Inc.'s stock price variations over the past 44 years. It includes the following columns:
<ul>
    <li>Date</li>
    <li>Opening Price</li>
    <li>Highest Price</li>
    <li>Lowest price</li>
    <li>Closing Price</li>
    <li>Adjusted Closing Price</li>
    <li>Trading Volume</li>
</ul>

#### This data has been used for the following purposes:
<ul>
    <li>Conducting historical analysis</li>
    <li>Understanding market trends</li>
    <li>Forecasting future stock prices using: 
        <ul>
            <li>Machine learning</li>
            <li>Time Series Forecasting</li>
            <li>Deep Learning</li>
        </ul>
    </li>
</ul>


## Insights Identified
#### The greatest number of stocks have been sold between the years 2005 to 2008, with the most number of stocks being sold during the year 2008.
#### There has been a continuous increase in the proce of stocks over the years.


## Machine Learning
#### The following machine learning algorithms were used for comparison purposes to see how well they identify trends in stock sales and predict prices on test data.
<ul>
    <li>Linear Regression</li>
    <li>Decision Tree Regressor</li>
    <li>Random Forest Regressor</li>
    <li>Support Vector Regressor</li>
    <li>K-Neighbours Regressor</li>
    <li>XGBoost Regressor</li>
    <li>Gradient Boosting Regressor</li>
</ul>

#### While evaluating these algorithms, it was noted that the Support Vector Regressor and the K-Neighbours Regressor performed poorly on the data.


## Time Series Forecasting
#### The auto-arima library was used to obtain the optimal parameters for the algorithms.
#### The following time series algorithms were used to predict stock prices.
<ul>
    <li>AutoRegressive Integrated Moving Average (ARIMA)</li>
    <li>Seasonal AutoRegressive Integrated Moving Average (SARIMA)</li>
</ul>


## Deep Learning
#### Deep Learning algorithms were used to obtain more powerful and precise predictions.
#### The following algorithms were used:
<ul>
    <li>Long Short Term Memory (LSTM)</li>
    <li>Gated Recurrent Unit (GRU)</li>
</ul>

#### The Gated Recurrent Unit is a simple and powerful Recurrent Neural Network (RNN) which is suitable for time series forecasting.


## Overall Findings
#### The machine learning algorithms performed better than expected with most of the predictions being almost identical to those in the test data.

#### The time series algorithms did not perform as well as they were expected to perform. This could be caused by the inability to identify potential sales trends in the dataset.

#### The deep learning algorithms performed really well with the Gated Recurrent Unit having a very good prediction graph against the actual values.



