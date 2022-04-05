# Multiplexed Image Analysis 2022

This repository hosts the scripts to reproduce the analysis presented in the practical session of [Tumors and the immune system 2022 - High dimensional spatial profiling of tumor microenvironment](https://www.cb.uzh.ch/en/Education/Compulsory-courses/ModuleB.html)

## Getting started

To follow the tutorial, please clone the repository:

```
git clone https://github.com/nilseling/MultiplexedImageAnalysis2022.git
```

or download the zipped version by clicking on `Code` and then `Download ZIP`.

The `MultiplexedImageAnalysis.Rmd` file contains runnable code to follow the tutorial.

To follow the tutorial online, please refer to [https://nilseling.github.io/MultiplexedImageAnalysis2022/](https://nilseling.github.io/MultiplexedImageAnalysis2022/).

## Install required packages

Please install [R](https://www.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/).

To follow the data analysis examples in this tutorial, you will need to 
install the following R packages from within R:

```{r, eval=FALSE}
install.packages("BiocManager")
BiocManager::install(c("cytomapper", "imcRtools", "openxlsx", "stringr", 
                       "dittoSeq", "tidyverse", "bluster", "patchwork",
                       "viridis", "scater", "scuttle", "S4Vectors", "igraph"))
```

Please also install [FIJI](https://imagej.net/software/fiji/) and [QuPATH](https://qupath.github.io/).
