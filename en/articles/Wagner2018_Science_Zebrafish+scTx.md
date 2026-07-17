---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Single-cell mapping of gene expression landscapes and lineage in the zebrafish embryo

## Citation (NLM)
Wagner DE, Weinreb C, Collins ZM, Briggs JA, Megason SG, Klein AM. Single-cell mapping of gene expression landscapes and lineage in the zebrafish embryo. Science. 2018;360(6392):981-987. doi:10.1126/science.aar4362

**DOI:** [https://doi.org/10.1126/science.aar4362](https://doi.org/10.1126/science.aar4362)

---

## Background

A central goal of developmental biology is to trace how embryonic lineages progress from pluripotency to differentiated adult cell types. Classical fate mapping and mutant analysis have explained much of development, but a systematic atlas of all cell states in a developing vertebrate embryo has been lacking. Advances in single-cell RNA sequencing (scRNA-seq) now make it possible to assemble comprehensive single-cell atlases of complex, dynamic in vivo processes.

Here the authors apply inDrops scRNA-seq to more than 92,000 cells from zebrafish embryos across the first 24 hours of development, building a cell-state landscape that captures axis patterning, germ-layer formation, and organogenesis — including neural plate, spinal cord, and neural crest lineages relevant to nervous-system development and to zebrafish as a regeneration model. They further introduce a transposon-based clonal barcoding method (TracerSeq) to record single-cell lineage histories and test how clonally related cells traverse the state landscape.

---

## Key Experiment Methods

1. inDrops droplet-based scRNA-seq on >92,000 single cells from dissociated wild-type and mutant zebrafish embryos sampled across the first 24 hours post fertilization (hpf), with seven biological replicates at the 24-hpf endpoint.
2. A graph-based computational strategy that locally embeds consecutive time points (single-cell k-nearest-neighbor graphs joined across adjacent time points) rather than using a single global coordinate system, producing a branching cell-state landscape.
3. Diffusion pseudotime (DPT) graph-distance measures, coarse-graining of the graph into state nodes, and construction of a spanning "state tree" rooted at a 4-hpf state; a "canalization score" to quantify off-tree connectivity.
4. TracerSeq: Tol2 transposase-mediated random integration of GFP reporter cassettes carrying unique 20-nucleotide barcodes (introduced via Gibson assembly) to reconstruct clonal lineage trees; combined lineage + transcriptome data for 1269 clonal barcodes over 4342 cells from 5 embryos at 24 hpf.
5. Lineage coupling scores (shared barcodes relative to randomized data) with hierarchical clustering to relate cell-state pairs.
6. CRISPR-Cas9 disruption of the chordin locus (BMP inhibitor) with tyrosinase-targeted controls, profiled by inDrops at ~14–16 hpf to test the effect of a signaling perturbation on the landscape.
7. Web-based interactive portals for the state tree and full single-cell graph (scZfish2018).

---

## Results

- Clustering of wild-type transcriptomes revealed an expanding set of epidermal, neural, mesodermal, and endodermal cell states over developmental time, annotated by marker genes; sampling was deep enough to detect states as rare as 0.1–0.5% (including germ cells at all time points).
- The joined single-cell graph forms a branching network whose initial branches represent neural, epidermal, and mesendodermal states, with early branching for germline, notochord, enveloping-layer epidermis, and prechordal plate.
- Graph distance recapitulated known lineage relationships: 24-hpf neural tissues mapped back to the 6-hpf dorsal anterior epiblast, whereas direct gene-expression correlation between 6- and 24-hpf states failed to capture these relationships.
- The coarse-grained "state tree" reproduced many specific developmental features (optic cup, diencephalon, telencephalon, mesencephalon, rhombencephalon branch points; neural crest giving melanoblasts/iridoblasts/xanthoblasts; hematopoietic, endothelial, heart, pharyngeal, pronephros, and fin-bud branches).
- Widespread low-canalization regions (notably neural plate and somitic mesoderm) show off-tree interconnections, indicating the landscape cannot be fully represented as a simple tree.
- TracerSeq showed cell-lineage history does not invariantly mirror graph topology: large founder clones marked diverse states, with nested subclones showing fate restriction. Lineage coupling grouped states largely by position (e.g., anterior-posterior axis) rather than strictly by germ layer.
- Both convergence (clonally distant cells reaching similar states) and divergence (clonally related cells reaching distant states) were observed. A notable divergent case: one pharyngeal arch state (ph.arch-cd248b) was clonally related to neural crest / posterior neural states, indicating divergence from a neural-plate lineage followed by convergence with lateral-plate derivatives. Mesoderm–spinal cord couplings were consistent with transient neuromesodermal progenitors in the tailbud.
- chordin CRISPR disruption produced no qualitatively new cell state; within-state differential expression was modest. Instead, cell-state abundances shifted reciprocally — expansion of ventral tissues (somitic mesoderm, epidermis, hatching gland, blood, endothelium) at the expense of dorsal tissues (neural plate, notochord). Adjacent graph domains of opposing chordin sensitivity (heart vs. fin bud; notochord vs. hatching gland; spinal cord vs. somitic mesoderm in the tailbud) sat downstream of inferred branch points, i.e., the landscape was "tilted" while fates remained canalized.
- In the tailbud, a brachyury+;sox2+ neuromesodermal-like progenitor gave rise to neural (sox3, sox19a, pax6a, neurog1) and somitic (tbx16, tbx6, tbx24, msgn1, myod1) branches; the neural-mesodermal branchpoint coincided with chordin expression and sensitivity boundaries, suggesting a chordin-dependent posterior neurogenic transition state.

---

## Perspective

This study establishes a minimal-assumption, graph-based framework for reconstructing whole-embryo developmental landscapes over time from scRNA-seq, and pairs it with an independent clonal-lineage readout (TracerSeq). A key conceptual contribution is that the true relationship between a cell lineage (a tree) and the gene-expression landscape (a topologically complex graph with loops and continua) is not one-to-one: both convergent and divergent clonal behaviors occur, so cell state and lineage must be measured independently. For nervous-system and regeneration research, the atlas provides temporal and tissue associations for neural plate, spinal cord, and neural-crest programs, and demonstrates how a signaling perturbation can dramatically reshape cell-state abundances without creating new states.

Limitations include the timing of TracerSeq integrations (capturing only the transition from unrestricted pluripotency to first fate restrictions), reliance on inferred/annotated cell-state labels that may need community refinement, and analysis restricted to the first 24 hours of a single species. Future directions highlighted are systematic mapping of additional signaling perturbations to reveal the embryo's full signaling logic, and extension to further stages, tissues, and species.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
