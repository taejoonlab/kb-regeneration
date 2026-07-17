---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p02.txt
---

# A Single-Cell Atlas Depicting the Cellular and Molecular Features in Human Anterior Cruciate Ligamental Degeneration: A Single Cell Combined Spatial Transcriptomics Study

## Citation (NLM)
Yang R, Xu T, Zhang L, Ge M, Yan L, Li J, Fu W. A Single-Cell Atlas Depicting the Cellular and Molecular Features in Human Anterior Cruciate Ligamental Degeneration: A Single Cell Combined Spatial Transcriptomics Study. eLife. 2023;12:e85700. doi:10.7554/eLife.85700

**DOI:** [https://doi.org/10.7554/eLife.85700](https://doi.org/10.7554/eLife.85700)

---

## Background
Anterior cruciate ligament (ACL) degeneration contributes to chronic knee pain, instability, and osteoarthritis onset, yet the cellular and molecular mechanisms remain poorly understood. The extracellular matrix (ECM) is the physical basis for ligament function, and ACL degeneration involves ECM remodeling, collagen disorganization, and chondroid metaplasia. Previous studies have focused on individual cell types or pathways, but a comprehensive single-cell resolution understanding of ligament cellular heterogeneity and cell-cell interactions during degeneration is lacking. This study creates a single-cell and spatial transcriptomic atlas of healthy and degenerated human ACL to elucidate the pathogenesis of ligamental degeneration.

## Key Experiment Methods
1. Single-cell RNA sequencing (scRNA-seq) of 49,356 cells from 4 healthy and 4 degenerated human ACL specimens using 10× Genomics platform
2. Spatial RNA sequencing (spRNA-seq) of normal and lesioned ligament samples for spatial distribution mapping of cell subpopulations
3. Fibroblast subclustering and identification of 10 subsets (Fib.1-Fib.10) with differential gene expression analysis
4. Pseudotime trajectory analysis using Monocle3 to reconstruct lineage programs and identify dynamic transcriptional changes during degeneration
5. Ligand-receptor interaction analysis using CellPhoneDB and CellChat to map intercellular signaling networks
6. Bulk RNA-seq deconvolution analysis using SCDC tool and GSVA for cell type proportion validation
7. Multiplex immunofluorescence (OPAL) staining for spatial validation of key markers (FGF7, TGFβ1, APOE, TOP2A, ACTA2, MYH11, CD90)
8. Gene Ontology (GO), KEGG, and Gene Set Enrichment Analysis (GSEA) for functional interpretation of differentially expressed genes

## Results
- Identified four major cell classes: fibroblasts (66.14%), immune cells (16.25%), pericytes (9.78%), and endothelial cells (7.83%); degenerated ACL showed higher immune cell ratio and lower pericyte ratio
- Fibroblast subclustering revealed 10 subsets: Fib.1/2 (ECM remodeling-associated, increased in disease), Fib.3 (homeostasis-associated, decreased in disease), Fib.4 (resident fibroblasts, decreased), Fib.5 (structural fibroblasts), Fib.6 (chondrocyte-like), Fib.8 (cycling cells, increased), Fib.9 (inflammation-related, increased), Fib.10 (damage repair)
- Pseudotime analysis identified two opposing trajectories: cell fate1 (Fib.2, Fib.9) characterized by inflammatory damage and ECM degradation; cell fate2 (Fib.10) characterized by wound repair and ECM assembly
- Endothelial cell subsets increased in degenerated ACL, indicating angiogenesis; pericyte1 (myocyte-like) increased while pericyte2 (fibroblast-like) decreased
- Macrophages were the most abundant immune cells and increased in degeneration, upregulating ECM remodeling genes (PRG4, FN1, HTRA1) and complement pathways
- CellChat analysis identified FGF and TGF-β signaling as key pathways: Fib.9 expressed FGF7 acting on FGFR1 in fibroblast subsets; macrophages expressed TGFB1 acting on TGFBR1/2 in fibroblasts and endothelial cells
- Spatial transcriptomics confirmed disease-specific fibroblasts (Fib.9) and immune cells were more numerous and widely distributed in degenerated samples, with spatial proximity enabling cell-cell interactions
- Immunofluorescence validated increased Fib.8 (TOP2A+, TGFB1+) and Fib.9 (APOE+, FGF7+) populations in degenerated ACL

## Perspective
This study provides the first comprehensive single-cell and spatial atlas of human ACL degeneration, revealing that the disease is characterized by ECM remodeling driven by specific fibroblast subpopulations (Fib.1, Fib.2, Fib.9) and regulated through FGF7-FGFR1 and TGFB1-TGFBR2 signaling axes. The identification of two opposing trajectories (inflammatory damage vs. repair) suggests therapeutic strategies could aim to shift the balance toward the repair pathway. Key targets include FGF7-FGFR1 and TGFB1-TGFBR2 interactions for modulating ECM remodeling. The spatial proximity of disease-specific fibroblasts to immune and endothelial cells highlights the importance of the ligament microenvironment in degeneration progression. Future work should validate these findings in larger cohorts and explore targeted interventions to modulate specific fibroblast subpopulations or signaling pathways.

---

*Processed by **qwen3.6-plus** (OpenCode Go) on 2026-06-07*
