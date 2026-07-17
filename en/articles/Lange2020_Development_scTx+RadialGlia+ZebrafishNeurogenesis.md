---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
---

# Single cell sequencing of radial glia progeny reveals the diversity of newborn neurons in the adult zebrafish brain

## Citation (NLM)
Lange C, Rost F, Machate A, Reinhardt S, Lesche M, Weber A, Kuscha V, Dahl A, Rulands S, Brand M. Single cell sequencing of radial glia progeny reveals the diversity of newborn neurons in the adult zebrafish brain. Development. 2020;147(1):dev185595. doi:10.1242/dev.185595

**DOI:** [https://doi.org/10.1242/dev.185595](https://doi.org/10.1242/dev.185595)

---

## Background
Zebrafish display widespread and pronounced adult neurogenesis, which underlies their capacity to regenerate the central nervous system after injury. In contrast to mammals, where adult neurogenesis is confined to the hippocampal subgranular zone and the sub-ependymal zone of the lateral ventricles, teleost fish generate new neurons throughout the neuraxis. In the adult zebrafish telencephalon, radial glia (RG) neural stem cells reside in the ventricular zone and give rise to neurons that integrate into the adjacent parenchyma. Efficient repair after telencephalic injury proceeds through RG proliferation, neuron generation, and integration of newborn neurons (NBNs).

Despite this, the cellular identity and biological properties of adult newborn neurons remained elusive for most brain areas, and prior work focused mainly on RG rather than the neuronally committed progeny. This study set out to prospectively isolate and transcriptionally characterize RG, RG-derived NBNs, and mature neurons (MNs) from the homeostatic adult zebrafish forebrain to understand the diversity and differentiation trajectories of newborn neurons.

---

## Key Experiment Methods
1. Short-term lineage tracing using double-transgenic reporter fish: combining the RG reporter her4.1:mcherry (or a newly generated gfap:nls-mcherry line) with the neuronal reporter elavl3:gfp. NBNs are identified as mCherry-low/GFP-positive cells that inherit stable mCherry protein from RG precursors.
2. Flow cytometry (FACS) and Image Stream imaging flow cytometry to quantify and isolate RG (mCherry-high/GFP-neg), NBNs (mCherry-low/GFP-pos), and MNs (mCherry-neg/GFP-pos) from dissociated forebrains.
3. EdU pulse-chase labeling (injections at 12 h intervals; analysis at 2 h, 7 days, 4 weeks) to verify enrichment of adult-generated neurons and their transient kinetics.
4. Single cell RNA sequencing (SMARTSeq2) of sorted RG, NBN, and MN cells (264 cells passing QC), followed by Louvain clustering, t-SNE, and PCA.
5. Diffusion-map/diffusion pseudotime analysis to reconstruct differentiation trajectories.
6. Cross-species cell-type homology analysis by transforming zebrafish and mouse transcriptomes into shared orthologue pairs and hierarchical clustering against adult/developing mouse hippocampus data (Hochgerner et al., 2018).
7. In situ hybridization for cluster-specific markers (tubb5, ebf3a, msi2b, tbr1b) and EdU/HuC-D co-labeling to localize NBN populations in the forebrain.

---

## Results
- RG-derived NBNs can be prospectively isolated via inherited fluorescent protein; NBNs account for ~10.9% of live forebrain cells, comparable in number to bona fide RG (8.7%), while MNs dominate (72.1%).
- EdU pulse-chase confirmed NBNs are enriched for adult-generated neurons, transiently retaining her4.1:mCherry for at least 7 days but no more than 4 weeks.
- Single cell sequencing identified five clusters: RG, two pure newborn-neuron clusters (NBN.1, NBN.2), a mixed NBN/MN cluster, and an oligodendrocyte progenitor cell (OPC) cluster—indicating RG generate both neuronal and oligodendroglial progeny.
- Each cluster carried distinct markers (e.g., RG: fabp7a, her4.1, glula; NBN.1: tubb5, cd99l2, cnp; NBN.2: ebf3a, tbr1b, msi2b; OPC: olig2, aplnra).
- Pseudotime ordering placed NBN.1 as the state most closely related to RG, with a branchpoint leading separately to the MN cluster or the NBN.2 cluster.
- Cross-species homology analysis showed zebrafish RG cluster with mouse ependymal cells/young astrocytes/RGL-NSCs, NBN.1 with immature granule cells and pyramidal neurons, and NBN.2/MN with mature neurons—demonstrating conservation of neurogenic cell types with the mammalian hippocampus.
- Proliferation (ccnd1, mki67, mcm5) was confined to the RG cluster; proliferating RG were enriched for neurogenic fate determinants (ascl1a, sox4a) and NBN.1 markers (tmsb, stmn1b), indicating most proliferating RG are committed to neurogenesis.
- Spatial analysis: tubb5+ NBN.1 cells localize to the ventricular/peri-ventricular zone of the telencephalon (glutamatergic projection neuron identity), whereas ebf3a/msi2b/tbr1b+ NBN.2 cells localize to the ventral entopeduncular nucleus (vENT) in the diencephalon—a previously unreported adult neurogenesis site confirmed by EdU/HuC-D co-labeling.

---

## Perspective
This work provides the first prospective isolation and single-cell transcriptomic characterization of adult newborn neurons in the zebrafish forebrain, establishing new markers and revealing intrinsic heterogeneity among RG progeny. The demonstrated homology between zebrafish and mammalian adult neurogenic cell types supports zebrafish as a model for understanding neuron generation and integration—key roadblocks for mammalian brain repair after injury or neurodegeneration. The finding that glutamatergic projection neurons are generated in the adult telencephalon, and that a distinct NBN population is added to the diencephalic vENT, expands the map of adult neurogenesis.

Limitations include the relatively small number of sequenced cells (264 passing QC, especially few MNs), reliance on short-term population-level lineage tracing rather than clonal tracing, and analysis restricted to the homeostatic (uninjured) forebrain—so the behavior of these NBN populations during regeneration remains to be tested. The biological role of the surprisingly large NBN population and the mechanisms of their integration are still unknown. Future directions include applying this framework to injured/regenerating brain and manipulating the identified markers to probe NBN function.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
