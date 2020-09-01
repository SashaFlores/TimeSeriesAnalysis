My model findings in Time Series Analysis are:

1. Akaike Information Criterion (AIC) which estimates the quality of statistical model, when comapring 2 models, the one with the lower AIC is generally the better; based on this ARMA model is lower than ARIMA.

2. The Bayesian information criterion (BIC) which penalizes model complexity more heavily, BIC the lower the better, but it's almost the same value as AIC in both models.

3. P is above threshold in both models.

4. Returns forecasted to increase in ARIMA, and decrease in ARIMA.

5. Based on above reasons, I can't trust this anaylsis 

6. for GARCH, the volatility is expected to increase and P value is below the 0.05 threshold. It looks to me it isn't a good timing investing/Buying Yen now.


Regression Analysis:
* RMSE is the standard deviation of the residuals (prediction errors) so training subset should normally have higher RMSE than test subset, which wasn't the case in this analysis.