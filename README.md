# _airportscreening_: Effectiveness of airport screening at detecting infected travellers

<!-- badges: start -->
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![R-CMD-check](https://github.com/epiverse-trace/finalsize/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/epiverse-trace/finalsize/actions/workflows/R-CMD-check.yaml)
[![Codecov test coverage](https://codecov.io/gh/epiverse-trace/finalsize/branch/main/graph/badge.svg)](https://app.codecov.io/gh/epiverse-trace/finalsize?branch=main)
<!-- [![CRAN status](https://www.r-pkg.org/badges/version/finalsize)](https://CRAN.R-project.org/package=finalsize) -->
<!-- badges: end -->

| Authors |
| :-- |
| Mr. Billy Quilty |
| Assoc. Prof. Stefan Flasche |
| Dr. Sam Clifford |
| Assoc. Prof. Rosalind Eggo |
| Other members of CMMID at LSHTM |

<!-- https://cmmid-lshtm.shinyapps.io/traveller_screening/ -->

This repository contains the code for a Shiny app whose purpose is to display the effectiveness of screening arrivals for infectious diseases. We assume that the infection may have a latent stage during which travellers are infected but not symptomatic. They may become symptomatic during their flight, which may be detected by entry screening, or after their arrival, and therefore no screening would have detected an infection.

![Screenshot of app](inst/info/figures/app_screenshot.png)

Users may adjust the following parameters:

* duration of flight
* mean and variance of the probability distribution describing time between infection and onset of symptoms
* mean and variance of the probability distribution describing time between onset of symptoms and severe symptoms
* sensitivity of exit screening
* sensitivity of entry screening

