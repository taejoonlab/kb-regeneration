---
tags: [2026-07, Fibroblast]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# Mechanoresponsive regulation of fibroblast-to-myofibroblast transition in three-dimensional tissue analogues: mechanical strain amplitude dependency of fibrosis

## Citation (NLM)

Jacho D, Rabino A, Garcia-Mata R, Yildirim-Ayan E. Mechanoresponsive regulation of fibroblast-to-myofibroblast transition in three-dimensional tissue analogues: mechanical strain amplitude dependency of fibrosis. Sci Rep. 2022;12(1):16832. doi:10.1038/s41598-022-20383-5

**DOI:** [https://doi.org/10.1038/s41598-022-20383-5](https://doi.org/10.1038/s41598-022-20383-5)

---

## Background

Musculoskeletal tissue injuries account for 65% of occupational injuries in the US, and repair can follow either a regenerative path or a fibrosis/fibroplasia path in which cells continuously secrete fibrogenic cytokines and deposit excessive ECM that becomes permanent scar. The fibroblast-to-myofibroblast transition (FMT) is the key cellular mediator of fibrotic tissue formation during healing. Prior mechanobiology relied on 2D fibroblast-monolayer strain models, which fail to reproduce the interstitial ECM feedback, cell shape, and 3D adhesion fields cells experience in vivo, or on floated collagen-lattice and stiffness-varying 3D models that ignore the extracellular mechanical loading actually exerted on tissue. Yet in the clinic, mechanical loading and pressure therapy are recognized modulators of fibrotic tissue formation. This study asked how the *amplitude* of mechanical strain applied to a fibroblast-laden 3D tissue analogue governs the shift from normal tissue repair to FMT, aiming to identify a strain amplitude that promotes regeneration without triggering myofibroblast differentiation.

---

## Key Experiment Methods

**1. Fibroblast-laden 3D tissue analogue fabrication**
- Composite biomaterial of neutralized type-I collagen (4 mg/mL) admixed with functionalized human soluble elastin (0.4 mg/mL)
- Human dermal fibroblasts (ATCC HFF1) encapsulated at 10⁶ cells/mL; polymerized in a mechanical-loading chamber

**2. Uniaxial mechanical loading regime**
- Applied uniaxial tensile strain of 0% (control), 4%, 8%, and 12% at 0.1 Hz using a custom-built Uniaxial Strain Bioreactor
- 2 h/day over a 7-day culture period; strains chosen to mimic physiological (5–9%) to high-intensity (12%) musculoskeletal tissue loading (tendon, ligament, muscle)

**3. Cellularity and morphology assessment**
- Calcein-AM / ethidium homodimer-1 Live-Dead assay, confocal imaging, cell counts extrapolated per mL
- Cell elongation index (EI, long/short axis) from F-actin (phalloidin) 3D renderings; EI = 1 spheroidal, EI ≥ 2 elongated

**4. Matrix remodeling analysis**
- SEM for fibrous protein density and collagen/elastin fiber alignment; % porosity via Fiji/ImageJ
- Directionality histograms; H&E histology for matrix thickness

**5. Molecular and myofibroblast markers**
- RT-qPCR (ΔΔCt, GAPDH normalizer) for early mechanoresponsive c-jun, ECM markers (collagen I, collagen IV, fibronectin, elastin), MMP1/2/3, activation stressors (TGF-β1, TGF-βR1), profibrotic markers (CD206, CCL18, TRPV4), and α-SMA
- IHC and immunofluorescence for α-SMA and F-actin stress fibers on 0% vs 12% groups

---

## Results

**Hyper-mechanical strain increased cellularity**
Cell number rose with strain amplitude, most dramatically at 12%, where cells per mL nearly doubled (12 × 10⁶ ± 1.78) versus the 0, 4, and 8% groups, which did not differ significantly from each other. Viability remained ~85–92% across all groups, so the 12% increase reflected proliferation rather than survival. Cells in the 12% group became elongated with spindle-shaped cytoplasmic extensions and reoriented within the matrix, while other groups stayed rounded like the unloaded control.

**Hyper-mechanical strain reduced porosity and aligned the matrix**
SEM and histology showed denser de novo collagen fibers and increasing fiber diameter with strain; porosity fell from 84.5 ± 0.23% (control) to 57.4 ± 0.31% (12%), and matrix thickness/fiber content rose ~25% at 12%. Collagen and elastin fibers aligned parallel to the loading axis, with directionality increasing nearly threefold from 0.012 (0%) to 0.035 (12%). The cell elongation index increased significantly only in the 12% group, tracking the matrix alignment.

**Hyper-mechanical strain upregulated profibrotic gene expression**
The early mechanoresponsive gene c-jun rose ~sevenfold at 12%, confirming that the applied load was transduced to the cells, with no significant change at 4% or 8%. ECM markers increased with strain: at 12%, collagen IV ~4-fold, fibronectin ~7-fold, and collagen I ~13-fold (elastin peaked at 8%, ~3-fold). MMP1/2/3 rose ~3-, 6.5-, and 30-fold at 12%, indicating dysregulated matrix turnover. Activation stressors TGF-β1 (~2.5-fold) and TGF-βR1 (~10–11-fold) and profibrotic markers CD206 (~16-fold), CCL18 (~10-fold), and TRPV4 (~12-fold) were all significantly higher at 12% than at 4% or 8%.

**Hyper-mechanical strain induced full FMT; 4% is anabolic without myofibroblast differentiation**
The myofibroblast marker α-SMA increased ~1.7-fold at 8% and ~13-fold at 12%, with no α-SMA detected at 4%. α-SMA protein was present only in the 12% group by IHC, and F-actin stress-fiber intensity rose ~3.6-fold (≈25% by another quantification) at 12%, confirming incorporation into filaments rather than soluble monomer. Collectively, 4% strain produced an anabolic, regenerative response without initiating FMT, whereas ≥8–12% strain over-stimulated fibroblasts through a proto-myofibroblast state into fully differentiated α-SMA+ myofibroblasts and fibrotic matrix.

---

## Perspective

This study defines a dose–response relationship between mechanical strain amplitude and fibroblast fate in an ECM-realistic 3D tissue analogue, identifying a therapeutic window in which loading drives regeneration without fibrosis.

First, it establishes 4% uniaxial strain as an anabolic stimulus—increasing matrix synthesis and organization without α-SMA induction—while 8–12% strain crosses into pathological FMT. This amplitude threshold offers a concrete design parameter for mechanotherapy and rehabilitation protocols in musculoskeletal healing, where the goal is to load tissue enough to promote repair but not so much as to trigger scar.

Second, the coordinated upregulation of c-jun, TGF-β1/TGF-βR1, ECM proteins, MMPs, and profibrotic mediators (CD206, CCL18, TRPV4) culminating in α-SMA+ stress fibers provides a stepwise molecular map of strain-driven FMT, reinforcing TGF-β1 as the pivotal activation stressor and linking overload directly to fibroproliferative disease including keloid.

Third, for the vault's cartilage and connective-tissue regeneration themes, the model is directly relevant: the collagen/elastin analogue mimics tendon, ligament, and muscle loading, and the finding that excessive strain converts reparative fibroblasts into fibrotic myofibroblasts parallels the mechanical control of chondrocyte and tendon/ligament cell phenotype. The tunable strain platform could be adapted to optimize loading regimes for engineered cartilage or tendon constructs.

Limitations include the use of a single dermal fibroblast line, a fixed 0.1 Hz frequency and 7-day window, and the absence of longer or variable-frequency loading; the authors note that low strain (4/8%) may require longer stimulation to be transduced as efficiently as 12%.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
