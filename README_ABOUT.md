1. Dataset Generation and Distribution Fitting for Order Statistics

This project explores synthetic dataset generation and statistical distribution fitting for insurance claim-size modelling. Implemented in Julia, it generates synthetic claim data using five probability distributions: Normal, Log-Normal, Exponential, Pareto and Weibull.

The generated data is evaluated against candidate distributions using the Akaike Information Criterion (AIC) and Kolmogorov–Smirnov (KS) test to identify suitable distribution fits. The project also studies the mathematical foundations of order statistics, including the distributions of the i-th smallest observation and joint distributions of multiple order statistics.

The resulting framework provides a foundation for generating controlled synthetic datasets and exploring stress-testing scenarios by varying distribution choices, weights and parameters.






2. Approximate Bayesian Computation for Insurance Loss Models

This project investigates Approximate Bayesian Computation (ABC) for fitting and comparing insurance loss models when conventional likelihood-based inference is computationally difficult or analytically intractable.

The implementation explores simulation-based Bayesian parameter estimation, using summary statistics and distance measures to compare simulated observations with observed insurance data. It examines claim frequency and claim severity models, dependence between these components, aggregated claim data and time-dependent Poisson arrival models.

The study also compares ABC with Maximum Likelihood Estimation (MLE) and evaluates model fit using posterior estimates, Q-Q plots and the Bayesian Information Criterion (BIC). The findings highlight the importance of informative frequency-based summary statistics and the trade-off between computational cost and inference accuracy.
