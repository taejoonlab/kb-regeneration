---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
---

# Specialized signaling centers direct cell fate and spatial organization in a mesodermal organoid model

## Citation (NLM)
Skoufa E, Zhong J, Hu K, Kahre O, Tsissios G, Carrau L, Herrera A, Dominguez Mantes A, Leleu M, Castilla-Ibeas A, Jang H, Weigert M, La Manno G, Lutolf M, Ros M, Aztekin C. Specialized signaling centers direct cell fate and spatial organization in a mesodermal organoid model. Sci Adv. 2025;11(48):eady7682. doi:10.1126/sciadv.ady7682

**DOI:** [https://doi.org/10.1126/sciadv.ady7682](https://doi.org/10.1126/sciadv.ady7682)

---

## Background

Specialized signaling centers are unique cell populations defined by their morphogen secretion capabilities that transiently form to orchestrate morphogenesis during both development and regeneration. In vertebrate limbs, surface ectoderm cells differentiate into the apical-ectodermal ridge (AER), which simultaneously establishes multiple morphogen gradients (FGFs, BMPs, WNTs, TGFBs, DELTAs) that influence the growth and differentiation of the underlying multipotent limb bud mesoderm. Mesodermal cells leaving the AER gradient zone are thought to differentiate into chondrocytes and fibroblasts, while non-AER surface ectoderm signals are suggested to suppress chondrocyte differentiation.

Studying these intricate cell-cell interactions in vivo is severely restricted to tissue- or gene-level examinations, and prior simplified limb models focused almost exclusively on the mesoderm, lacking a tractable model of the AER-containing ectoderm. To overcome this, the authors developed a highly efficient mouse embryonic stem cell (mESC)–based 3D organoid model—termed "budoids"—comprising cells with AER, surface ectoderm, and mesoderm properties, enabling large-scale, quantitative dissection of signaling center–mesoderm interactions during limb morphogenesis and regeneration.

---

## Key Experiment Methods

1. **Directed mESC differentiation**: A published protocol (SB431542 + BMP4) induced surface ectoderm–like precursors; subsequent BMP4 + FGF10 + Wnt agonist Chiron ("BFC") treatment induced AER-like cells, generating heterogeneous 2D cultures.
2. **Reporter lines**: Fgf8:tdTomato knockin reporter and Prrx1-enhancer:mVenus (limb bud mesoderm) reporter mESC lines; a constitutive CAG:mVenus line for cell tracing.
3. **Time-course scRNA-seq** (days 0, 3, 5, 7) with clustering-based cell type annotation; comparison/projection against published in vivo E9.5–E12.5 mouse limb datasets.
4. **3D budoid generation**: Dissociation and aggregation in U-bottom low-attachment plates; brief FGF8b + WNT3A treatment to promote symmetry breaking and elongation.
5. **In vivo validation**: Dissociation of E12.5 mouse forelimb/hindlimb distal and proximal samples subjected to the same protocol.
6. **BMP pathway perturbation**: NOGGIN or LDN193189 (inhibition) vs. recombinant BMP4 (activation) to test chondrogenesis dependence.
7. **FACS-based cell enrichment**: EpCAM/CD9 sorting to isolate mesoderm (EpCAM-neg), surface ectoderm–like (EpCAM-high/CD9-high), and AER-like (EpCAM-high/CD9-low) populations.
8. **Recombinant budoids**: 1:1 combinations of sorted mesoderm with AER-like, surface ectoderm–like, or mesoderm cells.
9. **Immunostaining/confocal** (TP63, TFAP2C, SOX9, TWIST1, E-cadherin) and **HybISS** hybridization-based spatial in situ sequencing of 131 limb development genes at single-cell resolution.

---

## Results

- The BFC protocol produced heterogeneous day-7 cultures dominated by cells with AER (Sp6/Sp8/Fgf8/Bmp4/Wnt5a/Trp63), surface ectoderm (Krt8/Wnt3/Wnt6), and early lateral plate / limb bud mesoderm (Hand1/Hand2/Prrx1) identities. AER-like cells resembled in vivo E9.5 AER most closely and were largely mitotically quiescent (G1 phase), consistent with the known AER.
- Cells self-organized into 3D "domes" in 2D, with TP63+ cells covering outer layers, AER-like cells at the tip/outer bottom, and Prrx1enh+ mesodermal cells in the core.
- Free-floating aggregates broke symmetry and elongated only ~5% of the time, but brief FGF8b + WNT3A treatment raised symmetry-breaking efficiency to ~80% ("budoids"). Primary E12.5 limb cells (especially hindlimb distal) underwent similar morphogenesis.
- scRNA-seq showed budoids enrich for mesodermal cells with multipotent limb bud markers (Msx1, Grem1, Fgf10), sequential Hox cluster activation, and emergence of chondrocyte (Sox9, Col2a1) and fibroblast/tenocyte/pericyte populations. A polarized SOX9+ domain emerged after symmetry breaking.
- **Symmetry breaking is chondrogenesis-driven and BMP-dependent**: NOGGIN/LDN193189 impaired elongation and reduced SOX9+ cells, whereas BMP4 elongated nearly all organoids and made them entirely SOX9+.
- Mesoderm-enriched cells alone could break symmetry and elongate upon brief FGF8b; AER-like or surface ectoderm–like cells alone could not.
- **Recombinant budoids**: Even a transient, small number of AER-like cells polarized to one end. AER-like recombinants underwent robust symmetry breaking/elongation, whereas surface ectoderm recombinants remained circular (consistent with ectoderm counteracting chondrogenesis). AER-like and SOX9+ cells localized to opposite poles—suggesting local suppression of chondrogenesis while permitting it at a distance.
- **Spatial sequencing (HybISS)** revealed two polarized domains: a proximal chondrogenic domain (Sox9, Col2a1, Col9a1/2) and a distal domain enriched for limb bud mesoderm/fibroblast markers (Prrx1, Msx1, Twist1, Lum, Col1a1, Col3a1) and high signaling activity (Bmp4/7, Wnt5a/6, Rspo2/3, Axin2, Fgf7, Spry2/4). PCA showed AER-like cells increased inter-domain polarization.

---

## Perspective

This work provides a scalable, embedding-free (no Matrigel), and reproducible platform to dissect epithelial signaling center–mesoderm interactions that are difficult to study in vivo. The central finding is that AER-like signaling center cells act non-cell-autonomously: they sustain nearby limb bud mesoderm and fibroblast identities while locally suppressing chondrogenesis, yet permit and even promote spatially distant cartilage formation by enhancing tissue polarization. This quantitatively extends earlier tissue- and gene-level models by showing that signaling-center influence reaches spatially distant populations to shape overall tissue organization.

Because signaling centers orchestrate both development and regeneration (e.g., limb/appendage regeneration), the budoid system is relevant to regenerative biology as a tractable model for studying morphogen-gradient control of cell fate and pattern. Its throughput (thousands of budoids per experiment) supports statistical robustness and combinatorial perturbations impractical in embryos.

Limitations acknowledged by the authors: ectodermal cells are underrepresented and poorly maintained in 3D (requiring optimization); budoid cell types show a mixed developmental-stage profile partly attributable to annotation inconsistencies and single-cell capture biases; Hox activation appears only in 3D for unclear reasons; and budoids are explicitly not equivalent to limb buds but simplified models recapitulating specific aspects (mesoderm-to-cartilage differentiation, AER-mediated signaling). In vivo studies remain the gold standard for limb morphogenesis.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
