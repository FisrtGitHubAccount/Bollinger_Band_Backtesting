# Bollinger Band Backtesting

Bollinger bands are calculated by taking the 20-day simple moving average (SMA) of a stock price (for the most part) and then calculating the upper and lower bounds as the SMA +- two standard deviations of the actual stock price. Buy/Sale signals are spotted when the price crosses the Boilinger bands.

The details of the strategies will be varied to investigate how Boilinger bands should be implemented for different assets, starting from Stock indices to tbd. This project is a hopeful research to find trends for certain types of asset with respect to Boilinger bands.

Position sizing will be investigated but stop-loss is currently ignored as we will focus on assets that are expected to survive in the long run (naively assumed to have zero probability of being delisted). However, it might be implemented later if, for example, a really good strategy was discovered but the maximum drawdown was too big.

**This project is currently undergoing.**
