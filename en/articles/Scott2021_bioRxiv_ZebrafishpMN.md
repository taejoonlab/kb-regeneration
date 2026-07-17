---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
---

# Temporal single-cell transcriptomes of zebrafish spinal cord pMN progenitors reveal distinct neuronal and glial progenitor populations

## Citation (NLM)
Scott K, O'Rourke R, Winkler CC, Kearns CA, Appel B. Temporal single-cell transcriptomes of zebrafish spinal cord pMN progenitors reveal distinct neuronal and glial progenitor populations. bioRxiv. 2021 Apr 29. doi:10.1101/2021.04.28.441874

**DOI:** [https://doi.org/10.1101/2021.04.28.441874](https://doi.org/10.1101/2021.04.28.441874)

---

## Background
Ventral spinal cord pMN progenitors, marked by the bHLH transcription factor Olig2, sequentially produce motor neurons and then oligodendrocyte precursor cells (OPCs); some OPCs differentiate into myelinating oligodendrocytes while others persist. Much is known about the molecular profiles of the differentiated cell types, but less about the progenitors that produce them.

Lineage tracing and prior zebrafish fate mapping/time-lapse imaging (Ravanelli and Appel, 2015) suggested that motor neurons and OPCs arise from distinct pMN progenitor cells that initiate olig2 expression at different times. This study aimed to identify the developmental origins and transcriptional profiles of motor neuron and OPC progenitors in the developing zebrafish spinal cord using single-cell RNA sequencing.

---

## Key Experiment Methods
1. FACS isolation of olig2:EGFP+ cells from the trunk/tail of Tg(olig2:EGFP) zebrafish embryos at 24, 36, and 48 hpf (capturing motor neurogenesis, OPC specification, and initiation of oligodendrocyte differentiation).
2. Single-cell RNA sequencing (10X Genomics Chromium; Illumina NovaSeq 6000) and unsupervised Seurat clustering of individual stages and an integrated dataset; cluster identity by known marker genes.
3. Sub-clustering to resolve MEP glia vs cranial motor neuron precursors and to separate interneuron precursors from Pre-OPCs within the oligodendrocyte lineage.
4. Trajectory analyses: RNA velocity (velocyto/scVelo) and Slingshot pseudotime; generalized additive model (GAM) for differentially expressed genes along lineages.
5. Fluorescent in situ RNA hybridization (RNAScope Multiplex Fluorescent V2) for ascl1a, neurog1, gsx2, sox10, olig1 in 36 and 40 hpf embryos to validate progenitor populations in vivo.

---

## Results
- Integrated scRNA-seq (28 clusters) captured a progression from neural progenitors to differentiated cells; most cells were neurons/neuronal precursors, ~24% progenitors, ~10% glial lineages. Long EGFP perdurance explained olig2– elavl4+ post-mitotic neurons.
- pMN cells comprised two distinct progenitor populations: sox19a+ neurog1+ neuronal progenitors (associated with the motor neuron lineage) and sox19a+ neurog1– Pre-OPC progenitors (associated with the oligodendrocyte lineage).
- At 48 hpf, OPCs (sox10+, sox5, sox9a/b, olig1) and pre-myelinating oligodendrocytes (tcf7l2, myrf) formed distinct clusters; radial glia (sox19a+ pcna– gfap+), known to produce new neurons after spinal cord injury, were present. Cells with Pre-OPC characteristics were absent at 48 hpf, indicating they arise earlier and are depleted after OPC formation.
- At 36 and 24 hpf, Pre-OPCs expressed nkx2.2a, low olig1, and Pre-OPC markers ascl1a and gsx2; at 24 hpf Pre-OPCs split into a less mature Pre-OPC1 (lower olig2, dorsal markers pax6a/dbx1a/irx3a) and a more mature Pre-OPC2 (higher olig2/olig1/nkx2.2), with RNA velocity predicting Pre-OPC1→Pre-OPC2 transition.
- RNA velocity and Slingshot supported separate developmental trajectories for motor neurons and oligodendrocytes; neuronal lineages expressed isl1, mnx1, neurod4, while the oligodendrocyte lineage expressed sox9b, prdm8, olig1, nkx2.2a and maintained olig2.
- gsx2 was expressed exclusively in Pre-OPC1/2 and mutually exclusive with neurog1; FISH confirmed ascl1a+ neurog1+ gsx2– neuronal pMN progenitors and ascl1a+ neurog1– gsx2+ Pre-OPCs in the ventral spinal cord, and that most sox10+ cells expressed gsx2 (a subset also olig1).

---

## Perspective
The study provides a developmental single-cell atlas of zebrafish pMN progenitors and demonstrates that motor neurons and oligodendrocytes arise from transcriptionally distinct progenitor populations specified early, before OPC specification. It identifies gsx2 as a marker of Pre-OPCs, offering a new tool to explore the earliest steps of oligodendrocyte lineage formation; the authors relate gsx2's role to prior mouse cortex findings where Gsx2 restricts OPC formation. The Pre-OPC1 population may represent dorsally recruited progenitors that slide ventrally into the pMN domain. For the regeneration knowledgebase, the resolved progenitor heterogeneity and radial glia (which can generate neurons after spinal cord injury) are directly relevant to CNS repair. As a preprint, findings await peer review.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
