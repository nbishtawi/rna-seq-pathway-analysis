# RNA-Seq Pathway Enrichment Analysis in Mouse Salivary Glands

This project performs RNA-seq differential expression analysis and KEGG pathway enrichment using irradiated vs untreated mouse salivary gland samples. It uses DESeq2 for modeling and clusterProfiler for enrichment interpretation.

## 🔍 Objectives
- Normalize and analyze RNA-seq count data
- Identify significantly differentially expressed genes (DEGs)
- Perform pathway enrichment using KEGG
- Produce a reproducible analysis pipeline in R

## 🗂️ Repository Structure
- `data/`: Input files (gene counts, metadata)
- `results/`: CSV outputs of DEGs and enrichment
- `report/`: Final R Markdown report (HTML/PDF)
- `scripts/`: (Optional) Supporting R scripts
- `figures/`: Pathway plots and visualizations

## 📦 Tools & Packages
- `DESeq2`
- `clusterProfiler`
- `org.Mm.eg.db`
- `AnnotationDbi`
- `tidyverse`