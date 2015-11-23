![impcov R package](impcov_logo.png)
======================================================================
> Fast, Robust and Tunning-Free Regularized Covariance Matrix Estimators

## How To Install?
```r
library('devtools')
install_github(repo = "davidnexer/impcov")
```

## Regularization Methods
* Ledoit-Wolf (LW) Shrinkage Estimator  [1]
* Oracle Approximating Shrinkage (OAS) Estimator [2]
* Schafer-Strimmer (SS) Shrinkage Estimator [3]
* Reduced-Rank Estimator based on Probabilistic PCA (PPCA) [4]
* Sparse Reduced-Rank Estimator based on Sparse Principal Components (SPC) [5]
* Sparse Estimator based on Penalized Likelihood with Quadratic Approximation (QUIC) [6]

## Coming Soon
* Regularization of a covariance matrix estimate given by the user;
* Weighted estimation based on sample weights given by the user.

### References
[1] Ledoit, Olivier, and Michael Wolf. "A well-conditioned estimator for large-dimensional covariance matrices." Journal of multivariate analysis 88.2 (2004): 365-411.

[2] Chen, Yilun, et al. "Shrinkage algorithms for MMSE covariance estimation." Signal Processing, IEEE Transactions on 58.10 (2010): 5016-5029.

[3] Schäfer, Juliane, and Korbinian Strimmer. "A shrinkage approach to large-scale covariance matrix estimation and implications for functional genomics." Statistical applications in genetics and molecular biology 4.1 (2005).

[4] Tipping, Michael E., and Christopher M. Bishop. "Probabilistic principal component analysis." Journal of the Royal Statistical Society: Series B (Statistical Methodology) 61.3 (1999): 611-622.

[5] Witten, Daniela M., Robert Tibshirani, and Trevor Hastie. "A penalized matrix decomposition, with applications to sparse principal components and canonical correlation analysis." Biostatistics (2009): kxp008.

[6] Hsieh, Cho-Jui, et al. "Sparse inverse covariance matrix estimation using quadratic approximation." Advances in Neural Information Processing Systems. 2011.
