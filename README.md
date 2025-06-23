# Beyond the headlines

## Abstract
Numerical analysis reveals Financial Crises may not be as devastating as thought for average investors.

We often see headlines like _"The stock market fell by X%"_ but did our own portfolios really drop by the same amount? Most average investors don’t invest everything at the all-time high. While lump-sum investing is statistically the most effective approach on average, in reality, factors like regular income and gradual savings lead most people to invest on a recurring basis, more akin to dollar-cost averaging (DCA).

Our analysis focuses on extreme market conditions. We will demonstrate that:
* Investors who were in the market at least one year prior to the all-time high tend to experience significantly smaller losses.
* The time required to recover from downturns is notably shorter. In fact, risk shouldn't be viewed solely in terms of market volatility, but also in terms of time to recovery  (the duration it takes for a portfolio to return to its previous value). **Note:** our hypothesis assumes that the DCA approach stops at the market bottom.

## Conclusion
We observe that based on the analysis of three major market crashes, average investors:
* Improved the performance by 20.45%
* Reduced the time to recovery by 40.54%

## Output
```
*** Analyzing dates from 01 January 2007 to 31 January 2010 ***

We observed the worst market drawdown of -56.78% occurring between 09 October 2007 and 09 March 2009. It took 1480 days for the market to fully recover.

Now, let's simulate starting a DCA investment 1 year(s) prior to the crash, from 9 October 2006 to 09 March 2009
Over this period, the investment had a P/L of -46.26% and fully recovered in 660 days
The average investor had:
1) A P/L improvement of 18.52%
2) A reduction in recovery time of 44.59%

---------------------------------------------------------------
*** Analyzing dates from 01 January 2000 to 31 December 2003 ***

We observed the worst market drawdown of -49.15% occurring between 24 March 2000 and 09 October 2002. It took 1694 days for the market to fully recover.

Now, let's simulate starting a DCA investment 1 year(s) prior to the crash, from 24 March 1999 to 09 October 2002
Over this period, the investment had a P/L of -36.78% and fully recovered in 1014 days
The average investor had:
1) A P/L improvement of 25.17%
2) A reduction in recovery time of 59.86%

---------------------------------------------------------------
*** Analyzing dates from 01 January 1927 to 31 December 1933 ***

We observed the worst market drawdown of -86.19% occurring between 16 September 1929 and 01 June 1932. It took 8148 days for the market to fully recover.

Now, let's simulate starting a DCA investment 1 year(s) prior to the crash, from 16 September 1928 to 01 June 1932
Over this period, the investment had a P/L of -70.97% and fully recovered in 1400 days
The average investor had:
1) A P/L improvement of 17.66%
2) A reduction in recovery time of 17.18%
```

## Limitations
The analysis
* Should have analyzed at least rolling windows from up to `n-5` instead of a fixed `n-1`
* Has analyzed only 3 market crashes, which, although severe, may not have been sufficient to establish statistical significance
