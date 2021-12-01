# CSE3013 Artificial Intelligence

## Team Members
<li>Arohan Mishra - 19BCE0270</li>
<li>Praneel Jimmy - 19BCE0277</li>
<li>Aryan Blouria - 19BCE0330</li>
<li>Samarth Arora - 19BCE0334</li>
<li>Aryan Vats - 19BCE0336</li>
<li>Kanit Mann - 19BCE2040</li>

## Abstract

<li>After the boom and bust of cryptocurrencies’ prices in recent years, Bitcoin has been progressively viewed as a venture resource and investment asset. Due to its profoundly unpredictable nature, there is a need for good prediction algorithms on which investment decisions can be based. Although existing studies have utilized machine learning for more accurate Bitcoin price prediction, few have zeroed in on the possibility of applying different modelling techniques to samples with different data structures and dimensional features. </li>

<li>Using machine learning techniques to predict Bitcoin price at different frequencies, we first classify Bitcoin price according to adjusted close price. Then the adjusted close price values are compressed into a magnitude between 0 and 1 using MinMaxScalar to eliminate any possible errors due to the high difference between data values. Then this scaled data is divided into test and train data. The training data is then fed into various machine learning models such as Linear Regression, Decision Tree Regression, Random Forest Regression, K-Nearest Neighbours, Xtreme Gradient Boost (XGB) and deep learning models such as Long Short Term Memory with appropriate required parameters. </li>

<li>The Root Mean Squared Error (RMSE) is found for every algorithm by comparing the predictions with the actual values and each RMSE is compared to find the best-suited model which is applicable here. Additionally, a deep learning model, namely LSTM, is also used to predict the prices of bitcoin, the RMSE value is calculated and a graph is plotted based on the prediction. Our investigation of Bitcoin price prediction can be considered a pilot study of the importance of the sample dimension in machine learning techniques. </li>
