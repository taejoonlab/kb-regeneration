---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
raw_data:
  - "GEO: GSE137844"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Comparative gene expression profiling between optic nerve and spinal cord injury in Xenopus laevis reveals a core set of genes inherent in successful regeneration of vertebrate central nervous system axons

## Citation (NLM)
Belrose JL, Prasad A, Sammons MA, Gibbs KM, Szaro BG. Comparative gene expression profiling between optic nerve and spinal cord injury in Xenopus laevis reveals a core set of genes inherent in successful regeneration of vertebrate central nervous system axons. BMC Genomics. 2020;21(1):540. doi:10.1186/s12864-020-06954-8

**DOI:** [https://doi.org/10.1186/s12864-020-06954-8](https://doi.org/10.1186/s12864-020-06954-8)

---

## Background

The capacity for CNS axon regeneration becomes progressively restricted both phylogenetically (anamniote to amniote) and developmentally (embryo to adult). The South African claw-toed frog, *Xenopus laevis*, occupies a unique transition point: some CNS neurons (retinal ganglion cells after optic nerve crush, ONC) regenerate axons throughout life, whereas others (hindbrain neurons after spinal cord injury, SCI) lose this ability as tadpoles metamorphose into frogs, driven by the surge of thyroid hormone. This allows a comparison of regenerative versus non-regenerative CNS injury responses within the same organism.

The authors exploited these features in a novel three-way RNA-seq comparison of axotomized CNS neuron populations, sampling tissue containing the neuronal cell bodies (rather than the lesion site) to distinguish axon-regenerative programs from generalized wound/trauma responses. The goal was to identify a core gene expression program that distinguishes successful from failed vertebrate CNS axon regeneration.

---

## Key Experiment Methods

1. **Three-way tissue comparison**: two axon-regenerative regions — post-metamorphic juvenile frog eye after optic nerve crush (ONC) and stage 53 tadpole hindbrain after spinal cord transection (SCI) — versus one non-regenerative region — juvenile frog hindbrain after SCI.
2. **Time points** chosen from prior histological/behavioral studies: early trauma phase (3 days), peak regenerative axon outgrowth (7 days for SCI, 11 days for ONC), and late recovery (3 weeks).
3. **RNA-seq design**: nominal 30 million reads/sample; each replicate pooled from 5 hindbrains or 6 eyes; 3 biological replicates per condition/time point; 51 samples across 17 conditions. Age-matched co-reared unoperated controls for tadpole SCI; contralateral unoperated eye as ONC control.
4. **Alignment/annotation** against *X. laevis* genome (Xenbase v9.1) with Bowtie2/TopHat and Mayball gene model; S and L homeologs resolved separately.
5. **Differential expression** by CuffDiff2/CummeRbund (FDR ≤ 0.05), cross-validated with DESeq2; genes filtered below FPKM threshold.
6. **Identification of DESR genes** ("Differentially Expressed in Successful Regeneration") — genes differentially expressed in both regenerative tissues but not the non-regenerative one.
7. **Downstream analyses**: Principal Component Analysis (eigenvector), GO term (Metascape) plus manual literature curation of each gene, KEGG pathway enrichment, and STRING protein-protein interaction networks.

---

## Results

- The two regenerative tissues (tadpole SCI hindbrain, frog ONC eye) shared a similar temporal pattern, peaking in number of differentially expressed genes at the peak regenerative phase (7/11 days), whereas the non-regenerative frog SCI hindbrain peaked earlier, at 3 days.
- **324 DESR genes** were identified (253 up-regulated, 71 down-regulated), comprising ~2.7% of all injury-induced differentially expressed genes — most differential expression was tissue-specific.
- PCA confirmed tissue of origin exerted the strongest influence on expression profiles; within SCI hindbrain, regenerative capacity was the next strongest factor. The unoperated contralateral eye also responded to unilateral ONC, justifying its use as a filter for axon-regeneration-specific changes.
- Many DESR genes had prior links to neural injury (e.g., socs3, leptin, fabp7, mapk8/JNK1, sox11, sdcbp/syntenin, prph/peripherin) and to non-neural tissue regeneration (axolotl limb: tmsb4x, anxa5, crabp2; mammalian liver: top2A, C9, rrm2), demonstrating deep phylogenetically conserved commonalities.
- DESR genes fell into **eleven functional categories**, led by Inflammatory Response/Wound Healing and Cytoskeletal genes; all eleven were active at the peak phase, with cell signaling, intracellular transport, axon outgrowth, and lipid/cellular metabolism limited to the peak.
- The **KEGG Adipocytokine signaling pathway** (linking leptin with metabolic, inflammatory and gene-regulatory pathways) emerged as a key network hub, containing up-regulated DESR genes lep, socs3, mapk8, and acsbg2 (notably socs3, generally considered inhibitory in mammals, was pro-regenerative here).
- Of 33 DESR genes with opposing expression between regenerative and non-regenerative cases, 55% were functionally interconnected (STRING), with a gene-regulatory network centered on chromatin-accessibility regulators (histones, epigenetic enzymes, Polycomb Repressive Complex components such as jarid2).

---

## Perspective

This study identifies deep, phylogenetically conserved commonalities between successful CNS axon regeneration and other examples of tissue regeneration (limb, liver, fin), and provides a curated resource of candidate genes and networks (the adipocytokine hub and a chromatin-accessibility regulatory network) for probing the molecular basis of CNS repair. Importantly, by contrasting regenerative and non-regenerative responses within one organism, it offers a guide for distinguishing pro-regenerative injury-induced gene expression changes from detrimental ones — a key challenge in mammalian studies where inflammation is both pro-regenerative and damaging.

Limitations include the use of complex whole tissues (mixtures of neurons, glia, myeloid cells) rather than purified cell types, reliance on gene functions inferred mostly from mammalian orthologs, analysis restricted to X. laevis-annotated genes (excluding novel genes, lncRNAs, and detailed homeolog/paralog behavior), and the correlative nature of the identified networks. Future work suggested includes functional validation of individual DESR genes and networks, cell-type-resolved analyses, and translation of these candidate distinctions to mammalian CNS injury.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE137844


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
