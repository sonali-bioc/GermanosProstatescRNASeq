---
title: "scRNASeq Prostate Cancer"
author: "Alex Germanos, Sonali Arora"
date: "January 18, 2022"
output: 
  html_document:
    toc: true
    theme: united
---

## Introduction

This github repository contains code to reproduce the analysis in our upcoming [paper](https://www.biorxiv.org/content/10.1101/2022.03.02.482711v1)
"Defining cellular population dynamics at single cell resolution during prostate cancer progression".

## Tools used for the Analysis 

1. [SingleCellExperiment](https://bioconductor.org/packages/release/bioc/html/SingleCellExperiment.html) for processing scRNASeq data
2. [Seurat](https://satijalab.org/seurat/) for processing scRNASeq data
3. [SingleR](https://bioconductor.org/packages/release/bioc/html/SingleR.html) for performing unbiased cell type recognition
4. [velocyto.R](https://github.com/velocyto-team/velocyto.R) for RNA velocity analysis
5. [Monocle](https://cole-trapnell-lab.github.io/monocle3/) for trajectory analysis
6. [Palantir](https://github.com/dpeerlab/Palantir) for trajectory analysis
7. [ggplot2](https://ggplot2.tidyverse.org/) for making figures
8. [GSVA](https://bioconductor.org/packages/release/bioc/html/GSVA.html) for GSVA analysis
9. [pheatmap](https://cran.r-project.org/web/packages/pheatmap/index.html) for making heatamps
10. [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html) for color-scheme palettes
