---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Single-Cell RNA Sequencing of In Vitro Expanded Chondrocytes: MSC-Like Cells With No Evidence of Distinct Subpopulations

## Citation (NLM)
Karlsen TA, Sundaram AYM, Brinchmann JE. Single-cell RNA sequencing of in vitro expanded chondrocytes: MSC-like cells with no evidence of distinct subpopulations. Cartilage. 2021;13(Suppl 2):774S-784S. doi:10.1177/1947603519847746

**DOI:** [https://doi.org/10.1177/1947603519847746](https://doi.org/10.1177/1947603519847746)

---

## Background

Autologous chondrocyte implantation (ACI) is a standard cell therapy for treating focal defects of articular cartilage. In ACI, a small tissue sample is harvested from the patient's articular cartilage, chondrocytes are isolated and expanded in vitro, and then implanted into the defect site. However, during in vitro culture, chondrocytes undergo dedifferentiation and synthesize fibrocartilage-specific ECM molecules (COL1, versican), which have inferior mechanical properties compared to normal hyaline cartilage. Although some studies suggest that stem cells or progenitor cells exist within human cartilage, whether the cultured chondrocyte population is a homogeneous cell population or consists of multiple subpopulations with different regenerative potentials remains unclear. This study used single-cell RNA sequencing (scRNA-seq) to investigate the heterogeneity of in vitro expanded human articular chondrocytes.

---

## Key Experiment Methods

- **Cell culture**: Chondrocytes isolated from femoral cartilage of osteoarthritis (OA) patients, cultured for 14 days (Passage 3). Single donor used.
- **Single-cell isolation**: FACS sorting of 86 single cells into 96-well plates at 1 cell/well.
- **scRNA-seq**: Smart-Seq2 protocol, Illumina NextSeq500, paired-end 2×25 bp. Tophat v2.0.10 alignment, Cufflinks v2.2.1 quantification. NCBI SRA: PRJNA522964.
- **Analysis**: PCA, t-SNE, Cross R² hierarchical clustering (Pearson correlation, average linkage), LIMMA differential expression analysis, MEV v4.9.0.
- **Validation**: flow cytometry (CD44, CD90, CD73, CD105, CD34, CD45, CD19, HLA-DR, etc.), single-cell RT-qPCR (COL1A1, COL3A1, B2M).
- **Multilineage differentiation confirmation**: Polyclonal chondrocyte population from the same donor differentiated into adipocytes (Oil Red O) and osteoblasts (Alizarin Red S).

---

## Results

### Single-cell transcriptome analysis
- PCA analysis: 86 single cells clustered as a single cell population. No evidence of distinct subpopulations.
- t-SNE analysis: no separate clusters observed.
- Hierarchical clustering: dendrogram at the top of the heatmap indicated clusters, but visualization revealed no distinct subpopulation patterns.
- Differential expression analysis between the two most separated clusters: no significant DE genes → confirming no systematic differences.

### Gene expression heterogeneity
- Housekeeping genes including GAPDH, B2M, and ACTB also showed large expression variability between cells: GAPDH highest/lowest 2.9-fold, B2M 4.9-fold, ACTB 30-fold difference.
- FPKM values of individual genes showed considerable variability between cells, which could be explained by continuous expression differences rather than presence of subpopulations.

### MSC characteristics of chondrocytes
- Most cultured chondrocytes expressed MSC-defining markers (CD44, CD90, CD73, CD105) and did not express hematopoietic markers (CD34, CD45, CD19, HLA-DR).
- Polyclonal chondrocyte population from the same donor could differentiate into adipocytes and osteoblasts → demonstrating that they meet International Society for Cellular Therapy (ISCT) criteria for MSCs.

---

## Perspective

- This study provides the first single-cell RNA sequencing evidence that in vitro expanded human articular chondrocytes constitute a homogeneous single cell population without distinct subpopulations.
- The considerable gene expression variability between individual cells is likely due to cell cycle, local environment, or stochastic expression differences rather than the presence of subpopulations.
- Since cultured chondrocytes meet the ISCT definition of MSCs, dedifferentiated chondrocytes used in ACI are essentially equivalent to MSCs.
- The MSC characteristics of chondrocytes may be one reason for the limited quality of regenerated tissue after ACI, highlighting the importance of developing culture conditions that induce chondrocyte redifferentiation.
- Limitations: single donor only, relatively small number of cells (86) analyzed. Future studies including multiple donors and more cells are needed.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
