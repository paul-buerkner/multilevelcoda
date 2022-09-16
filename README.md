<!-- badges: start -->
[![lifecycle](https://lifecycle.r-lib.org/articles/figures/lifecycle-experimental.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
<!-- badges: end -->

## Overview

This package provides functions to model compositional data in 
a multilevel framework using full Bayesian inference.
It integrates the principes of Compositional Data Analysis (CoDA) 
and Multilevel Modelling and supports both compositional data as 
an outcome using multivariate models and compositional data as 
predictors of other multilevel outcomes.

## Installation

The current developmental version can be downloaded from github via

```r
if (!requireNamespace("remotes")) {
  install.packages("remotes")
}
remotes::install_github("florale/multilevelcoda")
```

Because multilevelcoda is built on brms, which is based on Stan, a C++ compiler is required. 
The program Rtools (available on https://cran.r-project.org/bin/windows/Rtools/) comes with a C++ compiler for Windows. On Mac, Xcode is required. For further instructions on how to get the compilers running, see the prerequisites section on https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started.

Release of `multilevelcoda` to CRAN is planned at a later date.

## Resources

You can learn about the package from these vignettes:

- [Introduction to Compositional Multilevel Modelling](https://florale.github.io/multilevelcoda/articles/introduction.html)
- [Multilevel Models with Compositional Outcomes](https://florale.github.io/multilevelcoda/articles/comp-outcome.html)
- [Multilevel Models with Compositional Predictors](https://florale.github.io/multilevelcoda/articles/comp-predictor.html)
- [Compositional Multilevel Substitution Models](https://florale.github.io/multilevelcoda/articles/substitution-model.html)
