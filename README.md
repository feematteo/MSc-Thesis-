# MSc-Thesis-
This research aims to analyze the outperformance of a selected set of high-quality stocks relative to the S&P 500 benchmark, summarized through the VGT ETF. We employ ARMA and ARCH models with non-Gaussian distributions to forecast conditional volatility and returns, ultimately estimating the optimal non-Gaussian Value at Risk (VaR) and Expected Shortfall (ES).

The methodology begins with an in-depth analysis of the financials of three representative stocks from the VGT index—NVIDIA, Microsoft, and Apple. We investigate their performance to understand the drivers behind their outperformance, utilizing various financial indicators, including earnings per share (EPS) growth, return on invested capital (ROIC), and profit margins.

Subsequently, we identify the most suitable distributions for the historical financial time series and develop algorithms to fit the optimal ARMA and ARCH models based on the Akaike Information Criterion (AIC). We compare multiple models, combinations, and distributions to determine the best-fitting approach.

The results indicate that the APARCH(1,1) model with a skewed t-distribution is the most effective for our VGT indicator. In the context of risk modeling, the VaR calculated with a skewed t-distribution demonstrates superior efficiency, while the Expected Shortfall calculated using a generalized error distribution (GED) proves to be the most effective.

In conclusion, advanced ARCH models and non-Gaussian distributions facilitate accurate forecasting of conditional volatility and returns. Our findings suggest that employing non-Gaussian distributions in ARCH modeling yields more efficient estimates of VaR and Expected Shortfall compared to the conventional normal distribution.
