# lab-notebook

Digital Laboratory Notebook with R markdown

## Overview

This repository contains a laboratory notebook in form of an R markdown document (`*.Rmd`).

All care was taken to guarantee scientific accuracy and adhere to good scientific practice in terms of statistics, reproducibility and code documentation. Please report any errors by filing a [github issue](https://github.com/m-jahn/lab-notebook/issues) for this repository, or contact michael.jahn@scilifelab.se.

## How to view notebooks

Data and notebook(s) collected in this repository are self-contained and executable. The code _and_ the documentation are part of one and the same R markdown document for each notebook. The notebook(s) can be downloaded and executed from the `/notebook` sub-folder. To simply view the rendered notebook follow the links to the `*.html` reports under [Notebooks](#Notebooks).

To download the repository on your local drive use `git clone` in a (linux) terminal:

``` bash
cd /your-target-folder
git clone https://github.com/m-jahn/lab-notebook
```

Open a notebook with Rstudio and execute code (chunks) with the `Run` button.
Alternatively, open an interactive R session and render the R markdown document:

``` bash
require(rmarkdown)
rmarkdown::render("lab-notebook.Rmd")
```

## Data

- `data/lab-notebook.RData` - data used in the notebook in `RData` format

## Libraries

- `lattice`
- `latticeExtra`
- [`latticetools` from github](https://github.com/m-jahn/lattice-tools)
- `tidyverse` (metapackage)

## Notebooks

- [Rendered lab notebook](https://m-jahn.github.io/lab-notebook/lab-notebook.nb.html) as HTML web page
