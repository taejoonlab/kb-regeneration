---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
---

# Identification of a discrete subpopulation of spinal cord ependymal cells with neural stem cell properties

## Citation (NLM)
Stenudd M, Sabelström H, Llorens-Bobadilla E, Zamboni M, Blom H, Brismar H, Zhang S, Basak O, Clevers H, Göritz C, Barnabé-Heider F, Frisén J. Identification of a discrete subpopulation of spinal cord ependymal cells with neural stem cell properties. Cell Rep. 2022;38(9):110440. doi:10.1016/j.celrep.2022.110440

**DOI:** [https://doi.org/10.1016/j.celrep.2022.110440](https://doi.org/10.1016/j.celrep.2022.110440)

---

## Background

Ependymal cells lining the central canal of the spinal cord do not generate other cell types under physiological conditions, but the population harbors cells with in vitro neural stem cell (NSC) properties and, after injury, produces the majority of scar-forming astrocytes and some remyelinating oligodendrocytes. Ependymal-derived astrocytes limit tissue damage and support neuronal survival, and modulating the ependymal injury response holds therapeutic potential. Prior work indicated morphological and marker heterogeneity, and a subpopulation with enriched neurosphere-initiation capacity was described, but those neurospheres did not self-renew efficiently and it was unknown which cells actually harbor stem cell potential and generate progeny after spinal cord injury.

This Report identifies a discrete Troy (Tnfrsf19)-expressing subpopulation, termed ependymal A (EpA) cells, and characterizes its stem cell behavior in vitro and after injury.

---

## Key Experiment Methods

1. Genetic fate mapping in Troy-CreER (Tnfrsf19) knock-in mice on Rosa26-tdTomato or Rosa26-Confetti reporter backgrounds; RNAscope in situ hybridization to confirm Tnfrsf19 transcripts in recombined cells.
2. Characterization of EpA cell identity, location, and morphology with pan-ependymal markers (FoxJ1, Sox2, Sox9, Vimentin, Nestin), super-resolution/3D-SIM microscopy, and Ki67 proliferation assessment.
3. Neurosphere assays across serial passages to test self-renewal, plus in vitro differentiation into astrocytes, neurons, and oligodendrocytes.
4. Spinal cord injury (dorsal funiculus incision and crush lesions) with EdU labeling; quantification of recombined progeny (Sox9+ astrocytes, Sox10/NogoA/Myrf+ oligodendrocytes) up to 15 weeks; timing experiments inducing recombination 1 week, 2 months, or 15 months before injury.
5. Clonal analysis using the R26-Confetti reporter with low stochastic recombination to trace individual EpA clones after injury.
6. Droplet-based single-cell RNA-seq of FACS-isolated recombined cells from injured and uninjured spinal cord 3 days post-injury; UMAP, RNA velocity (scVelo) and Monocle 3 trajectory analysis, SCENIC gene-regulatory-network/AUCell regulon analysis, and signaling entropy (LandSCENT) scoring.

---

## Results

- EpA cells constitute ~8.2% of spinal cord ependymal cells (~0.1% of all cells in a segment), are enriched in the dorsal ependymal pole, often extend a blood-vessel-contacting basal process, and uniformly express pan-ependymal markers while appearing highly differentiated and low-proliferative.
- In primary neurospheres, EpA recombination matched the ependymal rate (no enrichment), but from the second passage the vast majority of self-renewing neurospheres derived from EpA cells, indicating EpA cells account for essentially all extensive in vitro self-renewal capacity; EpA-derived neurospheres generated astrocytes, neurons, and oligodendrocytes.
- After dorsal funiculus incision or crush injury, EpA cells generated migrating Sox9+/PDGFRβ- progeny; the recombined population expanded ~5-fold, EpA cell number in the ependymal layer was maintained (self-renewal), and recombined astrocytes and oligodendrocytes were present at 15 weeks. No ependymal-derived neurons were seen in vivo. Recombination timing (up to 15 months before injury) gave comparable progeny, indicating stable rather than transient EpA identity.
- Clonal analysis identified 20 EpA clones with migrating EdU+/Sox2+ progeny; migration was predominantly dorsal/lateral with limited rostrocaudal spread; a nearby founder ependymal cell of matching color was found for 17/20 clones, demonstrating self-renewal at the single-cell level in vivo.
- scRNA-seq resolved three adjacent clusters (EpA1-3): EpA1 (uninjured + injured) expressed highest motile-cilia/differentiated ependymal genes (Foxj1, Fam183b, Rarres2, Tmem212); EpA2/EpA3 were almost exclusively from injured cord. RNA velocity/pseudotime ordered EpA1→EpA2→EpA3 with increasing signaling entropy (a proxy for differentiation potency), rising ribosomal/translation genes (EpA2) then cell-cycle genes (EpA3), and progressive gain of astrocyte (Gfap, Aldh1l1) and oligodendrocyte (Olig1/2) lineage genes.
- SCENIC revealed ependymal regulons (Rfx2/Rfx3) high in EpA1, stem/neurogenesis regulons (Sox4, Sox11, Tead2, Gata3) in EpA2, and proliferation/neurogenesis regulons (Pole3, Brca1, Ezh2) in EpA3; EpA2/EpA3 gained subventricular-zone NSC and transit-amplifying signature gene expression, indicating dedifferentiation to a stem-cell-like state.

---

## Perspective

The study identifies EpA cells as the discrete latent stem cell population of the adult spinal cord: highly differentiated ependymal cells that, after injury, dedifferentiate (losing ependymal programs, gaining signaling entropy) into a self-renewing, multipotent stem-cell-like state generating astrocytes and oligodendrocytes. This parallels injury-induced neurogenic reprogramming of parenchymal astrocytes after stroke and the glial-driven CNS regeneration seen in lower vertebrates, suggesting an evolutionarily conserved but restricted latent potential in mammalian glia. Defining a rare (~0.1%) targetable cell population provides a rational target for regenerative therapies for spinal cord repair. Limitations acknowledged by the authors: multipotency was not demonstrated at the single-cell level in vivo (requiring larger clonal analyses and longer post-injury windows given rare, slow oligodendrocyte generation), and the molecular basis distinguishing EpA cells from other ependymal cells that endows their stem cell potential remains unknown.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
