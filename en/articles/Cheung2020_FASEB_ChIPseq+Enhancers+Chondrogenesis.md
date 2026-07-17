---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
---

# Histone ChIP-Seq identifies differential enhancer usage during chondrogenesis as critical for defining cell-type specificity

## Citation (NLM)

Cheung K, Barter MJ, Falk J, Proctor CJ, Reynard LN, Young DA. Histone ChIP-Seq identifies differential enhancer usage during chondrogenesis as critical for defining cell-type specificity. _FASEB J._ 2020;34:5317-5331. doi:[10.1096/fj.201902061RR](https://doi.org/10.1096/fj.201902061RR)

---

## Background

Chondrocytes are the sole cell type in articular cartilage and maintain cartilage homeostasis. Chondrogenesis is a multi-step process in which mesenchymal stem cells (MSCs) differentiate into chondrocytes, with the SOX9 transcription factor playing a central role. Gene expression is regulated by epigenetic mechanisms such as histone modifications and DNA methylation, which are important for both normal development and disease (e.g., osteoarthritis, OA). Since most OA-associated genetic variants are located in non-coding regions, i.e., enhancers, characterizing the epigenomic landscape of chondrocyte-specific enhancers is essential. This study performed histone ChIP-seq during in vitro chondrogenesis of human MSCs to comprehensively analyze chromatin state changes and investigate the cell-type specificity of chondrocyte enhancers and their interaction with DNA methylation and SOX9 binding.

---

## Key Experiment Methods

**1. hMSC chondrogenic differentiation**

- Bone marrow-derived hMSCs (LONZA, two females, 22-24 years) differentiated into chondrocytes for 14 days in a Transwell scaffold-free micro-mass model
- Differentiation confirmed by upregulation of COL2A1, TNBS4, PRG4 (articular cartilage markers) and COL10A1, PTH1R, ALPL (hypertrophic chondrocyte markers)

**2. Histone ChIP-seq**

- ChIP-seq for 5 histone modifications: H3K4me3 (active promoter), H3K4me1 (enhancer), H3K27ac (active enhancer), H3K27me3 (transcriptional repression), H3K36me3 (transcriptional elongation)
- Illumina HiSeq 2500 (50 bp single-end) and NextSeq 500 (75 bp single-end) sequencing
- MACS2 for peak calling, ngs.plot for histone mark enrichment analysis by gene expression level

**3. ChromHMM chromatin state modeling**

- 16-state chromatin state model trained on hMSC and differentiated chondrocyte data using ChromHMM (v1.12)
- GREAT GO enrichment analysis for each state
- Riverplot visualization of hMSC→chondrocyte state transitions

**4. Similarity analysis with Roadmap Epigenomics data**

- Jaccard similarity coefficient comparison with 98 cell types from the 18-state Roadmap dataset
- Hierarchical clustering centered on enhancer states (9_EnhA1 ↔ 13_EnhS)

**5. DNA methylation data integration**

- Cross-analysis of Infinium HumanMethylation450K BeadChip data (GSE129266) with chromatin states
- Statistical test for enhancer overrepresentation of demethylated CpGs (Chi-square test, 1000 Monte Carlo permutations)

**6. Luciferase reporter assay**

- Six selected enhancer regions (ASPSCR1, TLE3, WWP2, ZMIZ1, LRP5, MYEOV) cloned into CpG-free pCpGL-EF1 vector
- Luciferase activity measured in osteosarcoma SW1353 cells after in vitro CpG methylation (M.SssI) treatment
- Effect of SOX9 overexpression (pUT-FLAG-SOX9 co-transfection) on enhancer activity assessed

**7. Motif analysis and SOX9 ChIP-seq data utilization**

- De novo motif discovery in chondrocyte enhancers using MEME suite (AME)
- Comparison with published mouse rib chondrocyte SOX9 ChIP-seq data (GSE69109) lifted over to hg38 for human SOX9 binding sites

---

## Results

**Large-scale chromatin state changes during chondrogenesis** ChIP-seq data for 5 histone modifications showed expected genomic distributions (e.g., H3K4me3 enrichment at TSS), with active histone marks (H3K4me3, H3K27ac, H3K36me3) enriched at highly expressed genes and repressive marks (H3K27me3) enriched at lowly expressed genes, confirming data quality. The ChromHMM 16-state model revealed extensive chromatin state changes between hMSCs and differentiated chondrocytes (Riverplot). Strong active enhancer states in differentiated chondrocytes (13_EnhS; high H3K4me1+H3K27ac enrichment) were significantly enriched for GO terms related to chondrogenesis and cartilage function (e.g., cartilage development, skeletal system development). Around the COL2A1 gene, a clear transition from repressive/inactive states in hMSCs to a transcription-permissive state in chondrocytes was observed.

**Cell-type specificity of enhancers** Jaccard similarity analysis with 98 cell types from Roadmap Epigenomics showed that only enhancer states (9_EnhA1/13_EnhS), unlike other chromatin states such as promoters, exhibited clear cell-type specific clustering. Differentiated chondrocytes from this study (CHON) clustered together with Roadmap bone marrow MSC-derived chondrocytes, while hMSCs clustered near primary culture cell groups such as myocytes, osteoblasts, and fibroblasts, demonstrating that the chondrocyte-specific epigenomic signature is conserved across different models and laboratories.

hMSC-derived chondrocyte enhancers (23,158 common regions) showed higher similarity to adult articular cartilage enhancers than to fetal articular cartilage enhancers. Among differentially accessible enhancers in OA knee cartilage, 1,239 (approximately 33%) overlapped with enhancers identified in this study (hypergeometric test, P < 3.75 × 10⁻⁹⁰), confirming that OA-deregulated enhancers are enriched in chondrocyte-specific enhancers.

**Enhancer demethylation and epigenetic crosstalk** Demethylated CpG sites during chondrogenesis (94% of all differentially methylated sites) were significantly overrepresented in strong enhancers marked by H3K4me1 and H3K27ac (13_EnhS). Fewer than 2% of total 450K array CpGs were located in the 13_EnhS state, yet 41.8% of demethylated CpGs were found in this state (Chi-square, P < 0.001). Luciferase reporter assays showed that all six selected enhancer regions (ASPSCR1, TLE3, WWP2, ZMIZ1, LRP5, MYEOV) exhibited significant enhancer activity in the unmethylated state, and CpG methyltransferase treatment significantly reduced activity in all regions, demonstrating that DNA methylation directly regulates enhancer activity.

**SOX9 binding and enhancer activity regulation** De novo motif discovery identified the SOX9 binding motif as the most highly enriched motif in strong chondrocyte enhancers, along with motifs for other transcription factors related to osteochondral development such as CREB3L1 (OASIS), ELF3, and HES/HEY. Newly acquired enhancers during chondrogenesis showed significantly higher SOX9 motif enrichment than constant enhancers present before and after differentiation. LiftOver of mouse rib chondrocyte SOX9 ChIP-seq data showed that most SOX9 peaks overlapped with strong promoter (2_TssS) and strong active enhancer (13_EnhS) states in chondrocytes. Luciferase assays showed that 4 of 6 enhancers (excluding TLE3) exhibited significantly increased activity upon SOX9 overexpression, confirming that SOX9 regulates the transcriptional activity of these enhancers.

---

## Perspective

This study presents the first comprehensive epigenomic analysis integrating ChIP-seq for 5 histone modifications in a human MSC chondrogenesis model, with the following important findings.

First, large-scale genome-wide chromatin state reprogramming occurs during chondrogenesis, and enhancers defined by H3K4me1/H3K27ac are far more cell-type specific than promoters. The chondrocyte enhancer signature is conserved across different in vitro chondrogenesis models and laboratories, supporting the reliability and reproducibility of in vitro models.

Second, enhancer demethylation is a major epigenetic event during chondrogenesis, and DNA methylation directly regulates enhancer activity, as functionally demonstrated. This provides insight into the crosstalk between two epigenetic mechanisms — histone modifications and DNA methylation — in the context of chondrocyte differentiation.

Third, SOX9 binding motifs are enriched in chondrocyte enhancers, and SOX9 regulates chondrogenesis through newly activated enhancers during differentiation. The potential binding of other transcription factors related to osteochondral diseases, such as CREB3L1 and ELF3, to enhancers was also identified, providing clues for disease research.

Fourth, differentially accessible enhancers in OA cartilage significantly overlap with chondrocyte-specific enhancers, supporting the possibility that OA pathogenesis is associated with reactivation of the developmental epigenome. This suggests that chondrocyte enhancers have potential value as therapeutic targets for OA.

Future tasks include: (1) chromatin conformation analysis (3C/Hi-C) to identify actual target genes of enhancers, (2) systematic comparison of the epigenomes of various in vitro models with actual human articular chondrocytes, and (3) complete elucidation of the development-disease link.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
