---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# SOX2 regulates common and specific stem cell features in the CNS and endoderm derived organs

## Citation (NLM)
Hagey DW, Klum S, Kurtsdotter I, Zaouter C, Topcic D, Andersson O, Bergsland M, Muhr J. SOX2 regulates common and specific stem cell features in the CNS and endoderm derived organs. PLoS Genet. 2018;14(2):e1007224. doi:10.1371/journal.pgen.1007224

**DOI:** [https://doi.org/10.1371/journal.pgen.1007224](https://doi.org/10.1371/journal.pgen.1007224)

---

## Background

Stem cells share the capacities to self-renew and to generate multiple differentiated lineages, yet stem cells of different organs have distinct gene expression profiles. The transcription factor SOX2 is expressed across many stem cell populations, from pluripotent cells to adult organ-specific stem cells, and controls maintenance, proliferation and cell fate. However, whether SOX2 achieves these functions through similar mechanisms in distinct stem cell populations was unknown.

To address this, the authors compared SOX2 genomic binding and gene expression across CNS tissues (cortex, spinal cord) and endoderm-derived organs (stomach, lung/esophagus), testing how SOX2 regulates both shared (core) and cell-type-specific stem cell programs.

---

## Key Experiment Methods

1. SOX2 ChIP-seq on dissected E11.5 mouse lung/esophagus and stomach, compared with published in vivo SOX2 ChIP-seq from E11.5 cortex and spinal cord; peak calling with SISSRS and validation with MACS14.
2. RNA-seq (Smart-seq2) of FACS-sorted SOX2-GFP+ cells from E11.5 cortex, spinal cord, stomach and lung/esophagus.
3. Motif enrichment (HOMER, CentriMo) and motif-spacing analysis to identify candidate SOX2 partner factors.
4. Co-immunoprecipitation (with/without DNase I) to test physical interaction of SOX2 with OTX1, FOXA1 and ZEB1.
5. Luciferase reporter (cis-regulatory module, CRM) transactivation assays in P19 cells.
6. Transgenic zebrafish Tol2-e1b-GFP reporter assays to test tissue-specific enhancer activity of SOX2-bound CRMs.
7. In vivo/ex vivo perturbation of SOX2 levels (overexpression or dominant-negative dnSoxB1/shRNA) by chick spinal cord in ovo electroporation and mouse stomach explant electroporation, with BrdU proliferation assays; epistasis with Wnt/β-catenin effectors (LEF1GBM, dnTcf7L2).

---

## Results

- SOX2 binds a similar core motif in all four tissues, but target regions are primarily cell-type-specific (503 peaks in lung/esophagus, 962 in stomach, 6357 in cortex, 2313 in spinal cord); only 232 peaks shared across both germ layers and 32 across all four tissues.
- SOX2 binding is more similar within a germ layer; embryonic endodermal binding resembled adult stomach, while cortex/spinal cord binding resembled ESC-derived NPCs.
- Cell-type-specific SOX2 peaks were enriched for distinct partner-factor motifs: OTX1 (cortex), PAX2 (spinal cord), GATA4/HNF1A (stomach), FOXA1/TEAD4 (lung/esophagus); shared peaks were enriched for ZEB1 and ZBTB33 motifs.
- SOX2 physically interacts with OTX1 (DNA-dependent, via HMG+B domains), FOXA1 and ZEB1 (via C-terminus). Functionally, OTX1 additively activated CNS CRMs, FOXA1 weakly activated stomach CRMs, and ZEB1 repressed commonly bound CRMs.
- Cell-type-specific SOX2 binding was enriched around genes specifically expressed in the corresponding tissue (e.g., "cell differentiation in spinal cord"), whereas commonly bound genes were enriched for generic stem cell GO terms ("regulation of stem cell proliferation/differentiation").
- SOX2-bound CRMs functioned as tissue-specific enhancers in zebrafish (11/12 common CRMs active in both tissues; 5/7 CNS-specific in CNS; 4/7 endoderm-specific in endoderm).
- High SOX2 levels reduced proliferation (fewer BrdU+ cells) in spinal cord and stomach, while reduced SOX2 activity increased proliferation—mirroring the cortex. The Ccnd1 (Cyclin D1) promoter is bound by SOX2 in all four tissues, and SOX2 acts by counteracting Wnt/β-catenin signaling (via GRO/TLE co-repression), a conserved mechanism across cortex, spinal cord and stomach.

---

## Perspective

This study demonstrates that a single transcription factor, SOX2, simultaneously drives cell-type-specific gene programs (through combinatorial partner factors expressed in each tissue) and a conserved core stem cell program centered on repressing proliferation via the Ccnd1/Wnt-β-catenin axis. For CNS/spinal cord biology, it clarifies how SOX2 maintains neural progenitors in a slowly proliferative state through mechanisms shared with non-neural stem cells. Limitations include possible contaminating non-target cells in FACS-sorted populations, in vitro co-IP using misexpressed proteins (leaving room for bridging factors), and reliance on cross-species (zebrafish) reporter validation. Future directions include defining the full combinatorial partner-factor code that specifies tissue-specific SOX2 activity.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
