
<!-- README.md is generated from README.Rmd. Please edit that file -->

# senso: An Interface to the Philippine Census of Population and Housing Data

<!-- badges: start -->
<!-- badges: end -->

The Philippine Statistics Authority (PSA) makes census of population and
housing data publicly available through various data publications and
releases over time via their website. This package provides utilities
for accessing and processing the census of population and housing data
released by the PSA.

## What does `senso` do?

Please note that `senso` is still highly experimental and is undergoing
a lot of development. Hence, any functionalities described below and in
the rest of the package documentation have a high likelihood of changing
interface or approach as we aim for a stable working version.

Currently, the package’s main functionalities are:

- Retrieval and/or download of census of population and housing data for
  every census conducted released by the PSA on their website;

- Standardised naming of census of population and housing statistical
  table files;

- Upload and/or archive raw census of population and housing data
  releases onto specific platforms; and,

- Process raw census of population and housing data releases into
  machine-readable and relational database-ready structures.

## Installation

`senso` is not yet on CRAN but can be installed from the [panukatan R
universe](https://panukatan.r-universe.dev) as follows:

``` r
install.packages(
  "senso",
  repos = c('https://panukatan.r-universe.dev', 'https://cloud.r-project.org')
)
```

## Usage

## Citation

If you find the `senso` package useful please cite using the suggested
citation provided by a call to the `citation()` function as follows:

``` r
citation("senso")
#> To cite senso in publications use:
#> 
#>   Ernest Guevarra (2024). talaan: An Interface to the Philippine Census
#>   of Population and Housing Data R package version 0.0.0.9000 URL
#>   https://panukatan.io/senso/
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {senso: An Interface to the Philippine Census of Population and Housing Data},
#>     author = {{Ernest Guevarra}},
#>     year = {2024},
#>     note = {R package version 0.0.0.9000},
#>     url = {https://panukatan.io/senso/},
#>   }
```

## Community guidelines

Feedback, bug reports and feature requests are welcome; file issues or
seek support [here](https://github.com/panukatan/senso/issues). If you
would like to contribute to the package, please see our [contributing
guidelines](https://panukatan.io/senso/CONTRIBUTING.html).

This project is released with a [Contributor Code of
Conduct](https://panukatan.io/senso/CODE_OF_CONDUCT.html). By
participating in this project you agree to abide by its terms.
