---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Single-cell analysis of lizard blastema fibroblasts reveals phagocyte-dependent activation of Hedgehog-responsive chondrogenesis

## Citation (NLM)
Vonk AC, Zhao X, Pan Z, Hudnall ML, Oakes CG, Lopez GA, Hasel-Kolossa SC, Kuncz AWC, Sengelmann SB, Gamble DJ, Lozito TP. Single-cell analysis of lizard blastema fibroblasts reveals phagocyte-dependent activation of Hedgehog-responsive chondrogenesis. Nat Commun. 2023;14:4489. doi:10.1038/s41467-023-40206-z

**DOI:** [https://doi.org/10.1038/s41467-023-40206-z](https://doi.org/10.1038/s41467-023-40206-z)

---

## Background

Appendage regeneration remains an unmet goal in mammalian regenerative medicine, where injury usually resolves into fibrosis and scarring rather than tissue replacement. Non-mammalian vertebrates offer clues to the molecular pathways enabling a regenerative outcome. Lizards are amniotes more closely related to humans than the commonly studied axolotl, and they retain lifelong epimorphic tail regeneration together with a more complex, mammal-like adaptive immune system. Uniquely, the regenerated lizard tail skeleton is not an ossified vertebral column but a single cartilage tube surrounding the regenerated spinal cord.

The cell types and gene signatures underlying lizard blastema formation and its large-scale chondrogenesis were largely unknown. This study uses single-cell RNA sequencing of the green anole lizard (Anolis carolinensis) tail regeneration time course to characterize the fibroblastic connective tissue cells (FCTCs) and phagocytes that drive blastema formation and cartilage formation, building on prior work implicating ependyma-derived Hedgehog (Hh) signaling as the critical cue for blastema cartilage.

---

## Key Experiment Methods

1. 10x Genomics scRNA-seq of staged A. carolinensis tail samples (0 DPA original tail; inflammatory 1/3/7 DPA; blastema 14/21 DPA; regenerated homeostasis 28 DPA), analyzed with Cell Ranger, Seurat, and Harmony.
2. Subclustering and Monocle2 pseudotime trajectory analysis of the integrated FCTC/chondrocyte populations.
3. RNAscope in situ hybridization / FISH and histology to validate cluster markers and map spatiotemporal expression (col3a1, pltp, sall1, sox9, spp1, sulf1, col2a1, shh, fabp7, gli1) across regeneration stages.
4. Pharmacological Hedgehog manipulation: Hh inhibitor cyclopamine, smoothened agonist (SAG), and vehicle for 28 days, with RT-PCR confirmation.
5. Fluorescent DiI/DiO-labeled FCTC transplantation assays in the parthenogenetic lizard Lepidodactylus lugubris (clonal, no immunosuppression) to test in vivo chondrogenic competence of original-, blastema-, and regenerated-tail and limb fibroblasts.
6. Phagocyte depletion and pericytic phagocyte-conditioned media rescue experiments in tail and amputated limb.

---

## Results

- Unsupervised clustering of the tail regeneration time course yielded 14 cell clusters, including ctsb+ macrophages, immune/blood cells, krt5+ epithelial, vwf+ endothelial, fabp7+ ependymal, sox9+ chondrocyte, and col1a1+ FCTC populations; FCTCs expanded markedly at the blastema stage, closely associated with chondrocytes.
- Pseudotime placed spp1+ blastema-stage fibroblasts early; a subset gains sulf1 expression and progresses toward sox9+ chondrocytes forming col2a1+ cartilage in regenerated homeostasis.
- FCTC markers activated in a spatiotemporal pattern: col3a1 marked homeostatic FCTCs at all stages; spp1, col12a1, mdk, sparc, tnl, cdh11 activated in injury-state FCTCs by 7 DPA; sulf1, pltp, sall1, sox9 labeled condensing chondrogenic mesenchyme around the regenerated spinal cord at 14 DPA.
- Hh signaling was necessary and sufficient for blastema chondrogenesis: cyclopamine abolished cartilage (with intact ependymal shh), SAG produced stunted tails with ectopic col2a1+ cartilage. Ependymal fabp7+ shh expression was unaffected by drugs.
- sulf1 was the only blastema marker responsive to Hh (reduced by cyclopamine, expanded by SAG); spp1 marked general injury-state FCTCs. Amputated limb fibroblasts expressed spp1 but lacked sulf1 and did not form cartilage even with SAG-driven gli1 activation, distinguishing tail-blastema competence from limb wound-healing responses.
- Transplantation showed blastema-derived FCTCs (but not original or regenerated tail fibroblasts) incorporated into Col2+ cartilage; both tail and limb fibroblasts could gain sulf1 and chondrogenic competence when exposed to the blastema niche.
- Phagocyte depletion blocked blastema formation, while pericytic phagocyte-conditioned media rescued blastema chondrogenesis and induced cartilage in amputated limbs, supporting a phagocyte-induced hierarchy of fibroblast gene activation culminating in sulf1+ pro-chondrogenic cells.

---

## Perspective

The study defines a phagocyte-to-fibroblast signaling hierarchy in which spp1+ injury-activated FCTCs give rise to a sulf1+, Hedgehog-responsive, pro-chondrogenic population that is the source of the regenerated lizard tail cartilage tube surrounding the spinal cord. By contrasting tail blastema with non-regenerating limb fibroblasts, it isolates blastema-specific competence from generic wound healing and identifies sulf1 and phagocyte-derived signals as actionable targets for inducing regeneration in less-regenerative species. Limitations include reliance on pharmacological Hh modulation and conditioned media rather than defined molecular effectors, and the pseudotime/correlative nature of the lineage inferences. As an amniote model with mammal-like immunity and central spinal-cord-associated cartilage regeneration, the lizard offers a translationally relevant bridge for CNS-adjacent appendage regeneration research.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
