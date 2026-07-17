---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Single-cell RNA analysis identifies pre-migratory neural crest cells expressing markers of differentiated derivatives

## Citation (NLM)
Lencer E, Prekeris R, Artinger KB. Single-cell RNA analysis identifies pre-migratory neural crest cells expressing markers of differentiated derivatives. eLife. 2021;10:e66078. doi:10.7554/eLife.66078

**DOI:** [https://doi.org/10.7554/eLife.66078](https://doi.org/10.7554/eLife.66078)

---

## Background

The neural crest is a transient, migratory population of stem-like cells unique to vertebrates that gives rise to diverse derivatives including craniofacial cartilage/bone, peripheral nervous system neurons and glia, and pigment cells. A long-standing question is when and how neural crest cells (NCCs) acquire their diverse fates. Classical models describe a stepwise series of bifurcating fate decisions, with some studies (chick, frog) suggesting migratory NCCs are multipotent and require cues from the migratory environment, while others (zebrafish, quail) suggest NCCs become lineage-restricted before migration.

Single-cell RNA sequencing (scRNA-seq) can expose transcriptional heterogeneity within developing tissues that bulk sequencing misses. Here the authors use scRNA-seq to characterize the transcriptional landscape of trunk NCCs (tNCCs) during the early stages of migration in zebrafish, sampling at a stage when both migratory and pre-migratory tNCC populations coexist, to test whether cells begin differentiation programs prior to migration.

---

## Key Experiment Methods

1. FACS isolation of tg(-4.9sox10:eGFP)+ cells from dissected trunks of 24 hpf (25-somite) zebrafish embryos (80 embryos pooled) followed by 10X Genomics scRNA-seq (607 cells analyzed).
2. Unsupervised clustering (Seurat), marker-gene annotation, and RNA velocity (Velocyto) to infer developmental pseudotime/transitions.
3. Cross-dataset integration with existing sox10:eGFP tNCC atlases at 48 and 68 hpf (Howard et al., 2021) and with a whole-embryo zebrafish atlas at 14/18/24 hpf (Wagner et al., 2018).
4. Quantitative hybridization chain reaction (qHCR) in situ hybridization to validate novel marker genes in xanthoblast and Rohon-Beard (RB) lineages, with tg(sox10:TagRFP) to mark NCCs and HNK-1 immunolabeling to mark RBs.
5. Analysis of the NRD/prdm1a-/- mutant to place candidate genes within NCC/RB gene regulatory networks.

---

## Results

- tNCCs at 24 hpf are transcriptionally heterogeneous; clusters included multipotent tNCC progenitors (crestin, sox10, foxd3, tfap2a; posterior Hox genes) plus otic/lateral line, mesenchymal, and posterior arch cranial NCC populations.
- A large fraction of presumptively pre-migratory tNCCs already expressed pigment-lineage programs: a pan-pigment/melanophore progenitor cluster (mitfa, gpr143, trpm1b) and a xanthoblast cluster expressing a differentiated xanthophore GRN (aox5, pax7a/b, gch), including novel markers slc2a15a/b and gjb8 (cx30.3).
- RNA velocity indicated tNCC progenitors (cluster 1) transitioning into the xanthoblast cluster, consistent with initiation of a pigment differentiation program before migration.
- A distinct population of Rohon-Beard sensory neurons (isl1, isl2a/b, scrt2, prdm14, drgx) was recovered; RBs expressed low levels of sox10/sox10 transgene, consistent with a shared neural-plate-border origin with NCCs. Novel RB markers included fgf13a/b, cxcr4b, and pou4f4.
- Cross-dataset integration confirmed identities: 24 hpf xanthoblasts bridge to differentiated 68 hpf xanthophores sharing genes (gjb8, pax7a/b, aox5, slc2a15a/b); genes for PNS derivatives appeared only at post-migratory 48/68 hpf stages, indicating NCCs delay neuronal differentiation until after migration.
- qHCR confirmed co-expression of slc2a15b and gjb8 with aox5 in pre-migratory/early-migrating dorsal neural tube tNCCs, and fgf13a/cxcr4b in HNK-1+ RB neurons.
- In prdm1a-/- mutants, dorsal neural tube expression of slc2a15b, gjb8, fgf13a, and cxcr4b was lost (while non-NCC/RB expression persisted), placing these genes downstream of the neural-plate-border specifier Prdm1a.

---

## Perspective

The study provides evidence that some zebrafish trunk NCCs initiate lineage-specific (xanthophore) gene regulatory networks prior to migration, extending classical lineage-restriction cell-labeling studies and aligning with recent mouse/chick scRNA-seq work that challenges purely environment-driven, bifurcating models of NCC fate. It also delivers a set of novel candidate markers (slc2a15b, gjb8, fgf13a/b, cxcr4b, pou4f4) for xanthoblast and Rohon-Beard neuron lineages and reinforces the developmental similarity/shared neural-plate-border origin of NCCs and RBs. Limitations noted by the authors include the relatively small sample size (607 cells) and single sampled stage, which limit detection of multi-fate/co-expressing cells and of putative "leader/trailblazer" migratory cells; whether the pre-migratory pigment cells are truly fate-restricted was not functionally tested. Future work sampling earlier stages, functional tests of candidate genes, and comparison to non-vertebrate chordate motor neurons (to address RB homology/evolution) are proposed.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
