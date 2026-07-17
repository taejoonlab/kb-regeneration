---
tags: [2026-07, Chondrocyte]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# Tracking chondrocyte-to-fibroblast transformation via changes in cell electrophysiology

## Citation (NLM)

Clarke KSP, Lewis R, Hughes MP, Labeed FH. Tracking chondrocyte-to-fibroblast transformation via changes in cell electrophysiology. Sci Rep. 2025;15(1):15865. doi:10.1038/s41598-025-98958-1

**DOI:** [https://doi.org/10.1038/s41598-025-98958-1](https://doi.org/10.1038/s41598-025-98958-1)

---

## Background

Cultured chondrocytes hold promise for cartilage regeneration, but during standard monolayer culture they dedifferentiate over time, adopting a more fibroblastic phenotype—losing collagen type II and cartilage-specific proteoglycans while gaining collagen type I, with morphological flattening and stress-fibre formation. This is a major obstacle for autologous chondrocyte implantation (ACI), which requires significant in vitro expansion, because dedifferentiation causes up to 70% of patients to develop fibrocartilaginous fill and undermines both clinical repair and osteoarthritis research. Existing monitoring methods (gene expression, characterized chondrocyte implantation, single-cell sequencing/ATAC-seq) are costly or inconsistent. Prior patch-clamp and dielectrophoresis (DEP) work showed that chondrocyte electrical properties (ion-channel expression, membrane potential) change with passage and with osteoarthritic state, suggesting electrophysiology could be a biomarker. This study used DEP to track the electrophysiological properties of primary bovine chondrocytes over 100 days in culture, aiming to provide a low-cost, high-throughput readout of chondrocyte dedifferentiation.

---

## Key Experiment Methods

**1. Primary bovine chondrocyte culture**
- Chondrocytes enzymatically isolated from bovine metacarpophalangeal joint cartilage; cultured in monolayer (DMEM + 10% FBS, sucrose) at 37 °C; passaged at 70–80% confluence
- n = 5 biological repeats (different cows); measurements at intervals up to 100 days

**2. Dielectrophoresis (DEP) measurement**
- Cells resuspended (1 × 10⁶ cells/mL) in DEP media of five conductivities (0/1/3/10/33% physiological ionic stock; 8, 21, 50, 150, 447 mS/m); acute suspension after a 5-min wash
- 3DEP reader, 10 kHz–20 MHz; DEP spectra fitted to the Clausius–Mossotti model in MATLAB (low-frequency dispersion considered), accepting r² > 0.8
- Extracted membrane conductance (Geff), membrane capacitance (Ceff), and cytoplasm conductivity (σcyto) at 21, 50, 150 mS/m; cell radius by ImageJ (spherical approximation); Trypan blue viability

**3. Membrane potential (Vm) derivation**
- Vm calculated from the DEP-derived relationship between δσcyto and δσmed (external surface potential Ψext = −12 mV), a label-free, non-contact method

**4. Statistics**
- Non-parametric Friedman + Dunn's for Geff/Ceff/σcyto vs σmed; repeated-measures ANOVA for radius; linear regression of parameters vs days in culture (age tracked by days, not passage number)

---

## Results

**Cytoplasm conductivity was the most reliable readout**
Testing five media conductivities, spectra remained modellable up to 150 mS/m (r² = 0.92) but were noisy at 447 mS/m; 21, 50, and 150 mS/m were selected. Ceff decreased with rising σmed (significantly lower at 150 mS/m: 1.88 ± 0.46 vs 5.32 ± 1.02 mFm⁻² at 50 mS/m, p = 0.0039), whereas σcyto increased with σmed (0.68 ± 0.06 at 150 mS/m vs 0.26 ± 0.02 Sm⁻¹ at 21 mS/m, p < 0.0001). Osmolarity and pH were constant across media, so these changes reflected ionic concentration differences.

**Electrical properties changed significantly over time in culture**
In 150 mS/m medium, σcyto increased significantly over 100 days (regression slope non-zero, p = 0.0036) and Geff also rose significantly (p = 0.012), though with modest r² (~0.45–0.55), so the parameters trend but are not precisely predictable from culture day alone. Ceff showed no significant time trend. Cell radius (~10 µm) was stable, and Trypan blue showed no viability change over time.

**Membrane potential hyperpolarized in three discrete stages**
Derived Vm became progressively more negative with culture time and, rather than varying continuously, transitioned between three stable regimes: before day ~40, Vm was −13 to −18 mV (chondrocyte range, matching patch-clamp literature ~−24 mV for bovine chondrocytes); it then hyperpolarized to −32 to −43 mV until day ~80 (proliferating fibroblast range, −20 to −30 mV); and finally to −55 to −71 mV (non-proliferating fibroblast, ~−68 mV). This staged transition suggests the population collectively shifts between chondrocytic, proliferating-fibroblastic, and non-proliferating-fibroblastic states.

---

## Perspective

This work is the first to track the cellular "electrome" of chondrocytes across the full duration of monolayer culture, showing that dielectrophoresis can non-invasively follow chondrocyte-to-fibroblast dedifferentiation via membrane potential and cytoplasm conductivity.

First, the discovery that derived Vm transitions through three discrete, patch-clamp-consistent regimes—rather than drifting continuously—implies a stepwise phenotypic conversion (chondrocyte → proliferating fibroblast → non-proliferating fibroblast) with transitions near days 40 and 80. This offers a label-free, low-cost, high-throughput candidate biomarker for chondrocyte quality control ahead of reimplantation, directly addressing the fibrocartilaginous-fill failure mode of ACI.

Second, the sensitivity of Geff and σcyto to medium conductivity (especially at 150 mS/m) points to changing K⁺/Na⁺ transmembrane transport—consistent with the known role of K⁺ and Ca²⁺ channels in chondrocyte signalling, proliferation, and cartilage-specific gene expression—as the physical basis of the electrical drift, linking the electrome to the chondrocyte channelome.

Third, the staged timing (chondrocytic phenotype lasting to ~day 38 in bovine cells) occurred later than the collagen I/II ratio switch reported around days 21–28 in human chondrocytes, plausibly reflecting species differences; combining DEP with microscopy, Western blotting, and genetic/epigenetic methods would give a fuller picture of the transformation.

Limitations include cell radii that imply larger volumes than in situ chondrocyte studies (edge-detection difficulty in 2D images), reliance on derived rather than directly patch-clamped Vm, and the fact that routine chondrocyte replacement for cartilage regeneration remains preclinical. Nonetheless, DEP is positioned as a promising future tool for assessing chondrocyte dedifferentiation in research and clinical settings.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
