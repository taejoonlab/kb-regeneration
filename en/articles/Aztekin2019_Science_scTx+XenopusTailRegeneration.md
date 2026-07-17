---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Identification of a regeneration-organizing cell in the Xenopus tail

## Citation (NLM)
Aztekin C, Hiscock TW, Marioni JC, Gurdon JB, Simons BD, Jullien J. Identification of a regeneration-organizing cell in the Xenopus tail. Science. 2019;364(6441):653-658. doi:10.1126/science.aav9996

**DOI:** [https://doi.org/10.1126/science.aav9996](https://doi.org/10.1126/science.aav9996)

---

## Background
Unlike mammals, *Xenopus laevis* tadpoles have a high regenerative potential and can regrow an amputated tail. Appendage regeneration is broadly divided into three steps: formation of a specialized wound epidermis, blastema/regenerative-bud formation, and outgrowth via proliferation. The wound epidermis is a ligand-expressing structure essential for regeneration in many species (e.g., zebrafish, axolotl), yet it was unclear which cell types compose it, what its origin is, and which ligands it expresses.

*Xenopus* tadpoles are an ideal comparative model because they have naturally occurring regeneration-competent and regeneration-incompetent developmental stages. The authors used single-cell RNA sequencing (scRNA-seq) to comprehensively profile the regenerating tail and identify essential regulators of regeneration.

---

## Key Experiment Methods
1. **scRNA-seq atlas** (10X Genomics, >13,000 cells) of *Xenopus laevis* tails from regeneration-competent (NF stage 40-41) and -incompetent (NF stage 46-47) tadpoles, sampling intact tails and 1-3 days post-amputation (dpa), with ≥2 biological replicates per condition.
2. **Dimensionality reduction and clustering** using UMAP and graph-based walktrap clustering; cluster identities assigned from known marker genes (46 putative cell types).
3. **Differential abundance analysis** (edgeR/cydar approach) comparing regeneration-competent vs. -incompetent conditions to find regeneration-specific cell-type changes.
4. **Localization** of candidate cells via published Xenbase in situ data plus a Lef1 reporter line (pbin7Lef:GFP) combined with TP63 immunolabeling.
5. **Genetic ablation** using nitroreductase/metronidazole (NTR/MTZ) with a Krt.L promoter driving NTR in F0 transgenic tadpoles; plus manual surgical removal of posterior-trunk cells.
6. **Live imaging** of Lef1-reporter cells; **chemical perturbations** (DPI for ROS, SB-505124 for TGFβ, SU5402 for FGF) to assess cell mobilization.
7. **Transplantation/grafting** of posterior tail-bud tissues ("large" and "small" grafts) to host trunk to test induction of ectopic outgrowths; scGSEA of ligand/receptor pairs.

---

## Results
- The scRNA-seq atlas revealed 46 putative cell types spanning immune, skin, nervous system, and somite lineages. Progenitors were biased to G2/M and S phases; terminally differentiated cells were in G1.
- Comparisons distinguished developmental, amputation-specific, and regeneration-specific changes. An amputation response (shared by competent and incompetent tadpoles) included a motor-neuron-like cell type expressing spinal-cord-injury genes (Fgf10) and metabolic hormones (Leptin).
- The most significant regeneration-specific change was a previously unidentified epidermal cell type, termed the **regeneration-organizing cell (ROC)**. ROCs express regeneration-supporting genes (Wnt5a, Fgf10, Fgf20, Msx1, Bmpr1a) and were identified as LEF1+/TP63+ cells localized to the midline edge of the epidermis.
- After amputation, ROCs are removed from the amputation plane but remain in the posterior trunk; in competent tadpoles they **relocalize/mobilize** to the amputation plane within 24 h to form the specialized wound epidermis, whereas they remain absent in incompetent tadpoles.
- **Genetic (NTR/MTZ) or manual ablation of ROCs blocked regeneration.** A critical time window exists during which posterior-trunk ROCs must relocate to initiate regeneration.
- ROS production and TGFβ pathway activity were required for ROC migration; FGF inhibition had no effect on migration.
- ROCs simultaneously express ligands of FGF, BMP, WNT, NOTCH, and TGFβ pathways, whereas progenitors express the corresponding receptors — indicating ROCs act as a **signaling center** promoting progenitor proliferation.
- ROCs transcriptionally resemble the limb apical ectodermal ridge (AER)/apical epithelial cap (AEC) (e.g., Sp8, Sp9, Msx2, Wnt5a). **Grafting ROC-containing tissue induced ectopic outgrowths** (tail-like from large grafts, fin-like from small grafts); ablating ROCs in donor grafts reduced outgrowth. Donor ROCs localized to the tip of ectopic structures.

---

## Perspective
This work provides a mechanistic, single-cell view of tail regeneration: a single cell type (the ROC) relocalizes to form the wound epidermis and acts as a signaling center that drives proliferation of underlying progenitors, without requiring a new multipotent progenitor state or transdifferentiation. The discovery reframes the wound epidermis as arising from mobilization of resident cells rather than a distinct post-amputation state.

Significance: identifying a discrete cell type defining the wound epidermis suggests "organizer grafts" as a concept for regenerative therapy. Limitations/future directions: whether a ROC-based mechanism is conserved in other species (neonatal mouse, salamander) remains to be tested; the classic AER regulators (Fgf2/4/8, Cx43) were not detected in ROCs, indicating the analogy is incomplete.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
