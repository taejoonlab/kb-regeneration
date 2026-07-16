---
tags: [2026-07]
extract: 2026-07-16
---

# Single-Cell Transcriptomics Reveals a Population of Dormant Neural Stem Cells that Become Activated upon Brain Injury

## Citation (NLM)
Llorens-Bobadilla E, Zhao S, Baser A, Saiz-Castro G, Zwadlo K, Martin-Villalba A. Single-Cell Transcriptomics Reveals a Population of Dormant Neural Stem Cells that Become Activated upon Brain Injury. Cell Stem Cell. 2015;17(3):329-340. doi:10.1016/j.stem.2015.07.002

**DOI:** [https://doi.org/10.1016/j.stem.2015.07.002](https://doi.org/10.1016/j.stem.2015.07.002)

---

## Background

Adult neural stem cells (NSCs, type B cells) in the subventricular zone (SVZ) continuously generate neuroblasts that migrate to the olfactory bulb, and they can be recruited to contribute to brain repair after injury. Emerging evidence indicated that NSCs are functionally heterogeneous, coexisting in different states of activation and with distinct capacities to generate neuronal and glial progeny. However, because prior studies examined only a few markers or worked with potentially mixed populations, the molecular control of NSC activation and lineage determination — and how distinct NSC pools respond to injury — remained unclear.

The authors applied single-cell RNA sequencing to an unbiased pool of acutely isolated adult SVZ NSCs to resolve this heterogeneity, map the transition from quiescence to activation, and identify the molecular triggers of injury-induced NSC activation.

---

## Key Experiment Methods

1. FACS isolation of SVZ NSCs as CD45−/O4−/GLAST+/Prominin1(CD133)+ cells, and neuroblasts as PSA-NCAM+ cells, avoiding the need for transgenic reporters.
2. Single-cell RNA-seq (Smart-seq2) of 104 GLAST+/Prom1+ cells and 26 PSA-NCAM+ cells, with 1,000-cell population controls and RNA spike-ins for technical noise control.
3. Principal component analysis (PCA), unsupervised hierarchical clustering, and cell-to-cell correlation to define cell types and subpopulations.
4. Monocle pseudotemporal ordering to reconstruct the dormancy-to-activation continuum.
5. Functional validation of protein synthesis rate via O-propargyl-puromycin (OP-Puro) incorporation, plus γ-secretase inhibition (DAPT) to test Notch's role in quiescence.
6. Comparative scRNA-seq of parenchymal astrocytes (n=21) and transit-amplifying progenitors (TAPs, n=27) to define NSC-specific markers (e.g., CD9).
7. Transcription-factor-only PCA and correlation analysis to reconstruct lineage/spatial priming; comparison to Ascl1 ChIP-seq.
8. Transient bilateral common carotid artery occlusion (ischemic injury) followed by scRNA-seq of 45 injured NSCs; Ingenuity upstream regulator analysis; validation in Ifngr1−/− mice.

---

## Results

- Single-cell transcriptomes cleanly separated three cell types: neuroblasts (PSA-NCAM+), NSCs (GLAST+/Prom1+), and a small oligodendroglial cluster.
- NSCs partitioned into quiescent (qNSC, Egfr−) and active (aNSC, Egfr+, cell-cycle genes) states, each further subdivided (qNSC1/2, aNSC1/2), forming a continuum. Pseudotime placed a dormant state (qNSC1) → primed-quiescent (qNSC2) → aNSC1 → aNSC2.
- Dormancy was characterized by high glycolytic and lipid (fatty acid) metabolism and low protein synthesis; activation involved upregulated protein synthesis (validated: aNSCs showed 7.9-fold higher OP-Puro incorporation than qNSCs), cell cycle, and lineage-specific transcription factors.
- CD9 distinguished SVZ NSCs from parenchymal astrocytes; TAPs and astrocytes sat at opposite ends of the activation continuum.
- Quiescence was associated with TFs Sox9, Id2, Id3 and with Notch (Notch2, Lfng) and BMP (Bmpr1b, Id2) signaling; activation with Egr1, Fos, SoxC (Sox4/11), and Ascl1. DAPT (Notch inhibition) drove qNSCs toward activation.
- NSCs were lineage/spatially primed: correlated TF modules (e.g., dorsal Emx1/Nr2f1, ventral Nkx2-1, lateral Gsx2/Dlx2, an Olig2 oligodendroglial cluster) reflected fated subpopulations in both quiescent and active cells.
- Ischemic injury shifted NSCs out of dormancy into primed-quiescent and active states. Injury-response genes were enriched for interferon-gamma (IFN-γ) targets; in Ifngr1−/− mice the IFN-γ response and the dormant→primed-quiescent transition were largely abrogated, identifying IFN-γ as the molecular trigger.

---

## Perspective

This study provided the first high-resolution, unbiased single-cell map of adult SVZ NSC states, establishing dormancy and primed-quiescence as distinct steps reminiscent of the G0-to-Galert transition in muscle satellite cells, and pinpointing translational control as an early event in exit from dormancy. It defined NSC-specific markers (CD9) and demonstrated pre-existing lineage priming in individual NSCs. Functionally, it identified IFN-γ as an injury-derived signal that recruits dormant NSCs, opening avenues for regenerative strategies that mobilize endogenous stem cells. Limitations include the modest number of single cells profiled, reliance on surface-marker–based sorting, and correlative/pseudotime inference of state transitions that warrant direct lineage-tracing validation.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
