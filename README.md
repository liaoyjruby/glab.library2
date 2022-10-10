
<!-- README.md is generated from README.Rmd. Please edit that file -->

# glab.library2

<!-- badges: start -->

[![R-CMD-check](https://github.com/liaoyjruby/glab.library2/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/liaoyjruby/glab.library2/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

Library of useful functions and R scripts for data mining.

This is a clean (remastered?) version of
[graeberlab-ucla/glab.library](https://github.com/graeberlab-ucla/glab.library)
according to [Hadley Wickham’s best practices for R Package
development](https://r-pkgs.org/).

## Installation

You can install the development version of glab.library2 from
[GitHub](https://github.com/) with:

``` r
if (!require("devtools", quietly = TRUE))
    install.packages("devtools")

devtools::install_github("liaoyjruby/glab.library2")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(glab.library2)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/v1/examples>.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
