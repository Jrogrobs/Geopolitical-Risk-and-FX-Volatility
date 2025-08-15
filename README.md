# Geopolitical-Risk-and-FX-Volatility

This project explores the impact of geopolitical risk on foreign exchange (FX) markets using the GPR Index developed by Caldara and Iacoviello (2021). Through multiple OLS regression models, it addresses three key research questions:

Does high currency volatility lead to higher currency returns?

Do changes in geopolitical risk affect currency volatility?

Can geopolitical risk and past excess returns forecast future currency volatility?

The findings suggest that geopolitical risk significantly influences FX volatility and high-minus-low returns based on currencies’ sensitivity to such risks. However, no causal link could be established between changes in geopolitical risk and FX volatility. The evidence points to geopolitical risk functioning as a short-term, rather than an idiosyncratic, risk factor in FX markets.

---

### Objective
To evaluate the impact of geopolitical risk on FX volatility and excess returns, and assess its predictive power.

### Methodology
- Data: Daily spot/forward rates for 18 USD-based currencies (Reuters, WRM, Bloomberg) + Caldara–Iacoviello GPR index.
- Portfolio Construction: High-minus-low currency baskets sorted by GPR sensitivity.
- Analysis: Lagged regression models at portfolio & currency level; controlled for momentum and carry factors.

## Tools & Technologies
- Python (Pandas, NumPy, Statsmodels, Matplotlib, Seaborn)
- Bloomberg Terminal, Refinitiv Datastream
- Econometric modelling, time series analysis
