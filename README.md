# \## 📈 Quantitative Time Series Analysis

# 

# <img src="https://pbs.twimg.com/media/GIbAJpcXAAEu7hw.png" height="300">

# 

# \### Overview

# 

# This project focuses on test the hypothesis that the solar activity can affect the aggregate risks preference (and, thereby, the S\&P 500 Index) using quantitative techniques to identify statistical relationships and dependencies across time between them. 

# 

# \### About the Data

# 

# We collected S\&P 500 Index via Web Scraping with Selenium and Python and Monthly Mean of Sunspots from \[SIDC](\[https://example.com](https://www.sidc.be/SILSO/datafiles))

# \#### Original Series

# !\[Temporal Evolution of the Series](temporal\_evolution\_series.png)

# \#### Differenced Series

# !\[Temporal Evolution of the Differenced Series](temporal\_evolution\_differenced\_series.png)

# 

# \### Methods

# 

# The project implements a set of quantitative techniques commonly used in time series analysis, including:

# 

# \- Differencing to achieve stationarity

# \- Correlation and cross-correlation analysis

# \- Implementation of Vector Autoregressive Model to analyse dependencies along lags.

# \- Bootstrap Method to resample and refit models to robust inference.

# \- Causality Tests

# 

# \### Inference

# 

# The metrics used to 

# 

# \* Mean, median, and variance of the time series

# \* Correlation and cross-correlation coefficients

# \* Error-based measures (e.g., Mean Squared Error)

# \* Stability and consistency metrics across time

# 

# !\[Table with Statistics of Coefficients](table\_stats\_coef.png)

# 

# \#### Correlation and cross-correlation analysis

# !\[Autocorrelation](autocorrelation\_series.png)

# 

# \#### Marginal Density of Coefficients

# 

# !\[Marginal Density of Coefficients](marginal\_density\_coef.png)

# 

# \### Conclusion

# 

# We modeled the difference in S\&P 500 Index (named as price\_lag1) against the difference in monthly mean sunspots (named as sunspots\_lag1) and our conclusion is that there is neither correlation and causality between them, i.e., the difference in in monthly mean sunspots does not affect significantly the differente in S\&P 500 Index. Therefore, I would not allocate capital to this signal.

# 

# \### Plus

# 

# I modeled the temporal behavioral of Monthly Mean of Sunspots with periodic functions (sin and cos) and predicted the next 60 months.

# 

# !\[Prediction of Monthly Mean of Sunspots](prediction\_sunspots\_series.png)

# 



