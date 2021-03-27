
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sqlr.template <a href='https://gipsousp.github.io/sqlr.template'><img src='man/figures/logo.png' align="right" height="139" /></a>

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/gipsousp/sqlr.template/workflows/R-CMD-check/badge.svg)](https://github.com/gipsousp/sqlr.template/actions)
[![Travis build
status](https://travis-ci.com/gipsousp/sqlr.template.svg?branch=main)](https://travis-ci.com/gipsousp/sqlr.template)
[![Codecov test
coverage](https://codecov.io/gh/gipsousp/sqlr.template/branch/main/graph/badge.svg)](https://codecov.io/gh/gipsousp/sqlr.template?branch=main)
[![License:
MIT](https://img.shields.io/badge/license-MIT-green)](https://choosealicense.com/licenses/mit/)
[![Contributor
Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](https://gipsousp.github.io/mctq/CODE_OF_CONDUCT.html)
<!-- badges: end -->

> This is a template repository for R packages of the GIPSO Systematic
> Quantitative Literature Reviews. If you’re looking for a specific
> review repository, check the [GIPSO GitHub
> page](https://github.com/gipsousp).

`sqlr.[INSERT THE NAME OF THE PACKAGE]` is an R package with the
research compendium of the project: `[INSERT THE NAME OF THE PROJECT]`.
The aim of `sqlr.[INSERT THE NAME OF THE PACKAGE]` is to facilitate
research work, in addition to contributing to the reproducibility of the
research.

The assemble of this package was inspired by Ben Marwick, Carl Boettiger
& Lincoln Mullen article [“Packaging Data Analytical Work Reproducibly
Using R (and Friends)”](https://doi.org/10.1080/00031305.2017.1375986).

Learn more about systematic quantitative literature reviews at
<http://bit.ly/2OMxvcD>.

## Installation

`sqlr.[INSERT THE NAME OF THE PACKAGE]` is still at the
[experimental](https://lifecycle.r-lib.org/articles/stages.html#experimental)
stage of development, that means that people can use the package and
provide feedback, but it comes with no promises for long term stability.

You can install `sqlr.[INSERT THE NAME OF THE PACKAGE]` from GitHub
with:

``` r
# install.packages("sqlr.[INSERT THE NAME OF THE PACKAGE]")
devtools::install_github("gipsousp/sqlr.[INSERT THE NAME OF THE PACKAGE]", dependencies = TRUE)
```

## Citation

If you use `sqlr.[INSERT THE NAME OF THE PACKAGE]` in your research,
please consider citing it. We put a lot of work to build and maintain a
free and open-source R package. You can find the
`sqlr.[INSERT THE NAME OF THE PACKAGE]` citation below.

``` r
citation("sqlr.template")
#> Warning in .canonicalize_person_role(role): Invalid role specification:
#> 'INSERTTHEFIRSTAUTHORNAME'.
#> 
#> To cite sqlr.[INSERT THE NAME OF THE PACKAGE] in publications use:
#> 
#>   [INSERT THE FIRST AUTHOR NAME]. Vartanian D., Benedito-Silva, A. A.,
#>   Pedrazzoli, M. (2021). sqlr.[INSERT THE NAME OF THE PACKAGE]: an R
#>   package with the research compendium of the project - [INSERT THE
#>   NAME OF THE PROJECT]. Retrieved from
#>   https://gipsousp.github.io/sqlr.[INSERT THE NAME OF THE PACKAGE]/ .
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Unpublished{,
#>     title = {sqlr.[INSERT THE NAME OF THE PACKAGE]: an R package with the research compendium of the project - [INSERT THE NAME OF THE PROJECT]},
#>     author = {Daniel Vartanian and Ana Amelia Benedito-Silva and Mario Pedrazzoli},
#>     year = {2021},
#>     url = {https://gipsousp.github.io/sqlr.[INSERT THE NAME OF THE PACKAGE]/},
#>     note = {Lifecycle: experimental},
#>   }
```
