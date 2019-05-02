# Software Requirements

## R and RStudio

[R](http://www.r-project.org/) is a programming language that is especially powerful for data exploration, visualization, and statistical analysis. To interact with R, we use [RStudio](http://www.rstudio.com/).

We require R > 3.4.0

####Windows

Install R by downloading and running [this .exe file from CRAN](http://cran.r-project.org/bin/windows/base/release.htm). Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop).

####Mac OS X

Install R by downloading and running [this .pkg file from CRAN](http://cran.r-project.org/bin/macosx/R-latest.pkg). Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop).

####Linux

You can download the [binary files](http://cran.r-project.org/index.html) for your distribution from CRAN. Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo yum install R`). Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop).

## Required R Packages

1. `tm` # text mining in R
2. `dplyr` # data preparation and pipes $>$
3. `ggplot2` # for plotting
4. `matrixStats` # for stats
5. `tidytext` # for sentiment dictionaries
5. `data.table` # for easier data manipulation
6. `scales` # to help us plot
7. `lsa` # latent semantic analysis
8. `cluster` # for clustering analysis
9. `fpc` # flexible procedures for clustering
10. `wordcloud` # to visualize wordclouds
11. `stm` for topic modelling
11. Any dependencies to the packages above.

#### Installation

To install these packages, you can open RStudio and use the command `install.packages()` in the console. For example, to install the `tm` package, you would type:

```{r}
install.packages('tm')
```
Make sure to use quotation marks around the name of the package.

If RStudio returns an error message, go to "Preferences" and check the "Packages" section. Under "CRAN Mirror," if no mirror is selected, choose "Global (CDN) - RStudio". Otherwise, check your internet connection.
