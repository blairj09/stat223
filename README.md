# stat223

This package contains tutorials and data used in teaching Stat 223.

## Installation

This package can be installed via the following commands:

``` r
# install.packages("remotes")
remotes::install_github("blairj09/stat223")
```

## Learnr
This package takes advantage of [`learnr`](https://rstudio.github.io/learnr/index.html) to create interactive tutorials. A tutorial on permutation tests can be viewed via the following:

``` r
learnr::run_tutorial("permutation", "stat223")
```
