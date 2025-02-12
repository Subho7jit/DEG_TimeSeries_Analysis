# DEG_TimeSeries_Analysis
This repository contains an R-based pipeline for analyzing time-series gene expression data from. The analysis involves data retrieval, normalization, differential expression analysis, and visualization of expression trends over multiple time points. SG.
# Time-Series Gene Expression Analysis (GSE22307)

## Overview
This repository contains an R script to analyze gene expression data from the GEO dataset GSE22307 using a time-series approach. The analysis involves differential expression testing and trend analysis across multiple time points.

## Dataset
- **Accession Number:** GSE22307
- **Platform:** GEO Microarray Data
- **Time Points:** 0 (Baseline), 2 Days, 4 Days, 6 Days

## Requirements
Ensure the following R packages are installed:
```r
install.packages(c("GEOquery", "limma", "edgeR", "ggplot2", "Biobase"))
