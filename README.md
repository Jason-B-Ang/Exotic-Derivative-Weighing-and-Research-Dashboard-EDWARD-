# Exotic-Derivative-Weighing-and-Research-Dashboard-EDWARD-
Capstone Project Planning Sheet

Title: Exotic Derivative Weighing and Research Dashboard (EDWARD)

Directory of public API: https://github.com/public-apis/public-apis#finance: 
{Finnhub: Real-Time RESTful APIs and Websocket for Stocks, Currencies, and Crypto, Alpha Vantage	
:Realtime and historical stock data, Yahoo Finance: Real time low latency Yahoo Finance API for stock market, crypto currencies, and currency exchange, IG: Spread Betting and CFD Market Data}

Literature
{John C. Hull’s Options, Futures, and Other Derivatives: [
Contains equations (or models) for pricing various derivative products,
Offers insight into the limitations of various models, as well as real-world applications of each model],
Archived Quantopian Lecture Series:[ 
Prior to being acquired by Robinhood, Quantopian offered lectures on various financial applications of Python (i.e., Value at Risk modeling, constructing backtests, etc.)]}

 Relevant Lecture Material
NYU is home to some of the most elite mathematical finance programs in the world; as such, it is only reasonable that we observe relevant lecture material concerning options pricing and options greeks

On Exotic Options
On Options Greeks


UCLA Mathematics Department

On Exotic Options


Utah State University

Options Pricing Through Computational Methods (2016)


ML for Options Pricing 

Accelerating Python for Exotic Option Pricing (2020)


Relevant Repositories 

Options Pricing Repository by hsjharvey
Use as reference; makes use of Black-Scholes model, so do not expect pricing to be completely accurate 


Roles:

Douglas Harrison
Task: Wireframe: UI, data, class attribures, dubugging

Jason Ang
Task:  UI, data, class attribures, dubugging

Ezzard Bradford
Task:  UI, data, class attribures, dubugging
Description/Summary
Roadmap


Goals
https://financetrain.com/best-python-librariespackages-finance-financial-data-scientists
Python libraries

Create lambda functions for pricing models (futures, options, and swaps on equities)

Relevant Pages
106-107 “Assumptions and Notation” of futures pricing models,
124-126 “Futures Prices” (various equations for stocks that may or may not pay dividends),
178 “Equity Swaps” disregard for now, pricing model not included in textbook,
213-223 “types of options” provides conceptual understanding of puts and calls,
234-246 “Factors Affecting Option Prices” provides insight into the behavior of options pricing models, 
254-269 “Trading Strategies involving options” provides insight into how we will recommend contracts to the user (i.e., provided market conditions, our code suggests XYZ strategy),
274-301 “Binomial Trees” relevant computational approach to pricing options, modeling stock price movements (also includes binomial tree approach to black-scholes),
321-347 “The Black-Scholes Model” relevant equations for pricing puts and calls (very important),
383-395 “Futures Options” explains model for options on futures (which is one of many types of exotic options),
399 - 426 “Greeks” provides relevant models for options greeks, which are metrics that describe the sensitivity of various factors to each other (re: pgs. 234-246),
431-443 “Volatility Smile” insight into the behavior of options and futures with respect to volatility of the underlying stock (no equations, just conceptual insight),
431 - 488, ‘Basic Numerical Procedures” rule of thumb: if it’s an equation, write it down and turn it into a lambda function (odds are it’ll be relevant to a method),
494 - 520 “Value at Risk” relevant equations for value at risk modeling, backtesting,
598 - 619 “ Exotic Options” annotate, record, and turn into lambda function(every equation is relevant to options pricing, and will be used in a method in some form or the other),
