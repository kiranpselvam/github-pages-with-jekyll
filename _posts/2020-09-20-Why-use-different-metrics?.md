---
title: "Why use different metrics?"
date: 2020-09-20
---
For the same problem i.e. the same function or response, RMSE from different DoE instances (of same sample size) can be compared without any issue. 
When sample sizes are different, for the same function or response, the expectation is for RMSE to go down as sample size increases and the magnitude of RMSE between these differently sized DoE instances can still be compared. It makes sense to compare them directly.
But to compare across different functions, RMSE cannot be used directly. Because the range and magnitude of responses need not be same. Hence you normalize using the range of the observed values or mean of the observed values. This necessitates NRMSE.

Correlation coefficient measures the linearity between predicted and observed values. It does not require any normalization. 

Sometimes, despite RMSE being low, you may get low correlation. When does that happen?
