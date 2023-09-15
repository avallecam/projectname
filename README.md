
<!-- README.md is generated from README.Rmd. Please edit that file -->

# projectname

<!-- badges: start -->

[![License: GPL (\>=
2)](https://img.shields.io/badge/License-GPL%20%28%3E%3D%202%29-blue.svg)](https://choosealicense.com/licenses/gpl-2.0/)
[![Dependencies](https://img.shields.io/badge/dependencies-2/95-green?style=flat)](#)
<!-- badges: end -->

Research Compendium of the project to test how to make an open,
reproducible, sustainable analysis project.

## How to cite

Please cite this compendium as:

    #> 
    #> Valle-Campos A (2023). "projectname: My Reproducible Project."
    #> <https://github.com/avallecam/projectname>.
    #> 
    #> A BibTeX entry for LaTeX users is
    #> 
    #>   @Misc{vallecampos:2023,
    #>     title = {projectname: My Reproducible Project},
    #>     author = {Andree Valle-Campos},
    #>     year = {2023},
    #>     url = {https://github.com/avallecam/projectname},
    #>     abstract = {A paragraph providing a full description of the project (on several lines...)},
    #>     version = {0.0.0.9000},
    #>   }

## Content

This repository is structured as follow:

- [`data/`](https://github.com/avallecam/projectname/tree/master/data):
  contains all raw data required to perform analyses

- [`analyses/`](https://github.com/avallecam/projectname/tree/main/analyses/):
  contains R scripts to run each step of the workflow

- [`outputs/`](https://github.com/avallecam/projectname/tree/main/outputs):
  contains all the results created during the workflow

- [`figures/`](https://github.com/avallecam/projectname/tree/main/figures):
  contains all the figures created during the workflow

- [`R/`](https://github.com/avallecam/projectname/tree/main/R): contains
  R functions developed especially for this project

- [`man/`](https://github.com/avallecam/projectname/tree/main/man):
  contains help files of R functions

- [`DESCRIPTION`](https://github.com/avallecam/projectname/tree/main/DESCRIPTION):
  contains project metadata (author, date, dependencies, etc.)

- [`make.R`](https://github.com/avallecam/projectname/tree/main/make.R):
  main R script to run the entire project by calling each R script
  stored in the `analyses/` folder

## Usage

First, clone this repository. You can follow [steps on how to create a
new Rstudio Project from a GitHub
repository](https://happygitwithr.com/new-github-first.html#usethiscreate_from_github).

Then, run:

``` r
source("make.R")
```

### Notes

- All required packages, listed in the `DESCRIPTION` file, will be
  installed (if necessary)
- All required packages and R functions will be loaded
- Some analyses listed in the `make.R` might take time

## Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

## Contributing

Contributions are always welcome!

See our [contributing guide](/.github/CONTRIBUTING.md) for ways to get
started.

Please adhere to this project’s [Code of
Conduct](/.github/CODE_OF_CONDUCT.md).

## Support

For support, please see our [Getting help guide](/.github/SUPPORT.md).
