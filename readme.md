# A sales forecasting playground, where I try to forecast the sales for a small business

---

### 1. Approach utilizing ARIMA models from [statsmodels](https://www.statsmodels.org/stable/statespace.html#statespace)

#### STEPS

-   [x] (IN PROGRESS) Learn about arima models
-   [x] Make a first try in forecasting
-   [ ] Find a proper way to validate the model
-   [ ] Improve

#### NOTES

All the past features you use for fitting the model, you should also use for predictions, i.e. if you use weather data to fit, you need future weather data to predict. We're not certain of what the weather in the future is gonna be, so the further we try to predict, the more the probability of the prediction being right degrades, since weather in a long term is also more uncertain.
However, features like Holidays or seasons or weekdays stay the same so it's easy to use them.
