# Lightsey_ScientificReports_2025
This repository contains a reproducible RNA-seq analysis and figure generation workflow in R used to produce publication-quality figures for comparative transcriptomic studies.   The pipeline implements standard normalization, PCA, correlation analysis, heatmaps, GSVA pathway scoring, and differential expression with `edgeR` and `limma`.

**Main script:** `scripts/Lightsey2025_Figures.Rmd`  
**Input:** `data/Lightsey2025_Data_Analysis.xlsx`  
**Output:** All figures (PNG) and DEG tables are saved in the `results/` folder.

Clone the repository and install required R packages:

```bash
git clone https://github.com/suzannelightsey/Lightsey_ScientificReports_2025.git
cd Lightsey_ScientificReports_2025

If you use this code or parts of it, please cite this repository and relevant R/Bioconductor packages.

**Author**
Suzanne Lightsey
J. Crayton Pruitt Family Department of Biomedical Engineering, Univeristy of Florida
