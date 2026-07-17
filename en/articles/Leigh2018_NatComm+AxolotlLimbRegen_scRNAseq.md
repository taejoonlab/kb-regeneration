---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Transcriptomic landscape of the blastema niche in regenerating adult axolotl limbs at single-cell resolution

## Citation (NLM)
Leigh ND, Dunlap GS, Johnson K, Mariano R, Oshiro R, Wong AY, Bryant DM, Miller BM, Ratner A, Chen A, Ye WW, Haas BJ, Whited JL. Transcriptomic landscape of the blastema niche in regenerating adult axolotl limbs at single-cell resolution. Nat Commun. 2018;9(1):5153. doi:10.1038/s41467-018-07604-0

**DOI:** [https://doi.org/10.1038/s41467-018-07604-0](https://doi.org/10.1038/s41467-018-07604-0)

---

## Background

Salamanders such as the axolotl can regenerate entire multi-tissue structures (e.g., limbs) throughout life, in stark contrast to the very limited regenerative capacity of mammals. After amputation, the wound is rapidly covered by a specialized wound epidermis (WE), and underneath it progenitor cells aggregate to form the blastema — a mixture of lineage-restricted and multipotent progenitors that rebuilds the internal structures of the limb. The WE, macrophages, and nerves are all required for regeneration, indicating a coordinated multi-cell-type effort.

Prior work relied largely on histology, grafting, and bulk RNA-sequencing, which yield composite measurements that can mask cell-type-specific transcripts. Here the authors apply unbiased single-cell RNA-sequencing to over 25,000 cells from homeostatic and regenerating adult axolotl limbs to define the molecular identities of the cell populations present, identify regeneration-induced genes, and reconstruct putative differentiation trajectories for blastema cells.

---

## Key Experiment Methods

1. Single-cell RNA-seq (inDrops microfluidic platform) on >25,000 cells from 13 homeostatic and regenerating adult axolotl forelimb samples (13 animals), sampling four states: homeostasis, wound healing, early-bud blastema, and medium-bud blastema.
2. Dimensionality reduction and unbiased clustering with the Seurat toolkit; visualization by t-SNE (11–19 distinct populations per time point).
3. Pseudotime trajectory analysis of epidermal populations using Monocle to test an outward differentiation model.
4. URD algorithm to reconstruct blastema-resident cell differentiation trajectories across the three regenerating time points.
5. RNA in situ hybridization validation of marker/regeneration-specific genes (e.g., krt12, otog, frem2, krt17, trac, apoeb, lum, dpt) and α-naphthyl acetate (NSE) staining for myeloid cells.

---

## Results

- Recovered a broad diversity of cell types: fibroblast-like blastema (FLB) cells, tenocytes, Pax7+ myogenic blastema cells, endothelial cells, erythrocytes, myeloid and lymphoid cells, and a heterogeneous epidermis; nearly all populations were present at both homeostasis and regeneration.
- The epidermis is heterogeneous, including putative ionocytes (foxi1, atp6v1b1), Langerhans cells (hla-drb1), basal epidermis (col17a1), proliferating cells (pcna), intermediate epidermis (krt12), small secretory cells (otog, fcgbp), and a wound-healing–specific Leydig-like population (chs1, agr2a).
- Pseudotime analysis showed both homeostatic epidermis and WE follow an outward differentiation trajectory rooted at the basal epidermis/WE, which serves as a progenitor reservoir; krt17 was differentially expressed over pseudotime and validated in situ.
- Both adaptive (trac+ T cells, igll5+ B cells) and innate immune cells (mpeg1/marco+ myeloid cells, dendritic cells, neutrophils, recruited macrophages) were present throughout regeneration; trac+ T cells were localized within the blastema, and myeloid cells (apoeb+) peaked during wound healing.
- Identified nerve-associated and vascular cells: Schwann cells (mpz; acquiring sox2 and neural-crest foxd3 in medium-bud blastema), pericytes (cygb, abcc9; delayed arrival), and endothelial cells (pecam1).
- Defined blastema cell identity: myogenic blastema cells (pax7, myf5, with six1/eya1 as more consistent markers) and FLB cells expressing lum, dpt, postn. URD trajectories suggested synovial fibroblast, joint-like, and cartilage fates share a common distal undifferentiated FLB progenitor, while osteoblast-like fibroblasts, pericytes, endothelial, Schwann, and myogenic cells followed distinct trajectories; FAPs appeared as an intermediate state.

---

## Perspective

This study provides a foundational single-cell molecular resource that defines the cellular composition of the homeostatic and regenerating axolotl limb, supplying markers for populations (basal WE, macrophages, FLB cells, Pax7+ satellite cells) that were previously known functionally but poorly characterized molecularly. It establishes a putative framework for adult axolotl limb regeneration and enables future molecular dissection of individual populations' contributions.

Relevance to spinal cord/regeneration: the work is a comparative-regeneration atlas in a premier model organism, and the authors explicitly note that regulatory T cells have been shown to be required for zebrafish spinal cord, heart, and retina regeneration — linking blastema immune populations to CNS regeneration questions.

Limitations acknowledged by the authors include the inability to capture nerve cell bodies (only axons project into the limb, so nrg1/nerve signals are underrepresented), the low read coverage of microfluidic scRNA-seq that can miss lowly expressed transcription factors (e.g., pax7), and the fact that trajectories are computational predictions requiring lineage-tracing confirmation. Whether the blastema T cells actually function in axolotl limb regeneration remains to be determined.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
