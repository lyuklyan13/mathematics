# Introduction:
Statistical distributions provide the fundamental   mathematical geometry by   whichuncertainty, random   variables, and empirical phenomena are quantified. In the  context of modern data science, computational statistics heavily relies on the Python scientific stack, specifically the scipy.stats and statsmodels libraries.
In the context of modern data science, computational statistics heavily relies on the Python scientific stack, specifically the `scipy.stats` and `statsmodels` libraries.

Based on the architectural paradigms of `scipy.stats`, distributions are abstracted into two primary classes: `rv_continuous` for continuous random variables and `rv_discrete` for discrete random variables. As established in the foundational methodologies for working with these classes, any specific distribution object initialized with shape, location (`loc`), and scale (`scale`) parameters exposes a unified functional interface.

This standardized interface includes:
- `rvs(size=N)`: Generates a random sample of size $N$.
- `pdf(x)` / `pmf(k)`: Probability Density Function (continuous) or Probability Mass Function (discrete).
- `cdf(x)`: Cumulative Distribution Function, returning the probability that the variate takes a value less than or equal to $x$.
- `ppf(q)`: Percent Point Function (inverse of CDF), returning the $q$-quantile.
- `stats(moments='mvsk')`: Returns the mean, variance, Fisher's skewness, and Fisher's kurtosis.
- `mean()`, `var()`, `std()`: Central tendency and dispersion metrics.

This report systematically details the theoretical foundations, practical applications, and Python implementations of all requested distributions, expanding upon their utility in Data Science and Engineering.