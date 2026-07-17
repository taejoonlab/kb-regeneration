---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# Microglia coordinate cellular interactions during spinal cord repair in mice

## Citation (NLM)
Brennan FH, Li Y, Wang C, Ma A, Guo Q, Li Y, Pukos N, Campbell WA, Witcher KG, Guan Z, Kigerl KA, Hall JCE, Godbout JP, Fischer AJ, McTigue DM, He Z, Ma Q, Popovich PG. Microglia coordinate cellular interactions during spinal cord repair in mice. Nat Commun. 2022;13:4096. doi:10.1038/s41467-022-31797-0

**DOI:** [https://doi.org/10.1038/s41467-022-31797-0](https://doi.org/10.1038/s41467-022-31797-0)

---

## Background

Traumatic spinal cord injury (SCI) triggers a neuroinflammatory response dominated by CNS-resident microglia and infiltrating monocyte-derived macrophages (MDMs). Because activated microglia and MDMs are morphologically similar and express overlapping phenotypic markers in vivo, it has historically been difficult to assign distinct injury responses to microglia specifically. Microglia comprise roughly 10% of CNS cells and continuously interact with neuronal and non-neuronal cells to maintain homeostasis.

This study exploits microglia-specific depletion (CSF1R antagonist PLX5622) combined with anatomical, histopathological, tract-tracing, bulk RNA-seq, and single-cell RNA-seq approaches to define the cellular and molecular responses to SCI that are coordinated by microglia, using three different mouse SCI models.

---

## Key Experiment Methods

1. Pharmacological microglia depletion by feeding PLX5622 (CSF1R antagonist) chow starting two weeks before a 75 kdyne T9 contusion SCI and continuing to 35 days post-injury (dpi); ~99% depletion confirmed.
2. Functional recovery assessment: Basso Mouse Scale (BMS) scores and subscores, and horizontal ladder test.
3. Histopathology / immunostaining: myelin (eriochrome cyanine, MBP), neurofilament/axons, GFAP (astroglial border), P2RY12 (microglia) vs F4/80/CD68 (MDMs), BrdU proliferation, Oil Red O (lipid); lesion volume/length reconstructions.
4. Replication in more severe models: complete forceps crush injuries at T9 and L1.
5. Bulk RNA sequencing of sham and injured cords (vehicle vs PLX5622) at 7 dpi; pathway analysis with WebGestalt and Reactome; gene network analysis (GeneMANIA).
6. Rescue experiment: intraspinal and intraperitoneal injection of recombinant CCL2 (rCCL2) + TLR2 agonist (PAM3CSK4) at 2-3 dpi to restore microglia-dependent signaling.
7. Single-cell RNA sequencing (scRNA-seq) of 21,016 cells from sham, 7 dpi, and 28 dpi cords; UMAP clustering, Monocle 3 pseudotime, and CellChat ligand-receptor communication analysis.

---

## Results

- Microglia are required for optimal recovery: depletion worsened locomotor recovery (only 2/7 PLX mice achieved consistent plantar stepping by 35 dpi vs 100% controls), increased ladder-test errors, and exacerbated myelin and axon pathology, lesion volume, and lesion length.
- Without microglia, MDMs formed large ectopic "foamy" clusters that migrated into spared white matter, and the delimiting astroglial (GFAP+) border was attenuated with reduced astrocyte and NG2 cell proliferation. Phenotype reproduced in T9 and L1 crush models.
- Bulk RNA-seq: the main effect of SCI was increased gene expression; the main effect of microglia depletion was decreased expression. ~51% of the top SCI-induced genes failed to increase without microglia. Microglia-dependent genes control phagocytosis, cytokine production/response, endocytosis, and protein secretion; a core network of 31 genes was identified, with Tlr2 (central node) and Ccl2 (edge node) as key hubs.
- Rescue: injecting rCCL2 + TLR2 agonist into microglia-depleted cords restored lipid phagocytosis, glial scarring, MDM corralling, and improved recovery; the same treatment in microglia-intact mice worsened outcomes.
- scRNA-seq resolved 14 cell types and 11 microglia subsets (homeostatic, proliferating, lipid processing, iron processing, interferon, antigen processing, etc.); homeostatic microglia are replaced by proliferating and lipid-processing subsets after SCI. Consistently increased genes included Apoe, Spp1, Fth1.
- MDMs formed 10 subsets; microglia control MDM recruitment and functional phenotype. Without microglia, MDMs skewed toward lipid-binding/matrix-remodeling states and were poised for unchecked matrix degradation.
- Astrocytes formed 3 subsets (Transporter, Metabolism, Inflammation); the SCI-induced Inflammation astrocyte state was microglia-dependent, and 55% of SCI-increased astrocyte genes failed to increase without microglia.
- CellChat identified microglia-dependent signaling axes: microglial Psap–astrocyte Gpr37l1 (glioprotective), microglial Spp1 (osteopontin) to MDM Cd44/integrins at 7 dpi, and Csf1r-Csf1 at 28 dpi.

---

## Perspective

The study provides a comprehensive, multi-omic demonstration that microglia are indispensable orchestrators of the reparative response after SCI, coordinating MDM recruitment/phenotype, astroglial border formation, lipid handling, and vascular repair. Mechanistically it pinpoints a CCL2/TLR2 "core" signaling signature that can be therapeutically co-opted to rescue recovery in microglia-depleted cords, while cautioning that the same intervention is deleterious when microglia are present, underscoring a tightly balanced, context-dependent signaling network.

Limitations include reliance on pharmacological depletion (potential off-target/systemic effects, though controls argue against major confounds), capture bias enriching microglia/MDMs in scRNA-seq, and the mouse-only setting. Future directions include translating select ligand-receptor axes into timed, cell-targeted therapies and testing whether restoring microglia-dependent signaling generalizes to other CNS injuries and neurological diseases.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
