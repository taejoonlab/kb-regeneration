---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
---

# Species and cell-type properties of classically defined human and rodent neurons and glia

## Citation (NLM)
Xu X, Stoyanova EI, Lemiesz AE, Xing J, Mash DC, Heintz N. Species and cell-type properties of classically defined human and rodent neurons and glia. eLife. 2018;7:e37551. doi:10.7554/eLife.37551

**DOI:** [https://doi.org/10.7554/eLife.37551](https://doi.org/10.7554/eLife.37551)

---

## Background

Genetically targeting and molecularly profiling specific cell types has driven fundamental insight into mammalian brain function, but such genetic tools are largely restricted to mice. Fundamental questions about human brain complexity — how many cell types exist, how they vary across individuals and species, and whether aging affects cell types equivalently — remain unresolved. Single-cell/single-nucleus methods provide unbiased surveys but are noisy, biased toward abundant cell types, and under-sample rare ones.

To address this, the authors develop a non-genetic strategy to purify nuclei from defined cell types using antibodies, then profile gene expression and chromatin accessibility. Exploiting the continuity of the endoplasmic reticulum membrane with the nuclear membrane, they expand the antibody repertoire (targeting ER-resident and plasma-membrane proteins in addition to nuclear proteins), enabling cell-type-specific nuclear isolation from postmortem human brain without transgenics.

---

## Key Experiment Methods

1. Reference profiles from transgenic mice expressing EGFP-L10a under cell-type-specific drivers, with FACS purification of nuclei and nuclear RNA-seq (Purkinje, granule, Bergmann glia, corticopontine/corticothalamic neurons).
2. Antibody-based nuclear sorting from wild-type mouse cerebellum using antibodies to a transcription factor (OLIG2), an ER protein (ITPR1), plasma-membrane proteins (SORCS3, EAAT1/GLAST), and RBFOX3/NeuN, isolating granule, Purkinje, basket, astrocyte, and oligodendrocyte nuclei.
3. RNA-seq of sorted nuclei; purity assessed by known markers and pairwise Pearson correlation/hierarchical clustering.
4. Transfer of the same antibody strategy to rat and to postmortem human cerebellum (donors XK, PK; ultimately sixteen human brains).
5. Specificity Index algorithm to define cell-type-specific genes; validation against Allen Mouse Brain Atlas in situ hybridization.
6. Cross-species comparison restricted to high-confidence 1:1 orthologs (mouse, rat, human), with hierarchical clustering and principal components analysis.
7. ATAC-seq (fixed-nuclei protocol) on mouse and human granule and basket nuclei to map chromatin accessibility; DNA sequence conservation analysis.
8. Comparison to published single-nucleus/single-cell RNA-seq datasets; immunofluorescence validation.

---

## Results

- Antibody-sorted nuclear RNA-seq profiles were pure, reproducible (biological replicate r = 0.98-1), and matched genetically (EGFP-L10a) sorted profiles (r = 0.98-0.99), clustering by cell class then cell type regardless of sorting method.
- The approach resolved subpopulations: OLIG2-high nuclei captured OPCs (Pdgfra, Cspg4) while OLIG2-low were mature oligodendrocytes.
- The population-based method outperformed single-nucleus sequencing in genes detected and reproducibility, complementing single-cell surveys especially for rare cell types.
- The strategy transferred to rat (700-1600 enriched genes per cell type) and to postmortem human cerebellum; most sorting conditions worked in human, though human Purkinje nuclei could not be isolated with the rodent conditions (Purkinje cells are rarer in human).
- Cross-species comparison revealed surprising evolutionary divergence: homologous, classically defined cerebellar cell types differ between rodent and human by hundreds of orthologous, cell-specific genes. Clustering by most-variable genes grouped samples by cell type; species differences emerged as an accumulation of subtler changes (PC1/PC3 = cell type, PC2/6/8 = species).
- Genes changing in expression between mouse and human had concordant changes in chromatin accessibility (ATAC-seq) and less conserved regulatory sequences than stably expressed genes (illustrated by the JKAMP/CCDC175/RTN1 locus — CCDC175 human-specific granule expression).
- Analysis of sixteen human postmortem brains revealed gender-specific transcriptional differences, cell-specific molecular responses to aging (aging unfolds differently per cell type), and a shared robust molecular response to an unknown external event in three donor samples.

---

## Perspective

This work delivers a broadly applicable, non-genetic (antibody-based nuclear sorting) platform for cell-type-specific transcriptomic and epigenetic profiling in any species, including postmortem human brain, thereby enabling correlative studies with human genetic and clinical data. Its key biological finding — that even highly conserved, classically defined neuronal and glial cell types diverge substantially in gene expression between rodent and human, with concordant chromatin/regulatory changes — has important implications for the translational validity of rodent models. For this knowledgebase, it is relevant as a methods-and-resource study of CNS cell types (neurons, astrocytes, oligodendrocytes, OPCs) and cross-species neural biology. Limitations include focus on the cerebellum, use of postmortem tissue (with agonal/processing confounds, as flagged by the unexplained shared response in three donors), potential residual effects of genome-annotation differences on apparent species divergence, and the need to expand to additional brain regions and cell types.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
