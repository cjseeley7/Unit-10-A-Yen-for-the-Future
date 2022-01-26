# **A-Yen-for-the-Future**

## **Background:**

The project is to forecast the CAD-JPY exchange rate using time series analysis. I have used the Hodrick-Prescott Filter to separate the trend and noise. The forecasting was completed using an ARMA model by passing the returns to the model, and by using ARIMA model by passing the price to the model. I also used a GARCH model, which predicts the future volatility of the CAD-JPY exchange rate.

---

>Model: Time Series Forecasting

### **Question: Do you see any patterns, long-term and/or short?**

Answer: Generally speaking, the Japanese Yen has grown in strength against the Canadian Dollar, since 1992. However, there have been periods in time of up to 7 years where the Canadian Dollar strengthens against the Yen. This was seen between 2000 and 2007, then again between 2008 and 2015, after a signfiicant correction post the Global Financial Crisis.


### **Question: Do you see any patterns, long-term and/or short?**

Answer: The trend since 2015 is mostly similar to the prior longer terms trend, with the Yen strengthening against the Canadian Dollar. However, the price can deviate higher or lower than the trend line, indicating possible trading opportunities.
Based on your time series analysis, would you buy the yen now?

### **Question: Based on the p-value, is the model a good fit?**

Answer:

When p-value > .10 → the observed difference is "not significant"\ 
When p-value ≤ .10 → the observed difference is "marginally significant"\ 
When p-value ≤ .05 → the observed difference is "significant" \
When p-value ≤ .01 → the observed difference is "highly significant"\

This model is therefore not a good fit as the p value is greater than 0.05.

### **Question: What does the model forecast will happen to the Japanese Yen in the near term?**

Answer: The model shows that the JPY will strengthen against the Canadian Dollar as 1 CAD is currently ¥80.70 and in 5 days, it is predicted to be ¥80.62.

### **Question: What does the model forecast will happen to volatility in the near term?**

Answer: The model forecasts there will be an increase to volatility over the next 5 days.

# **Conclusions**

### **Based on your time series analysis, would you buy the yen now?**
No, the models did not prove a good fit due to the high p values and it appears there will be increased volatility in the short term

### **Is the risk of the yen expected to increase or decrease?**
There is projected to be an increase in the volatility, which means the risk is expected to increase.

### **Based on the model evaluation, would you feel confident in using these models for trading?**
I would not be confident to trade with these models as the ARMA and ARIMA models were not a good fit due to the p-values. The GARCH model was a better fit as the results indicated an increase to volatility. The issue is that volatility does not tell you which way the market is going to move.

>Model: Linear Regression Forecasting

# **Conclusions**

### **Question: Does this model perform better or worse on out-of-sample data as compared to in-sample data?**

Answer: Generally a lower RMSE is better than a higher one. The out-of-sample data performed better then the In-Sample Training Data, with an RMSE of 0.6445805658569028 compared with 0.841994632894117 for the In-Sample data.