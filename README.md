Paper supplementary material
================

# Introduction

The supplementary material for the lancet paper looking at how different
service components effect key clinical outcomes and health care use. Add
in some text to talk about what we’re doing in the paper and what this
document is going to show

# Library

These are the packages that were used in the analysis of the data.
Please note, the version numbers might be different, but the methods are
still the same.

``` r
library(tidyverse)
```

    ## Warning: package 'tidyverse' was built under R version 4.3.1

    ## Warning: package 'ggplot2' was built under R version 4.3.1

    ## Warning: package 'tibble' was built under R version 4.3.1

    ## Warning: package 'tidyr' was built under R version 4.3.1

    ## Warning: package 'readr' was built under R version 4.3.1

    ## Warning: package 'purrr' was built under R version 4.3.1

    ## Warning: package 'dplyr' was built under R version 4.3.1

    ## Warning: package 'stringr' was built under R version 4.3.1

    ## Warning: package 'forcats' was built under R version 4.3.1

    ## Warning: package 'lubridate' was built under R version 4.3.1

    ## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
    ## ✔ dplyr     1.1.3     ✔ readr     2.1.4
    ## ✔ forcats   1.0.0     ✔ stringr   1.5.0
    ## ✔ ggplot2   3.4.3     ✔ tibble    3.2.1
    ## ✔ lubridate 1.9.2     ✔ tidyr     1.3.0
    ## ✔ purrr     1.0.2     
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()
    ## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors

``` r
library(tidybayes)
```

    ## Warning: package 'tidybayes' was built under R version 4.3.1

``` r
library(brms)
```

    ## Warning: package 'brms' was built under R version 4.3.1

    ## Loading required package: Rcpp

    ## Warning: package 'Rcpp' was built under R version 4.3.1

    ## Loading 'brms' package (version 2.20.4). Useful instructions
    ## can be found by typing help('brms'). A more detailed introduction
    ## to the package is available through vignette('brms_overview').
    ## 
    ## Attaching package: 'brms'
    ## 
    ## The following objects are masked from 'package:tidybayes':
    ## 
    ##     dstudent_t, pstudent_t, qstudent_t, rstudent_t
    ## 
    ## The following object is masked from 'package:stats':
    ## 
    ##     ar

# ICD 10 codes
