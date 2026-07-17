---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
---

# Fibroblast growth factor signaling induces a chondrocyte-like state of peripheral nerve fibroblast during aging

## Citation (NLM)
Stefanovska D, Sassu E, Tekman M, Naghsh Nilchi A, Haider S, Domisch C, Hossfeld M, Perez-Feliz S, Miarka L, Schneider-Warme F, Arnold SJ, Prinz M, Grüning B, Preissl S, Hortells L. Fibroblast growth factor signaling induces a chondrocyte-like state of peripheral nerve fibroblast during aging. Nat Commun. 2025;16:10020. doi:10.1038/s41467-025-65297-8

**DOI:** [https://doi.org/10.1038/s41467-025-65297-8](https://doi.org/10.1038/s41467-025-65297-8)

---

## Background
During aging, peripheral nerves undergo structural and cellular changes—including increased extracellular matrix (ECM) deposition—that reduce nerve conduction velocity and general function, impairing target organs (skeletal muscle, heart, intestine) and raising disease risk. The cellular and molecular mechanisms behind these age-induced alterations remain poorly understood. A recent report described increased deposition of chondral proteoglycans (e.g., CSPG4) in sciatic nerves of old mice, but how neural fibroblasts contribute to this ECM remodeling was unclear.

Fibroblast growth factor (FGF) signaling is implicated in age-related intramuscular fat deposition, fibrosis, and vascular calcification, and is known to induce chondrocyte differentiation, yet its role in peripheral nervous system (PNS) aging was unknown. SOX9, a chondrocyte marker, is present in endoneurial fibroblasts and in satellite glial cells during nerve repair, and plays roles in degenerative processes such as vascular calcification and cardiac fibrosis. This study uses single-nucleus RNA-sequencing (snRNA-seq) to map cell-state and composition dynamics in aging mouse sciatic nerves and to test whether FGF signaling drives a chondrocyte-like fibroblast state.

---

## Key Experiment Methods
1. snRNA-seq of mouse sciatic nerves at three ages (2–3, 15–16, 20–30 months); FACS-based nuclei isolation; clustering of 19,175 nuclei into 19 first-level clusters, with second-level re-clustering of macrophages, fibroblasts, and adipocytes.
2. Marker-based cluster annotation and re-analysis of a published young-mouse (P60) dataset to locate the chondrocyte-like fibroblast population.
3. Immunofluorescence and cell counting on mouse sciatic nerve sections (markers: CD45, CD68, MRC1, GRN, TGFβR1, SOX9, CSPG4, GLUT1, KCNC2, FABP4, FGF2, γH2AX, VIM) plus fluoromyelin labeling.
4. Schwann-cell lineage tracing using Sox10-CreERT2;R26tdTomato mice to assess senescence (γH2AX) in Schwann cells and mesenchymal (VIM+/SOX10−) cells.
5. Cell–cell interaction inference with CellChat and STRING protein-association analysis to nominate FGF signaling (adipocyte→fibroblast).
6. Pseudotime (Monocle) trajectory analysis with endo-/peri-/epineurial fibroblasts as origins and chondrocyte-like fibroblasts as endpoint.
7. In vitro assays on human perineurial fibroblasts (hPnFbs): early-passage (3–4) vs senescent (passage 8–9); treatment with FGF2, FGF1 (+heparin), and combinations for 14 days, plus FGF2 withdrawal for 7 days; readouts EdU, SOX9, FOXC2, CSPG4, γH2AX.
8. Validation in human peripheral nerve FFPE samples from young (17–33 y) vs older (55–68 y) donors.

---

## Results
- snRNA-seq identified 19 cell clusters in sciatic nerve, including a previously undescribed fibroblast population co-expressing chondrocyte-lineage markers Sox9, Foxc2, and Cspg4 with low perineurial-fibroblast marker Slc2a1/Glut1.
- Adipose-tissue cells and the chondrocyte-like state fibroblasts became more prevalent in nerves from mice older than 15 months; endo-/peri-/epineurial fibroblast relative numbers were unchanged.
- Macrophage phenotype shifted with age: resident steady-state (Cx3cr1, Mrc1) predominated in young mice, phagocytic macrophages (Cd44, C1qa, Grn) peaked at 15–16 months, and chronic-inflammation macrophages (Tgfβr1, Kynu) peaked at 20–30 months; protein-level counts confirmed these shifts and increased myelin phagocytosis with age.
- Gene ontology of chondrocyte-like fibroblasts showed enrichment for skin morphogenesis (Col1a1/Col1a2, pro-fibrotic) and chondrocyte development/differentiation (Sox9, Sox6, Sox5). SOX9+ cell density and CSPG4 area increased significantly at 20–30 months.
- Pseudotime and in vivo counting indicated perineurial fibroblasts (PnFbs, GLUT1+) as the most probable origin of the chondrocyte-like state, more so than epineurial (KCNC2+) fibroblasts.
- CellChat predicted increased adipocyte→(PnFbs/chondrocyte-like) interactions; Fgf2 was highly expressed in adipocytes (top scores Fgf2-Fgfr1/Fgfr2), and FGF2-secreting FABP4+ adipocyte density increased in aged nerves. CSPG4 can bind FGF2 directly, amplifying signaling.
- In vitro: FGF2 did NOT induce a chondrocyte-like state in early-passage hPnFbs (and appeared protective against DNA damage), but in senescent hPnFbs, 100 ng/ml FGF2 significantly increased SOX9+/FOXC2+ co-expression. The effect was reversible upon FGF2 withdrawal; CSPG4 levels were not increased by FGF2, implicating additional signals.
- High-dose FGF1 did not reproduce the FGF2 effect and blocked FGF2-induced activation (competitive inhibition on shared receptors proposed); low-dose FGF1 was insufficient to block it.
- Human nerves from older donors had significantly more FGF2+ and SOX9+/FGF2+ cells and lower nuclear density than young donors, supporting translational relevance.

---

## Perspective
This work provides the first snRNA-seq map of mouse sciatic nerve aging and defines an age-related, FGF2-driven chondrocyte-like state of perineurial fibroblasts, alongside a phagocytic-to-chronic-inflammatory macrophage transition. Because CSPG4/chondroitin-sulfate proteoglycans are central to inhibitory scar biology in the nervous system, the identification of a neural fibroblast that deposits chondrogenic ECM upon FGF2 signaling is of broad relevance to nerve degeneration and repair. The finding that FGF1 antagonizes FGF2 suggests FGF1 as a potential anti-aging molecule for peripheral nerves. Limitations include that fluoromyelin/fluorescence microscopy may miss subtle myelination changes (electron microscopy needed), the human cohort included both mixed and pure sensory nerves and was small, and CSPG4 deposition was not induced by FGF2 in vitro—indicating other signals govern proteoglycan accumulation. Future work should test FGF2 effects on Schwann cells and nerve fibers and dissect the initial triggers of age-related nerve dysfunction.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
