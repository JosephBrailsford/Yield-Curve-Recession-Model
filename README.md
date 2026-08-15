# Yield-Curve-Recession-Model

Logistic regression model estimating US recession probability from Treasury yield curve spreads (2Y,10Y)
Uses 50 years’ worth of yield curve data from the FREDAPI, finding yield curve inversions, on average, precede recessions by 16 months
Uses historical data to output a probability of recession given a value for the 2s10s spread
Generates a simple asset allocation recommendation based on the deviation of the probability from the historical probabilities
