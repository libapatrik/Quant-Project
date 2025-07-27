# Welcome to my Project

## Stage 1
  - Using Carr-Madan, CONV, COS methods (ch.f. methods) for recovery of cumulative distribution function (CDF) and probability density function (PDF) given characteristic function (i.e. Black-Scholes, Heston model)
## Stage 2
  - Using ch.f. methods for pricing vanilla options under the Heston model.
  - Derive Heston model's ch.f. $\rightarrow$ COS method $\rightarrow$ Price Option  
      - Add other models: Variance Gamme, NIG, CGMY.
- Replicates: Fang, F., & Oosterlee, C. W. (2008). A novel pricing method for European options based on Fourier‑cosine series expansions (the COS method). SIAM Journal on Scientific Computing, 31(2), 826–848.
  - link: http://ta.twi.tudelft.nl/mf/users/oosterle/oosterlee/COS.pdf
## Stage 3
  - Can we make use of ch.f. methods in the rough volatility setup - under rough Heston, rough Bergomi models?

- P. Pezzoli Frigerio. Efficient option pricing under rough volatility models (MSc thesis). TU Delft. Link: https://repository.tudelft.nl/record/uuid:332fcf38-73eb-4da6-8640-09ef4ae5cc74

#### For much later
Market Making under Rough Volatility

1) Rough Volatility
  - If we zoom in sufficiently, will volatility look smooth? 
  - A: No, i.e. no matter how much we zoom in, the volatility will remain jagged.
  - Characterised by the Hurst exponent (H).
    - H = 0.5, we get standard Brownian motion.
    - H < 0.5, we get rough behaviour.
    - Empirically, H ~ 0.1 for real volatility indicating extreme roughness.

2) Market Making
  - MM needs to constantly provide/update bid and ask quotes based on their prediction of future volatility.
  - If volatility is rough, recent price movements contain much more information about immediate future volatility than traditional models suggest.
  - If MM uses smooth volatility models, he does not capture the complete information.
