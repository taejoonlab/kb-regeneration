---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# A high-resolution route map reveals distinct stages of chondrocyte dedifferentiation for cartilage regeneration

## Citation (NLM)

Chen Y, Yu Y, Wen Y, et al. A high-resolution route map reveals distinct stages of chondrocyte dedifferentiation for cartilage regeneration. _Bone Res._ 2022;10:38. doi: [10.1038/s41413-022-00209-w](https://doi.org/10.1038/s41413-022-00209-w).

---

## Background

Cartilage damage affects more than 250 million people worldwide, and autologous chondrocyte implantation (ACI) is used as an alternative for regenerative therapy. However, during in vitro expansion to obtain sufficient chondrocytes for ACI, chondrocytes undergo **dedifferentiation**, transitioning to a fibroblast-like morphology and losing their functional phenotype, which severely compromises regenerative outcomes. Previous studies suggested a **biphasic** transition during dedifferentiation, but the molecular characteristics and mechanisms of intermediate stages were not clearly defined. This study integrated single-cell RNA sequencing (scRNA-seq), live-cell metabolic analysis, and ATAC-seq to construct a high-resolution map of chondrocyte dedifferentiation for clinical application.

---

## Key Experiment Methods

**1. Mouse chondrocyte passage culture model**
- Isolation of primary chondrocytes from non-calcified cartilage of neonatal mouse knee joints
- Observation of morphological changes across P0, P2, P4, and P8 passages
- Tracking of collagen type II expression using Col2-pd2EGFP reporter mice

**2. Single-cell RNA sequencing (scRNA-seq)**
- Single-cell capture and library preparation using Fluidigm C1 workstation
- Total of 634 cells analyzed: P0 (19 cells), P2 (369 cells), P4 (187 cells), P8 (59 cells) (GSE193742)
- Identification of 4 subpopulations by Seurat unsupervised clustering
- Pseudotime trajectory analysis using Monocle

**3. Live-cell metabolic assay**
- Measurement of oxygen consumption rate (OCR) and extracellular acidification rate (ECAR) using Seahorse analyzer
- Comparison of glycolysis and oxidative phosphorylation (OXPHOS) capacity across P0, P2, P4, and P8 stages

**4. ATAC-seq analysis**
- Comparison of chromatin accessibility between P0 and P8 chondrocytes (GSE193743)
- Identification of P8-specific open chromatin regions and transcription factor binding motifs

**5. Mitochondrial F1Fo-ATPase inhibitor (BTB06584) treatment**
- BTB treatment of early (P2) and late (P4) dedifferentiated chondrocytes followed by COL2 and MMP13 expression assessment
- Measurement of cell and nuclear size, ROS production
- Bulk RNA-seq analysis of gene expression changes upon BTB treatment (MAPK pathway validation)

**6. Human chondrocyte validation and image-based prediction system**
- Validation of biphasic transition model in human chondrocytes including polydactyly patient chondrocytes (n=6)
- Construction of image analysis pipeline based on RBP4, SOD3 (early markers), IFITM3, F-actin (late markers)
- Quality assessment of donor chondrocytes using sample-to-sample distance and PCA
- Validation of predictive power for chondrogenic capacity by 3D micromass culture

---

## Results

**Construction of dedifferentiation time-series model** During serial passage, chondrocytes changed from round/polygonal to flat amoeba-like morphology with increased cell size. Col2a1 expression decreased progressively with passage, reflecting loss of functional phenotype. Comparison with existing data (GSE118236) confirmed that P0 cells represent a typical primary chondrocyte subpopulation.

**Identification of 4 cell subpopulations** scRNA-seq analysis classified four chondrocyte clusters: (1) ProC (proliferation cluster, Mki67/Top2a, cell cycle/DNA replication), (2) EcmC (ECM cluster, Col9a1/Col11a2, matrix production), (3) MetC (metabolic cluster, Rbp4/Idh1, glycolysis/antioxidant), and (4) DegC (degradation cluster, Mmp3/Mmp13, matrix degradation/inflammatory response). Cluster distribution analysis showed EcmC was dominant at P0 and P2, MetC was highest at P2 (37.8%), and DegC dominated P4 (77.1%) and P8 (74.5%).

**Pseudotime trajectory analysis** Monocle reconstruction identified a dedifferentiation trajectory of EcmC→MetC→DegC. Dynamically regulated genes were classified into five expression patterns (immediate downregulation, gradual downregulation, delayed upregulation, gradual upregulation, and oscillatory pattern). Genes related to ECM production and protein translation were broadly downregulated, while genes related to stress, inflammatory response, and collagen remodeling were upregulated.

**Glycolytic phenotype of early dedifferentiated chondrocytes** MetC exhibited a glycolytic phenotype with activation of glycolytic genes (Aldoa, Gpi1, Gapdh, etc.) and oxidative stress response genes (Sod3, Prdx5, Gpx1, etc.). Live-cell metabolic analysis showed that P2 cells had high glycolytic capacity and low mitochondrial ATP production, with higher proton leakage than P0 (protection mechanism), maintaining a glycolytic phenotype without increased ROS.

**Mitochondrial stress in late dedifferentiated chondrocytes** DegC was characterized by mitochondrial stress, mitochondrial unfolded protein response, MAPK pathway and AP-1 transcription factor activation. TEM analysis revealed damaged mitochondria, increased electron density, and abnormal structures in P4/P8 cells, while MitoTracker staining showed swelling and fragmentation. P4/P8 cells exhibited increased oxygen consumption rate (OXPHOS) and high ROS levels.

**Chromatin remodeling** ATAC-seq results showed an overall decrease in chromatin accessibility in P8 cells, but increased accessibility at promoter regions of genes related to fibrosis (Col1a1, S100a4), immune response (Ccl2, Ly6c1), and metabolic stress (Gstm2, Sod3). ATF3, BATF, and AP-1 family transcription factor binding motifs were strongly enriched in P8.

**BTB06584 treatment rescues early dedifferentiation** BTB (F1Fo-ATPase inhibitor) treatment increased COL2 expression and suppressed MMP13 expression in P2 (early) chondrocytes (Acan, Sox9, Col2a1 up; Adamts5, Mmp13 down), with a significant reduction in ROS production. Mechanistically, BTB inhibited the MAPK pathway (Mapk1, Map2k4, Map3k4) and downstream response genes (Jun, Creb3l2, Nfkb2, Atf2). In contrast, in P4 (late) cells, only MMP13 was suppressed with no recovery of COL2 expression, and no ROS reduction was observed.

**Biphasic transition model validated in human chondrocytes** Both mouse and human chondrocytes showed the same pattern: RBP4 and SOD3 increased at intermediate passages (P2/P4), while IFITM3 and F-actin increased at late passages. The constructed image-based prediction system effectively assessed donor chondrocyte quality: donor cells classified as early stage (donors 1, 3, 4) formed superior cartilage matrix in 3D micromass, while those classified as late stage (donors 2, 5, 6) showed poor chondrogenic capacity.

---

## Perspective

This study integrated scRNA-seq, live-cell metabolic analysis, and ATAC-seq to construct the first high-resolution time-series map of chondrocyte dedifferentiation, proposing a **biphasic dedifferentiation model** comprising early and late stages. The early dedifferentiation stage (P2, MetC) is characterized by transient glycolytic activation and low oxidative stress, representing a reversible phenotypic change, whereas the late stage (P4/P8, DegC) involves mitochondrial damage, increased ROS, and chromatin remodeling, representing an irreversible phenotypic loss from which recovery is difficult.

Notably, chemical manipulation with BTB06584 effectively rescued the phenotype of early dedifferentiated chondrocytes but had minimal effect on late dedifferentiated cells, highlighting the importance of appropriate timing for chondrocyte quality assessment and intervention strategies in clinical settings. The image-based biomarker prediction system offers a practical tool for clinical application, with the potential to prospectively assess the quality of chondrocytes to be used for ACI.

Future challenges include elucidating the detailed regulatory mechanisms of glycolytic metabolic reprogramming during early dedifferentiation, in-depth investigation of the epigenetic mechanisms of chromatin remodeling that determine irreversibility in late dedifferentiation, and large-scale clinical validation of the image-based prediction system.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
