---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
---

# Single-cell transcriptome profiling of the human developing spinal cord reveals a conserved genetic programme with human-specific features

## Citation (NLM)
Rayon T, Maizels RJ, Barrington C, Briscoe J. Single-cell transcriptome profiling of the human developing spinal cord reveals a conserved genetic programme with human-specific features. Development. 2021;148(15):dev199711. doi:10.1242/dev.199711

**DOI:** [https://doi.org/10.1242/dev.199711](https://doi.org/10.1242/dev.199711)

---

## Background

The spinal cord processes sensory input from the peripheral nervous system and controls motor output by regulating motor neurons. These functions rely on molecularly distinct neuronal subtypes that are generated in a stereotypic spatial and temporal order from proliferating progenitors in the embryonic neural tube, under the control of gene regulatory networks driven by extrinsic signals (e.g. SHH, WNT/BMP). Whereas single-cell profiling has extensively characterized the mouse neural tube and neural crest, the embryonic human spinal cord and peripheral nervous system have been comparatively poorly described.

The authors set out to systematically profile cell identity in the developing human neural tube to build a spatiotemporal gene expression atlas, allow direct comparison with mouse, and identify potential human-specific features. This is a Techniques and Resources research article that also delivers an online data viewer (https://shiny.crick.ac.uk/scviewer/neuraltube/).

---

## Key Experiment Methods

1. Droplet-based single-cell RNA sequencing (10x Chromium) of microdissected cervical-thoracic trunk regions from four human embryos at Carnegie stages CS12, CS14, CS17 and CS19 (gestational weeks 4-7); anterior/posterior and replicate splits for older stages.
2. Quality filtering matched to the prior mouse neural tube dataset (Delile et al., 2019), yielding 71,219 cells (43,485 neural); sex assignment via SRY expression.
3. Dimensionality reduction (UMAP) and gene module scoring to annotate tissue and cell types.
4. Cell-type classification using an adapted binarised "knowledge matrix" of marker genes to assign dorsoventral progenitor domains and neuronal classes (and a separate matrix for PNS/dorsal root ganglion cells).
5. Cross-species comparison of mouse and human using Pearson/Spearman correlation of transcription-factor expression per cell type; comparison to in vitro human ESC-derived motor neuron differentiation.
6. RNA velocity (scVelo) and lineage/latent-time modelling (CellRank) to reconstruct neurogenic trajectories; analysis of primate-specific gene expression; immunohistochemistry validation of selected markers (PAX7, NKX6-2, OLIG2/NKX2-2, gliogenic markers).

---

## Results

- Identified dozens of distinct cell types spanning neural tube progenitors/neurons, dorsal root ganglia, mesoderm, haematopoietic and skin cells; cell-type proportions shifted with developmental stage (more neurons at CS19, more mesoderm early).
- Progenitors arranged along the dorsoventral axis into 11 DV domains (plus floor and roof plate); overall identities and organisation were similar between mouse and human, with same-type cells showing highest cross-species correlation.
- Human-specific features: PAX7 expression in floor plate cells (absent in mouse FP), broader ventral NKX6-2 expression (vs p1-restricted in mouse), and scarce TBX20 in human visceral (PHOX2B+) motor neurons.
- Most primate-specific genes surveyed (43/49) were expressed broadly across tissues rather than being nervous-system specific; TMEM14B was the notable brain-development gene expressed in the CNS.
- PNS neurogenesis was delayed relative to CNS; classification recovered mechanoreceptor, proprioceptor, peptidergic and non-peptidergic sensory neuron programmes consistent with a single neurogenic trajectory.
- Human neural tube showed a higher initial proportion of pMN and p3 ventral progenitors and a temporally protracted dorsal neurogenesis compared with mouse; a conserved temporal transcription-factor code (Onecut early; POU2F2/ZFHX intermediate; NEUROD2/6, NFIA/B late) was detected.
- RNA-velocity trajectories confirmed conserved sequential gene expression during pMN-to-motor-neuron differentiation across species.
- Human OLIG2+/NKX2-2+ co-expressing progenitors were more abundant at early stages than in equivalent mouse stages, resembled an amalgamation of pMN and p3 identities, and expressed gliogenic markers (FABP7, OLIG1/2), consistent with early oligodendrocyte precursors and a heterochronic difference between rodents and primates.

---

## Perspective

This study provides the first systematic single-cell atlas of the developing human spinal cord and dorsal root ganglia across four first-trimester stages, establishing that mammalian neural tube development is broadly conserved while pinpointing concrete human-specific and heterochronic differences (PAX7 in FP, broad NKX6-2, earlier/abundant OLIG2+NKX2-2+ OLPs, protracted dorsal neurogenesis). The accompanying interactive resource supports developmental and stem-cell biologists refining protocols to generate specific neuronal subtypes.

Limitations noted by the authors include modest temporal resolution (four stages over ~2 weeks, single embryo per stage), lower gene counts in CS17 (excluded from velocity analysis), and increased asynchrony of in vitro differentiations at later stages. Whether human neurogenesis is genuinely delayed, and the lineage relationships and neurogenic/gliogenic potential of double-positive progenitors, will require more embryos, later time points and functional experiments.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
