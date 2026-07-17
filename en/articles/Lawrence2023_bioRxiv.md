---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
---

# Single cell transcriptomics reveals chondrocyte differentiation dynamics in vivo and in vitro

## Citation (NLM)
Lawrence JEG, Woods S, Roberts K, Sumanaweera D, Balogh P, Predeus AV, He P, Li T, Polanski K, Prigmore E, Tuck E, Mamanova L, Zhou D, Webb S, Jardine L, He X, Barker RA, Haniffa M, Flanagan AM, Young MD, Behjati S, Bayraktar O, Kimber SJ, Teichmann SA. Single cell transcriptomics reveals chondrocyte differentiation dynamics in vivo and in vitro. bioRxiv. 2023. doi:10.1101/2023.12.20.572425

**DOI:** [https://doi.org/10.1101/2023.12.20.572425](https://doi.org/10.1101/2023.12.20.572425)

---

## Background
Consistent production of in vitro chondrocytes that faithfully recapitulate embryonic development is critical for cartilage regenerative medicine and musculoskeletal disease modeling. Current in vitro chondrogenesis protocols are limited by off-target differentiation, resulting in heterogeneous products. The lack of comparison to human embryonic tissue precludes detailed evaluation of in vitro cells.

## Key Experiment Methods
1. Single-cell RNA sequencing (scRNA-seq) on human first-trimester (7-9 PCW) hindlimb long bones (72,944 cells)
2. Integration with public datasets to build a 249,151-cell developmental atlas spanning 5-17 PCW
3. Spatial mapping via k-nearest neighbor analysis with 90-gene in-situ sequencing (ISS) data
4. Comparison of in vitro chondrogenesis protocol bulk/scRNA-seq data against the atlas using CellSignalAnalysis
5. Genes2Genes dynamic programming trajectory alignment between in vivo and in vitro cells
6. FOXO1 inhibitor (AS1842856) treatment to suppress off-target osteoblastic differentiation
7. RNA in situ hybridization (FISH) for marker gene expression validation

## Results
- Identified diverse cell populations in the single-cell atlas: chondroprogenitors (PRRX1+, TWIST1+, FOXP1/2+), early resting/resting chondrocytes, proliferating, prehypertrophic, hypertrophic chondrocytes, interzone cells (GDF5+PRG4- and GDF5+PRG4+), and articular chondrocytes (PRG4+, AQP1+, TPPP3+, COL2A1-)
- Proximo-distal developmental gradient: femora contained more mature chondrocytes than tibiae/fibulae
- TF network analysis: SOX9, KLF4, STAT3 showed increasing activity across chondrogenesis; HAND1 specific to chondroprogenitors; DLX3/NFAT5/KLF15 active in prehypertrophic/hypertrophic chondrocytes; FOXO1 active in osteoblasts; FOXO3 active in hypertrophic chondrocytes
- In vitro protocol evaluation: MSC-based protocols matched fibrous/osseous types; BMP4 protocol matched hypertrophic chondrocytes; TGF-β protocol enhanced articular signal
- Genes2Genes trajectory alignment: only 58% of highly variable genes matched between in vivo and in vitro; SOX6, SOX9, KLF2, KLF4 matched well, while COL1A1, ALPL, SPP1, SP7, FOXO1 were aberrantly expressed in vitro
- FOXO1 inhibitor (AS18, 4-20 nM) increased expression of chondrocyte genes (COL2A1, COL9A1, MATN3, COMP) and hypertrophy markers (COL10A1, PTH1R), while downregulating osteoblastic genes (DDX5, KCNQ1OT1, SNHG14)

## Perspective
This study presents a new framework for evaluating and improving tissue engineering protocols using single-cell data from human development. The proof-of-principle demonstration that FOXO1 inhibition increases chondrocyte gene expression shows that embryonic development data can guide musculoskeletal tissue engineering. Future work targeting transcription factors should minimize off-target transcription and more faithfully recapitulate in vivo cell states. Limitations include scRNA-seq challenges with matrix-rich tissues, sampling window ending at PCW17, and inter-experiment variability in differentiation protocols.

---

*Processed by **qwen3.6-plus** (OpenCode Go) on 2026-06-07*
