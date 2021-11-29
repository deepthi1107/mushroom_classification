## Kernel Ridge Regression "KRR" 
## [Click here to listen the audio]()

Kernel ridge regression is a non-parametric form of ridge regression. The aim is to learn a function in the space induced by the respective kernel k by minimizing a squared loss with a squared norm regularization term.

Gaussian Kernel Regression is a regression technique which interestingly does not require any iterative learning (such as gradient descent in linear regression). 

**How does kernel ridge regression work**

Kernel ridge regression (KRR) combines ridge regression (linear least squares with l2-norm regularization) with the kernel trick. It thus learns a linear function in the space induced by the respective kernel and the data. For non-linear kernels, this corresponds to a non-linear function in the original space.

