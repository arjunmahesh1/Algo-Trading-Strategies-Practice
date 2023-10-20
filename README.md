# algo-trading-strategies-practice

Practice from "Algorithmic Trading: Winning Strategies and Their Rationale". Ernest P. Chan. © 2013 Ernest P. Chan. Published 2013 by John Wiley & Sons, Inc.

#### Mean Reversion and Stationarity:  
_Utilizes EUR_USD data from https://sdw.ecb.europa.eu/quickview.do;jsessionid=D2CD02A53B09A6A89782BD21F16BC2A6?SERIES_KEY=120.EXR.D.USD.EUR.SP00.A_
> Tests Demonstrated:
> - ADF Test
> - Hurst Exponent
> - Variance Ratio Test
> - Half-Life of Mean Reversion


  
#### Impractical Mean-Reverting Strategy:
Mean-Reverting Strategy on non mean-reverting EUR_USD data above. Shows that trading a nonstationary price series can be profitable with a mean-reverting strategy.  
Impractical Assumptions:
 - Unlimited capital (no maximum imposed on portfolio market value)
 - No transaction costs
 - Look-ahead bias (half_life extracted from in-sample data in 'Mean Reversion and Stationarity')

#### Cointegration:
_Utilizes EWA and EWC ETF historical data from Nasdaq, IGE ETF data for 3-way_
> Tests Demonstrated:
> - CADF Test
> - Johansen Test
> - 3-Way Cointegration Johansen Test
> - Backtesting a Linear Mean-Reverting Strategy on a Portfolio (best eigen)
> - Kalman Filter + Kalman Strategy


#### Trading Pairs Comparison:  
_Utilizes USO and GLD historical data from Nasdaq_
> Compared:
> - Spread (Strategy + Returns)
> - Log Spread (Strategy + Returns)
> - Ratio (Strategy + Returns)
> - + Final statistics for each (Sharpe + APR)


#### Bollinger Bands Strategy:  
_Utilizes USO and GLD historical data from Nasdaq_
> Bollinger Bands Strategy/Returns/Statistics (Sharpe + APR)


#### Buy/Short-on-Gap Strategy:
_Utilizes hourly DOW Jones data_
Intra-Day mean reversion strategy  
Unlimited capital/No transaction costs, signal noise from open/preopen difference
> Buy-on-Gap Strategy + Statistics
> Short-on-Gap Strategy + Statistics


#### Cross-Sectional Mean Reversion Strategy:
_Utilizes DOW Jones data_
Close-to-close
> Linear Long-Short Model + Statistics


#### Trading Currency Cross-Rates:
_Utilizes USDCAD and AUDUSD data from NASDAQ_
> Pair Trading USD.AUD v. USD.CAD Using the Johansen Eigenvector


#### High-Frequency Index Arbitrage:
_Universe of DOW Jones Data_
> UNDER CONSTRUCTION


#### Spot Roll Returns:
_Futures Data from Investing.com_
> UNDER CONSTRUCTION


#### Calendar Spreads:
_Futures Data from Investing.com_
> UNDER CONSTRUCTION


#### Time Series Momentum:
_US Treasury Futures Data_
> Finding Correlations between Returns of Different Time Frames (TU)
> Equity Curve


#### Future v. ETF Arbitrage:
_USO, CLE ETF data from Nasdaq, CL Futures Data from Investing.com_
> Extracting Roll Returns through Future v. ETF Arbitrage


#### Opening Gap Strategy:
_FSTX data from Yahoo Finance_
> Intraday Opening Gap Strategy
