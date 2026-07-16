---
tags: [2026-07]
extract: 2026-07-16
---

# RNA-Seq Characterization of Spinal Cord Injury Transcriptome in Acute/Subacute Phases: A Resource for Understanding the Pathology at the Systems Level

## Citation (NLM)
Chen K, Deng S, Lu H, Zheng Y, Yang G, Kim D, Cao Q, Wu JQ. RNA-Seq Characterization of Spinal Cord Injury Transcriptome in Acute/Subacute Phases: A Resource for Understanding the Pathology at the Systems Level. PLoS One. 2013;8(8):e72567. doi:10.1371/journal.pone.0072567

**DOI:** [https://doi.org/10.1371/journal.pone.0072567](https://doi.org/10.1371/journal.pone.0072567)

---

## Background

Spinal cord injury (SCI) is a devastating neurological condition with no effective treatment; about 300,000 people live with SCI in the US and ~11,000 new cases occur annually. After the primary mechanical trauma, secondary injury cascades cause further tissue loss and dysfunction. Previous molecular studies typically examined only a small number of genes or used microarrays, which have limited resolution, dynamic range, and accuracy, and therefore could not provide a comprehensive systems-level view of SCI pathology.

The authors apply RNA-Seq to characterize temporal transcriptome changes after contusive SCI in mice during the acute (2 days) and subacute (7 days) phases, aiming to identify key pathways, genes, and splicing isoforms, and to build a systems-based analytical framework and reference resource for the SCI community.

---

## Key Experiment Methods

1. Moderate T9 contusive SCI in female C57BL/6J mice using an Infinite Horizons impactor (60 kdyn); sham controls received laminectomy only. Injury severity confirmed by eriochrome cyanine histology and Basso Mouse Score locomotion tests.
2. RNA-Seq (paired-end, Illumina HiSeq) of polyA-selected RNA from injury-epicenter tissue at control (sham), 2 days (2D), and 7 days (7D); reads mapped to mouse mm9 with Tophat/Bowtie and assembled/quantified (FPKM) with Cufflinks.
3. FPKM reliability threshold determination via false-positive/negative rate curves (threshold set at 0.1 FPKM); differential expression called at >2-fold change and t-test p < 0.05.
4. c-means (mfuzz) clustering of temporal expression and unsupervised hierarchical clustering of replicates; comparison with a prior contusion-SCI microarray dataset (GEO GSE5296).
5. Functional/pathway analysis with Ingenuity Pathway Analysis (IPA) and Gene Set Enrichment Analysis (GSEA, MSigDB); systems-based network construction with a Relevance Index (RI = |log(fold change)| x connection number) to prioritize candidate genes, incorporating pharmacogenomic (drug) information.
6. Alternative splicing/isoform expression analysis, and qRT-PCR validation of selected genes (C3AR1, CCL7, CD22, CD36, CLEC6A, FCER1G, FCGR2B, Il7r, LPL, MSR1, PTX3).

---

## Results

- RNA-Seq detected 2,832 differentially expressed genes at 2D and 4,207 at 7D (1,802 shared); 7D had more downregulated genes (2,579 vs. 1,187), attributed to increased neural cell death. Upregulated genes were enriched for "inflammatory response," downregulated genes for "nervous system development."
- Top enriched functional categories at both time points were inflammation response, neurological disease, cell death and survival, and nervous system development; top canonical pathways included LXR/RXR Activation, Atherosclerosis Signaling, and TREM1 Signaling. Glutamate Receptor Signaling (mostly downregulated) appeared specifically at 7D.
- RNA-Seq showed higher sensitivity and broader dynamic range than the comparable microarray dataset, detecting more differentially expressed genes.
- Alternative splicing was pervasive (up to 12 isoforms per gene; ~99% with 1-5); 10,327 isoforms changed >2-fold. Examples: Spp1 (osteopontin) rose overall, driven by isoform NM_009263; Morf4l2 showed "isoform switching," with NM_001168230 becoming dominant after injury.
- The systems framework ranked known SCI genes (Il6, Tnf, Il1b, Ccl2) at the top, validating the approach, and highlighted less-studied candidates with drug information (Cd36, Lpl, C3ar1, Msr1), confirmed by qRT-PCR.
- Cell-type marker analysis showed macrophage dynamics (M1 marker Cd86 up at 7D, M2 marker Arg1 up at 2D; M1 gene set further enriched at 7D), suggesting a rising M1/M2 ratio in the subacute phase; reactive astrocyte markers Gfap, Lcn2, and Serpina3n were upregulated (Lcn2/Serpina3n higher at 2D). Markers for OPCs (Cspg4/Ng2), NSCs (Nestin), endothelial cells (Pecam-1/Cd31), and HSCs (Cd34) were also profiled.

---

## Perspective

This study provides a genome-wide, systems-level reference transcriptome of acute and subacute mouse contusion SCI, demonstrating that RNA-Seq outperforms microarrays and adds isoform-level resolution valuable for drug specificity. Its systems-based prioritization framework (combining differential expression, network connectivity, cellular localization, and pharmacogenomics) successfully recovers known SCI genes and nominates novel candidates (e.g., Cd36, Lpl, C3ar1, Msr1) and pathways (LXR/RXR, Atherosclerosis Signaling) for functional testing. Limitations include profiling of mixed-cell-type whole tissue (limiting cell-type attribution), only two post-injury time points, pooled biological replicates, and restriction of analysis to known transcripts. The datasets and framework are offered as a hypothesis-generating resource; the authors note plans to test prioritized genes in animal models to identify new mechanisms and therapeutic targets for reducing secondary damage and promoting regeneration.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
