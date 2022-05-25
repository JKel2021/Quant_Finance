# Quant_Finance
PDE solver from grad project using explicit FDM. The latest version was accidentally deleted. However, on inspection I believe the later versions merely include code for a smaller step size and therefore greater accuracy.

VWAP code is looking at the distribution of hourly trading volumes among Pfizer, Apple and JP Morgan. This was another assignment for Uni.

Asian Option Monte Carlo simulated stock price paths and prices both an arithmetic and geometric asian option. Another assignment for Discrete time financial modelling at Uni.

1st attempt at a semi-implicit PDE solver. This is using the Crank-Nicolson method. At this stage the error is staying relatively constant. Derivative approximations are a forward time and the spatial derivatives are an average across the time domain.