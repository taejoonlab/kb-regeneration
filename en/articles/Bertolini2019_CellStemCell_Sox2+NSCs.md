---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
raw_data:
  - "GEO: GSE90561"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Mapping the Global Chromatin Connectivity Network for Sox2 Function in Neural Stem Cell Maintenance

## Citation (NLM)
Bertolini JA, Favaro R, Zhu Y, Pagin M, Ngan CY, Wong CH, et al. Mapping the Global Chromatin Connectivity Network for Sox2 Function in Neural Stem Cell Maintenance. Cell Stem Cell. 2019;24(3):462-476. doi:10.1016/j.stem.2019.02.004

**DOI:** [https://doi.org/10.1016/j.stem.2019.02.004](https://doi.org/10.1016/j.stem.2019.02.004)

---

## Background

The SOX2 transcription factor is critical for neural stem cell (NSC) maintenance and brain development. In humans, SOX2 mutations cause a dominant nervous system disease (hippocampal and eye defects, epilepsy, learning disabilities), and in mice Sox2 ablation causes analogous defects including hippocampal hypoplasia and microcephaly, some traceable to a defect in NSC self-renewal. Sox2-deleted NSCs fail to self-renew in long-term culture.

Transcriptional regulation is mediated by DNA looping between promoters and distal enhancers, forming a cell-type-specific three-dimensional network ("connectome"). It was previously unknown to what extent a single transcription factor influences the function of genome-wide interaction networks in controlling cell-specific transcription. This study asked how SOX2 shapes the Pol II-mediated long-range chromatin interaction network in NSCs, and which downstream genes mediate Sox2-dependent long-term self-renewal.

---

## Key Experiment Methods

1. **NSC model**: brain-derived NSC cultures from neonatal (P0) forebrain of conditionally (E11.5) Sox2-ablated mice (MUT) and control (WT) littermates.
2. **ChIA-PET** (chromatin interaction analysis with paired-end tag sequencing) with anti-Pol II antibodies to map genome-wide long-range chromatin interactions in WT vs MUT NSCs; original protocol (TR1) plus an improved *in situ* ChIA-PET (TR2, TR3) with higher intra-molecular ligation efficiency, run on individual forebrains.
3. **ChIP-seq** for SOX2 (WT NSCs) and for histone modifications H3K27ac and H3K4me1 (WT and MUT) to define active and poised enhancers, using peak-calling and chromHMM segmentation.
4. **RNA-seq** of WT and MUT NSC transcriptomes to correlate interactions with gene expression.
5. **Transgenic enhancer assay in zebrafish**: SOX2-bound distal anchors cloned upstream of a minimal promoter + GFP; tested for forebrain reporter activity and modulation by anti-Sox2 morpholinos / Sox2 mRNA.
6. **Functional rescue**: lentiviral overexpression of Socs3 (a SOX2 target, Jak/Stat inhibitor) in MUT NSCs, with growth curves and FACS tracking of GFP+ cells.

---

## Results

- Sox2 ablation caused a substantial, genome-wide reduction of Pol II-mediated long-range chromatin interactions (normalized significant loops fell from ~6-10K in WT to ~2-3K in MUT), while Pol II binding regions were largely retained (92%). Changes were non-uniform, with drastic reduction at some loci and little at others; occasionally new loops appeared in MUT cells.
- SOX2-bound sites were rarely at promoters and mostly in distal intronic/intergenic regions; >90% carried active enhancer marks (mostly H3K27ac+). SOX2-bound, epigenetically marked distal regions were highly enriched within interaction anchors relative to random loci and relative to non-SOX2-bound marked regions.
- ~35-46% of all interactions in WT NSCs carried a SOX2-bound site at an anchor; SOX2 was particularly enriched at distal enhancer anchors of promoter-enhancer (P-E) interactions.
- SOX2-dependent interaction anchors predicted novel forebrain enhancers: 15/17 tested distal anchors drove GFP to the developing zebrafish forebrain, matching endogenous ortholog expression; some overlapped VISTA enhancers (whose anchor overlap dropped sharply in MUT cells).
- Genes engaged in P-E interactions, especially with SOX2-bound enhancers, showed higher expression; loss of Sox2 decreased expression of ~1,000 genes. Genes with significantly reduced expression in MUT (group 1) were highly co-associated specifically with promoter-to-SOX2-bound-enhancer interactions, whereas SOX2 binding at promoters and P-P interactions were much less functionally relevant.
- Overexpression of **Socs3** — a multi-connected SOX2 target strongly downregulated in MUT NSCs — rescued the long-term self-renewal defect: Socs3-transduced MUT NSCs continued to grow long-term (progressive enrichment to ~100% GFP+), whereas untransduced MUT NSCs exhausted by passages 8-12.
- Sox2 loss did not substantially alter epigenetic enhancer marks (H3K27ac/H3K4me1), suggesting SOX2 acts on interactions/transcription rather than establishing/maintaining these marks (Sox2 was ablated at E11.5, after marks may already be set).

---

## Perspective

The work establishes SOX2 as a major regulator of gene expression through its enrichment in, and maintenance of, Pol II-mediated promoter-enhancer long-range interactions in NSCs, contrasting with architectural proteins (CTCF/Cohesin) that reshape interactions with only moderate transcriptional effect. By defining this connectivity network it provides a route to identifying enhancers and genes involved in NSC maintenance and neurodevelopmental disorders (several distal anchors connect to human brain-disease genes). The functional identification of SOCS3 as sufficient to rescue self-renewal pinpoints a critical downstream effector.

Limitations and open questions include: the difficulty of proving complete loss (versus reduced frequency) of specific interactions given dependence on sequencing depth; whether interaction loss results directly from SOX2 removal from anchors or indirectly via deregulation of SOX2-controlled transcription factors; the candidate role of SOX2 partner complexes (NurD, SWI/SNF, CHD7, SMRT/NCOR) and the relationship to YY1 in mediating interactions; and the fact that enhancer marks persist without SOX2, leaving the mechanism of interaction stabilization to be resolved.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE90561


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
