---
tags: [2026-06, Chondrocyte]
extract: 2026-06-08
log:
  - "2026-06-08 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Combining Bulk and Single-Cell RNA-Sequencing Data to Reveal Gene Expression Pattern of Chondrocytes in the Osteoarthritic Knee

## Citation (NLM)
Li X, Liao Z, Deng Z, Chen N, Zhao L. Combining bulk and single-cell RNA-sequencing data to reveal gene expression pattern of chondrocytes in the osteoarthritic knee. Bioengineered. 2021;12(1):997-1007. doi:10.1080/21655979.2021.1903207

**DOI:** [https://doi.org/10.1080/21655979.2021.1903207](https://doi.org/10.1080/21655979.2021.1903207)

---

## Background
Osteoarthritis (OA) is the most common joint disease characterized by cartilage degeneration, affecting approximately 240 million people worldwide. Bulk RNA-seq provides transcriptomic information from whole tissues but obscures differences between individual cells, while single-cell RNA-seq (scRNA-seq) provides expression profiles of individual cells but is limited in depth of transcriptomic coverage. Although both types of sequencing data for OA knee chondrocytes are available separately, integrated analyses to comprehensively understand the molecular mechanisms of OA pathogenesis have been lacking. This study aimed to integrate bulk RNA-seq and scRNA-seq analyses to characterize gene expression patterns in OA chondrocytes and to identify key transcription factor (TF) and long noncoding RNA (lncRNA) regulatory networks.

---

## Key Experiment Methods
1. Collection of bulk RNA-seq data (GSE114007, 38 samples: 18 normal, 20 OA) and scRNA-seq data (GSE104782, 10 OA patients, 1,464 chondrocytes) from the GEO database
2. Differential expression gene (DEG) analysis of bulk RNA-seq using the R package DESeq2 (adjusted p < 0.05, |fold change| > 2)
3. Identification of gene modules most strongly correlated with OA using the R package WGCNA (signed network, scale-free topology fit index 0.85)
4. Pseudotime analysis of scRNA-seq using the R package Monocle 2 — tracking dynamic gene expression changes in chondrocytes across pathological stages (S0–S4)
5. Identification of core genes through intersection analysis of DEGs, WGCNA module genes, and pseudotime-associated genes
6. Identification of transcription factors and key transcriptional regulators using HumanTFDB v3.0 and TRRUST v2 databases
7. Analysis of lncRNA and target gene regulatory relationships using HGNC BioMart and LncTarD databases
8. GO and KEGG pathway enrichment analysis using clusterProfiler

---

## Results
1. Bulk RNA-seq analysis identified 1,375 upregulated DEGs and 1,026 downregulated DEGs in OA — major upregulated pathways included ECM, focal adhesion, and CAMs; downregulated pathways included MAPK, FoxO, HIF-1, and TNF signaling
2. The WGCNA module most strongly positively correlated with OA (1,240 genes) was enriched in ECM-related pathways, while the most strongly negatively correlated module (731 genes) was enriched in FoxO and HIF-1 signaling pathways
3. Pseudotime analysis showed a trend of increasing pseudotime values with disease progression, with inflammatory genes (CCL3, CXCL8, IL1B) upregulated early and ECM genes (COL1A1, COL1A2, PRG4) upregulated later
4. The intersection of the three analyses yielded 271 core genes (183 upregulated, 88 downregulated)
5. Fourteen transcription factors (MAFB, HMGB3, GLI3, SOX11, NR1D1, HMGB2, etc.) were identified, with TWIST2, MYBL2, RELA, JUN, KLF4, and PTTG1 confirmed as major transcriptional regulators of the 271 core genes
6. Eight lncRNAs (FZD10-AS1, PART1, ISM1-AS1, SILC1, CYTOR, ILF3-DT, HG1, S6-AS1) were identified
7. A potential ceRNA mechanism in which CYTOR sponges miRNA-206 to positively regulate NRP1 was suggested to also exist in OA — NRP1 is a co-receptor for vascular endothelial growth factor (VEGF) and semaphorin, potentially contributing to cartilage angiogenesis and pain
8. Activation of the PTTG1 → S100A4/LGALS1 axis was identified as a potential driver of inflammation and catabolic signaling in OA cartilage

---

## Perspective
This study is the first attempt to multidimensionally characterize gene expression patterns in OA chondrocytes through integrated analysis of bulk RNA-seq (DEG + WGCNA) and scRNA-seq (pseudotime). It systematically presents the molecular network of OA pathology by identifying 271 core genes, 14 transcription factors, 6 major transcriptional regulators, and 8 lncRNAs. In particular, the potential involvement of the CYTOR–NRP1 axis in cartilage angiogenesis and pain, and the regulation of inflammatory signaling by PTTG1 through S100A4/LGALS1, represent promising therapeutic targets. The downregulation of HIF-1 signaling suggests that reduced hypoxic adaptation of chondrocytes contributes to OA progression. Limitations include the substantial age difference between control and OA groups (36.6 vs. 66.2 years) and the purely bioinformatic approach, which requires experimental validation. Future functional validation of the proposed regulatory networks and pathways will contribute to understanding the molecular mechanisms of OA and to the development of therapeutics.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*
