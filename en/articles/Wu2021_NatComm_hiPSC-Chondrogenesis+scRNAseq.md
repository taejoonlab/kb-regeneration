---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Single cell transcriptomic analysis of human pluripotent stem cell chondrogenesis

## Citation (NLM)
Wu CL, Dicks A, Steward N, Tang R, Katz DB, Choi YR, Guilak F. Single cell transcriptomic analysis of human pluripotent stem cell chondrogenesis. Nat Commun. 2021 Jan 14;12(1):362. doi:10.1038/s41467-020-20598-y. PMID: 33446649.

**DOI:** [https://doi.org/10.1038/s41467-020-20598-y](https://doi.org/10.1038/s41467-020-20598-y)

---

## Background

Osteoarthritis (OA) is a disease characterized by cartilage degeneration, and the limited self-renewal capacity of cartilage has driven interest in stem cell-based regenerative therapies. Human induced pluripotent stem cells (hiPSCs) have emerged as a key resource for in vitro disease modeling for cartilage regeneration therapy and OA drug discovery. However, consistently differentiating hiPSCs into chondrocytes remains challenging, as off-target cell populations (such as neurons and melanocytes) are generated unpredictably during differentiation, reducing the yield and homogeneity of chondrocytes. The gene regulatory networks (GRNs) driving these off-target differentiation pathways and the heterocellular signaling mechanisms by which off-target cells affect chondrogenesis had not been characterized at single-cell resolution.

---

## Key Experiment Methods

**1. Stepwise hiPSC chondrogenic differentiation protocol**
- Three independent hiPSC lines (STAN, ATCC, BJFF) used
- Stepwise mesoderm differentiation: Activin A/CHIR99021/FGF-2 (anterior primitive streak) → SB-505124/CHIR/FGF-2/dorsomorphin (paraxial mesoderm) → sclerotome → chondroprogenitor (Cp, BMP4 treatment)
- After Cp stage, 3D pellet culture with TGF-β3 for up to 42 days of chondrogenic differentiation

**2. Bulk RNA sequencing (bulk RNA-seq)**
- 6 mesoderm stages + 5 chondrogenic stages from 3 hiPSC lines (total 33 samples)
- Stage-wise differential expression gene (DEG) analysis using DESeq2
- GO enrichment analysis using GAGE package

**3. Single cell RNA sequencing (scRNA-seq)**
- 10× Chromium platform; 9 time points from hiPSC to d42 (>19,000 cells passed QC)
- Seurat (CCA alignment, unsupervised clustering, tSNE visualization), Monocle2 (pseudotime trajectory) analysis
- Additional scRNA-seq on WNT-inhibited (C59-treated) pellets (total 14,683 cells)

**4. Weighted Gene Co-expression Network Analysis (WGCNA)**
- GRN reconstruction using d14 pellet scRNA-seq data (2,148 cells, 3,784 genes)
- Cytoscape visualization of neurogenesis and melanogenesis subnetworks; hub genes determined by degree, weight, and betweenness centrality (BC)

**5. WNT inhibition and MITF inhibition experiments**
- Pan-WNT inhibitor Wnt-C59 (C59, 1 µM) and MITF antagonist ML329 (ML, 1 µM) alone or in combination in pellet culture
- Flow cytometry measuring CD146+/CD166+/CD45− progenitor cell ratio at Cp stage

**6. Individual WNT ligand treatment experiments**
- WNT2B, WNT3A, WNT4, WNT5B, WNT7B (100 ng/mL each) in pellet culture
- RT-qPCR (SOX9, ACAN, COL2A1, COL1A1), GAG/DNA ratio, IHC for cartilage phenotype assessment

**7. Heterocellular signaling model**
- Quantification of WNT-FZD receptor-expressing cell ratios from scRNA-seq data using a database of 2,557 human ligand-receptor pairs
- Multicellular signaling direction visualization with Circlize R package

**8. In vivo experiments**
- Subcutaneous and knee osteochondral defect model transplantation of d14 pellets in immunodeficient NSG mice (histological evaluation after 14-28 days)

---

## Results

**Identification of off-target cell identity** scRNA-seq and Monocle2 trajectory analysis revealed lineage bifurcation into neuronal (expressing NES, OTX2, SOX2, WNT3A) and MITF+ melanocyte lineages in addition to the cartilage lineage during hiPSC differentiation. Cells expressing neural crest markers (PAX3, FOXD3) first appeared at the Cp stage, and black pigmentation on the pellet surface was confirmed by IHC to be due to melanocytes.

**Hub gene identification by WGCNA** WGCNA analysis of d14 pellets identified **WNT4** as a key hub gene of the neurogenesis GRN and **WNT2B** as a hub gene of the melanogenesis GRN. WNT2B showed high correlation with MITF and ETV1.

**WNT inhibition improves chondrogenic differentiation homogeneity** C59 treatment during pellet culture markedly reduced off-target cells and significantly increased Saf-O staining and GAG/DNA ratio (p=0.00001, d28). C59 treatment at the Cp stage, however, inhibited differentiation. RNA-FISH showed reduced WNT3A/WNT4 expression and homogeneous COL2A1 distribution in C59-treated pellets.

**WNT heterocellular signaling model** WNT3A, WNT4, and WNT7B were primarily secreted by neuronal cells, and WNT2B by melanocytes (30%), while the WNT receptor FZD2 was expressed in 31.6% of chondrocytes, suggesting a heterocellular signaling pathway in which WNTs secreted by off-target cells induce chondrocyte hypertrophy. In individual WNT treatment experiments, WNT3A significantly reduced GAG/DNA ratio, and several WNTs increased COL10A1 expression and COL1A1 staining.

**Chondrocyte subpopulation characterization** scRNA-seq of C59-treated pellets identified 4 conserved chondrocyte subpopulations: (1) HMGB2/CDK1+ proliferating chondrocytes, (2) IGFBP5+ early differentiating chondrocytes, (3) LECT1/EPYC/FRZB+ early maturing chondrocytes (highest COL2A1/ACAN expression), (4) ISG15/IFI6/MX1+ mature-hypertrophic chondrocytes. In the mature-hypertrophic subset, IGFBP3 was suggested to alleviate chondrocyte hypertrophy by activating STAT-1 and suppressing FOS expression.

**In vivo cartilage regeneration confirmation** In an NSG mouse knee osteochondral defect model, d14 pellet transplantation resulted in defect repair with proteoglycan- and COL2A1-rich cartilage matrix at 28 days. Non-transplanted controls showed only fibrous tissue.

---

## Perspective

This study is the first comprehensive investigation systematically characterizing cellular heterogeneity and its underlying molecular mechanisms during hiPSC chondrogenesis at single-cell resolution, with the following significance.

First, combined WNT inhibition (C59) and MITF inhibition (ML329) enabled an improved differentiation protocol that removes off-target cells and produces homogeneous chondrocytes at high yield **without cell sorting**, increasing the clinical applicability of hiPSC-based cartilage regeneration therapy.

Second, off-target cells (neurons, melanocytes) were identified not merely as "contaminants" but as active sources of heterocellular signaling that promote chondrocyte hypertrophic differentiation through WNT ligand secretion, suggesting that cell composition and intercellular signaling must be considered together to improve differentiation efficiency.

Third, the existence and functional significance of novel chondrocyte subpopulations were suggested, including ISG15/IFI6/MX1+ mature-hypertrophic chondrocytes and LECT1/EPYC/FRZB+ mature chondrocytes, with full functional characterization remaining as a future research goal.

Fourth, the single-cell transcriptome-based GRN analysis approach developed in this study provides a broadly applicable roadmap for optimizing other cell differentiation processes.

Future challenges include confirming the multipotency of CD146/CD166+ progenitors, in-depth study of the interaction between C59 treatment and BMP/GDF signaling, and long-term validation of cartilage phenotype maintenance and safety after transplantation.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
