
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sqlr.template <a href='https://gipso.github.io/sqlr.template'><img src='man/figures/logo.png' align="right" height="139" /></a>

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/gipso/sqlr.template/workflows/R-CMD-check/badge.svg)](https://github.com/gipso/sqlr.template/actions)
[![Codecov test
coverage](https://codecov.io/gh/gipso/sqlr.template/branch/main/graph/badge.svg)](https://codecov.io/gh/gipso/sqlr.template?branch=main)
[![License:
MIT](https://img.shields.io/badge/license-MIT-green)](https://choosealicense.com/licenses/mit/)
<!-- badges: end -->

> This is a template repository for R packages of the Interdisciplinary
> Sleep Research Group (GIPSO) Systematic Quantitative Literature
> Reviews (SQLR). If you’re looking for a specific repository, check the
> [GIPSO’s GitHub page](https://github.com/gipso).

`sqlr.template` is an R package with the research compendium of the
GIPSO’s \[INSERT NAME OF THE PROJECT\] systematic quantitative
literature review. The aim of `sqlr.template` is to facilitate the
research work, in addition to contributing to the reproducibility of the
research.

The assemble of this package was inspired by Ben Marwick, Carl Boettiger
& Lincoln Mullen’s article [“Packaging Data Analytical Work Reproducibly
Using R (and Friends)”](https://doi.org/10.1080/00031305.2017.1375986).

Learn more about Systematic Quantitative Literature Reviews (SQLR)
[here](https://www.griffith.edu.au/griffith-sciences/school-environment-science/research/systematic-quantitative-literature-review).

## Installation

`sqlr.template` is still at the
[experimental](https://lifecycle.r-lib.org/articles/stages.html#experimental)
stage of development. That means people can use the package and provide
feedback, but it comes with no promises for long term stability.

You can install `sqlr.template` from GitHub with:

``` r
# install.packages("remotes")
remotes::install_github("gipso/sqlr.template")
```

## Citation

If you use `sqlr.template` in your research, please consider citing it.
We put a lot of work to build and maintain a free and open-source R
package. You can find the `sqlr.template` citation below.

``` r
citation("sqlr.template")
#> 
#> To cite {sqlr.template} in publications use:
#> 
#>   Vartanian, D., Pedrazzoli, M. (2021). {sqlr.template}: an R package
#>   with the research compendium of the GIPSO's INSERT NAME OF THE
#>   PROJECT systematic quantitative literature review. Retrieved from
#>   https://gipso.github.io/sqlr.template/.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Unpublished{,
#>     title = {{sqlr.template}: an R package with the research compendium of the GIPSO's INSERT NAME OF THE PROJECT systematic quantitative literature review},
#>     author = {Daniel Vartanian and Mario Pedrazzoli},
#>     year = {2021},
#>     url = {https://gipso.github.io/sqlr.template/},
#>     note = {Lifecycle: experimental},
#>   }
```
