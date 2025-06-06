# RNA-Seq & Pathway Enrichment Analysis of Irradiated Mouse Salivary Tissue

This project explores molecular changes in irradiated mouse salivary gland tissue using RNA-seq and metabolomics data. We perform differential gene expression analysis and KEGG pathway enrichment, with ongoing integration of metabolomics data and development of a formal technical white paper.

---

## 🎯 Project Objectives

- ✅ **Identify differentially expressed genes (DEGs)** from RNA-seq data using DESeq2
- ✅ **Perform KEGG pathway enrichment** on DEGs using clusterProfiler
- 🔄 **Integrate metabolomics data** using MetaboAnalystR (in progress)
- 🔄 **Perform joint pathway analysis** across omics layers (in progress)
- 🧾 **Produce a professional white technical paper** documenting the full methodology and findings (in progress)

---

## 🧬 Data Sources

- **RNA-Seq**: [NCBI GEO - GSE155902](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE155902)  
- **Metabolomics**: [Zenodo - DOI: 10.5281/zenodo.4391402](https://zenodo.org/records/4391402)

---
## 📦 Tools & Packages Used

- `DESeq2`
- `clusterProfiler`
- `org.Mm.eg.db`
- `EnhancedVolcano`, `pheatmap`, `readr`, `dplyr`, `purrr`
- `MetaboAnalystR` (to be added)

---

## 📊 Example Outputs

### Top Enriched KEGG Pathways  
![](figures/kegg_barplot.png)

### Volcano Plot  
![](figures/volcano_plot.png)

---

## 📄 White Paper (In Progress)
The formal white technical paper for this project is being developed in the whitepaper/ folder.

Format: .docx 

Contents will include: research background, RNA-seq methods, KEGG enrichment, integration strategy, and figures


