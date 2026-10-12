# Identification of Genes Associated with Breast Cancer Histological Grade Using Machine Learning Techniques

[![Language: R](https://img.shields.io/badge/Language-R-blue.svg)](https://www.r-project.org/)
[![License: CC BY-NC-ND 3.0 ES](https://img.shields.io/badge/License-CC_BY--NC--ND_3.0_ES-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/3.0/deed.en)

---

## 📖 Description
This repository contains the source code developed for the Master's Thesis (*Trabajo Final de Máster - TFM*) for the **Master's Degree in Data Science at the Universitat Oberta de Catalunya (UOC)**.

The project implements an end-to-end bioinformatics pipeline for RNA-Seq gene expression analysis in breast cancer. A comparative evaluation of Machine Learning models (specifically Random Forest and Radial Kernel Support Vector Machines - SVM) was performed to classify tumor histological grade, identifying key gene biomarkers with high predictive capability and clinical relevance.

## 📂 Repository Structure
* `CODE/`: Contains the RMarkdown script (`MAIN.Rmd`) with the full analytical workflow, ranging from data preprocessing to model evaluation.
* `DATA/`: *Directory reserved for raw/source data files (not included in the repository).*

## 🚀 Reproducibility Guide
To run the analysis, follow these steps:

1. **Environment Setup:** Create a directory named `DATA` in the root of the repository.
2. **Data Download:** Retrieve the original dataset files (`GSE268851_series_matrix.txt` and `GSE268851_TNBC_Study_RawCounts.txt`) from [NCBI GEO (GSE268851)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE268851) and place them inside the `DATA/` folder.
3. **Execution:** Open `CODE/MAIN.Rmd` in RStudio and ensure all required R packages and dependencies are installed before knitting/running the script.

## ⚠️ Clinical Disclaimer
This model is intended solely as a **clinical decision-support tool** and does not, under any circumstances, replace professional medical diagnosis. The final validation of the identified biomarkers must be conducted by qualified clinical personnel.

## ⚖️ License
This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Spain License](https://creativecommons.org/licenses/by-nc-nd/3.0/deed.en).

---
**Author:** Oriol Castellano Aguilera  
*Master's Degree in Data Science, UOC.*
