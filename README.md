# Multi-Tissue Xenium Spatial Transcriptomics Analysis

**Author:** Funmi Oyebamiji &nbsp;|&nbsp; **Date:** July 2024

---

## Overview

This repository contains an R analysis report for a Xenium spatial transcriptomics analysis comparing human and non-human samples across three tissue types (brain, liver, intestine). The report (code and output together) covers:

- Loading and QC of Xenium data per sample
- Cropped-region visualization (violin plots, spatial molecule and feature plots)
- SCTransform normalization and PCA
- Multi-sample integration (RPCA) and clustering
- Cell-type annotation via SingleR (Human Primary Cell Atlas reference)
- Differential expression between human and non-human samples, per cell type and tissue
- Spatial visualization at multiple zoom levels, by cluster and by sample

**[View the full report](https://maryolufunmilola.github.io/html-reports/MultipleTissues_Xenium.html)**

## Requirements

R with Seurat, SingleR, celldex, scCustomize, and standard tidyverse packages. See the report for the full library list.

## Data

Raw Xenium data is not included in this repository.
