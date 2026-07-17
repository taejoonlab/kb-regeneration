---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Microglia-organized scar-free spinal cord repair in neonatal mice

## Citation (NLM)
Li Y, He X, Kawaguchi R, Zhang Y, Wang Q, Monavarfeshani A, Yang Z, Chen B, Shi Z, Meng H, Zhou S, Zhu J, Jacobi A, Swarup V, Popovich PG, Geschwind DH, He Z. Microglia-organized scar-free spinal cord repair in neonatal mice. Nature. 2020;587(7835):613-618. doi:10.1038/s41586-020-2795-6

**DOI:** [https://doi.org/10.1038/s41586-020-2795-6](https://doi.org/10.1038/s41586-020-2795-6)

---

## Background
In adult mammals, spinal cord injury (SCI) triggers the formation of a scar composed of several cell types (reactive astrocytes, fibroblasts, microglia and macrophages) with little or no spontaneous regeneration of axons across the lesion. By contrast, fish and amphibians form permissive glial/meningeal bridges that allow injured axons to regenerate. How the mammalian spinal cord organizes its injury response, and the role of reactive glia in regeneration failure, remains poorly understood, in part because adult neurons also have diminished intrinsic growth capacity.

To disentangle these factors, the authors asked whether spinal cord regeneration can occur in neonatal mice, a developmental stage at which CNS neurons still retain a strong capacity for growth. They found that a crush injury to the neonatal (postnatal day 2, P2) spinal cord heals without a scar and permits long projecting axons to grow through the lesion, and they set out to define the cellular and molecular basis of this repair — identifying microglia as the central orchestrator.

---

## Key Experiment Methods
1. **Age-dependent crush injury model:** Complete T10 spinal cord crush (2 s with 0.1-mm forceps) in wild-type C57BL/6 mice at P2, P7, P20 and adult stages, comparing axon regrowth and lesion characteristics.
2. **Axon tracing and quantification:** Immunostaining for serotonergic (5-HT) axons and AAV-ChR2-mCherry labeling of corticospinal tract (CST) axons, with sagittal-section axon density quantification relative to distance from the lesion epicenter.
3. **Lesion characterization by immunohistochemistry:** Staining for CD68, GFAP, P2Y12, fibronectin, collagen I, CSPG, laminin, CD31 (vasculature) and SPP1 to compare scar formation and ECM deposition between P2 and adult lesions and across time points (1-14 dpi).
4. **Microglia lineage/state tracking:** Cx3cr1-GFP reporter mice and CCR2-RFP reporter mice to follow microglia activation/morphology and monocyte-derived macrophage infiltration.
5. **Microglia depletion:** Pharmacological depletion with the CSF1R inhibitor PLX3397 (in-chow plus subcutaneous dosing for neonates) and genetic depletion via Cx3cr1cre;Csf1rfl/fl mice (~70% microglia loss).
6. **Single-cell RNA sequencing (scRNA-seq):** FACS-sorted CD11b+CD45low cells from lesion tissue at 0, 3 and 5 dpi, 10X Genomics profiling, Seurat clustering with cell-cycle regression, GO enrichment, and RNA in situ hybridization (HCR) for Fn1, Ms4a7, Thbs1 and P2ry12.
7. **Cell-type-specific fibronectin deletion:** Fn1fl/fl crossed with Cx3cr1cre (microglia), Albcre (liver) and Tie2cre (endothelial) drivers to identify the source of bridge fibronectin.
8. **Microglia transplantation into adult lesions:** Transplantation of neonatal (P1) microglia, or adult microglia pretreated with proteinase inhibitors (E64, a cysteine peptidase inhibitor, plus serpinA3N, a serine protease inhibitor), into adult SCI sites.
9. **Bulk RNA-seq** of adult microglia at 0, 3 and 5 dpi for comparison with neonatal microglia gene expression.

---

## Results
- **Age-dependent axon growth:** After P2 injury, numerous serotonergic axons and CST axons grew across the lesion into distal/lumbar spinal cord; P7, P20 and adult injuries showed little or no axon regrowth.
- **Scar-free healing in neonates:** Two weeks after P2 injury, lesions showed minimal CD68+ cell accumulation and little ECM deposition (fibronectin, collagen I, CSPG, laminin), evenly distributed P2Y12+ homeostatic microglia, and continuous vasculature — unlike the typical scar (CD68+ core, fibroblasts, reactive astrocytes, basal lamina) seen in adult lesions.
- **Transient microglial activation:** After P2 injury, microglia accumulated in the stumps, converted from ramified to amoeboid morphology, transiently lost P2Y12 and expressed activation markers (SPP1, CD68) around 2-3 dpi, then reverted to a homeostatic (P2Y12+, SPP1-/CD68-) state by ~7 dpi. Blood-derived (CCR2-RFP+) macrophages appeared transiently and were cleared by 14 dpi, whereas in adults microglia remained persistently activated and macrophages persisted.
- **Fibronectin bridge formation:** A fibronectin+ bridge formed between severed stumps at 3 dpi (before GFAP+ astrocytes/collagen I+ fibroblasts entered) and resolved by 7 dpi as axons crossed.
- **Microglia are required:** PLX3397 depletion or Csf1r conditional knockout impaired bridge formation, produced a GFAP+ astroglial scar lacking vasculature at 14 dpi, and stalled most axons at the epicenter.
- **Repair-promoting microglial signature (scRNA-seq):** Five microglial states (MG0-MG4) were identified. Homeostatic MG0 dominated intact cord; MG1 and MG3 dominated at 3 dpi; MG2 (intermediate) and returning MG0 at 5 dpi. MG3 cells localized immediately in/around the lesion and uniquely expressed Ms4a7 and Thbs1 alongside Fn1, plus genes for ECM/wound healing, angiogenesis, phagocytosis, and negative regulation of immune responses and endopeptidases (peptidase inhibitors Cstb, Stfa1, Serpinb6a; anti-inflammatory Anxa1).
- **Adult contrast:** Adult microglia showed persistent Fn1 expression and no significant induction of proteinase inhibitors.
- **Microglia-derived fibronectin is essential:** Only Cx3cr1cre;Fn1fl/fl mice (not Albcre or Tie2cre) showed defective bridge formation at 3 dpi and reduced axon growth at 14 dpi.
- **Proteinase inhibitors improve adult repair:** Transplanted neonatal microglia, or proteinase-inhibitor-treated (E64 + serpinA3N) adult microglia, reduced immune-cell (Ly6G) infiltration, decreased collagen I/CSPG deposition, re-established P2Y12+ homeostatic microglia, and increased serotonergic axons crossing adult lesions. Untreated adult microglia remained CD68+ and corralled in the lesion. Axon regrowth with treated adult microglia was still lower than with neonatal microglia.

---

## Perspective
This work reveals that neonatal mice, like fish and amphibians, can undergo scar-free wound healing and spontaneous axon regrowth after spinal cord injury, and it identifies microglia as the primary coordinator of this reparative response. The key mechanism is temporal control of microglial activation: neonatal microglia transiently secrete fibronectin (and binding partners such as thrombospondin-1) to bridge the severed cord, and transiently express peptidase inhibitors and anti-inflammatory molecules that resolve inflammation and restore microglial homeostasis, whereas adult microglia remain chronically activated. This parallels CTGF biology in zebrafish, where transient expression promotes bridging but persistent expression drives fibrotic scarring.

Therapeutically, transplanting neonatal microglia or proteinase-inhibitor-treated adult microglia into adult lesions improved healing and axon regrowth, suggesting that re-establishing homeostatic microglia is a viable strategy to promote repair in the adult mammalian nervous system. Limitations include that it remains unclear whether the crossing axons are truly regenerating or uninjured/late-arriving, the contribution of descending versus intraspinal reorganization to functional recovery is unknown, and axon regrowth with treated adult microglia remained below that achieved with neonatal microglia, implying additional unidentified factors. Future work should identify further components that restore homeostatic microglia and explore proteinase inhibitors and other neonatal-microglia-specific molecules in the context of chronically activated microglia and neurodegeneration.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
