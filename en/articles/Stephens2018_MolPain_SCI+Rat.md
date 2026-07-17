---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# RNA-seq of spinal cord from nerve-injured rats after spinal cord stimulation

## Citation (NLM)
Stephens KE, Chen Z, Sivanesan E, Raja SN, Linderoth B, Taverna SD, Guan Y. RNA-seq of spinal cord from nerve-injured rats after spinal cord stimulation. Mol Pain. 2018;14:1744806918817429. doi:10.1177/1744806918817429

**DOI:** [https://doi.org/10.1177/1744806918817429](https://doi.org/10.1177/1744806918817429)

---

## Background

Spinal cord stimulation (SCS) is a widely used neurostimulation therapy for neuropathic pain refractory to pharmacotherapy, based on gate-control theory and delivered via epidural leads that activate low-threshold Aβ-fibers of the dorsal column. Although SCS is linked to spinal inhibitory mechanisms and altered neurotransmitter release, the molecular control of the inhibitory and excitatory changes it produces is poorly understood, and prior evidence suggested SCS induces broad, prolonged changes in gene expression.

This study performed the first RNA-seq analysis of the lumbar spinal cord after repetitive conventional SCS in rats during the maintenance phase of neuropathic pain, aiming to identify differentially expressed genes and gene networks and to nominate new therapeutic targets for improving SCS efficacy.

---

## Key Experiment Methods

1. Chronic constriction injury (CCI) of the left sciatic nerve in adult male and female Sprague-Dawley rats; mechanical hypersensitivity confirmed by von Frey paw withdrawal threshold (PWT) testing.
2. Randomization to repetitive conventional SCS (CCI+SCS) via an epidurally implanted miniature quadripolar electrode at the T13-L1 level, or CCI only (no treatment); SCS delivered at 50 Hz, 80% motor threshold, 0.2 ms, constant current, 120 min/session across consecutive days.
3. Harvest of ipsilateral L4-L6 lumbar spinal cord within 1-2 h after the last SCS session; total RNA extraction with DNase treatment and quality assessment.
4. Strand-specific poly(A) RNA-seq library preparation and paired-end 150 bp sequencing on Illumina HiSeq4000 (~33.6 million reads/sample).
5. Alignment to rat genome (rn6) with HISAT2, featureCounts quantification, differential expression by DESeq2 (FDR < 0.05, including a sex-interaction term), gene ontology enrichment via ToppGene, and gene-class assignment using the IUPHAR/Guide to Pharmacology database.

---

## Results

- Each SCS session significantly increased mechanical PWT (peak inhibition at 60-90 min, returning to baseline within 30 min of cessation); pain inhibition correlated positively with motor threshold.
- Compared to CCI only, CCI+SCS spinal cord differentially expressed 1,113 genes (7.9%): 785 upregulated and 328 downregulated; 343 could be classed into transporters, enzymes, GPCRs, ion channels, catalytic receptors, and transcription factors.
- Upregulated genes were strongly enriched for immune-related biological processes; top upregulated transcripts included C3, Adgre1, Cd4, Il1b, Cxcl13, Csf1r, and markers of astrocytes (Gfap, Ccl2) and activated microglia (Cd68, Itgam), plus toll-like receptors, indicating increased non-neuronal/immune activation.
- Downregulated genes were enriched for synaptic transmission, synaptic organization, and neuron outgrowth; molecular-function enrichment highlighted serine/threonine kinase activity and scaffold protein binding.
- SCS repressed key postsynaptic density (PSD) scaffold genes (Dlg4/PSD-95, Dlgap1, Dlgap3, Shank1, Shank3, Grip2), which stabilize NMDAR/AMPAR localization; the GABA transporter gene Slc6a11 (GAT3) was also downregulated, suggesting mechanisms that could enhance synaptic GABA availability and destabilize the PSD to attenuate excitatory transmission.
- Sex analysis: males differentially expressed 149 genes, females 858 (FDR < 0.05), but both sexes showed similar GO processes (immune upregulation, synaptic downregulation); only a small number of genes differed significantly between sexes, so data were pooled.

---

## Perspective

This first RNA-seq study of the spinal cord after repetitive conventional SCS shows that SCS, despite reducing mechanical hypersensitivity, is paradoxically associated with further upregulation of immune/glial-activation genes while simultaneously repressing PSD scaffold genes. The authors propose that destabilization of the postsynaptic density (reduced NMDAR/AMPAR aggregation) and increased synaptic GABA availability may be novel mechanisms underlying SCS-mediated pain inhibition, offering candidate transcriptional/epigenetic targets to improve SCS efficacy. Limitations include a small sample size (five SCS rats, n = 1 rat/library), data pooled across sexes despite differing gene counts, harvesting of combined dorsal/ventral cord at distal segments, and the correlational (non-causal) nature of the gene-expression associations; the mechanisms driving transcriptional change in segments distal to the stimulating electrode remain unknown.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
