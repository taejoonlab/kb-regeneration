---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
---

# Nuclear microRNA 9 mediates G-quadruplex formation and 3D genome organization during TGF-β-induced transcription

## Citation (NLM)

Cordero J, Swaminathan G, Rogel-Ayala DG, Rubio K, Elsherbiny A, Mahmood S, Szymanski W, Graumann J, Braun T, Günther S, Dobreva G, Barreto G. Nuclear microRNA 9 mediates G-quadruplex formation and 3D genome organization during TGF-β-induced transcription. _Nat Commun._ 2024 Nov 27;15(1):10711. doi: [10.1038/s41467-024-54740-x](https://doi.org/10.1038/s41467-024-54740-x). PMID: 39604334.

---

## Background

Three-dimensional (3D) genome organization is essential for transcriptional regulation in eukaryotic cells. Enhancer-promoter interactions regulate cell-type-specific gene expression through chromatin looping, and atypical DNA secondary structures such as G-quadruplexes (G4) at promoters are associated with increased gene expression. However, **the role of G4 in promoter-distal regulatory elements (super-enhancers, SE) and chromatin looping** remains unknown. miRNAs are known to act primarily in the cytoplasm through translational repression, but mature miRNAs have also been found in the nucleus, and their nuclear functions have been studied only to a limited extent. This study revealed that mature miR-9 is abundantly present at nuclear promoters and super-enhancers in genes responding to TGF-β1 signaling, and is essential for G4 formation, promoter-super-enhancer looping, and maintenance of H3K4me3 broad domains.

---

## Key Experiment Methods

**1. Cell fractionation and miR-9 nuclear localization**

- Used MLg (mouse lung fibroblasts), MFML4, MLE-12 (lung epithelial), NMuMG, and hLF (human lung fibroblasts) cell lines
- Quantified mature miR-9 after cytoplasmic/nuclear fractionation using TaqMan assay
- Visualized miR-9 nuclear localization by RNA FISH; induced miR-9 loss-of-function (LOF) with antagomiR

**2. ChIRP-seq (Chromatin Isolation by RNA Purification)**

- Precipitated endogenous miR-9 + bound chromatin using biotinylated miR-9 antisense oligonucleotides
- Analyzed genome-wide miR-9 binding profiles in MLg and MLE-12 cells
- Control: miR-let7d-specific probe

**3. CUT&Tag and ChIP-seq**

- Performed CUT&Tag with H3K4me3, H3K27ac, and G4 antibodies (Ctrl vs miR-9-LOF)
- Analyzed Pol II, Pol II S5p, ATAC-seq, G4P ChIP-seq, and G4access data
- Classified super-enhancers (SE) vs typical enhancers (TYE) using the ROSE algorithm

**4. RNA-seq and PRO-seq/GRO-seq**

- Analyzed transcriptome changes in miR-9-LOF MLg cells by total RNA-seq
- Quantified nascent RNA using PRO-seq and GRO-seq

**5. G4 Ch-RIP and miR-Pd (miRNA pulldown)**

- Performed chromatin-RNA immunoprecipitation with G4-specific antibody, then quantified miR-9 by TaqMan
- Identified miR-9-binding proteins by mass spectrometry after pulldown with biotinylated miR-9 in nuclear fractions

**6. H3K4me3 HiChIP-seq**

- Combined in situ Hi-C library with ChIP using H3K4me3 antibody
- Analyzed chromatin conformation in Ctrl/miR-9-LOF × untreated/TGF-β1 treated (4 conditions)

---

## Results

**Nuclear presence and promoter binding of miR-9** miR-9 was detected in both the cytoplasm and nucleus of all analyzed cell lines, with higher relative nuclear levels in fibroblasts than epithelial cells. In IPF (idiopathic pulmonary fibrosis) patient hLF, miR-9 was predominantly nuclear, suggesting pathological nuclear translocation. In ChIRP-seq, miR-9 bound abundantly to promoters, TTS, and intronic regions, with different binding sites in MLg and MLE-12, suggesting cell-type-specific regulation.

**miR-9 is essential for H3K4me3 broad domains and basal transcription** In H3K4me3 CUT&Tag, 60.8% of H3K4me3 broad domains in Ctrl MLg cells were abundantly overlapped with miR-9, and miR-9-LOF reduced broad domains from 27.6% to 22.1%, with a shift to medium/narrow domains (significant at promoters). miR-9-LOF significantly altered 3,320 transcripts, of which 73.5% (2,439) showed decreased expression. Genes within H3K4me3 broad domains showed the greatest transcriptional reduction. Pol II, Pol II S5p, PRO-seq, GRO-seq, ATAC-seq, and H3K4me3 ChIP-seq all confirmed basal transcriptional activity at the TSS of miR-9 target genes.

**miR-9 is essential for G4 formation** G-rich motifs were enriched at the TSS of miR-9 target genes, and G4 enrichment was confirmed by G4P ChIP-seq and G4access data. In G4 CUT&Tag, genome-wide G4 levels significantly decreased upon miR-9-LOF. G4 Ch-RIP confirmed direct binding of miR-9 to G4, and this interaction was lost upon miR-9-LOF. miR-Pd mass spectrometry identified 169 (MLg) and 233 (MLE-12) nuclear miR-9-binding proteins, of which 20 (MLg) and 58 (MLE-12) were reported as G4-interacting proteins. GSEA showed enrichment of G4 interaction (p=1.23E-4), chromatin (p=1.5E-3), and RNA processing (p=1.65E-49) pathways.

**miR-9 maintains G4 and H3K27ac at super-enhancers** Alluvial plots showed co-enrichment of miR-9 and G4 at MED1- and H3K27ac-enriched SE loci. Of 3,583 common loci, 95.5% (3,423) were registered as enhancer RNAs in the eRNA database. ROSE analysis showed that 1,649 SEs in Ctrl MLg cells significantly decreased to 1,084 upon miR-9-LOF (p=9.9E-142). 25.5% of SEs were miR-9-enriched (vs 4% of TYEs). Upon miR-9-LOF, H3K27ac breadth at SEs significantly decreased, and both H3K27ac and G4 levels decreased at SEs and TYEs. ROSE analysis of G4 CUT&Tag showed G4-containing SEs significantly decreased from 1,753 to 937 (p=2.5E-35).

**miR-9 mediates promoter-SE looping in TGF-β1-induced transcription** GSEA showed that miR-9-enriched + nascent RNA loci were enriched in "TGFB cell response" (p=7.55E-09), "TGFB" (p=2.61E-08), and "Cell proliferation" (p=4.66E-08). Upon TGF-β1 treatment, miR-9, G4, and H3K4me3 levels increased in a miR-9-dependent manner. In H3K4me3 HiChIP-seq, chromatin interaction hubs significantly increased upon TGF-β1 treatment, of which 65.1% were miR-9-enriched. miR-9-LOF counteracted the TGF-β1-induced effect. k-means clustering showed that clusters 1 and 4 exhibited TGF-β1-responsive chromatin interactions, and these loci contained miR-9 target genes (Zdhhc5, Ncl, Lzts2, Hdac7). **Promoter-SE chromatin loops increased in a miR-9-dependent manner upon TGF-β1 treatment.** ChIP qPCR confirmed that H3K4me3 and G4 levels increased at promoters and SEs upon TGF-β1 treatment, and this effect was reduced by miR-9-LOF. qRT-PCR confirmed that miR-9 target gene expression increased in a miR-9-dependent manner upon TGF-β1 treatment.

---

## Perspective

This study is a groundbreaking work that first reveals mature miRNA directly participates in 3D genome organization and transcriptional activation in the nucleus, with the following significance.

First, it demonstrated that miR-9 directly binds to promoters and super-enhancers to mediate G4 formation, thereby regulating H3K4me3 broad domain maintenance and promoter-SE chromatin looping. This proves that miRNAs can function not only as cytoplasmic translational repressors but also as **nuclear chromatin structure regulators.**

Second, it showed that miR-9 acts as an essential component of transcriptional activation in the TGF-β1 signaling pathway (a key pathway in cancer and fibrosis). Nuclear accumulation of miR-9 was observed in IPF patient lung fibroblasts, suggesting that miR-9 nuclear translocation may be associated with fibrotic pathology.

Third, it demonstrated that miR-9 is involved in SE formation and maintenance, and that G4 acts as a structural element of SEs. Upon miR-9-LOF, SE numbers decreased by 34% and G4-containing SEs decreased by 47%, proving that the miR-9-G4-SE axis is a core module of transcriptional regulation.

Fourth, miR-Pd mass spectrometry identified numerous nuclear miR-9-binding proteins, many of which are G4-interacting proteins, suggesting that miR-9 may regulate chromatin structure through protein complexes.

Future directions include elucidating the mechanism of miR-9 nuclear translocation (functional validation of extended nuclear shuttling motifs), the molecular mechanism by which miR-9 promotes G4 formation (distinguishing DNA vs RNA G4), and developing fibrosis and cancer therapeutic strategies targeting the miR-9-G4 axis.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
