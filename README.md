--ABSTRACT--

The Algorithmic Trading solution for Bitcoin (BTC) and Ethereum 
(ETH) integrates technical indicators, statistical models, and an 
adaptive Master Alpha strategy for optimal trend detection and 
execution. The BTC strategy employs EMA crossovers, RSI, and 
Parabolic SAR, while the ETH approach uses candlestick patterns 
with adaptive Take Profit (TP) and Stop Loss (SL). The Kalman filter 
and Aroon indicator refine trend confirmation. The 
Master Alpha strategy dynamically selects the best-performing 
alpha based on market conditions, ensuring adaptability and 
minimizing false signals. It maintains an Alpha Pool optimized for 
different market states, periodically evaluating them based on 
volatility, mean positive returns, max drawdown, and Sharpe 
ratio to compute a composite alpha score for selection. The 
strategy assumes trend persistence, selecting the top-performing 
alpha from the previous period while minimizing turnover to 
reduce brokerage costs. Take Profit (TP) and Stop Loss (SL) are 
integrated within the strategy to capture full trend potential.


--MEATHODOLOGY--

 The Master Alpha strategy dynamically selects the best
performing alpha based on market conditions, ensuring 
adaptability and minimizing false signals.

1.Alpha Pool & Selection
 
  a.Maintains multiple alphas optimized for different 
  market states.
  
  b.Periodically evaluates alphas using volatility, mean 
  positive returns, max drawdown, and Sharpe ratio.
  
  c.Computes a composite alpha score to rank and 
  select the best alpha.
  
 2.Strategy Hypothesis & Optimization
 
  a.Assumes trend persistence, selecting the top
   performing alpha from the previous period.
  
  b.Minimizes turnover to reduce brokerage costs.
 Minimizes turnover to reduce brokerage costs.


--RESULT--

The Master Alpha strategy demonstrated strong performance 
across BTC and ETH markets:

 •BTC Performance: Achieved a 5430.4% total profit, with a 
69.76% win rate, a Sharpe ratio of 10.68

 •ETH Performance: Delivered a 348,064.77% total profit, a 
74.39% win rate, a Sharpe ratio of 10.799

 Both assets exhibited high returns with controlled risk, and both the algos were able to perform on future data as well.
