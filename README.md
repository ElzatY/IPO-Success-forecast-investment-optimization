# IPO-Success-forecast-investment-optimization

The Initial Public Offering (IPO) is the process when a private company sells shares to the public for the first time. Often, the company’s expectation can be significantly different from the market reaction which leads to a huge loss of capital. Hence, private companies need some metrics to decide if it is the right time to go public, ideally, a strong predictive model that can forecast the rate of return of the IPO. Meanwhile, the investors need a model that selects the best investment portfolio according to different objectives: risk-seeking, risk-averse or balanced. 

The main goal of this project consists of two steps: 
1. Predicting the rate of return of each IPO on the releasing date using random forest regressor 
2. Optimizing a portfolio that constructs a distribution of investment in private companies based on the type of investors.

I collected the company’s features and market variables that traditionally seen as good predictors to the closing price of IPO. Then I took in those features to build a random forest model to predict the closing price on the day of the IPO releases. The rate of return of each private company can be calculated with the predicted value of (close  price-offer price)offer priceand the risk is quantified using the standard deviation. Then, a set of companies’ rate of return and risk are inputted into the portfolio optimization models that constructs an optimal allocation of investment on the companies based on investors’ risk tolerance level.
