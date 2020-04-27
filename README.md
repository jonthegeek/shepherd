
<!-- README.md is generated from README.Rmd. Please edit that file -->

# shepherd <img src='man/figures/logo.svg' align="right" height="300" />

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
<!-- badges: end -->

The goal of shepherd is to make it as easy as possible to deploy an R
script as an AWS Lambda endpoint. The first version of this package will
*only* support base R. We hope to add support for further packages soon
afterward.

## Installation

You can install the released version of shepherd from
[CRAN](https://CRAN.R-project.org) with:

``` r
# No you can't.
# install.packages("shepherd")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("jonthegeek/shepherd")
```

## Example

NONE OF THIS EXISTS YET. The workhorse function is `deploy_script_api`.
This function creates an AWS Lambda instance with the necessary API to
invoke your function.

``` r
deploy_script_api(path = "my_script.R")
```

## Code of Conduct

Please note that the shepherd project is released with a [Contributor
Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
