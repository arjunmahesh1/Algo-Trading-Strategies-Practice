# algo-trading-strategies-practice

Practice from "Algorithmic Trading: Winning Strategies and Their Rationale" by Ernest Chan

#### Mean Reversion and Stationarity:  
_Utilizes EUR_USD data from https://sdw.ecb.europa.eu/quickview.do;jsessionid=D2CD02A53B09A6A89782BD21F16BC2A6?SERIES_KEY=120.EXR.D.USD.EUR.SP00.A_
> Tests:
> - ADF Test
> - Hurst Exponent
> - Variance Ratio Test
> - Half-Life of Mean Reversion


  
#### Impractical Mean-Reverting Strategy:
Mean-Reverting Strategy on non mean-reverting EUR_USD data above.  
Shows that trading a nonstationary price series can be profitable with a mean-reverting strategy.
> Assumptions:
> - Unlimited capital (no maximum imposed on portfolio market value)
> - No transaction costs
> - Look-ahead bias (half_life extracted from in-sample data in 'Mean Reversion and Stationarity')
