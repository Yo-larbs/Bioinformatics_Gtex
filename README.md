# GTEX analysis
## Overview

This repository contains a compact, fully reproducible computational analysis of GTEx gene-expression data. The project demonstrates an end-to-end dry-lab workflow — from data acquisition and preprocessing through exploratory data analysis, dimensionality reduction (PCA), differential expression testing and basic enrichment — with an emphasis on clarity, reproducibility and interpretability.

### What this repo delivers
- A cleaned, documented Jupyter notebook that runs the full analysis top → bottom.  
- Reproducible scripts to download data and generate a standalone HTML report.  
- Visual summaries (PCA, volcano plot, heatmap) and downloadable result tables for reuse.
- created 3 layer neural network to classify tissue type, 99% accurate


### Why it’s useful
- Shows practical skills recruiters value: data wrangling, statistical testing, visualization, and production-aware practices (requirements, scripts, Docker/Conda-ready environment).  
- Designed for quick review — results are available in `results/` so evaluators can see outputs without executing the pipeline.

### Key outputs
- `results/analysis.html` 
- `Figures/UMAP_tissue_type.png`, `Figures/Heatmap_genes_tissue_type.png`, `Figures/Gene_correlation_plot.png`, `Figures/Neural_network_confusion_matrix.png`
- `data/` (or link) — pointers to the exact public subset used for reproducibility


