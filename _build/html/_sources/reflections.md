# Reflections

## Conclusion

In conclusion, we have applied three different models to the same dataset: multiple linear regression, SARIMAX, and LSTM. Each model has its own strengths and weaknesses in terms of interpretability and performance.

The multiple linear regression model has an R-squared value of 0.967, which indicates a strong fit to the data. It is easy to interpret the coefficients and understand the relationship between the independent and dependent variables. The SARIMAX model, on the other hand, is a time series model that accounts for the autoregressive nature of the data. While its AIC and BIC values are higher than the multiple linear regression model, it captures the temporal dependencies that might be present in the data. The LSTM model is a deep learning approach that can model complex relationships and temporal dependencies in the data, but it lacks interpretability compared to the other two models.

The models' interpretations are not necessarily concurrent or conflicting; rather, they offer different perspectives on the data. The multiple linear regression model provides insight into the relationships between the independent variables and the dependent variable, while the SARIMAX and LSTM models account for the time series nature of the data. In this case, each model may offer unique insights, and a combination of the models could provide a more comprehensive understanding of the data.

The trade-off between interpretability and model complexity is an important consideration. While simpler models like multiple linear regression and SARIMAX are easier to interpret, they may not capture the complexity present in the data as well as LSTM. Since the mean squared error of predictions for LR, SARIMAX, and LSTM are 11778,408,374 respectively, LR performs significantly worse than the other two models in predicting future stock price. 

Predicting future stock prices is challenging due to the complex nature of financial markets. The chosen models—multiple linear regression, SARIMAX, and LSTM—each have limitations. Linear regression may oversimplify relationships, while SARIMAX assumes stability over time, which may not hold for stock prices. LSTM can model complex temporal dependencies but may overfit and lacks interpretability. While these models can provide insights, their predictive power is limited by their assumptions and the inherent unpredictability of markets. It's essential to combine their predictions with other sources of information for more informed decisions on stock price movements.