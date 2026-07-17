---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Cellular senescence promotes progenitor cell expansion during axolotl limb regeneration

## Citation (NLM)
Yu Q, Walters HE, Pasquini G, Singh SP, Lachnit M, Oliveira CR, León-Periñán D, Petzold A, Kesavan P, Subiran Adrados C, Garteizgogeascoa I, Knapp D, Wagner A, Bernardos A, Alfonso M, Nadar G, Graf AM, Troyanovskiy KE, Dahl A, Busskamp V, Martínez-Máñez R, Yun MH. Cellular senescence promotes progenitor cell expansion during axolotl limb regeneration. Dev Cell. 2023;58(22):2416-2427. doi:10.1016/j.devcel.2023.09.009

**DOI:** [https://doi.org/10.1016/j.devcel.2023.09.009](https://doi.org/10.1016/j.devcel.2023.09.009)

---

## Background

Regeneration is widespread across the animal kingdom, and urodele amphibians such as the axolotl (Ambystoma mexicanum) are exceptional, regrowing limbs, spinal cord, ocular tissues, and portions of heart and brain. Limb regeneration proceeds through the blastema, a mass of mesenchymal progenitor cells that accumulates at the amputation stump and then expands, differentiates, and patterns to restore the limb. Prior work by this group showed that limb regeneration is accompanied by transient induction of cellular senescence within a subset of blastemal and surrounding cells — the blastemal senescent cell (bSC) population — which is later cleared by macrophages.

Cellular senescence is a state of permanent growth arrest with a characteristic senescence-associated secretory phenotype (SASP), and it has been functionally implicated in both beneficial (tissue repair, wound healing, development) and pathological (aging, degeneration) processes. However, the precise role of senescence in epimorphic regeneration was unknown, and understanding of senescent cell behavior derived largely from in vitro models. This study set out to define the functions and molecular features of cellular senescence during axolotl limb regeneration in vivo.

---

## Key Experiment Methods

1. In vitro senescence model in the axolotl limb mesenchyme-derived AL1 cell line via etoposide + sustained p53 stabilization, validated by lysosomal/mitochondrial expansion, DNA-damage markers, proliferative arrest, and SA-β-galactosidase (SAbG) activity.
2. Gain-of-function assay: implantation of senescent vs. proliferating (or dead) AL1 cells (DiI-labeled) into contralateral regenerating limbs; blastema length and EdU incorporation measured.
3. Loss-of-function/depletion: galactose-coated nanoparticles (GalNP) targeting elevated β-galactosidase in senescent cells — rhodamine (GalNP-rho) for labeling and doxorubicin (GalNP-dox) for selective killing; plus three additional senolytics.
4. Neighboring-cell analysis: EdU+ cells within a 50 μm radius of senescent vs. non-senescent cells.
5. Bulk RNA-seq of proliferating vs. senescent AL1 cells and FACS-purified endogenous bSCs (Rho+) vs. non-senescent (Rho−) cells across regeneration stages; scRNA-seq of purified Rho+ cells.
6. qPCR of unprocessed/processed rRNA ratios (5′ETS vs. 18S); Rps14 overexpression in AL1 cells.
7. Wnt pathway assays: β-catenin nuclear translocation (IHC), Wnt target genes (axin2, mycn) qPCR, Wnt secretion inhibitor C59, GSK3 inhibitor CHIR99021 rescue.

---

## Results

- Implantation of senescent AL1 cells significantly accelerated blastema growth (specifically at mid/late-bud phases) and increased EdU incorporation in vivo, while dead cells had no effect; senescent-conditioned media also elevated EdU incorporation, indicating a secreted mitogenic factor acting non-cell-autonomously.
- GalNP-dox depletion of endogenous bSCs (and additional senolytics) attenuated blastema growth (~30% reduction at 15 dpa) and reduced proliferation, demonstrating that senescence is required to maintain a pro-proliferative microenvironment.
- Cells within a 50 μm radius of senescent cells showed higher EdU incorporation, establishing a short-range pro-proliferative "neighboring cell" effect for both endogenous and implanted senescent cells.
- Transcriptomics: endogenous bSCs display senescence markers (glb1, lamin B1, oxr1, mmp3/10b), lysosomal expansion, and cell-cycle arrest, but — unlike DNA-damage-induced AL1 cells — lack a p53-driven damage response or pro-inflammatory signature.
- Growth arrest in bSCs is mediated by disrupted ribosomal biogenesis and rRNA processing (overrepresented unprocessed spacer sequences); Rps14 overexpression alone induced senescence in vitro, showing loss of ribosomal homeostasis is sufficient.
- scRNA-seq revealed bSC heterogeneity dominated by connective tissue cells and macrophages, plus "deep-senescent" clusters with extremely high rRNA; a conserved senescence signature (downregulated G2/S/M, upregulated rRNA and MMP3/10b) held across cell ontogeny.
- Wnt ligands (wnt7b, wnt8b) are specifically upregulated in bSCs; bSC depletion reduced β-catenin nuclear translocation and Wnt targets (axin2, mycn). The neighboring-cell effect was abolished by Wnt secretion inhibitor C59, and pharmacological Wnt activation (CHIR99021) rescued regeneration defects caused by senescent-cell depletion.
- Wnt inhibition unexpectedly increased senescent cell burden, suggesting Wnt limits paracrine senescence — bSC-derived Wnt may primarily protect neighbors from entering senescence.

---

## Perspective

This work establishes that cellular senescence is required for axolotl limb regeneration, with bSCs forming a pro-regenerative niche that sustains progenitor proliferation and blastema outgrowth in a short-range, non-cell-autonomous manner via Wnt signaling. It provides a rare in vivo view of senescence biology, identifying disrupted ribosomal biogenesis (rather than p53) as the basis of regenerative growth arrest and distinguishing this program from DNA-damage-induced senescence. The apparent Wnt-mediated suppression of paracrine senescence spread may represent an important difference in the injury response between salamanders and mammals, with fundamental and therapeutic implications for regenerative medicine.

Limitations: selective abrogation of Wnt ligand production specifically in senescent cells is not yet technically feasible, so the causal chain remains partly inferred; nanoparticle-based isolation could non-specifically label phagocytic macrophages (though senolytics independent of phagocytosis gave concordant results); and the precise killing mechanism of GalNP-dox remains to be defined. Future directions include senescent-cell-specific genetic manipulation and dissecting Wnt–Fgf and Wnt–Notch crosstalk in blastema outgrowth.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
