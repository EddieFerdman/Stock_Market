# Stock Market!
#### Predict Stock Market Activity

**Goal 1: 70% Precision Accuracy using simple indicators.** 

**Goal1 2: Backtesting models and strategies**

**Scripts Overview:**
1. **FeatureEngineering** - Gather data for 1 stock ticker, develop simple indicators and target variables.
2. **Target2 Base Classifiers** - Using indicators created in FeatureEngineering script and a number of stocks, train various classifier and compare results. No tuning is done at this point.
3. **Backtesting** - This is another type of performance metric and is a bit of fun. Using any model already created, back test the outcome for any stocks and time period using a set number of trading days, stop loss and stop win amounts.


**Pipeline:**
1. Tune a model for better performance.
    - [ ] Hyperparameter tuning
    - [ ] Probability decisions - choose highest probabilty for backtesting
2. Create more features.
    - [ ] NLP of financial news.
    - [ ] Stock info - market cap, industry sector, employee size, sharesout, dividends ...
3. Regression models
    - [ ] Idea: Predict at what price to sell for backtesting script


