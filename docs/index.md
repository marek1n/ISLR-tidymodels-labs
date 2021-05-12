--- 
title: "ISLR tidymodels Labs"
author: "Emil Hvitfeldt"
date: "2021-05-12"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
description: "tidymodels lab sections mirroring ISLR labs"
---

# Introduction

This book aims to be a complement to the 1st version [An Introduction to Statistical Learning](https://www.statlearning.com/) book with translations of the labs into using the [tidymodels](https://www.tidymodels.org/) set of packages.

The labs will be mirrored quite closely to stay true to the original material.

## Colophon {-}

This book was written in [RStudio](http://www.rstudio.com/ide/) using [**bookdown**](http://bookdown.org/). The [website](https://emilhvitfeldt.github.io/ISLR-tidymodels-labs/index.html) is hosted via [GitHub Pages](https://pages.github.com/), and the complete source is available on [GitHub](https://github.com/EmilHvitfeldt/ISLR-tidymodels-labs).

This version of the book was built with R version 4.0.2 (2020-06-22) and the following packages:


|package      |version    |source                               |
|:------------|:----------|:------------------------------------|
|broom        |0.7.6      |CRAN (R 4.0.2)                       |
|corrr        |0.4.2      |CRAN (R 4.0.2)                       |
|dials        |0.0.9      |CRAN (R 4.0.2)                       |
|dplyr        |1.0.6      |CRAN (R 4.0.2)                       |
|factoextra   |1.0.7      |CRAN (R 4.0.2)                       |
|ggplot2      |3.3.3      |CRAN (R 4.0.2)                       |
|glmnet       |4.1-1      |CRAN (R 4.0.2)                       |
|infer        |0.5.4      |CRAN (R 4.0.2)                       |
|ISLR         |1.2        |CRAN (R 4.0.2)                       |
|kernlab      |0.9-29     |CRAN (R 4.0.0)                       |
|kknn         |1.3.1      |CRAN (R 4.0.2)                       |
|klaR         |0.6-15     |CRAN (R 4.0.0)                       |
|MASS         |7.3-53.1   |CRAN (R 4.0.2)                       |
|mclust       |5.4.6      |CRAN (R 4.0.0)                       |
|modeldata    |0.1.0      |CRAN (R 4.0.2)                       |
|paletteer    |1.3.0      |CRAN (R 4.0.2)                       |
|parsnip      |0.1.5.9002 |Github (tidymodels/parsnip\@bc125e9) |
|patchwork    |1.0.1      |CRAN (R 4.0.0)                       |
|proxy        |0.4-25     |CRAN (R 4.0.2)                       |
|purrr        |0.3.4      |CRAN (R 4.0.0)                       |
|randomForest |4.6-14     |CRAN (R 4.0.0)                       |
|readr        |1.4.0      |CRAN (R 4.0.2)                       |
|recipes      |0.1.16     |CRAN (R 4.0.2)                       |
|rpart        |4.1-15     |CRAN (R 4.0.2)                       |
|rpart.plot   |3.0.9      |CRAN (R 4.0.2)                       |
|rsample      |0.0.9      |CRAN (R 4.0.2)                       |
|scico        |1.2.0      |CRAN (R 4.0.2)                       |
|tibble       |3.1.1      |CRAN (R 4.0.2)                       |
|tidymodels   |0.1.3      |CRAN (R 4.0.2)                       |
|tidyr        |1.1.3      |CRAN (R 4.0.2)                       |
|tidyverse    |1.3.1      |CRAN (R 4.0.2)                       |
|tune         |0.1.5      |CRAN (R 4.0.2)                       |
|vip          |0.3.2      |CRAN (R 4.0.2)                       |
|workflows    |0.2.2      |CRAN (R 4.0.2)                       |
|workflowsets |0.0.2      |CRAN (R 4.0.2)                       |
|xgboost      |1.4.1.1    |CRAN (R 4.0.2)                       |
|yardstick    |0.0.8      |CRAN (R 4.0.2)                       |