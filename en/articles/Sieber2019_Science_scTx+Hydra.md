---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
---

# Stem cell differentiation trajectories in Hydra resolved at single-cell resolution

## Citation (NLM)
Siebert S, Farrell JA, Cazet JF, Abeykoon Y, Primack AS, Schnitzler CE, Juliano CE. Stem cell differentiation trajectories in Hydra resolved at single-cell resolution. Science. 2019;365(6451):eaav9314. doi:10.1126/science.aav9314

**DOI:** [https://doi.org/10.1126/science.aav9314](https://doi.org/10.1126/science.aav9314)

---

## Background

The freshwater cnidarian polyp Hydra continually self-renews all of its cells and can regenerate its whole body from a small tissue fragment, making it a classic model for regeneration, stem cell biology, and nervous system function. Its three stem cell lineages (endodermal epithelial, ectodermal epithelial, and interstitial), morphological cell types, and lineage relationships are well characterized, but the molecular definition of its cell states had remained elusive.

By applying single-cell RNA sequencing, the authors set out to capture the complete molecular diversity of Hydra cell states, reconstruct differentiation trajectories for each lineage, identify candidate regulators of cell-state specification, and build a spatial molecular map of the nervous system. As sister group to bilaterians with a largely conserved gene-family complement, Hydra provides an evolutionary reference point for ancestral developmental and neurogenic mechanisms.

---

## Key Experiment Methods

1. Drop-seq single-cell RNA-seq of dissociated whole adult *Hydra vulgaris* polyps (13 libraries) plus two FACS-enriched GFP+ neuron libraries from transgenic Hydra; ~25,000 transcriptomes (24,985 analyzed; median 1,936 genes / 5,672 UMIs per cell).
2. Read mapping to a de novo transcriptome and genome reference, graph-based clustering, tSNE visualization, and cluster annotation using published markers; validation by RNA in situ hybridization and double fluorescence in situ hybridization (FISH).
3. Non-negative matrix factorization (NMF) to identify coexpressed gene modules/metagenes and to detect biological/technical doublets and phagocytic events.
4. Differentiation-trajectory reconstruction with the URD software (branching trees for interstitial and male germline lineages; linear oral-aboral trajectories for epithelial and gland cells) using simulated random walks and pseudotime/latent-time ordering.
5. ATAC-seq on whole Hydra plus motif enrichment analysis (peaks within 5 kb upstream) and Pfam/JASPAR inference to link enriched transcription-factor binding motifs to candidate regulators of each metagene; TagSeq of separated tissue layers to assign neurons to ectodermal vs endodermal nerve nets; GFP reporter transgenic lines for validation.

---

## Results

- Clustering separated cells by lineage and recovered expected populations within each; several differentiation trajectories were visible directly in tSNE, with stem cell clusters connected to their differentiated progeny.
- Epithelial trajectories revealed position-dependent (oral-aboral) gene expression, including previously uncharacterized genes in Wnt, BMP, and FGF signaling, suggesting candidate patterning regulators.
- Multipotent interstitial stem cells (ISCs) were largely defined by an absence of cell-type-specific markers (a single unique marker found), similar to planarian cNeoblasts; HvSoxC marked cells transitioning toward neurons and nematoblasts.
- URD reconstruction indicated that neurogenesis and gland-cell differentiation transit through a shared progenitor state (marked by Myc3 and Myb), distinct from nematogenesis; a model was proposed in which a bipotential gland/neuron progenitor born in the ectoderm crosses the mesoglea to supply endodermal neurons and gland cells.
- Gland cells showed location-dependent transdifferentiation (zymogen to granular mucous gland cells) and oral-aboral expression programs, including oral-organizer genes (HyWnt1/3, HyBra1/2) in spumous mucous gland cells; candidate germline stem cell markers (HyFem-1/2) were identified.
- ATAC-seq + motif analysis found enriched motifs for 39 metagenes and candidate regulators for 25, including Pax-A in nematogenesis, RFX in gland-cell specification, and forkhead motifs in endoderm (conserved with Nematostella/bilaterians).
- A molecular map of the nervous system identified 12 distinct neuronal subtypes (including the first molecular markers for endodermal neurons) placed spatially and assigned to described neural circuits (RP1, RP2, CB), validated by NDF1 and Alpha-LTX-Lhe1a-like GFP reporter lines.

---

## Perspective

This study provides a comprehensive, extensively validated molecular atlas of Hydra cell states, differentiation trajectories, candidate gene-regulatory drivers, and a spatially resolved nervous-system map, establishing a powerful resource for developmental, evolutionary, and regenerative biology. The demonstration that a whole regenerative animal's differentiation landscape can be captured from one life stage with relatively few cells opens the door to organism-wide perturbation studies. The identification of a dynamic, regenerating nervous system map is especially relevant to understanding neuronal plasticity and regeneration in an evolutionary context. Limitations noted by the authors include the need for fate-mapping to confirm the proposed shared gland/neuron progenitor (versus separate progenitors sharing early transcriptional events), the challenge of highly phagocytic epithelial cells complicating scRNA-seq interpretation, and reliance on trajectory inference that requires functional validation.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
