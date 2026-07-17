---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
---

# The Transcription Factor-microRNA Regulatory Network during hESC-chondrogenesis

## Citation (NLM)

Griffiths R, Woods S, Cheng A, Wang P, Griffiths-Jones S, Ronshaugen M, Kimber SJ. The Transcription Factor-microRNA Regulatory Network during hESC-chondrogenesis. _Sci Rep._ 2020 Mar 16;10(1):4744. doi: [10.1038/s41598-020-61734-4](https://doi.org/10.1038/s41598-020-61734-4). PMID: 32179778.

---

## Background

Human embryonic stem cells (hESCs) and induced pluripotent stem cells (iPSCs) hold great potential as an unlimited cell source for cartilage defect repair in osteoarthritis (OA) and sports injuries. However, improving the chondrogenic differentiation efficiency of hESCs/iPSCs requires an understanding of the transcriptional and post-transcriptional regulatory mechanisms of chondrogenesis. miRNAs play key roles in skeletal development and ECM regulation, and inhibition of miRNA processing causes cartilage developmental defects and chondrocyte apoptosis in mice. Existing chondrocyte differentiation protocols relied on embryoid body formation, MSC-like cell induction, or serum use, but the authors developed a serum-free 3-stage 2D differentiation protocol to induce chondroprogenitors from hESCs. This study performed small RNA-seq and whole transcriptome sequencing at each stage of this protocol to systematically elucidate how miRNAs and transcription factors (TFs) cooperate to regulate gene expression during hESC chondrogenesis through a systems biology approach.

---

## Key Experiment Methods

**1. hESC chondrocyte differentiation protocol (DDP)**

- Used HUES1 and MAN7 hESC lines
- Stage 0 (hESC) → Stage 1 (primitive streak/mesendoderm, day 1–3: Wnt3a, Activin A, BMP4) → Stage 2 (mesoderm, day 4–8: BMP4, Follistatin) → Stage 3 (chondroprogenitor, day 9–14: GDF5, FGF2, NT4)
- Serum-free 2D culture, samples collected at the end of each stage

**2. Small RNA-seq and whole transcriptome RNA-seq**

- Prepared small RNA libraries and whole transcriptome libraries from Stage 0, 2, and 3 samples
- Illumina sequencing; hg19 genome mapping
- Detected 22,073 transcripts (17,835 protein-coding genes) and 1,052 mature miRNAs
- Differential expression analysis with DESeq2 (FDR < 0.05)

**3. Co-expression network analysis**

- Clustered genes and miRNAs using BioLayout3D with Pearson's correlation > 0.98
- Identified 6 clusters; performed GO term enrichment analysis for each cluster

**4. Transcription factor target enrichment analysis**

- Evaluated TF target gene enrichment within each cluster using known TF-target interaction databases (Fisher's Exact Test, odds ratio)

**5. miRNA target enrichment analysis**

- Generated high-confidence miRNA-target lists using TargetScan (total context score < -0.3) + miRTarBase (luciferase-validated interactions only)
- Evaluated miRNA target enrichment within each cluster

**6. Protein-protein interaction (PPI) network**

- Constructed PPI network for 'ECM Organization' cluster genes using the STRING database

---

## Results

**Stage-wise changes in transcriptome and miRome** PCA showed clear progression from Stage 0 to Stage 3, with Stage 2 showing greater variability as an intermediate stage. Transcriptome changes between the two hESC lines showed high correlation, with 479 commonly upregulated and 619 commonly downregulated genes identified.

**Differentially expressed genes** 3,274 genes were significantly regulated between Stage 0 and Stage 3. Upregulated genes included Hox genes (HOXA, C, D clusters), ECM-related genes (LOX, DCN, MGP, COL15A1), and mesoderm/limb development TFs (BARX2, HAND2, TBX2). Downregulated genes were pluripotency-related genes (NANOG, POU5F1, NODAL, LEFTY1, ZSCAN10).

**miRNA changes** 208 miRNAs were significantly altered. Pluripotency-related miRNAs (chromosome 19 cluster CM19C, miR-302 family) were downregulated, while Hox cluster-derived miRNAs and chondrogenesis-related miRNAs (miR-99a-5p, miR-143-5p, miR-181a-3p) were upregulated. Prechondrocyte miRNAs (miR-99b-5p, miR-27b-3p) were expressed much higher than hypertrophic chondrocyte miRNAs (miR-20a-5p, miR-17-5p, miR-127-3p), indicating that this protocol maintains prechondrocyte characteristics.

**6 co-expression network clusters**
- Cluster 1: Pluripotency maintenance (NANOG, POU5F1, NODAL, miR-302a)
- Cluster 2: Primitive streak formation (miR-200, miR-141)
- Cluster 3: RNA polymerase II transcriptional regulation
- Cluster 4: **ECM organization** (fold enrichment 9.1, FDR=4.5E-24)
- Cluster 5: **Limb development** (fold enrichment 19.4, FDR=9.5E-5)
- Cluster 6: Ion transport

**TF target enrichment analysis** 77 TFs showed target enrichment (odds ratio > 1, p < 0.001) in the 'ECM Organization' cluster, of which 25 were upregulated during chondrogenesis. JUN (39 targets) and RELA (36 targets) broadly regulated ECM-modulating genes (TIMP1, LOX, TGM2, ADAM9, COL1A1, COL1A2, COL4A2, DCN, FN1, HSPG2). HOXA9/A10/D13 and NFAT5 were also upregulated.

**miRNA target enrichment analysis** In the 'ECM Organization' cluster, **miR-29c-3p** (odds ratio 33.5) and **miR-140-3p** (odds ratio 23.7) targets were most enriched. Of 39 confirmed targets of miR-29c-3p, 10 belonged to the ECM organization cluster. miR-29c-3p expression increased during differentiation, but target gene expression did not decrease, suggesting transcript stabilization or involvement in a complex regulatory network. In the 'Limb development' cluster, **miR-134-5p** targets were enriched 5.5-fold (HAND2, HOXB2, MEIS2, PBX1, TBX2), and **miR-22-3p** showed high co-expression with ECM genes, suggesting it may indirectly regulate ECM genes by targeting chondrogenesis regulators HDAC4 and SP1.

**PPI network** In the 'ECM Organization' cluster PPI network, IL6 and IGF-1 were identified as key hub genes. The IGF-1 network included IGFBP3, suggesting a mechanism whereby ADAM12 cleaves IGFBP-3/5 to increase IGF-1 bioavailability. TIMP1/TIMP3 showed positive correlation with IL6.

---

## Perspective

This study is a systems biology work that systematically elucidates the TF-miRNA-ECM regulatory network through integrated analysis of the transcriptome and miRome during hESC chondrogenesis, with the following significance.

First, it demonstrated that the ECM organization cluster during chondrogenesis is under multiple regulation by TFs (JUN, RELA, HOXA9/A10/D13, NFAT5) and miRNAs (miR-29c-3p, miR-140-3p, miR-22-3p). Notably, miR-22-3p, similar to miR-140, may target HDAC4 and SP1 to contribute to chondrocyte hypertrophy inhibition and ECM degradation prevention, making it a notable candidate as a **novel chondrogenesis-regulating miRNA.**

Second, miR-29c-3p directly regulates ECM organization cluster genes, and the paradoxical relationship between increased expression and maintained target expression suggests that miRNAs may act not merely as repressors but as transcript stabilizers or components of feedback networks.

Third, this protocol maintains prechondrocyte characteristics (low RUNX2, no COL10A1), and despite 2D culture, appropriately regulates limb development-related Hox genes and cartilage development TFs (SOX9, SOX5/6, DLX2, MSX1), validating its feasibility as an in vitro model of human cartilage development.

Fourth, it demonstrated that the IGF-1-IGFBP3-ADAM12 axis and IL6-TIMP network are central to ECM homeostasis maintenance, suggesting potential targets for ECM catabolism regulation in OA pathology.

Future directions include functional validation of miR-22-3p and miR-29c-3p (gain/loss-of-function), enhancing chondrocyte maturity in 3D culture (inducing high ACAN and COL2A1 expression), extending the protocol to iPSCs, and applying it to OA disease modeling.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
