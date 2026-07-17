---
tags: [2026-07, Fibroblast]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add Data Availability section"
---

# Uncovering a fibroblast differentiation-based keloid classification by integration of single-cell and bulk RNA sequencing

## Citation (NLM)

Zhang W, Lu J, Tong X, Xie S, Xian S, Liu Y, Yan J, Qian W, Sun H, Zhu Y, Jiang L, Guo X, Ding X, Li Y, Bai C, Huang R, Xia Z, Ji S. Uncovering a fibroblast differentiation-based keloid classification by integration of single-cell and bulk RNA sequencing. Commun Biol. 2025;8(1):1387. doi:10.1038/s42003-025-08741-1

**DOI:** [https://doi.org/10.1038/s42003-025-08741-1](https://doi.org/10.1038/s42003-025-08741-1)

---

## Background

Keloids are dermal fibroproliferative disorders caused by abnormal wound healing, affecting roughly 4.5–16% of the population and manifesting as raised amorphous scars that invade adjacent normal skin, causing pain, pruritus, and functional/aesthetic impairment. Recurrence after surgical resection alone is 70–100%, and existing therapies (corticosteroid injection, cryotherapy, radiotherapy, laser) carry unavoidable side effects. Because genetic, endocrine, and local tissue factors all contribute, keloids are phenotypically heterogeneous and should not be treated as homogeneous growths, yet few studies have built a diagnostic molecular classification. Fibroblasts—driving abnormal proliferation and excessive collagen deposition—are central to keloid formation, and prior scRNA-seq work (e.g., the four-subpopulation scheme with expanded mesenchymal fibroblasts) established their heterogeneity. This study integrated single-cell and bulk RNA-seq to reconstruct the keloid fibroblast differentiation trajectory and derive a fibroblast-differentiation-based molecular classification of keloids.

---

## Key Experiment Methods

**1. Single-cell atlas of keloid and normal scar**
- scRNA-seq of 3 keloids and 3 normal scars; 44,463 cells after QC (keloids 23,638; normal scars 20,825)
- UMAP clustering into 18 clusters annotated as 9 major cell types; cell–cell communication analysis (CellChat-type)
- Extracted 13,925 fibroblasts, reclustered into 6 subtypes (fibroblast 1–6)

**2. Trajectory analysis and gene identification**
- Monocle 2 pseudotemporal ordering (DDRTree) revealing 7 differentiation states; identified fibroblast-differentiation-related genes (FDRGs)
- Integrated 14,467 Monocle-significant FDRGs with univariate Cox regression on RNA-seq + clinical metadata (SAR database): 32 diagnosis-significant and 137 time-significant DEGs
- Intersection yielded 25 core differentially expressed FDRGs (DEFDRGs)

**3. Consensus classification (FDBKC)**
- Consensus clustering of 25 DEFDRGs stratified patients into three subtypes (k = 3)
- PCA-derived fibroblast score (FS) named clusters: LFDC (low), MFDC (moderate), HFDC (high fibroblast differentiation classification)
- Immune infiltration analysis (23 immune cell types); protein sequencing and 3 public microarray datasets (GSE188952, GSE7890, GSE44270) for validation

**4. Bulk transcriptomics and clinical model**
- Bulk RNA-seq of 37 keloids and 27 healthy samples: 1,828 DEGs; 4 differentially expressed TFs (HOXC9, LMO2, PDX1, RUNX1); GSVA hallmark pathways
- LASSO logistic regression selected 11 DEFDRGs; train/test ROC (AUC 0.995 train, 0.868 test)
- Subtype-specific regulatory networks (DETFs, pathways, immune cells); Connectivity Map (CMap) drug prediction

**5. Clinical validation**
- RNA-FISH (PECAM1/TPSB2 + COL1A1 + VIM) to confirm fibroblast expression
- IHC for MMP1, FOXC2, KLK6, TPSB2 in 19 keloid patients; correlation with Vancouver Scar Scale (VSS), thickness, hardness, pain, itch, vascularity

---

## Results

**Fibroblasts dominate keloid cell composition and communication**
Of 44,463 cells across 9 cell types, endothelial cells and fibroblasts predominated in all samples. Cell communication analysis showed fibroblasts as the principal interactors with the highest communication frequency and outgoing interaction strength, and global communication activity was significantly enhanced in keloids versus normal scars.

**Fibroblast subtype 3 expands in keloid with a POSTN/ASPN/COMP signature**
The 13,925 fibroblasts resolved into 6 subtypes: fibroblasts 1 and 2 predominated in normal scar, while fibroblast 3 dominated keloids. Fibroblast 3 highly expressed POSTN, ASPN, and COMP (previously linked to keloid formation), interacted most frequently with other subtypes (COL1A1/COL1A2 as key connectors), and was enriched for collagen formation and ECM-receptor interaction pathways—recapitulating the expanded mesenchymal fibroblast of prior keloid scRNA-seq work.

**Trajectory analysis and clinical integration define 25 DEFDRGs**
Monocle 2 reconstructed 7 differentiation states, with fibroblast 3 occupying intermediate-late pseudotime (States 3–6). Intersecting 14,467 FDRGs with diagnosis- and time-significant DEGs yielded 25 clinically relevant DEFDRGs, mostly positively correlated except KLK6 and TPSB2, which were negatively correlated with the others.

**Three molecular subtypes (LFDC/MFDC/HFDC) stratify keloid severity**
Consensus clustering of the 25 DEFDRGs produced three subtypes. The PCA fibroblast score was lowest in cluster 1 (LFDC), intermediate in cluster 2 (MFDC), and highest in cluster 3 (HFDC). FDBKC was significantly associated with diagnosis and time (P < 0.001): healthy samples fell mainly in cluster 1, keloid samples (day 0 and day 42) mainly in cluster 3. Subtype markers were LFDC (MMP1, F13A1), MFDC (FOXC2, MDK), and HFDC (KLK6, TPSB2). The bulk-RNA-seq LASSO model (11 DEFDRGs) predicted keloid diagnosis with AUC 0.995 (train) / 0.868 (test); high risk was associated with age <30, female sex, prolonged time, and keloid diagnosis.

**Regulatory networks, candidate drugs, and clinical correlation**
RUNX1 was a common upstream transcription factor across all three subtypes and is implicated in fibrosis. Subtype-specific hubs included CLEC11A/MDK (LFDC), PECAM1/LMO2 (MFDC), and KLK6/F13A1 (HFDC, with F13A1 linked to Wnt/β-catenin signaling). RNA-FISH confirmed keloid fibroblasts express PECAM1 and TPSB2. CMap nominated small-molecule inhibitors per subtype, with Ouabain (a Na⁺/K⁺-ATPase inhibitor with reported anti-fibrotic, TGF-β-suppressing activity) highlighted for HFDC. IHC in 19 patients (12 HFDC, 3 MFDC, 4 LFDC) matched the classification: MMP1 highest in LFDC, FOXC2 highest in MFDC, KLK6/TPSB2 highest in HFDC. HFDC keloids had significantly higher VSS scores, were thicker (~83% >2 mm), harder, and more often painful, itchy, and vascularly abnormal—confirming HFDC as the most severe subtype.

---

## Perspective

This study delivers the first fibroblast-differentiation-based molecular classification of keloids (FDBKC), integrating single-cell trajectory analysis, bulk transcriptomics, clinical metadata, and IHC validation into a three-tier system (LFDC/MFDC/HFDC) that tracks disease severity.

First, by anchoring the classification in the fibroblast differentiation trajectory rather than static biomarkers, it links molecular subtype to a mechanistic axis—fibroblast fate determination—and provides endogenously expressed, cell-of-origin markers (MMP1, F13A1, FOXC2, MDK, KLK6, TPSB2) with therapeutic potential. The HFDC subtype, marked by inflammation- and fibrosis-associated KLK6 and mast-cell tryptase TPSB2, corresponds to clinically harder, thicker, more symptomatic keloids.

Second, the recurrent identification of fibroblast subtype 3 with a POSTN/ASPN/COMP mesenchymal signature converges with independent keloid and cross-tissue fibroblast atlases, reinforcing an expanded, differentiation-advanced mesenchymal fibroblast as the core pathogenic population in skin fibrosis. RUNX1 emerges as a shared upstream regulator worth investigating in skin fibrosis.

Third, the CMap-nominated inhibitors—especially Ouabain for HFDC via TGF-β/α-SMA suppression—offer testable precision-therapy hypotheses aligned with the vault's fibrosis and anti-fibrotic themes, and the differentiation-state framework echoes the dedifferentiation/redifferentiation logic central to cartilage regeneration.

Limitations include the small scRNA-seq cohort (3 keloids), reliance on in silico predictions requiring experimental validation, and immune-infiltration findings inconsistent with prior mast-cell studies, which the authors attribute to limited sample size and individual variation.


## Data Availability

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE188952, GSE7890, GSE163973, GSE113619, GSE44270
- SRA: SRP137071


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
