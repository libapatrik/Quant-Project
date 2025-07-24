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
