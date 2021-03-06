<!-- README.md is generated from README.Rmd. Please edit that file -->
An RStudio addin for roxygen2 code blocks
=========================================

[![Build Status](https://travis-ci.org/csgillespie/roxygen2Comment.png?branch=master)](https://travis-ci.org/csgillespie/roxygen2Comment) [![CRAN](http://www.r-pkg.org/badges/version/roxygen2Comment)](http://cran.rstudio.com/package=roxygen2Comment)

RStudio addins let you execute a bit of R code or a Shiny app through the RStudio IDE, either via the Addins dropdown menu or with a keyboard shortcut. This package contains an RStudio addin for commenting roxygen2 code.

This package can be installed via

``` r
devtools::install_github("csgillespie/roxygen2Comment")
```

Running addins
--------------

After installing the package, the *Addins* menu toolbar will be populated with the new, exported addin. The addin will work exactly like the RStudio keyboard shortcut for commenting.

-   If you execute the addin on standard code, it will add `#'` to the start of the line.
-   If you execute the addin on an roxygen2 comment, it will remove `#'`

Manage your addins
------------------

See my other [package](https://github.com/csgillespie/addinmanager) for conviently adding and removing RStudio addins.

Other information
-----------------

-   If you have any suggestions or find bugs, please use the github issue tracker.
-   Feel free to submit pull requests for new addins.
