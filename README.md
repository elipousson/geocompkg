
<<<<<<< HEAD
<!-- badges: start -->

[![R build
status](https://github.com/geocompr/geocompkg/workflows/R-CMD-check/badge.svg)](https://github.com/geocompr/geocompkg/actions)
<!-- badges: end -->
=======
[![Build
Status](https://travis-ci.org/geocompr/geocompkg.svg?branch=master)](https://travis-ci.org/geocompr/geocompkg)
>>>>>>> master

<!-- README.md is generated from README.Rmd. Please edit that file -->

# geocompkg
<<<<<<< HEAD

This is a metapackage that will install all packages used in the book
[Gecomputation with R](https://geocompr.robinlovelace.net/), the source
code of which can be found at
[github.com/Robinlovelace/geocompr](https://github.com/Robinlovelace/geocompr).
It is used to keep up-to-date solutions additional materials to
supplement the book. See [the vignettes
folder](https://github.com/geocompr/geocompkg/tree/master/vignettes) for
the source code.

## Installation

=======

This is a ‘metapackage’ support the book [Gecomputation with
R](https://geocompr.robinlovelace.net/). Installing installing it will
give you the dependencies needed to run the code in the book. The
repository also contains up-to-date solutions additional materials to
supplement the book. See [the vignettes
folder](https://github.com/geocompr/geocompkg/tree/master/vignettes) for
the source code.

## Installation

>>>>>>> master
You can install the packages needed to reproduce the code in
Geocompuation with R by installing the
[geocompkg](https://github.com/geocompr/geocompkg) package as follows:

``` r
devtools::install_github("geocompr/geocompkg")
```

If you have any issues, check-out
[Chapter 2](https://geocompr.robinlovelace.net/spatial-class.html) of
<<<<<<< HEAD
the book. You may need to install **spDataLarge** from
drat:
=======
the book. You may need to install **spDataLarge** from drat:
>>>>>>> master

``` r
install.packages("spDataLarge", repos = "https://nowosad.github.io/drat/",
                 type = "source")
```
