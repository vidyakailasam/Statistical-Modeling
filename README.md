## Zillow Property Price Analysis using Bayesian Inference

This Python script utilizes the Zillow API to fetch property prices based on a given address and city/state/ZIP code. It then performs data analysis and Bayesian inference to model the distribution of property prices. Bayesian inference is conducted to estimate the parameters of the property price distribution.

### Description
- The script defines a function `fetch_property_prices()` to fetch property prices from the Zillow API.
- It then computes basic statistics such as mean, median, and standard deviation of the property prices fetched.
- The distribution of property prices is visualized using a histogram.
- Bayesian inference is performed using PyMC3 to estimate the parameters (`mu` and `sigma`) of the property price distribution.
- The script provides summaries and plots of the posterior distributions of the parameters.
