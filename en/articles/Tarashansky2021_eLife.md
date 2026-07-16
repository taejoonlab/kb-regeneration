---
tags: [2026-07]
extract: 2026-07-16
---

# Mapping single-cell atlases throughout Metazoa unravels cell type evolution

## Citation (NLM)
Tarashansky AJ, Musser JM, Khariton M, Li P, Arendt D, Quake SR, Wang B. Mapping single-cell atlases throughout Metazoa unravels cell type evolution. eLife. 2021;10:e66747. doi:10.7554/eLife.66747

**DOI:** [https://doi.org/10.7554/eLife.66747](https://doi.org/10.7554/eLife.66747)

---

## Background
Single-cell transcriptomic atlases are being produced for an increasing diversity of organisms, opening the possibility of using cross-species cell type comparisons to trace the evolutionary origins of cellular diversity and to transfer annotations from well-studied model organisms to under-characterized animals. However, comparisons across large evolutionary distances (across phyla) are hindered by two problems: gene regulatory programs diversify over evolution, diminishing similarity in cell-type-specific expression, and complex gene evolutionary history (duplications, losses, gains) means distantly related organisms share few one-to-one orthologs while paralogs may be more functionally similar than orthologs.

The authors previously introduced the self-assembling manifold (SAM) algorithm to reconstruct manifolds from single-cell data. Here they build on SAM to develop SAMap (Self-Assembling Manifold mapping), which relaxes the reliance on sequence orthology and iteratively refines both a gene-gene homology graph and the cross-species cell mapping. This enables mapping single-cell transcriptomes between phylogenetically remote species, including regeneration-capable invertebrates (planaria, Hydra, sponge) and vertebrates.

---

## Key Experiment Methods
1. **SAMap algorithm** — iterates between (a) a gene-gene bipartite graph with cross-species edges connecting homologous gene pairs (initially weighted by protein sequence similarity from reciprocal BLAST, E-value <10^-6) and (b) projection of the two single-cell datasets into a joint low-dimensional manifold, linking cells by mutual nearest cross-species neighborhoods. Gene-gene expression correlations from the aligned manifold reweight the homology graph; the cycle repeats to convergence (RMSE of alignment scores).
2. **Mutual nearest neighborhood alignment** — integrates each cell's within-species local neighborhood to establish robust cross-species mutual connectivity, allowing diverged expression profiles to remain linked.
3. **Seven whole-body atlases compared** — Xenopus tropicalis and Danio rerio embryos; planarian Schmidtea mediterranea and blood fluke Schistosoma mansoni; freshwater sponge Spongilla lacustris; Hydra vulgaris; mouse (Mus musculus) embryogenesis. Data from multiple platforms (10X, Drop-Seq, SmartSeq, MARS-Seq).
4. **Benchmarking** — compared SAMap against Seurat, LIGER, Harmony, Scanorama, BBKNN using one-to-one vertebrate orthologs (from eggNOG).
5. **Paralog substitution analysis** — identified genes with higher expression correlation to paralogs than orthologs; categorized by phylogenetic age of duplication.
6. **Cell type family / transitivity analysis** — quantified edge and node transitivity to identify densely interconnected cell type families and prune spurious connections; KOG functional enrichment of shared genes.

---

## Results
- SAMap produced a highly aligned combined manifold for zebrafish and frog, linking 26 of 27 expected cell type pairs based on ontogeny; the only exception was embryonic kidney. It also quantified heterochrony at cell type resolution.
- SAMap linked homologous secretory cell types arising from different germ layers (e.g., frog cement gland to zebrafish muc5ac+ secretory epidermal cells; hatching glands), supported by conserved TFs (myb, foxa1, xbp1, klf17).
- Existing integration methods (Seurat, LIGER, Harmony, Scanorama, BBKNN) failed to map the frog and zebrafish atlases even with one-to-one orthologs; SAMap succeeded and was robust to incomplete/downsampled atlases.
- Paralog substitution was prevalent: 565 genes had markedly higher correlation with paralogs than orthologs; more recent paralogs substituted at higher rates, consistent with functional compensation.
- Between the two flatworms (planarian and schistosome), SAMap revealed broad cell type homology across neoblasts (stem cells) and differentiated tissues. Schistosome e-cells clustered with planarian pluripotent neoblasts (shared soxp2, unc4, pax6a, gcm1); m/m' stem cells mapped to muscle progenitors (myoD).
- Across all seven species (sponge to mouse), SAMap linked 1051 cross-species cell type pairs and identified densely interconnected, highly transitive **cell type families**: a neural family (including vertebrate brain/spinal cord, bilaterian and cnidarian neurons, nematocytes, sponge choanocytes/apopylar cells) and a contractile family (myocytes, Hydra myoepithelial cells, sponge pinacocytes/myopeptidocytes), plus an invertebrate multipotent stem cell family (neoblasts, Hydra interstitial cells, sponge archeocytes).
- Conserved contractile-cell transcriptional signatures extended beyond the core contractile apparatus (cytoskeleton, signal transduction; regulators Csrp, Fox including FoxC and FoxG). Multipotent stem cells shared a deeply conserved module enriched for RNA processing/translation and regulators sox, klf, sub1, ssrp1 (FACT), kat7.

---

## Perspective
SAMap provides a roadmap for tracing cell type evolutionary history by mapping both genes and cells in mutually reinforcing directions, accounting for the complexity of gene evolution. The findings support hierarchical diversification of cell types into families sharing ancestral regulatory programs, with one-to-one homologies persisting only where no further diversification followed speciation. The systematic detection of paralog substitutions offers a new lens on molecular evolution of cell types. A practical significance is the ability to accelerate annotation of non-model organism atlases — highly relevant to regeneration research in planaria, Hydra, and sponges.

Limitations: the most memory-intensive steps (neighborhood coarsening, cross-species imputation) may be intractable for datasets of millions of cells, currently mitigated by chunking at the cost of runtime, or by downsampling. The analysis is largely pairwise; incorporating multiple species with explicit phylogeny is a future direction, requiring dense sampling of clades. Source code is available at GitHub (atarashansky/SAMap).

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
