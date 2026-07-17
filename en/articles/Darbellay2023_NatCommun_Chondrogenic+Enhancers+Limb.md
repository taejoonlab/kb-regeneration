---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Pre-hypertrophic chondrogenic enhancer landscape of limb and axial skeleton development

## Citation (NLM)

Darbellay F, Ramisch A, Lopez-Delisle L, Kosicki M, Rauseo A, Jouini Z, Visel A, Andrey G. Pre-hypertrophic chondrogenic enhancer landscape of limb and axial skeleton development. _Nat Commun._ 2024 Jun 7;15(1):4820. doi: [10.1038/s41467-024-49203-2](https://doi.org/10.1038/s41467-024-49203-2). PMID: 38849444.

---

## Background

Chondrocyte differentiation is a critical process that determines skeletal development and stature. After mesenchymal cells differentiate into chondrocytes, cells in the center of the cartilage condensations undergo hypertrophy (inducing mineral deposition), while cells at the ends form the growth plate to sustain bone elongation. Mutations in chondrocyte differentiation-related genes such as SOX9, COL10A1, COL2A1, and FGFR3 cause stature abnormalities and various skeletal disorders. Distant-acting enhancers are key elements regulating spatiotemporal and cell-type-specific gene transcription, yet a **genome-wide map of active enhancers in fetal chondrocytes** has not been defined. This study used a Col2a1 fluorescent reporter mouse to isolate pre-hypertrophic chondrocytes from fetal limbs and trunk, and combined transcriptomic and chromatin profiling to create a comprehensive map of chondrocyte-specific enhancers.

---

## Key Experiment Methods

**1. Col2a1 fluorescent reporter mouse line development**

- Inserted a regulatory sensor cassette (minimal ß-globin promoter + EGFP coding sequence) 1.2 kb upstream of the Col2a1 transcription start site
- Generated fetuses from Col2a1EGFP ESCs via tetraploid aggregation
- Microdissected limbs (stylo/zeugo/autopod) and trunk (cervical to caudal, viscera removed) from E14.5 fetuses

**2. Single-cell RNA-seq and cell classification**

- scRNA-seq of E14.5 Col2a1EGFP limb mesenchyme: identified 8 clusters (MCT, dermis, PM, tendon, pre-osteoblast, perichondrium, interdigit mesenchyme, chondrocyte)
- Col2a1 and EGFP co-expressed in the chondrocyte cluster (correlation = 0.74)
- FACS sorting of EGFP+ (~10%) and EGFP- (~90%) cells

**3. RNA-seq, ATAC-seq, H3K27ac ChIP-seq**

- Performed RNA-seq, ATAC-seq, and H3K27ac ChIP-seq on EGFP+/EGFP- × limb/trunk (4 conditions)
- Differential expression analysis with DESeq2 (abs(log2FC) > 1.5, FDR < 0.05)
- Classified 30,953 of 112,095 ATAC-seq peaks (27.6%) with H3K27ac signal as active regulatory regions

**4. Chondrocyte enhancer definition and TAD analysis**

- Promoter-excluded regions with ≥4-fold H3K27ac difference between EGFP+ vs EGFP- → identified **2,704 chondrocyte enhancers**
- Assigned enhancers to TADs (3,109) based on E14.5 mouse whole-embryo cartilage Hi-C
- Compared chondroTADs (TADs containing chondrocyte genes + enhancers, n=357) vs chondroEnhTADs (enhancers only, n=661)

**5. SOX9 and TF binding analysis**

- Overlapped E13.5 mouse limb SOX9 ChIP-seq data with enhancers
- Enrichment analysis of 356 TF binding motifs

**6. Association with human height GWAS**

- Overlapped enhancers with 7,209 height variance-explaining loci from a 5.4M human GWAS
- Analyzed 8 loci associated with tibia length in Longshanks mice
- Compared overlap with 1,771 non-coding mHVEL (mouse-conserved height variance-explaining loci) and enhancers

**7. Enhancer functional validation**

- Cloned human enhancer sequences into LacZ reporter vectors (site-directed integration)
- Homozygous deletion of enhancers at Col2a1, Fgfr3, Hhip, and Nkx3-2 loci in Col2a1EGFP background
- Analyzed target gene expression changes by bulk RNA-seq of E14.5 fetal limbs/trunk

---

## Results

**Col2a1 reporter specifically labels pre-hypertrophic chondrocytes** In scRNA-seq, EGFP expression was restricted to the chondrocyte cluster, with only weak signal in the perichondrium. EGFP+ cells highly expressed chondrocyte markers (Col2a1, Sox9, Foxa2/3, Matn, Fgfr3), while perichondrium markers (Foxp1/2, Sox11) were not enriched, confirming isolation of a homogeneous chondrocyte population.

**Identification of 780 chondrocyte-specific genes** Among 780 genes overexpressed in EGFP+, 655 (84%) were common to limb and trunk, 67 (9%) were limb-specific (e.g., Gdf5), and 58 (7%) were trunk-specific (e.g., Pax1).

**Map of 2,704 chondrocyte enhancers** Of 2,704 enhancers, 2,003 (74%) were **pan-chondrogenic** (common to limb and trunk), 483 (18%) were **limb-specific**, and 218 (8%) were **trunk-specific**. Most chondrocyte enhancers opened chromatin accessibility between E9.75–E11.5, suggesting that Sox9 and Foxc1/2 expression initiates during this period.

**TF binding analysis** SOX9, MEF2C/D, and FOX factor motifs were enriched in chondrocyte enhancers, while CTCF, MAZ, and MYOD1/MYOG/MYF6 motifs were depleted. 967 (39%) enhancers overlapped with E13.5 limb SOX9 ChIP-seq peaks, while only 3.5% of inactive regions overlapped, demonstrating capture of both SOX9-dependent and -independent enhancers.

**TAD-based enhancer-gene linking** chondroTADs (n=357) contained an average of 3.8 enhancers/TAD (chondroEnhTADs had 2/TAD, p=4.68e-23). chondroTAD genes were enriched for bone and cartilage development GO terms, while chondroEnhTAD genes were enriched for general developmental processes (Shox2, Hoxd, Tbx4, etc.). Limb/trunk-specific genes tended to be located in TADs with corresponding tissue-enriched enhancers.

**Association of human height variation with enhancers** 73 chondrocyte enhancers (2.7% of total) were identified in 8 Longshanks mouse tibia length-associated loci, and the N1 enhancer at the Nkx3-2 locus contained SNPs. 169 of 1,771 human GWAS non-coding mHVEL (9.5%) overlapped with chondrocyte enhancers, explaining 18.4% of total height variance. **Chondrocyte enhancers explained height variance better than non-chondrocyte enhancers.**

**Enhancer functional validation** Deletion of hs2697/hs2698 (9.1 kb) at the Col2a1 locus reduced Col2a1 expression by 20% in the trunk. Deletion of hs2696 (5.9 kb) at the Fgfr3 locus reduced Fgfr3 expression by 75% in limb and trunk. Deletion of CE2-3 (3.5 kb) at the Hhip locus reduced Hhip expression by 15% in the limb. Deletion of CE1-N1 (27.6 kb) at the Nkx3-2 locus reduced Nkx3-2 expression by 25% in limb and 37% in trunk, along with broad reduction of downstream chondrocyte genes including Sox9, Col2a1, and Ihh.

---

## Perspective

This study is a groundbreaking work that presents the first genome-wide enhancer map of fetal pre-hypertrophic chondrocytes, with the following significance.

First, it demonstrated that 74% of 2,704 chondrocyte enhancers are pan-chondrogenic, while the remainder are limb- or trunk-specific, revealing the enhancer-based mechanism of chondrocyte differentiation regulation by skeletal region. SOX9 binds to 39% of enhancers, but the remaining 61% are SOX9-independent enhancers, demonstrating the importance of a comprehensive approach beyond single TF-based enhancer discovery.

Second, it showed that chondrocyte enhancers serve as a mechanistic framework for explaining human height GWAS variants. Notably, chondroEnhTADs enhancers explained height variance better than chondroTADs enhancers, suggesting that **enhancer variants of general developmental genes, not just chondrocyte genes, can have a major impact on skeletal traits.**

Third, direct in vivo validation of target gene expression reduction through enhancer deletion at 4 loci (Col2a1, Fgfr3, Hhip, Nkx3-2) demonstrated that enhancer variants can cause skeletal disorders (e.g., Fgfr3 enhancer variants → CATSHL syndrome, Nkx3-2 enhancer variants → short stature).

Future directions include improving target gene mapping accuracy through enhancer-promoter 3D interactions (Hi-C/HiChIP), elucidating dynamic enhancer changes across chondrocyte subpopulations (early/mature/hypertrophic), and functional validation of enhancers in human chondrocytes.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
