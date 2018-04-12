
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ecdmdata

[![Project Status: Active - The project has reached a stable, usable
state and is being actively
developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Travis-CI Build
Status](https://travis-ci.org/tmsalab/ecdmdata.svg?branch=master)](https://travis-ci.org/tmsalab/ecdmdata)
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/ecdmdata)](https://cran.r-project.org/package=ecdmdata)
[![CRAN RStudio mirror
downloads](http://cranlogs.r-pkg.org/badges/ecdmdata)](http://www.r-pkg.org/pkg/ecdmdata)

The goal of `ecdmdata` is to provide a set of an example assessment data
sets for psychometric modeling.

## Installation

You can install `ecdmdata` from github with:

``` r
# install.packages("devtools")
devtools::install_github("tmsalab/ecdmdata")
```

## Data Sets Included

  - Examination for the Certificate of Proficiency in English (ECPE),
    Templin, J. and Hoffman, L. (2013).
      - `items_ecpe`, N = 2922 subject responses to J = 28 items.
      - `qmatrix_ecpe`, J = 28 items and K = 3 traits.
  - Fraction Addition and Subtraction, Tatsuoka, K. K. (1984).
      - `items_fractions`: N = 536 subject responses to J = 20 items.
      - `qmatrix_fractions`: J = 20 items and K = 8 traits.
  - Revised PSVT:R, Culpepper and Balamuta (2013).
      - `items_spatial`: N = 516 subject responses to J = 30 items.
