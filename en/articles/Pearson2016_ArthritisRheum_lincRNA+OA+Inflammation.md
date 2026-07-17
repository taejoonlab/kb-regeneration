---
tags: [2026-06, Chondrocyte]
extract: 2026-06-08
log:
  - "2026-06-08 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Long Intergenic Noncoding RNAs Mediate the Human Chondrocyte Inflammatory Response and Are Differentially Expressed in Osteoarthritis Cartilage

## Citation (NLM)
Pearson MJ, Philp AM, Heward JA, Roux BT, Walsh DA, Davis ET, Lindsay MA, Jones SW. Long Intergenic Noncoding RNAs Mediate the Human Chondrocyte Inflammatory Response and Are Differentially Expressed in Osteoarthritis Cartilage. Arthritis Rheumatol. 2016;68(4):845-56. doi:10.1002/art.39520

**DOI:** [https://doi.org/10.1002/art.39520](https://doi.org/10.1002/art.39520)

---

## Background
Osteoarthritis (OA) is a disease characterized by cartilage degeneration, and inflammation is recognized as a key driver of OA cartilage pathology. Several pro-inflammatory cytokines are elevated in the synovial fluid of OA joints, and cytokine stimulation induces pathological changes within OA joints. While evidence has accumulated that microRNAs (miRNAs), a class of short noncoding RNAs, regulate inflammatory responses, the role of long noncoding RNAs (lncRNAs)—particularly long intergenic noncoding RNAs (lincRNAs), antisense RNAs, and pseudogenes—in the OA chondrocyte inflammatory response remains largely unknown. This study aimed to identify lncRNAs associated with the inflammatory response in human primary OA chondrocytes through RNA sequencing, and to explore their expression and function in OA.

---

## Key Experiment Methods
1. OA cartilage tissue was collected from OA patients undergoing total hip and knee arthroplasty, along with non-OA cartilage from post-mortem donors and patients with femoral neck fracture
2. Primary chondrocyte isolation and culture via collagenase type II digestion
3. IL-1β (1 ng/mL) stimulation followed by RNA extraction, ribosomal RNA depletion, and RNAseq using Illumina HiSeq 2000 (100-bp paired-end, stranded)
4. Transcriptome assembly using Tophat2/Cufflinks pipeline and lncRNA identification by comparison with Gencode v19 and the Human LincRNAs Catalog
5. Differential expression analysis using CuffDiff (FDR < 0.05, fold change > 2, FPKM change > 1)
6. CILinc01 and CILinc02 knockdown using LNA longRNA GapmeR in the TC28 chondrocyte cell line
7. Measurement of inflammatory cytokine secretion using Luminex-based Bio-Plex Pro 17-plex cytokine immunoassay
8. Validation of lincRNA expression in OA and non-OA cartilage tissue by qRT-PCR

---

## Results
1. A total of 983 lncRNAs were identified in human OA chondrocytes, including 642 lincRNAs, 124 antisense RNAs, and 217 pseudogenes
2. 158 lincRNAs and 25 antisense RNAs were novel transcripts not present in existing databases
3. Following IL-1β stimulation, 125 lncRNAs (including 93 lincRNAs) were differentially expressed (106 upregulated, 19 downregulated), of which 37 (30%) were novel lncRNAs
4. Eight inflammation-related lincRNAs (CILinc01–07) were identified, including PACER (p50-associated COX-2-extragenic RNA)
5. PACER, CILinc01, and CILinc02 were significantly decreased in hip and knee OA cartilage compared to non-OA cartilage
6. These lincRNAs were rapidly and transiently induced by multiple pro-inflammatory cytokines, including IL-1β, TNF, visfatin, and leptin
7. CILinc01 knockdown significantly increased IL-6, IL-8, TNF, MIP-1β, and G-CSF secretion under IL-1β stimulation, while CILinc02 knockdown increased IL-6 secretion
8. Treatment with the IKK-2 inhibitor (TPCA-1) significantly reduced IL-1β-induced CILinc01 and CILinc02 expression, suggesting regulation by the NF-κB pathway

---

## Perspective
This study is the first to characterize the lncRNA profile of human primary OA chondrocytes using RNAseq and to report widespread changes in lncRNAs associated with the inflammatory response. The finding that CILinc01 and CILinc02 are decreased in OA cartilage and that their knockdown increases inflammatory cytokine production suggests that these lincRNAs act as negative regulators of the chondrocyte inflammatory response. This raises the possibility that the reduction of CILinc01/02 in OA cartilage leads to a loss of inflammatory regulation, contributing to inflammation-mediated cartilage degeneration. The decrease in PACER in OA cartilage may be associated with impaired anti-inflammatory function of the PTGS2/COX-2 pathway and reduced resolution capacity. Interestingly, the expression patterns of inflammation-related lincRNAs differed between hip and knee OA, confirming OA heterogeneity at the lncRNA level according to anatomical location. Future studies are needed to elucidate the mechanism of action of CILinc01/02 and the role of other chondrocyte inflammation-related lincRNAs in OA pathology, which may lead to the discovery of new therapeutic targets.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*
