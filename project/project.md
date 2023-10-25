# Course Project 

#### Proposal due: 2023-11-02 @ 11:59PM
#### Presentation: 2023-12-12 and 2023-12-14 (tentative)

This page lists some potential course project ideas. 
The goal of the project is to review recent developments in statistical computing, implement in *Julia*, and compare the related methods. 
Two or three students should team up to accomplish the goal. Each team may propose a paper on its own or choose one paper from the list below (no duplication is allowed) and submit a project proposal by the due date.

## Stochastic optimization

In large-scale optimization, often the objective function or its derivatives can only be estimated. In this case, *stochastic* methods come to rescue. Recent developments include:

<!--
* Chen, H., Lu, W., & Song, R. (2021). Statistical Inference for Online Decision Making via Stochastic Gradient Descent. Journal of the American Statistical Association, 116(534), 708–719. https://doi.org/10.1080/01621459.2020.1826325
-->

* Han, R., Luo, L., Lin, Y., & Huang, J. (2023). Online Inference with Debiased Stochastic Gradient Descent. Biometrika, To appear. https://doi.org/10.1093/biomet/asad046
	
* Yu, G., Yin, L., Lu, S., & Liu, Y. (2020). Confidence Intervals for Sparse Penalized Regression With Random Designs. Journal of the American Statistical Association, 115(530), 794–809. https://doi.org/10.1080/01621459.2019.1585251


<!--
## Optimal Design

In design of experiments, optimal designs are a class of experimental designs that are optimal with respect to some statistical criterion. Recent algorithmic developments include:

* Schmidt, D. (2019). Characterization of $c$-, $L$- and $\phi_k$-optimal Designs for a Class of Non-Linear Multiple-Regression Models. Journal of the Royal Statistical Society Series B: Statistical Methodology, 81(1), 101–120. https://doi.org/10.1111/rssb.12292

* Yue, Yuguang, Lieven Vandenberghe, and Weng Kee Wong (2019). "T-optimal designs for multi-factor polynomial regression models via a semidefinite relaxation method." Statistics and Computing 29(4), 725-738.
-->

## Mixed integer optimization for model selection

Model selection is a difficult statistical problem with an exponential complexity. A typical example is high-dimensional linear model with L0 penalty. Nonetheless, recent progress in mixed integer optimization (MIO) has made large-scale problems tractable. They include:

<!--* Bertsimas, Dimitris, and Bart Van Parys (2020). "Sparse high-dimensional regression: Exact scalable algorithms and phase transitions." Annals of Statistics 48(1), 300-323.

* Bertsimas, Dimitris, Angela King, and Rahul Mazumder (2016). "Best subset selection via a modern optimization lens." Annals of Statistics 44(2), 813-852.

* Hastie, Trevor, Robert Tibshirani, and Ryan Tibshirani (2020). "Best subset, forward stepwise or lasso? Analysis and recommendations based on extensive comparisons." Statistical Science 35(4), 579-592.
	+ R code available at <https://github.com/ryantibs/best-subset/>

* Dedieu, A., Hazimeh, H., & Mazumder, R. (2021). Learning Sparse Classiﬁers: Continuous and Mixed Integer Optimization Perspectives. Journal of Machine Learning Research, 22, 1--47.
-->
		
* Hazimeh, H., Mazumder, R., & Radchenko, P. (2023). Grouped variable selection with discrete optimization: Computational and statistical perspectives. The Annals of Statistics, 51(1). https://doi.org/10.1214/21-AOS2155


<!--
## Fused lasso and total variation penalty

Total variation (TV) penalty has been popular in image processing since the work of Rudin, L. I., Osher, S. and Fatemi, E. (1992), "Nonlinear total variation based noise removal algorithms," Physica D: 60(1), 259–268. This penalty has become popularized in statistics under the name "fused lasso," due to Tibshirani, R. , Saunders, M., Rosset, S., Zhu, J., and Knight, K. (2005), "Sparsity and Smoothness Via the Fused Lasso," Journal of the Royal Statistical Society, Series B, 67, 91–108; and Tibshirani, R. J., and Taylor, J. (2011), "The Solution Path of the Generalized Lasso," Annals of Statistics, 39, 1335–1371. TV penalty is becoming increasingly popular in other estimation problems than regression:
Tang, P., Wang, C., Sun, D., & Toh, K.-C. (2020). A Sparse Semismooth Newton Based Proximal Majorization-Minimization Algorithm for Nonconvex Square-Root-Loss Regression Problems. Journal of Machine Learning Research, 21, 1--38.

* Bassett, Robert, and James Sharpnack. "Fused density estimation: theory and methods." Journal of the Royal Statistical Society -- Series B (2019): 839-860. 

* Tan, K. M. and Witten, D. "Statistical properties of convex clustering." Electron. J. Statist. (2015): 2324–2347. 
-->

## Algorithms for square-root lasso

The square-root lasso has a theoretical advantage over the plain lasso in easing tuning parameter selection by dispensing with the need of knowing the noise variance. However, fitting a square-root lasso model is computationally more challenging due to the nondifferentiability of the loss function. Recent computational developments include:

* Chu, H. T. M., Toh, K.-C., & Zhang, Y. (2022). On Regularized Square-root Regression Problems: Distributionally Robust Interpretation and Fast Computations. Journal of Machine Learning Research, 23, 1--39.

* Tang, P., Wang, C., Sun, D., & Toh, K.-C. (2020). A Sparse Semismooth Newton Based Proximal Majorization-Minimization Algorithm for Nonconvex Square-Root-Loss Regression Problems. Journal of Machine Learning Research, 21, 1--38.

* Li, X., Jiang, H., Haupt, J., Arora, R., Liu, H., Hong, M., & Zhao, T. (2020). On Fast Convergence of Proximal Algorithms for SQRT-Lasso Optimization: Don't Worry About its Nonsmooth Loss Function. Proceedings of The 35th Uncertainty in Artificial Intelligence Conference, 49–59. https://proceedings.mlr.press/v115/li20a.html


