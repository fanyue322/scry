# scry

[![Build Status](https://travis-ci.com/kstreet13/scry.svg?token=o1x5ZKVR5sA6MpqhDnQX&branch=master)](https://travis-ci.com/kstreet13/scry)
[![codecov](https://codecov.io/gh/kstreet13/scry/branch/master/graph/badge.svg?token=2QCzltvkbJ)](https://codecov.io/gh/kstreet13/scry)

The released version of scry can be found on Bioconductor at https://bioconductor.org/packages/scry.

A collection of methods for the analysis of small-count data, such as single-cell RNA-seq.

Included methods:
 - Deviance for feature selection
 - GLM-PCA for dimension reduction
 - Null residuals, a transformation that when combined with PCA approximates GLM-PCA

Planned additions for upcoming release:
 - Quasi-UMI normalization for single-cell read counts
 - Cell type prediction for scRNA-seq

## Installation
```
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("scry")
```

## Issues and bug reports
Please use https://github.com/kstreet13/scry/issues to submit issues, bug reports, and comments.
