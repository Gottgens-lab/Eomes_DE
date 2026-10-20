# Eomes_DE

Analysis repository for integrated **RNA-seq** and **ATAC-seq** processing and downstream manuscript figures.

This project was run in the following order:

1. `rna/` – run the RNA Snakemake pipeline (in /rna/snakemake)
2. `atac/archR/` – run the ATAC/ArchR Snakemake pipeline (in /atac/archR/snakemake)
3. `rna_atac/` – run shared dimensionality reduction using MOFA  
4. `Manuscript/` – run notebooks for final analyses and figures

---
