---
tags: [2026-07]
extract: 2026-07-16
---

# Mapping the Global Chromatin Connectivity Network for Sox2 Function in Neural Stem Cell Maintenance

## Citation (NLM)
Bertolini JA, Favaro R, Zhu Y, Pagin M, Ngan CY, Wong CH, et al. Mapping the Global Chromatin Connectivity Network for Sox2 Function in Neural Stem Cell Maintenance. Cell Stem Cell. 2019;24(3):462-476. doi:10.1016/j.stem.2019.02.004

**DOI:** [https://doi.org/10.1016/j.stem.2019.02.004](https://doi.org/10.1016/j.stem.2019.02.004)

---

## Background

SOX2 is a transcription factor essential for pluripotency but also critical for neural stem cell (NSC) maintenance and correct brain development. In humans, SOX2 mutations cause dominant nervous system disease (hippocampal/eye defects, epilepsy, learning disabilities); in mice, Sox2 ablation causes hippocampal hypoplasia, microcephaly, ventral forebrain depletion, and anophthalmia, some of which stem from an NSC self-renewal defect. Sox2-deleted NSCs fail to self-renew in long-term culture.

Transcriptional regulation is mediated by DNA looping between promoters and distal enhancers, forming a cell-type-specific genome-wide interaction network ("connectome"). It was previously unknown to what extent a single transcription factor shapes the function of these genome-wide interaction networks. Here the authors use ChIP and chromatin interaction analysis by paired-end tag sequencing (ChIA-PET) to define genome-wide SOX2-bound regions and Pol II-mediated long-range chromatin interactions in brain-derived NSCs, and to identify SOX2-dependent genes governing NSC self-renewal.

---

## Key Experiment Methods

1. Established NSC cultures from neonatal (P0) forebrain of conditionally (E11.5) Sox2-ablated mice (MUT) and control littermates (WT).
2. Pol II ChIA-PET (original pooled protocol and an improved in situ ChIA-PET) to map genome-wide Pol II-mediated long-range chromatin interactions in WT and MUT NSCs (triplicates: wTR1-3, mTR1-3).
3. ChIP-seq of SOX2 in WT NSCs, and ChIP-seq of histone modifications H3K27ac and H3K4me1 in WT and MUT NSCs to classify active vs. poised enhancers (peak-calling and chromHMM).
4. Classification of interaction anchors/nodes as promoter (within 2.5 kb of TSS) or non-promoter (enhancer), and integration of SOX2 binding with epigenetic marks and interactions.
5. Transgenic enhancer-reporter (GFP) assays in zebrafish to test SOX2-bound distal anchors for forebrain enhancer activity; perturbation with anti-Sox2 morpholinos and injected Sox2 mRNA.
6. RNA-seq of WT and MUT NSCs to correlate gene expression with interaction categories; co-association scoring of expression groups with interaction types.
7. Lentiviral Socs3 (co-expressing GFP) overexpression in WT and MUT NSCs with growth-curve and FACS-based rescue assays for long-term self-renewal.

---

## Results

- Sox2 ablation substantially reduced genome-wide chromatin connectivity: normalized significant interactions dropped from ~6-10K per million intra-molecular PETs in WT to ~2-3K in MUT NSCs, with reductions highly variable across loci (some drastically reduced, some unchanged, occasional new loops in MUT).
- Reduction was not due to differing Pol II IP efficiency: ~92% of ChIA-PET Pol II binding regions in WT were retained in MUT, and Pol II density profiles were highly similar.
- SOX2-bound sites were rarely at promoters and mostly in intronic/intergenic distal regions; >90% carried enhancer marks (mostly H3K27ac+). ~35-46% of all WT interactions carried a SOX2-bound site in at least one anchor. SOX2-positive epigenetically marked distal regions were significantly more involved in interactions than SOX2-negative marked regions.
- SOX2-dependent distal anchors predicted novel forebrain enhancers: 15 of 17 reporter constructs drove GFP to the developing zebrafish forebrain, matching endogenous ortholog patterns; anchors overlapped known VISTA forebrain enhancers, and VISTA overlap dropped sharply in MUT cells.
- Genes involved in promoter-enhancer (P-E) interactions—especially SOX2-positive P-E interactions—showed the highest expression, and expression increased with number of P-E interactions per gene.
- Loss of Sox2 downregulated ~1,000 genes; genes with significantly decreased expression in MUT were highly enriched for WT promoter-to-SOX2-bound-enhancer interactions, whereas SOX2 binding at promoters was only marginally associated with expression change. P-P interactions correlated only with mild expression decreases.
- Socs3 (a Jak/Stat inhibitor, multi-connected SOX2 target, downregulated to 10-15% in MUT) was strongly enriched by lentiviral overexpression in MUT NSCs and rescued their long-term self-renewal defect; WT NSCs were not further selected, indicating endogenous SOCS3 is not limiting in WT.
- Sox2 loss did not substantially alter enhancer histone marks (H3K27ac/H3K4me1), suggesting SOX2 acts on interactions/expression rather than establishing the marks (Sox2 ablated at E11.5, after marks may be established).

---

## Perspective

This work establishes SOX2 as a major regulator of gene expression through the enhancer connectivity network in NSCs, showing that a single sequence-specific transcription factor can shape genome-wide long-range chromatin interactions. The demonstration that SOX2-bound distal enhancers (not promoter binding) predominantly drive SOX2-dependent transcription, and that a single downstream target (Socs3) can rescue self-renewal, provides a route to identify genes and enhancers involved in NSC maintenance and neurodevelopmental disorders.

Limitations include that no gene is completely silenced and interactions are reduced rather than fully lost (partly due to detection sensitivity for rare interacting PETs, making complete loss of any single interaction hard to prove), and that enhancer marks persist after Sox2 loss, leaving open whether SOX2 generates versus stabilizes interactions. The relationship to the recently identified enhancer-promoter mediator YY1 (bound at NPC-specific interactions) is raised as a future question, as is the contribution of SOX2 partner complexes (NurD, SWI/SNF, CHD7, SMRT/NCOR).

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
