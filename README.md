
# ryx

<!-- badges: start -->
<!-- badges: end -->

The goal of ryx is to help users to learn about the correlation among variables of a data set.

<img src="tools.jpg" width="200" />

## Installation

You can install the development version of ryx like so:

``` r
if(!require(remotes)){
  install.packages("remotes")
}
remotes::install_github("yuanmianbao/new_ryx")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(ryx)
library(MASS)
myryx<- ryx(Boston, "medv")
print(myryx)
plot(myryx)
summary(myryx)
```

# new_ryx
