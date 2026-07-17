---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Single-Cell Transcriptomics and Fate Mapping of Ependymal Cells Reveals an Absence of Neural Stem Cell Function

## Citation (NLM)
Shah PT, Stratton JA, Stykel MG, Abbasi S, Sharma S, Mayr KA, Koblinger K, Whelan PJ, Biernaskie J. Single-Cell Transcriptomics and Fate Mapping of Ependymal Cells Reveals an Absence of Neural Stem Cell Function. Cell. 2018;173(4):1045-1057. doi:10.1016/j.cell.2018.03.063

**DOI:** [https://doi.org/10.1016/j.cell.2018.03.063](https://doi.org/10.1016/j.cell.2018.03.063)

---

## Background

Ependymal cells are multi-ciliated epithelial cells lining the brain's ventricular system and form part of the neural stem cell (NSC) niche in the adult ventricular-subventricular zone (V-SVZ). Whether ependymal cells are themselves latent NSCs capable of acquiring neurogenic function has been highly controversial, largely because ependymal cells and neighboring GFAP+ type B NSCs share many markers (CD24, Sox2, Nestin, CD133) and both derive from radial glia, making prospective in vivo distinction difficult. Earlier lineage-tracing tools such as the FoxJ1 promoter also label a subset of postnatal V-SVZ NSCs, confounding prior claims of ependymal neurogenic capacity.

This "Matters Arising" study introduces a transgenic system to specifically target ependymal cells at the exclusion of neural lineages, then uses single-cell RNA-seq, in vitro assays, and injury/growth-factor challenges to directly test whether ependymal cells behave as stem cells.

---

## Key Experiment Methods

1. Generated aSMACreERT2::ROSA26 (eYFP or tdTomato) transgenic mice ("aSMA::R26") for tamoxifen-inducible labeling of V-SVZ ependymal cells; validated identity with cilia and cell-identity markers (acetylated-tubulin, CD133, FoxJ1, Sox2, Nestin, GFAP, Ki67) and en-face pinwheel analysis.
2. Fate mapping over 2-5 months with induction at embryonic (E17), postnatal (P3+4), and adult (P40/41) timepoints to define targeting specificity and olfactory bulb neurogenesis contribution.
3. FACS purification of aSMA::eYFP+/- cells and neurosphere culture under NSC-promoting conditions (FGF2+EGF, VEGF+FGF2+EGF, co-culture with E13 NSCs, conditioned media); developed a double-transgenic aSMACreERT2::ROSA26tdTomato/Sox2-GFP reporter to exclude non-ependymal (mural) contamination.
4. Single-cell RNA-seq (10X Chromium v2) of FACS-purified ependymal cells vs. neural stem/progenitor cells (~1,700 cells), graph-based clustering, tSNE, and PAGODA pathway/gene-set overdispersion analysis.
5. In vivo challenges: intraventricular VEGF+bFGF infusion with EdU labeling, and striatal intracerebral hemorrhagic (collagenase) stroke in adult and neonatal mice to test injury-induced activation.

---

## Results

- aSMA::R26 specifically labeled multi-ciliated, CD133+/FoxJ1+/Sox2+/Nestin+ ependymal cells (71% of ventricular-wall cells), largely GFAP- and non-proliferative (Ki67-); induction at P3+4 marked immature committed ependymal cells that matured following the known rostro-caudal/dorso-ventral pattern.
- FACS-purified adult ependymal cells failed to proliferate or survive under any NSC mitogen condition in vitro (0/600 cells), whereas control aSMA-negative Sox2-GFP+ cells robustly formed self-renewing spheres.
- scRNA-seq: ependymal cells (Acta2, Foxj1) clustered distinctly from neural-lineage cells; despite sharing many quiescent-NSC genes (Clu, Gja1, Sox9, S100b; 2,375 shared genes), they were enriched for cilia-related genes and lacked functional stemness.
- A rare Flt1-expressing cluster reproduced the "ependymal" angiogenic signature reported by Luo et al. (2015) (Slco1a4, Spock2, Cldn5, Kdr, Fn1) but lacked cilia genes; VEGFR1(Flt1)/FN1 were absent from bona fide ependymal cells, arguing this rare population does not represent ependymal cells at large.
- Neither intraventricular VEGF+bFGF nor striatal hemorrhagic stroke induced ependymal cell proliferation, delamination, or neurogenesis; ependymal cells only transiently upregulated GFAP. Proliferative/neurogenic (EdU+ GFAP+, Dcx+) responses came exclusively from sub-ependymal, non-recombined cells.

---

## Perspective

Using a labeling strategy that strictly excludes the NSC lineage, this work provides strong evidence that adult V-SVZ ependymal cells are remarkably stable, non-neurogenic cells rather than latent NSCs, directly challenging prior claims (e.g., Luo et al., 2015; Carlén et al., 2009) that were likely confounded by contaminant labeling of type B NSCs. It defines a clean molecular signature of the ependymal compartment and clarifies that the neurogenic potential of the niche resides in GFAP+ type B cells. Limitations include reliance on a single (aSMA) driver that labels ~71% of ependymal cells (leaving open a rare escaper subpopulation) and focus on the brain V-SVZ rather than the spinal cord ependyma, where regenerative/neurogenic behavior may differ. The findings caution against therapeutic strategies premised on awakening brain ependymal cells as stem cells.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
