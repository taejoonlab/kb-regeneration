---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p02.txt
---

# Comparison of the major cell populations among osteoarthritis, Kashin-Beck disease and healthy chondrocytes by single-cell RNA-seq analysis

## Citation (NLM)

Wang X, Ning Y, Zhang P, Poulet B, Huang R, Gong Y, Hu M, Li C, Zhou R, Lammi MJ, Guo X. Comparison of the major cell populations among osteoarthritis, Kashin-Beck disease and healthy chondrocytes by single-cell RNA-seq analysis. _Cell Death Dis._ 2021 Jun 3;12(6):551. doi: [10.1038/s41419-021-03832-3](https://doi.org/10.1038/s41419-021-03832-3).

---

## Background

Kashin-Beck disease (KBD) is a chronic degenerative osteochondral disease endemic to specific regions such as northwestern China, characterized by shortened and enlarged fingers in early stages, and joint deformity, movement restriction, and dwarfism in advanced stages. Osteoarthritis (OA) is the most common degenerative joint disease in the elderly. Both diseases share similar pathological findings such as extracellular matrix (ECM) degradation, cartilage lesions, and reduced proteoglycan and collagen, but differ in onset age, symptoms, X-ray findings, and etiology. KBD typically initiates with chondrocyte necrosis in the deep zone of cartilage, whereas OA begins with progressive degeneration in the superficial zone. However, comparative studies considering chondrocyte heterogeneity are lacking, and the cell population-level differences between the two diseases remain unclear. This study aimed to systematically compare the major cell populations of KBD, OA, and healthy cartilage using single-cell RNA sequencing (scRNA-seq) and to identify disease-specific cell populations and markers.

---

## Key Experiment Methods

**1. Cartilage sample collection and chondrocyte isolation**

- Knee joint articular cartilage collected from KBD patients, OA patients, and healthy controls (trauma/amputation patients)
- KBD diagnosed according to Chinese national diagnostic criteria (WS/T 207-2010), OA diagnosed by Modified Outerbridge Classification
- Enzymatic digestion: 0.25% trypsin (30 min) → 0.2% type II collagenase (12-16 hours)
- Single-cell suspension preparation after 70 μm nylon filter filtration

**2. Single-cell RNA sequencing (scRNA-seq)**

- 10× Chromium Single Cell 3′ Library V2 platform
- Sequencing on Illumina NovaSeq6000 (≥57,374 reads per cell, PE150)
- Total of 16,375 cells analyzed (KBD 6,140, OA 5,834, healthy 4,401)
- Clustering with Seurat 3.0 (cells with gene count <200 or >top 1%, mitochondrial ratio >25% excluded)
- t-SNE and UMAP visualization

**3. Cell differentiation trajectory analysis**

- Pseudotime trajectory reconstruction with Monocle
- PAGA (Partition-based graph abstraction) analysis

**4. Marker gene validation**

- Immunohistochemistry (IHC): SH3BGRL3, IGFBP5, BIRC5, SOX9, EIF5A, CDC20, MT-ND1, MT1X, AEBP1, CHI3L1, STEAP1, CENPW, PTTG1, etc.
- qRT-PCR: MT-ND1, MT1X, AEBP1, CHI3L1, etc.

**5. WGCNA and cell type annotation**

- Gene co-expression network analysis using WGCNA (R package)
- Cell type annotation based on reference datasets (Human Primary Cell Atlas, blueprint_encode) using SingleR

---

## Results

**Identification of 7 cell populations in healthy cartilage**

Seven cell populations were identified in healthy human cartilage by scRNA-seq analysis:
1. Fibrocartilage cells-1 (FCs-1): SH3BGRL3, S100A6, MYL9
2. Fibrocartilage cells-2 (FCs-2): IGFBP5, LMCD1
3. Chondroprogenitor cells-1 (CPCs-1): CDC20, UBE2C, CENPF, CKAP2
4. Regulatory chondrocytes (RegCs): EIF5A, PGK1, ANXA1, TUBA1A
5. Pre-hypertrophic chondrocytes (preHTCs): SOX9, COL9A3, COL11A1
6. Homeostatic chondrocytes (HomCs): TXNIP, IFITM3, GDF15, TIMP1
7. Chondroprogenitor cells-2 (CPCs-2): KIAA0101, BIRC5, CDKN3, TMN1

In pseudotime analysis, CPCs-1/2 were located at the root, branching into fate 1 (FCs-1/RegCs) and fate 2 (FCs-2/preHTCs/HomCs). IHC showed FCs mainly distributed in the superficial/middle zones, CPCs in the middle/deep zones, RegCs in the superficial zone, and preHTCs in the superficial/deep zones.

**Integrated analysis of KBD, OA, and healthy cartilage: 10 populations + 1 novel population**

Integrated analysis of the three groups identified 10 existing populations and a novel population, **mitochondrial chondrocytes (MTCs)**:
- PreHTCs: 3 subpopulations (S100A4hi, COL9A3hi, AKR1C1hi)
- RegCs: 2 subpopulations (CTNNB1hi, CHI3L1hi)
- MTCs (novel): 2 subpopulations (MT-ND1hi, MT-CO1hi) — expressing genes related to mitochondrial electron transport and hydrogen peroxide response
- FCs: 2 subpopulations (IGFBP5hi, COL14A1hi)

CPC cells (cluster 8) were present only in normal cartilage and were largely lost in OA and KBD.

**Expanded cell populations in KBD: HomCs and MTCs**

HomCs (expressing MT1X, MT2A, MT1E, ATF5, DDIT3) and MTCs (expressing MT-ND1, MT-ATP6, MT-ND2, MT-ND3) were markedly expanded in KBD. IHC showed MTCs mainly distributed in the middle/deep zones and HomCs in the superficial zone. qRT-PCR showed increased MT-ND1 and MT1X expression in KBD patients, consistent with scRNA-seq results. Metallothionein (MT) is involved in metal detoxification, antioxidant defense, immune defense, and cell differentiation, and is important for regulating intracellular ROS levels, suggesting that HomCs may play a protective role against oxidative stress in KBD.

**Expanded cell populations in OA: RegCs**

RegCs identified by CHI3L1, AEBP1, PLIN2, and STEAP1 expression were markedly expanded in OA. IHC showed AEBP1 upregulated in the superficial/middle zones, and CHI3L1 and STEAP1 upregulated in the superficial/middle/deep zones of OA cartilage. qRT-PCR showed increased AEBP1 and CHI3L1 expression in OA patients.

**Pseudotime trajectory: divergence of KBD and OA**

Monocle analysis positioned normal cartilage cells at the trajectory starting point, branching into two fates: fate 1 was predominantly filled with KBD cells, and fate 2 with OA cells. In fate 1 (KBD), FN1, CHI3L2, RGCC, COL9A3, and MDFI were markedly upregulated, while in fate 2 (OA), HMOX1, COL1A1, WISP2, CD9, PCOLCE, IGF1, VCAN, PCSK5, and SPP1 were upregulated. This suggests that the two diseases activate different gene programs from an early branching point.

**Re-clustering analysis**

Re-clustering of PreHTCs, HTCs, RegCs, and effector chondrocytes (ECs) further subdivided them into HTC-A (IGF2, SLC5A3), HTC-B (MMP3, GDF5), PreHTCs (S100A4, HLA-B), ECs (MIA, PLA2G2A), and RegCs (CHI3L1, AEBP1). Re-clustering of FCs identified RPS4Y1hi, COL3A1hi, FGF1+, IGFBP6+, and COL14A1+ subpopulations. When KBD and OA were analyzed separately, ECs showed the same marker pattern (MIA, S100B, FRZB, C2orf82, S10A1) in both diseases, whereas HTCs in KBD were defined by IBSP, MMP13, RUNX2, and TMEM119.

---

## Perspective

This study is the first to systematically compare the single-cell transcriptomes of KBD and OA cartilage, demonstrating that the two diseases exhibit distinct differences at the chondrocyte population level. In KBD, HomCs and MTCs associated with mitochondrial function and oxidative stress response were expanded, suggesting that mitochondrial dysfunction and mitochondria-mediated cell death are central to KBD pathogenesis. In OA, CHI3L1+ RegCs were expanded, highlighting inflammatory and tissue remodeling responses. The loss of CPCs, which are abundant only in normal cartilage and depleted in diseased cartilage, may be associated with the loss of cartilage regenerative capacity. These disease-specific cell populations and marker genes provide important resources for molecular-level differential diagnosis and targeted therapy development for KBD and OA. In particular, MTCs and HomCs may provide clues linking the endemic characteristics of KBD (selenium deficiency, mycotoxins, etc.) with oxidative stress. Limitations of this study include small sample sizes (3 pairs per group) and the possibility of sex bias since all OA samples were collected from females. Future validation with larger cohorts and inducible Col2-CreERT models is needed.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
