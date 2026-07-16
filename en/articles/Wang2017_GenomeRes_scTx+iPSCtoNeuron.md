---
tags: [2026-07]
extract: 2026-07-16
---

# Single-cell gene expression analysis reveals regulators of distinct cell subpopulations among developing human neurons

## Citation (NLM)
Wang J, Jenjaroenpun P, Bhinge A, Espinosa Angarica V, Del Sol A, Nookaew I, Kuznetsov VA, Stanton LW. Single-cell gene expression analysis reveals regulators of distinct cell subpopulations among developing human neurons. Genome Research. 2017;27(11):1783-1794. doi:10.1101/gr.223313.117

**DOI:** [https://doi.org/10.1101/gr.223313.117](https://doi.org/10.1101/gr.223313.117)

---

## Background
The stochastic dynamics and regulatory mechanisms that govern differentiation of individual human neural precursor cells (NPCs) into mature neurons remain incompletely understood. Human embryonic stem cells (hESCs) and organoid cultures recapitulate aspects of early development, but the heterogeneity of the cell mixtures and the presence of rare, short-lived cell-fate transitions make it difficult for bulk genomics to resolve the molecular changes underlying cell-fate decisions.

Single-cell RNA-sequencing (scRNA-seq) can identify novel cell types, establish developmental kinetics, and reveal discrete cell-state transitions. However, most computational trajectory methods (Monocle, Wanderlust, Wishbone, SLICER, Diffusion Pseudotime, SCUBA) compulsively order all cells into smooth continuous trajectories, potentially missing discontinuous development and stochastic fate changes. Here the authors develop an unsupervised, high-resolution strategy to dissect NPC subtypes and critical developmental bifurcations during differentiation of hESC-derived hindbrain/spinal cord neurons.

---

## Key Experiment Methods
1. Differentiated hESCs (H9 line) into SOX2+/NESTIN+ NPCs using small-molecule inhibitors of GSK3, SMAD, and NOTCH; then induced non-directed neuronal differentiation with neurotrophic factors (BDNF, GDNF, cAMP) over 30 days, yielding predominantly TUJ1+/MAP2+ hindbrain/spinal cord (HOX+) neurons.
2. Captured single cells at discrete time points (days 0, 1, 5, 7, 10, 30; and days 0, 3, 7, 14 in a second experiment) using the Fluidigm C1 system; prepared libraries with Illumina Nextera XT and deep-sequenced individual transcriptomes (final 8957 genes across 483 high-quality cells).
3. Mapped reads to hg19 (TopHat/Bowtie2), quantified with HTSeq-count, normalized with DESeq2; identified differentially expressed genes with single-cell differential expression (SCDE), yielding 528 "dynamic classifier" (DC) genes (fold change >1.5, P < 10⁻⁷).
4. Performed unsupervised hierarchical clustering (pvclust, bootstrapping) at each time point to define subpopulations; established lineage connections using common DEGs and Pearson correlations between neighboring time points.
5. Reconstructed subpopulation-specific gene regulatory networks using the MetaCore database of validated interactions; identified 195 differentially expressed transcription factors and 138 lincRNAs.
6. Functionally validated candidate regulators by lentiviral (plko.1) shRNA knockdown in NPCs and by pharmacological WNT activation (CHIR99021), quantifying neuronal differentiation by TUJ1/GFAP immunostaining.

---

## Results
- NPC populations were heterogeneous at day 0, underwent a rapid constriction of heterogeneity within 1 day of differentiation (coordinated gene switch-on), then re-diversified, becoming most heterogeneous among day-30 neurons.
- Subpopulation tracking revealed three lineages: two subpopulations ("a" and "b") present in starting NPCs, a third ("c") arising from "b" on day 1 and persisting to day 30; "a" and "b" converged into a single "ab" lineage by day 7.
- The "c" lineage differentiated into neurons earlier than "ab" (enriched for neuronal-function GO terms); "ab" retained mitosis/cell-cycle signatures, indicating immature neurons (some day-30 cells still in G2/M).
- Subpopulation analysis exposed gene dynamics masked in bulk analysis: e.g., PAX6 appeared unchanged in bulk Q-RT-PCR but rose sharply in "a" while staying high in "b"; cell-cycle genes (HMGA1, CENPF) fell fastest and neuronal markers (DCX, STMN2) rose fastest in "c".
- Identified known neurogenesis regulators (PAX6, MEIS1, ASCL1, NEUROD1, NEUROD4, REST) and validated newly implicated regulators: knockdown of transcription factors POU3F2 and PBX1 and lincRNA MIAT each significantly blocked neuronal differentiation; WNT5A down-regulation was required for neurogenesis (CHIR99021 blocked differentiation).
- Gene regulatory network analysis showed ASCL1 as a hub in "c" on day 1 and NEUROD1 as a hub on days 5/10, with REST as a master repressor negatively regulating PAX6, ASCL1, NEUROD1, and MEIS1; network modeling supported that either ASCL1 or NEUROD1 alone can specify "c" cells (discontinuous, non-sequential activation).
- WNT5A co-expressed with specific HOX genes (HOXC8/9/10, HOXA3) in neural stem cells, consistent with the derived NPCs being lineage-restricted toward hindbrain/spinal cord identity.

---

## Perspective
The study provides an experimental and computational framework for scRNA-seq time-course analysis that resolves both continuous and discontinuous developmental processes, capturing rare/transient subpopulations (the day-1 "c" lineage) that smooth-trajectory methods obscure. By coupling subpopulation-specific dynamics with functional validation, it identifies POU3F2, PBX1, and MIAT as critical early regulators of hindbrain/spinal cord neuron differentiation. Relevance to spinal cord biology lies in its use of an in vitro model of human hindbrain/spinal cord neurogenesis (HOX+ neurons), offering candidate regulators and markers for developing spinal neurons. Limitations noted by the authors include conservative subpopulation calling (likely more than two subpopulations exist), limited cell numbers per time point, and the absence of an observed lineage shift upon knockdown—indicating that tightly controlled, temporally resolved perturbations are needed to test lineage-bifurcation predictions. The approach is generalizable to other developmental or stimulus-response processes.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
