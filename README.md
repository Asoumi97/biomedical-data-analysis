# Biomedical Data Analysis

## Overview

This repository showcases bioinformatics and biomedical data analysis projects developed using Python and R.

During my Master's thesis and my position as a Research Assistant at the University Medical Center Mainz, I contributed to the development of computational workflows for spatial transcriptomics analysis.

Spatial transcriptomics is a cutting-edge technology that combines gene expression profiling with spatial information, enabling researchers to study where genes are expressed within intact tissue and how different cell types are spatially organized.

My work focused on the analysis of large-scale spatial transcriptomics datasets, often exceeding **500 GB** per experiment, requiring efficient computational workflows for preprocessing, quality control, annotation, visualization, and downstream analysis.

The primary objective of these analyses was to investigate **cell–cell interactions** by integrating spatial gene expression data with tissue morphology, providing insights into cellular communication within the tissue microenvironment.

> **Note:** Due to confidentiality agreements and ongoing research leading to future scientific publications, the original datasets, code, figures, and analysis pipelines cannot be shared. This repository demonstrates the methodologies, computational approaches, and technical expertise using publicly available resources where appropriate.



## Project Objective

The objective of this project was to develop a reproducible workflow for the analysis of Xenium-based spatial transcriptomics data by integrating molecular and histological information.

The workflow combines multiple annotation strategies (RCTD, marker-based annotation, and SingleR), histology-guided tissue annotation using QuPath, and spatial neighborhood analysis to investigate **cell–cell interactions** within the tissue microenvironment.

---

## Workflow

1. Data preprocessing and quality control
2. Cell type annotation
   - RCTD
   - Marker-based annotation
   - SingleR
   - Annotation merging
3. Spatial visualization and distribution analysis
4. Histological annotation and ROI mapping using QuPath
5. Cell–cell communication analysis
6. Statistical analysis and visualization

---

## Technologies

### Programming
- Python
- R

### Bioinformatics
- Xenium
- Scanpy
- Squidpy
- Seurat
- SingleR
- RCTD
- SpaceXR

### Image Analysis
- QuPath (H&E histology annotation and ROI mapping)

### Data Analysis
- Pandas
- NumPy
- data.table
- dplyr
- Matrix

### Visualization
- ggplot2
- Matplotlib
- patchwork

---

## Skills Demonstrated

- Large-scale biomedical data processing (>500 GB datasets)
- Spatial transcriptomics analysis
- Cell type annotation
- Histology-guided data integration
- Cell–cell interaction analysis
- Statistical analysis
- Scientific programming in Python and R
- Scientific visualization


> Due to ongoing research and an upcoming publication, the original code, figures and datasets cannot be shared.
