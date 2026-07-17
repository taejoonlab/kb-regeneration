---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Axon guidance at the spinal cord midline—A live imaging perspective

## Citation (NLM)
Dumoulin A, Zuñiga NR, Stoeckli ET. Axon guidance at the spinal cord midline—A live imaging perspective. J Comp Neurol. 2021;529(10):2517-2538. doi:10.1002/cne.25107

**DOI:** [https://doi.org/10.1002/cne.25107](https://doi.org/10.1002/cne.25107)

---

## Background

During neural circuit formation, axons navigate a series of intermediate targets (choice points), at each of which growth cones must switch responsiveness from attraction to repulsion to move on. In the developing spinal cord, dorsal dI1 commissural interneurons are a classic model: their axons cross the ventral midline (floor plate, FP), exit it, and turn rostrally along the contralateral border. For decades, mechanisms have been inferred from static "snapshots" of many growth cones in fixed tissue harvested at different time points, or from "open-book" preparation cultures. However, open-book cultures introduce artifacts (notably aberrant overshooting at the FP exit site), and snapshots cannot reveal the dynamic behavior of a single growth cone arriving at and leaving an intermediate target.

This Toolbox paper describes a novel ex vivo intact spinal cord preparation from chicken embryos that allows live imaging of individual dI1 axons navigating the midline within their intact environment, overcoming the artifacts of open-book cultures.

---

## Key Experiment Methods

1. **In ovo electroporation** of chicken neural tube at HH17-18 with Math1::tdTomato-F (dI1-specific label) and β-actin::EGFP-F (environment), plus Hoxa1::EGFP-F for FP labeling and miFzd3 constructs for Fzd3 knockdown.
2. **Dissection of intact spinal cords** from HH22 embryos, keeping ventral/dorsal midlines and DRGs intact, embedded ventral-side-down in low-melting agarose in a glass-bottom dish; compared with conventional **open-book preparations** from HH24 embryos.
3. **Live imaging** with an inverted spinning-disk confocal microscope (37°C, 5% CO2), acquiring z-stacks every 5–15 min for up to 24 h at 20x or 40x magnification.
4. **Virtual tracing** (MtrackJ/Fiji) of single Math1-positive growth cones to extract crossing timing and local growth speed; **kymographic and temporal-color projection** analyses.
5. **Immunohistochemistry / whole-mount staining** for patterning markers (Lhx2, Islet-1, Nkx2.2, Hnf3β/FoxA2, BEN/ALCAM), guidance cues (Shh, NrCAM), laminin (basal lamina/meninges), and cleaved caspase-3 (apoptosis).
6. **Shh intensity measurement** in the FP at lumbar vs. thoracic levels to assess gradient preservation.

---

## Results

- In intact spinal cord cultures, dI1 axons crossed the FP, turned rostrally, and formed the contralateral ventral funiculus normally over 24 h, faithfully reproducing the in vivo trajectory; a Math1-positive ipsilateral subpopulation was also seen.
- Tissue integrity was preserved after 1 day ex vivo: patterning markers, FP triangular shape, meninges/basal lamina (laminin), and the caudal-to-rostral Shh gradient were all maintained, with minimal apoptosis.
- In contrast, open-book cultures showed severe artifacts: 91 ± 6% of axons overshot the contralateral FP boundary (vs. 0% in intact preparation, where 98 ± 2% turned rostrally), loss of the Shh gradient, absent meninges, deformed/discontinuous basal lamina, and massive ventral apoptosis.
- Timing quantification: dI1 axons took 5.6 ± 1.4 h to cross the entire FP and 1.4 ± 1.0 h to turn rostrally (total 6.9 ± 1.8 h). No difference between the first and second FP halves. Turning time (but not crossing time) decreased significantly over time, suggesting pioneer axons help followers turn faster.
- Growth cones grew with fluctuating acceleration–deceleration pulses. Growth cone area transiently enlarged at the FP exit site (~105 μm² vs. ~45 μm² inside FP), matching in vivo values.
- 100% of growth cones extended long rostral and caudal filopodia just before turning; 16 ± 8% transiently split before turning. Higher-magnification 3D imaging revealed dynamic dorso-ventral protrusions (up to 13 μm) into the FP during crossing.

---

## Perspective

This method provides a stable, artifact-free ex vivo platform to follow individual commissural growth cones through the spinal cord midline choice point in their intact 3D environment, enabling measurement of growth speed, morphological changes, and aberrant behaviors (stalling, wrong turning) that static snapshots and open-book cultures cannot capture. It revealed the active participation of the FP intermediate target and possible axon–axon collaboration during turning. Limitations noted by the authors include limited resolution—particularly in 3D at low magnification—which may miss subtle growth cone morphology changes during crossing. The approach opens avenues for studying the precise timing of receptor switching (e.g., Fzd3, Slits, Shh, Wnt responsiveness) and interactions between axons at choice points, and is applicable to older embryos (at least HH24-25).

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
