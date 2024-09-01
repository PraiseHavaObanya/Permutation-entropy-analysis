# Permutation-entropy-analysis
**Description**
Permutation entropy is a time series analysis tool which was introduced by Bandt and Pompe in 2002 
for the measurement of the complexity of a given time series. It is represented by the variable _H_.
In 2004, Lamberti and others extended the method with the introduction of the intensive statistical variable _C_.
The introduction of the _C_ variable is the basis of the the complexity-entropy plane (_CH_-plane) used to dinstinguish
between stochastic (random) and chaotic (deterministic) properties.

**Functions and Codes**
The codes are MATLAB codes, and the functions were created by the author.
The main functions are:
1. the _H_ functon for the calculation of permutation entropy, _H_
2. the _C_ function for the calculation of the intensive statistical variable, _C_
3. the minimum curve function for the derivation of the theoretical minimum complexity  curve, required in the construction of a complexity-entropy plane (_CH_-plane), and
5. the maximum curve function for obtaining the theoretical maximum complexity curve, which is also required to plot a _CH_-plane.

Other functions are the permutation entropy analysis (PEA) function, which can be used to obtain both _H_ and _C_ simultaneously and the curves 
function which merges the minimum curve function and the maximum curve function.

Note that this repository contains illustrations of how the codes work. The illustrations are as follows:

1. Chapter1 CHplane: Shows how _CH_-planes are obtained.
2. Chapter2 JSE Nasdaq Annual H: To show how _H_ values can be obtained for a single time series.
3. Chapter3 Bitcoin Volatility Annual H: Shows how _H_ values can be obtained for multiple time series simultaneously.
4. Chapter4 H Changes to Fault Introduction: Shows how _H_ changes in a time series due to deviations from normality.

**Authorship**

These codes were written by Praise Otito Obanya and were used in her thesis titled, "Permutation entropy: Applications to industries and financial markets"

**Acknowledgements**

Promoters: Carel Olivier, Tanja Verster and Modisane Seitshiro
