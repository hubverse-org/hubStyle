
<!-- README.md is generated from README.Rmd. Please edit that file -->

# hubStyle <img src="man/figures/logo.png" align="right" height="131" alt="" />

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/hubStyle)](https://CRAN.R-project.org/package=hubStyle)
<!-- badges: end -->

hubStyle provides a custom pkgdown template for hubverse packages. We
use this to render our R package sites at
<https://github.com/Infectious-Disease-Modeling-Hubs>. Please don’t use
it for your own package if it’s not a hubvserse package.

Inspired by [rotemplate](https://github.com/ropensci-org/rotemplate).
\## Installation

You can install the development version of hubStyle from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("Infectious-Disease-Modeling-Hubs/hubStyle")
```

## Using the hubStyle template

To include the hubStyle template in your pkgdown site, add the following
to your `_pkgdown.yml` file:

``` yaml
template:
  package: hubStyle
```

You will also need to add the following to your `DESCRIPTION` file:

``` yaml
Config/Needs/website: Infectious-Disease-Modeling-Hubs/hubStyle
```

## Code of Conduct

Please note that the hubStyle package is released with a [Contributor
Code of Conduct](.github/CODE_OF_CONDUCT.md). By contributing to this
project, you agree to abide by its terms.

## Contributing

Interested in contributing back to the open-source Hubverse project?
Learn more about how to [get involved in the Hubverse
Community](https://hubdocs.readthedocs.io/en/latest/overview/contribute.html)
or [how to contribute to the hubStyle package](.github/CONTRIBUTING.md).
