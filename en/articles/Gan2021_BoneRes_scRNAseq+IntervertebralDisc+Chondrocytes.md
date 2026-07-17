---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Spatially defined single-cell transcriptional profiling characterizes diverse chondrocyte subtypes and nucleus pulposus progenitors in human intervertebral discs

## Citation (NLM)

Gan Y, He J, Zhu J, Xu Z, Wang Z, Yan J, Hu O, Bai Z, Chen L, Xie Y, Jin M, Huang S, Liu B, Liu P. Spatially defined single-cell transcriptional profiling characterizes diverse chondrocyte subtypes and nucleus pulposus progenitors in human intervertebral discs. _Bone Res._ 2021 Oct 11;9(1):37. doi: [10.1038/s41413-021-00163-z](https://doi.org/10.1038/s41413-021-00163-z).

---

## Background

Degenerative disc disease (DDD) is a major cause of low back pain, imposing enormous healthcare burdens and socioeconomic costs worldwide. Current DDD treatments (rest, rehabilitation, medication, interventional therapy, surgery) only provide symptomatic relief and do not reset intervertebral disc (IVD) homeostasis. The healthy human IVD consists of three components: the central nucleus pulposus (NP), the surrounding annulus fibrosus (AF), and the cartilage endplate (CEP) adjacent to the vertebral body. The IVD has a heterologous origin, with the NP derived from the notochord and the AF and CEP from the sclerotome. Existing bulk RNA sequencing has been limited in elucidating the molecular mechanisms of degeneration due to the high heterogeneity and complex microenvironment of IVD cells. This study aimed to construct a single-cell transcriptomic atlas of healthy human IVD (NP, AF, CEP) to spatially characterize cellular heterogeneity, identify progenitor populations within the NP, and analyze intercellular signaling networks in the NP microenvironment.

---

## Key Experiment Methods

**1. Human IVD specimen collection and scRNA-seq**

- NP, AF, and CEP isolated from 5 healthy human IVDs (Pfirrmann grade I)
- 128,833 cells profiled by 10X Genomics Chromium droplet-based scRNA-seq; 108,108 cells analyzed after quality control
- Batch effect correction with fastMNN, clustering by tSNE

**2. Cell type identification and validation**

- 9 root clusters identified by marker genes: SOX9/ACAN/COL2A1 (chondrocytes), TBXT/KRT8 (notochordal cells), PDGFRA/PRRX1/IGF1 (NP progenitor cells), ACTA2/TAGLN/MCAM (pericytes), PECAM1/CD34/CDH5 (endothelial cells)
- Spatial distribution of SOX9, PDGFRA, ACTA2, PECAM1 validated by immunohistochemistry

**3. Chondrocyte subpopulation characterization**

- 3 chondrocyte clusters subdivided into 6 subclusters (C1–C6)
- Functional and ECM matrisome gene expression patterns analyzed by GO analysis, PANTHER, and MatrisomeDB
- Pearson correlation analysis with human articular cartilage OA stage data (Ji et al.)

**4. NP progenitor cell (NPPC) analysis**

- NPPCs subdivided into 4 subclusters (NPPC-1 to 4)
- Transcription factor regulon analysis by SCENIC (HOXA10, SOX4, SMAD3, GLI1, etc.)
- NPPC-3 identified by PDGFRA/PROCR surface markers, isolated by flow cytometry
- Clonogenicity evaluated by CFU-F colony formation assay
- SMAD3 activation confirmed by p-SMAD3 immunofluorescence

**5. Differentiation trajectory reconstruction**

- Monocle 3 used to reconstruct chondrogenic and osteogenic branch trajectories with NPPC-3 as starting point
- 16 gene modules identified by Louvain community analysis
- Trilineage (osteogenic, chondrogenic, adipogenic) differentiation capacity of PROCR+ cells validated (Alizarin Red, Oil Red O, Alcian Blue, Safranin O/Fast Green staining)

**6. Intercellular signaling network analysis**

- Ligand-receptor interactions among 14 subclusters within NP analyzed by CellChat
- VEGF, TGFB, PDGF, FGF signaling networks analyzed in detail
- Chondrogenic differentiation of PROCR+ cells with TGF-β3 (10 ng/mL) and SB505124 (TGF-β receptor inhibitor)
- Proliferation analysis of PROCR+ cells with PDGF-AA (20 ng/mL) and crenolanib (PDGFR α/β inhibitor) by CCK-8

**7. Cross-species comparison**

- Comparison of human and rat IVD scRNA-seq data to confirm conserved cellular heterogeneity

---

## Results

**Identification of major IVD cell types** 9 root clusters were identified from 108,108 cells: 3 types of SOX9+ chondrocytes (Chond1-3), notochordal cells, stromal cells, pericytes, endothelial cells, NP progenitor cells (NPPC), and blood cells. Spatially, chondrocytes and stromal cells were abundant in NP, CEP, and AF, while notochordal cells were primarily distributed in the NP. PDGFRA+ NPPCs were mainly distributed in the NP and rarely in AF and CEP.

**Characterization of 6 chondrocyte subpopulations** C1 showed high expression of growth factor genes such as BMP2/TGFB1/FGF2 (regulatory chondrocytes), C3/C4 showed high expression of ECM components such as ACAN/COL2A1 (homeostatic chondrocytes), and C5/C6 showed high PRG4/CNMD expression and high metabolic rate (effector chondrocytes). C1/C2 were mainly located in AF and CEP, while C5 was primarily in NP. Matrisome analysis showed C1 predominantly expressed secreted factors, C3 expressed core matrisome (collagens, proteoglycans, ECM glycoproteins), and C5 expressed ECM regulators.

**Identification of 4 NPPC subpopulations and PROCR+ cells** NPPCs were subdivided into NPPC-1 (PAX1+), NPPC-2 (ANGPT1+), NPPC-3 (PRG4+/PROCR+), and NPPC-4 (SOX9+). NPPC-3 specifically expressed PROCR, suggesting stem cell characteristics (stemness). The frequency of PDGFRA+PROCR+ cells was 0.36% in NP, and PROCR+ cells showed significantly higher CFU-F formation capacity (25.9±3.3 vs 2.9±1.4 per 1,000 cells, p<0.0001). p-SMAD3 expression was elevated in PROCR+ cells, confirming SMAD3/TGF-β pathway activation.

**Bilineage differentiation trajectory of PROCR+ cells** Monocle 3 analysis showed that NPPC-3 (PROCR+) branched into a chondrogenic branch (NPPC-3→NPPC-1→Chond2→Chond3) and an osteogenic branch (NPPC-3→NPPC-2→NPPC-4→osteogenic cells→Fib3). In vitro, PROCR+ cells confirmed trilineage differentiation capacity (osteogenic, chondrogenic, adipogenic).

**NP microenvironment signaling network** CellChat analysis showed that NPPC clusters served as key contributors (secreting PDGFA ligands) in the PDGF signaling network. The TGF-β pathway mediated interactions between chondrocyte and NPPC clusters via TGFB3-TGFBR/ACVR1 signaling. TGF-β3 induced chondrogenic differentiation of PROCR+ cells, which was blocked by the TGF-β receptor inhibitor SB505124. PDGF-AA promoted PROCR+ cell proliferation, which was inhibited by the PDGFR inhibitor crenolanib. Fib3 was involved in nearly all pathways including VEGF, PDGF, and FGF, playing an important role in NP homeostasis.

**Cross-species conservation** Re-analysis of rat IVD scRNA-seq data confirmed that the same cell clusters (NPPC, endothelial cells, pericytes) and gene expression patterns (PDGFRA, PRRX1, IGF1) were conserved between human and rat.

---

## Perspective

This study constructed the first spatial single-cell transcriptomic atlas of healthy human IVD, classifying IVD chondrocytes into three functional subtypes (regulatory, homeostatic, effector) and identifying a PROCR+ multipotent progenitor cell population within the NP. PROCR+ cells possess CFU-F formation capacity and trilineage differentiation ability, and play a critical role in maintaining NP homeostasis by responding to TGF-β and PDGF signaling.

CellChat-based signaling network analysis revealed that PDGF and TGF-β cascades are key cues for intercellular crosstalk in the NP microenvironment, and identified Fib3 as a hub cell type involved in multiple signaling pathways. This provides an important foundation for understanding the mechanisms of NP cell homeostasis loss in degenerative disc disease (DDD) and for developing cell-based regenerative therapeutic strategies targeting PROCR+ progenitor cells.

Future studies should include comparison of single-cell atlases in degenerated IVDs (Pfirrmann grade III-IV), in vivo validation of PROCR+ cell regenerative capacity, and therapeutic approaches for DDD through modulation of PDGF/TGF-β signaling. The IVD cell markers and signaling networks established in this study will serve as valuable resources for discovering new therapeutic targets in DDD.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
