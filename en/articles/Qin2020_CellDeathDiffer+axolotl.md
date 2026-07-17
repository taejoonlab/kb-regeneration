---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
---

# Single-cell RNA-seq reveals novel mitochondria-related musculoskeletal cell populations during adult axolotl limb regeneration process

## Citation (NLM)

Qin T, Fan CM, Wang TZ, Sun H, Zhao YY, Yan RJ, Yang L, Shen WL, Lin JX, Bunpetch V, Cucchiarini M, Clement ND, Mason CE, Nakamura N, Bhonde R, Yin Z, Chen X. Single-cell RNA-seq reveals novel mitochondria-related musculoskeletal cell populations during adult axolotl limb regeneration process. Cell Death Differ. 2020. doi:10.1038/s41418-020-00640-8

**DOI:** [https://doi.org/10.1038/s41418-020-00640-8](https://doi.org/10.1038/s41418-020-00640-8)

---

## Background

The axolotl is a classic model of epimorphic regeneration, able to regrow entire limbs and major organs after amputation via a blastema — a pool of progenitor cells that autonomously patterns itself to replace lost structures. Lineage tracing has shown that blastema cells arise from mesodermal tissues including dermal fibroblasts, Schwann cells, and myogenic cells, and prior transcriptomic/proteomic work has flagged key blastema genes (e.g., *cirbp*, *kazald1*) and an early oncogene burst. However, the cellular composition of the blastema, the role of the extracellular matrix (ECM), and the cell–cell interactions driving regeneration remained inadequately characterized.

This study applies large-scale single-cell RNA sequencing (scRNA-seq) across a time course of adult axolotl limb regeneration to build an unbiased cell atlas, with the goal of resolving cell heterogeneity, reconstructing differentiation trajectories, and uncovering regeneration-specific populations relevant to eventually understanding regeneration in mammals.

---

## Key Experiment Methods

1. scRNA-seq (Fluidigm C1 HT IFC + HiSeq) of single cells dissociated from adult axolotl distal limb tips at 0, 3, 7, and 21 days post amputation (dpa), representing intact, early, middle, and late regeneration; 938 cells passed QC (~5000 genes/cell), mapped to axolotl transcriptome assemblies.
2. Differentially expressed gene analysis and Gene Set Enrichment Analysis (GSEA) across the four time points.
3. Seurat t-SNE unsupervised clustering to define cell clusters and their signature genes; GO analysis of cluster-upregulated genes (with mitochondrial genes optionally removed to unmask other markers).
4. Ligand–receptor connectivity mapping across the seven clusters at each time point to infer microenvironmental cross-talk.
5. Monocle pseudo-temporal ordering to reconstruct differentiation trajectories; k-means clustering of genes into temporal expression groups.
6. Validation by immunofluorescence/immunohistochemistry (MDK, PTPRC, PIF1, KRT8, TOMM20, COL1), RNA FISH (COL2A1), and transmission electron microscopy (mitochondrial counts); MCODE protein–protein interaction network analysis of the COL2-mito subcluster.

---

## Results

- Seven clusters (C0–C6) were identified: general, mitochondria (e.g., *CYTB*, *ATP6*), connective tissue/CT (*FBN2*, *MDK*), chondrocyte (*COL2A1*, *MATN1*), inflammation (*CCL5*, *PTPRC*), cycling (*SLC2A8*, *PIF1*), and apical epithelium cap/AEC (*KRT12*, *KRT8*).
- A novel mitochondria cluster was strongly enriched in the regenerating stages (3, 7, 21 dpa) vs. 0 dpa. After removing mitochondrial genes, its GO functions related to neuron/stem-cell regeneration and development and regulation of programmed cell death; GSEA showed upregulated TCA cycle plus cell-division and cell-death pathways (ROBO signaling, RHO GTPases, JNK/Nrage). TOMM20 immunostaining and TEM confirmed higher mitochondrial content in regenerating tissue, peaking at 3 dpa.
- Connectivity mapping detected 928 ligand–receptor pairs; the chondrocyte cluster (C3) had the strongest signaling to the AEC (C6), enriched in ECM (COL1A1, COL3A1, MATN1) and growth-factor (ITGB1, EGFR, BMPR2, VEGF) interactions, implicating cartilage-secreted ECM in promoting AEC migration/morphogenesis and blastema formation. The inflammation cluster showed strongest connectivity at 3 dpa.
- Pseudotime placed the cycling cluster at the primitive state and the chondrocyte cluster at the trajectory end; some 0 dpa cells occupied the primitive state, suggesting residual stem-like cells in intact limbs. FGF and BMP family members rose along pseudotime.
- COL1A1/2+ and COL2A1+ musculoskeletal populations showed dynamic dedifferentiation/re-differentiation: proportions fell sharply at 3 dpa (COL2A1+ from 72% to 9%, further to 2% at 7 dpa) then re-increased by 21 dpa (COL2A1+ to 43%), mirroring the in vitro chondrocyte dedifferentiation signature (up COL1, down COL2).
- Subclustering COL2+ cells revealed six subclusters, including a COL2-mitochondria (COL2-mito) subcluster (fully contained in the mitochondria cluster) marked by mitochondrial ATP synthase (ATP5F1A/B) and mitochondrial ribosomal genes, with functions in ATP metabolism, oxygen response, and wound response. RNA FISH + TOMM20 co-staining localized COL2-mito cells to the top of the blastema and beneath the AEC. CT precursor subclusters (PRRX1, FBN2; one expressing limb-patterning genes HOXA13, HAND2) versus mature CT (FBN1) were resolved along a bifurcating COL2+ trajectory.

---

## Perspective

The study delivers the first single-cell atlas resolving the dynamic musculoskeletal cell landscape of adult axolotl limb regeneration and introduces a regeneration-specific mitochondria-related population — including a COL2-mito subcluster — as an energy-providing support cell for regeneration rather than merely a differentiation state. It provides single-cell-level evidence for dedifferentiation/re-differentiation of COL1+/COL2+ musculoskeletal cells and highlights cartilage-derived ECM as a medium coupling chondrocytes to the AEC during blastema formation.

Limitations include the modest cell number (938 cells) inherent to the Fluidigm C1 platform, reliance on cluster/marker-based inference rather than genetic lineage tracing to prove dedifferentiation, and the still-incomplete axolotl reference resources. Future directions include functional/lineage-tracing validation of the mitochondria and COL2-mito populations, deeper sampling, and testing whether analogous energy-supplying populations or ECM–epithelial cross-talk could be leveraged to promote regeneration in mammalian tissues.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
