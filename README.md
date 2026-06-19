# Econ 3650: Advanced Econometrics I

This repository contains course materials for **Econ 3650: Advanced Econometrics I** at the University of Pittsburgh.

The course is designed for second-year PhD students in economics. It provides an updated treatment of advanced econometric methods with an emphasis on the connection between econometric theory, identification, computation, and empirical implementation. No previous familiarity with nonparametric or semiparametric methods is assumed.

The course combines theoretical foundations with hands-on implementation using Julia, Python, or R. Problem sets and computational exercises are designed to help students understand how modern econometric methods work in practice rather than treating them as black boxes.

## Course Modules

### Module 1: Foundations — Identification and Nonparametric Estimation

This module introduces core concepts in identification, estimation, and flexible nonparametric methods. Topics include parameters, estimands, estimators, conditional expectations, kernel regression, local linear regression, bandwidth choice, cross-validation, the curse of dimensionality, and series/sieve estimation.

### Module 2: Semiparametric Estimation and Modern Methods

This module studies econometric models that combine finite-dimensional parameters with infinite-dimensional nuisance functions. Topics include partially linear models, residualization, average derivative estimation, generated regressors, regularization bias, Neyman orthogonality, cross-fitting, and double/debiased machine learning.

### Module 3: Identification and Partial Identification

This module focuses on what can be learned from data under different assumptions. Topics include point identification, rank and completeness conditions, moment restrictions, conditional moments, identified sets, sharp bounds, outer bounds, missing data, interval data, treatment response, moment inequalities, confidence regions for set-identified parameters, and random set methods.

### Module 4: Structural Estimation with IO Applications

This module applies the tools developed earlier in the course to structural econometric models, with emphasis on industrial organization. Topics include structural primitives, equilibrium, counterfactuals, moment-based estimation, likelihood, simulation, indirect inference, discrete choice demand, differentiated products demand, BLP, price endogeneity, elasticities, merger counterfactuals, production function estimation, dynamic discrete choice, entry games, multiple equilibria, and moment inequalities.

## Teaching Goals

* Build a foundation in flexible nonparametric and semiparametric methods.
* Understand the distinction between estimation, identification, and inference.
* Learn how to estimate finite-dimensional parameters in the presence of flexible nuisance functions.
* Use computation to clarify theoretical concepts such as bias, variance, tuning, identification, and counterfactual analysis.
* Understand what can still be learned when assumptions are not strong enough to deliver point identification.
* Connect econometric theory to structural applications in industrial organization.
* Implement advanced estimators using Julia, Python, or R.
* Read modern econometric papers with a clearer understanding of their identification arguments, estimation strategies, and computational choices.

## Course Work

Grading will be based on **four problem sets** and a **final project**.

The problem sets will combine theory, computation, and applications. The final project will ask students to apply tools from the course to an empirical, computational, theoretical, or replication-based question.


## Software

Students may use Julia, Python, or R. Course examples will emphasize reproducible workflows using notebooks and scripts.

Recommended tools include:

* Julia or Python
* Jupyter notebooks or VS Code
* Git and GitHub
* Standard packages for numerical computation, optimization, simulation, and data analysis

## Course Theme

The central goal of the course is to understand how econometric theory becomes empirical practice. Students will learn how assumptions define what is identified, how estimators approximate identified objects, and how computation allows these methods to be implemented in applied economic research.
