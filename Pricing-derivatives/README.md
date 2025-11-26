**Pricing-derivatives :** 

**exotic/main_complete_notebook.ipynb**
 1. Geometric Asian Option - Closed form,  Exact binomial, Monte Carlo (BSM, Merton, Heston), PDE -Crank Nicholson(BSM), Characteristic Function -COS (BSM)






**vanilla/main_complete_notebook.ipynb**
 Pricing of vanilla options (call and put from yfinance) with European/American/Bermudan exercises using different methods:

  1. Exact Binomial Tree - Cox Ross Rubinstein | 
  2. Monte Carlo : Euler-Maruyama discertization of BTree | Black-Scholes | Merton Jump diffusion | Heston model
  3. Closed form solutions : Black-Scholes (1973) | Merton Jump Diffusion (1976)| Heston (1993)
  4. Numerical solutions : Black-Scholes | Merton Jump Diffusion | Heston
     
         1. P(I)DE : (Implicit, Explicit, Crank-Nicholson + Quadrature/FFT)
         2. Characteristic Function : Carr Madan FFT, Fourier-Cosine expansion

**Wherever possible "Greeks" available.

**Exercise - American/Bermudan - Monte Carlo**
 1. longstaff schwartz : Linear regression
 2. Random Forest
 3. Neural Network (underprocess)
 4. Nested Monte Carlo (underprocess)

**Parameters**
 1. For stochastic modelling, initial parameters (mu, sigma etc) are abstracted from fitted log return of historical stock prices depending on their probability   distribution. eg. GBM/Btree model prices have lognormal distribution and Merton jump diffusion model have a poisson weighted lognormal distribution.
 2. For Hestion, minimizing log loss from (calculated - historical option price). Particle swarm optimization - gradient free heuristic optimization  

**Data**
 The data used is from yfinance.

        
