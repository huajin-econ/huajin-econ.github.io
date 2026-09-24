---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<h2 style="border-bottom: 1px solid #ddd; padding-bottom: 0.3em;">Job Market Paper</h2>

**Estimation of BLP Models with High-dimensional Controls**

<details>
<summary>Full abstract</summary>

This study proposes a framework for estimating demand in differentiated product markets with high-dimensional product characteristics, building upon the seminal Berry, Levinsohn, and Pakes (1995) model, using market level data. We allow for a very large set of potential product characteristics, where the number of characteristics may exceed the number of market observations. Our contributions are twofold. First, we establish a general estimation theory for BLP models featuring high-dimensional nuisance parameters. We propose a Neyman orthogonal estimator specifically adapted to this framework, utilizing machine learning techniques, such as Lasso, to construct nuisance parameter estimators that are plugged into the Neyman orthogonal estimator. This approach offers a significant advantage: it achieves root-T asymptotic normality for parameters of interest—such as the price coefficient and price heterogeneity—even when nuisance parameters are estimated at slower rates due to their high-dimensionality. Second, we apply this theory to a specialized BLP model under approximate sparsity, developing an estimation strategy for the high-dimensional nuisance parameters. The approximate sparsity condition posits that nuisance parameters can be controlled, up to a small approximation error, by a small and unknown subset of variables, which makes the recovery of nonzero parameters feasible by enabling nuisance parameter estimators to converge at the required rates. The practical performance of the method is evaluated through comprehensive Monte Carlo simulations, which demonstrate its efficacy in finite samples. We apply the method to analyze the juice market using Kantar's Worldpanel Take Home data as an empirical illustration.

</details>


<h2 style="border-bottom: 1px solid #ddd; padding-bottom: 0.3em;">Working Papers</h2>

**Conditional-Moment Estimation and Inference in the BLP Model** (with Rui Sun and Tian Xie)

<details>
<summary>Full abstract</summary>

The random-coefficient demand model of Berry, Levinsohn, and Pakes (1995) is commonly estimated by the generalized method of moments (GMM), using an unconditional moment restriction with a fixed set of instruments. Identification of the model, however, rests on a conditional moment restriction. The two are not equivalent: the unconditional restriction may admit additional parameter values. We construct a counterexample in which the model is identified by the conditional restriction yet standard GMM is not, even with the optimal instrument. Building directly on the identifying restriction, we propose a two-step estimator, following Ai and Chen (2003), that first estimates the relevant conditional expectations nonparametrically and then selects the structural parameters by a conditional-variance-weighted minimum-distance criterion; standard GMM is recovered as the special case of a linear projection onto finitely many instruments. We establish root-T asymptotic normality for the proposed estimator, and we develop the theory for both kernel and series implementations of the first stage. The two implementations share a common limiting distribution, attaining the semiparametric efficiency bound under certain conditions. Simulation evidence illustrates the consequences of the identification gap and demonstrates that the proposed estimator outperforms standard GMM in finite samples.


</details>

**Local Polynomial Estimation in Irregular Correlated Random Coefficient Panel Data Models** (with Yelong Chen and Yuxuan Ren)

<details>
<summary>Full abstract</summary>

We study estimation of the average partial effect (APE) in an irregular correlated random coefficients panel data model in which the time dimension equals the number of random coefficients, T equals p, and the density function is degenerate. We extend Graham and Powell (2012) in two directions. First, we allow the density of the determinant of the individual regressor matrix to vanish or diverge at the origin at a polynomial rate of order a, with a greater than minus one, and show that the aggregate time effects and the APE remain identified for every such a; extending earlier work studying the case where a equals zero. Second, we propose a three-step estimator: a local polynomial regression of order m over the stayers for the time effects; a local polynomial fit of the conditional mean coefficient just outside the trimming threshold; and an imputation step that extrapolates the latter into the stayer region rather than discarding stayers. We establish joint asymptotic normality in three regimes determined by the sign of a, and obtain a convergence rate approaching n to the power of negative (m+1)/(2m+3) when a equals zero, against the cube root of n rate of Graham and Powell (2012), whose estimator is the special case where m and a are both zero. The results show that smoothness of the underlying conditional expectations can be traded for a faster convergence rate in irregularly identified models. Simulations confirm lower bias and root mean squared error across designs. We redo the over-identification analysis of a markup model in Raval (2023) where we allow for correlated random elasticity.

</details>

**Non-Asymptotic Convergence Rates for High-Dimensional Penalized Estimators** (with Dennis Kristensen)

<h2 style="border-bottom: 1px solid #ddd; padding-bottom: 0.3em;">Selected Work in Progress</h2>

<!--**Uniform Inference on Structural Disparity in Covariance Transfer Learning** (with Rui Sun) -->

**High-Dimensional GMM Estimation** (with Dennis Kristensen)

**Flexible Nonparametric Estimation of Random Coefficients** (with Yihan Li and Tian Xie)

