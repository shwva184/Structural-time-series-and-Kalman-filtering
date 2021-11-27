# Structural-time-series-and-Kalman-filtering

The data is taken from
https://climate.nasa.gov/vital-signs/sea-level/

Steps performed :
1) Setting up a structural state space model ( finding the trend and seasonality)
2) Kalman filtering for the structural model
3) Using the Kalman filter to infer the states of the structural time series applied to the sealevel data
4) Identifying the noise variances using the EM algorithm and kalman smoother
5) Reruning the Kalman filter to compute a long range prediction for the validation data points

