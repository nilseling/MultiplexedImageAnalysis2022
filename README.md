# Multiplexed Image Analysis 2022

This repository hosts the scripts to reproduce the analysis presented in the practical session of [Tumors and the immune system 2022 - High dimensional spatial profiling of tumor microenvironment](https://www.cb.uzh.ch/en/Education/Compulsory-courses/ModuleB.html)

## Getting started

To follow the tutorial, please clone the repository:

```
git clone https://github.com/nilseling/MultiplexedImageAnalysis2022.git
```

or download the zipped version by visiting [https://github.com/nilseling/MultiplexedImageAnalysis2022](https://github.com/nilseling/MultiplexedImageAnalysis2022)
click on `Code` and then `Download ZIP`.

The `MultiplexedImageAnalysis.Rmd` file contains runnable code to follow the tutorial.

## Install required packages

To follow the data analysis examples in this tutorial, you will need to 
install the following R packages:

```{r, eval=FALSE}
install.packages("BiocManager")
BiocManager::install(c("cytomapper", "imcRtools"))
```

Please also install [FIJI](https://imagej.net/software/fiji/) and [QuPATH](https://qupath.github.io/).
