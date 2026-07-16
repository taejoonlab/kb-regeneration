---
tags: [2026-07]
extract: 2026-07-16
---

# Foxm1 regulates neural progenitor fate during spinal cord regeneration

## Citation (NLM)
Pelzer D, Phipps LS, Thuret R, Gallardo-Dodd CJ, Baker SM, Dorey K. Foxm1 regulates neural progenitor fate during spinal cord regeneration. EMBO Rep. 2021;22(11):e50932. doi:10.15252/embr.202050932

**DOI:** [https://doi.org/10.15252/embr.202050932](https://doi.org/10.15252/embr.202050932)

---

## Background

Mammals have limited CNS regeneration, and spinal cord injuries are often irreversible. In contrast, *Xenopus* tadpoles can fully regenerate their tail, including the spinal cord, after amputation. The injured spinal cord is sealed within a day by a neural ampulla and regenerates from its original stump. A hallmark of spinal cord regeneration is re-activation of Sox2/3+ neural progenitor cells (NPCs) to drive both regrowth and generation of new neurons. In axolotl, NPCs in an amputation-adjacent "source zone" proliferate extensively as progenitors switch from neurogenic to proliferative divisions (a switch driven in part by the planar cell polarity pathway). However, how the balance between self-renewal/proliferation and differentiation is controlled during regeneration was poorly understood.

During development, the proliferative-to-neurogenic division switch depends in part on changes in relative cell-cycle phase length. Taking an unbiased RNA-seq approach on isolated spinal cords, the authors identified Foxm1—a transcription factor known to promote the G2/M transition—as a candidate regulator specifically expressed during *X. tropicalis* spinal cord regeneration.

---

## Key Experiment Methods

1. **Bulk RNA-seq** of isolated spinal cords at 0, 1, and 3 days post-amputation (dpa) with GO clustering and Ingenuity Pathway Analysis (IPA) to identify upstream regulators; comparison with published whole-tail regeneration data.
2. **Validation of foxm1 expression** by in situ hybridisation (ISH, whole-mount + sections) and RT-qPCR time course (0h–7d); pharmacological tests of upstream signals—NOX/ROS inhibitor DPI, FGFR inhibitor SU5402, Shh inhibitor cyclopamine.
3. **CRISPR/Cas9 knockout** of foxm1 (gRNA targeting bases 129–152 downstream of ATG); germline-transmitted frameshift mutants to generate foxm1−/− tadpoles; morpholino (splice-blocking) knockdown as complementary loss-of-function.
4. **Regeneration assays** comparing foxm1+/+, +/−, −/− tail regrowth at 3 and 7 dpa; F0 mosaic analysis.
5. **Proliferation/cell-cycle analysis**: EdU labelling with chase; Dual-Pulse S-phase Labelling (DPSL, EdU→BrdU) to measure absolute cell-cycle length (Tc); PCNA staining to score S/G1-G2/M phases; growth-fraction (PCNA+Sox3+) quantification.
6. **Single-cell RNA-seq** (10X Genomics) of uninjured (2,908 cells) and regenerating (0 vs 3 dpa) spinal cord, with Seurat batch correction, cluster annotation, pseudo-time (Monocle) and cell-cycle inference.
7. **Fate analysis**: EdU pulse at 3 dpa with 5-dpa fate readout (Sox3/EdU), and Sox3/Myt1 immunofluorescence to quantify progenitor vs neuron proportions.

---

## Results

- Bulk RNA-seq revealed three temporal phases after amputation: early metabolic gene upregulation, strong cell-cycle gene upregulation, then downregulation of nervous-system development genes. IPA identified Foxm1 as the top upstream regulator at 3 dpa; Foxm1 and its target genes are upregulated specifically in the spinal cord (not whole tail) at 3 dpa.
- foxm1 is not expressed at 0/1 dpa but is restricted to the regenerating spinal cord at 3 dpa (peaks at 3 dpa, returns to baseline by 7 dpa). Its induction requires ROS (DPI reduces foxm1 by ~69%) but is independent of FGF and Shh signalling.
- foxm1−/− tadpoles develop normally but show impaired spinal cord regeneration: ~35% lower tail regrowth by 7 dpa; heterozygotes have an intermediate (~17%) reduction, indicating a dose-dependent effect.
- Foxm1 does **not** regulate proliferation rate or cell-cycle length: EdU+ fractions and absolute Tc (~50 h) were equal in wt and foxm1−/−; primary neurogenesis proliferation was also unaffected.
- scRNA-seq identified the expected spinal cord cell types plus two 3-dpa-specific clusters: a foxm1+ progenitor cluster (sox2+, many cells in S phase, enriched for cell-cycle genes such as ccna2, pcna, cdk2) and a leptin+ neuron cluster. Cell-cycle inference and PCNA staining showed a transient increase in S-phase cells at 3 dpa (returning to baseline by 5 dpa).
- In foxm1−/− regenerates, the proportion of Sox3+ progenitors increased (62% → 69%) with disorganized multilayered arrangement, self-renewal divisions rose (65% → 75%), and Myt1+ neurons dropped sharply (30% → 14%)—with no change in proliferation rate or apoptosis. Thus Foxm1 shifts dividing progenitor fate toward neuronal differentiation rather than self-renewal.

---

## Perspective

This study uncovers a spinal cord-specific injury response and assigns Foxm1 a cell-cycle-independent role in regeneration: rather than driving proliferation, Foxm1 controls the fate of dividing neural progenitors, promoting neuronal differentiation required for successful spinal cord regeneration. This contrasts with Foxm1's cell-cycle-dependent roles reported in *X. laevis* primary neurogenesis and the mouse telencephalon, suggesting context-specific functions for a canonical cell-cycle regulator. The work also emphasizes that neuronal differentiation itself is necessary for the regenerative process, and identifies ROS as an upstream inducer of foxm1.

Limitations noted: the sequencing depth/cell number did not allow unambiguous assignment of progenitor and neuron subtypes; the role of the newly identified leptin+ neuron population during regeneration remains unclear; and the downstream mechanism by which Foxm1 biases fate (independent of cell-cycle length) is not fully defined. The comparative amphibian model provides insight relevant to why mammalian spinal cord regeneration fails.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
