---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
---

# Cell type prioritization in single-cell data

## Citation (NLM)
Skinnider MA, Squair JW, Kathe C, Anderson MA, Gautier M, Matson KJE, Milano M, Hutson TH, Barraud Q, Phillips AA, Foster LJ, La Manno G, Levine AJ, Courtine G. Cell type prioritization in single-cell data. Nat Biotechnol. 2021;39(1):30-34. doi:10.1038/s41587-020-0605-1

**DOI:** [https://doi.org/10.1038/s41587-020-0605-1](https://doi.org/10.1038/s41587-020-0605-1)

---

## Background

Single-cell technologies have shifted from atlasing healthy tissues to delineating cell-type-specific responses to disease and experimental perturbation. This shift requires resolving subtle phenotypic alterations *within* cell types, rather than cataloguing differences *between* them. Existing tools focus on identifying individual differentially expressed (DE) genes or proteins, which is ill-suited to the broader question of *which cell types* are most responsive to a perturbation in high-dimensional single-cell space.

The authors introduce Augur, a machine-learning method to prioritize the cell types most responsive to a biological perturbation. As a flagship biological application, they use Augur to expose the spinal cord neuron subtypes recruited by targeted epidural spinal stimulation (TESS), a neurotechnology shown to restore walking after spinal cord injury (SCI). The neural circuits engaged by this treatment had remained unknown, motivating a single-nucleus transcriptomic dissection of the injured lumbar spinal cord.

---

## Key Experiment Methods

1. **Augur algorithm**: For each cell type, a random forest classifier is trained to predict experimental condition (e.g., treatment vs control) from single-cell measurements; separability is quantified by cross-validation area under the ROC curve (AUC). Cell types are ranked by AUC. Repeated subsampling (default 50 subsamples of 20 cells per condition) removes the confound of unequal cell-type abundance.
2. **Validation**: Tested on simulated scRNA-seq (Splatter), a compendium of 22 published scRNA-seq datasets, chromatin accessibility (scATAC-seq), and imaging transcriptomics (STARmap, MERFISH); compared against six DE-based prioritization tests (t-test, Wilcoxon, likelihood ratio, logistic regression, MAST, negative binomial). Ground-truth benchmarks included LPS dose-response and FACS-purified microarray/bulk RNA-seq gold standards.
3. **RNA velocity mode**: Applied Augur to transcriptome dynamics to prioritize cell types undergoing acute transcriptional responses.
4. **SCI/TESS experiment**: Mice received a severe T8 contusion causing permanent bilateral leg paralysis. With serotonergic (5HT) and D1 agonists, TESS of lumbar segments enabled immediate walking. Single-nucleus RNA-seq of 18,514 nuclei was performed from mice walking 30 min with TESS (n=3) vs paralyzed controls (n=3), 6 weeks post-injury.
5. **Circuit identification**: 6,035 neurons subclustered into 38 neuron subtypes; Augur applied to RNA velocity to prioritize acutely engaged subtypes. Validated by immediate early gene (Fos) expression, RNAscope in situ hybridization, and monosynaptic anterograde viral tracing in Vsx2-Cre mice.

---

## Results

- Subsampling abolished the dependence of AUC on the number of cells, whereas DE-based methods were strongly biased toward abundant cell types (e.g., DE methods incorrectly flagged oligodendrocytes as most perturbed in Alzheimer's disease due to their abundance).
- Augur AUCs scaled monotonically with both the proportion and magnitude of simulated DE, and remained accurate (r ≥ 0.95) regardless of cell-type distribution, while DE methods degraded rapidly with uneven proportions.
- Augur matched ground-truth benchmarks: LPS dose-response across 4 species, interferon FACS gold standard (r=0.98), reproducibility across two Alzheimer's studies (neurons and endothelial cells prioritized), and cross-modality consistency (scRNA-seq vs STARmap; scATAC-seq vs bulk RNA-seq).
- In the SCI/TESS experiment, single-nucleus RNA-seq resolved all 6 major lumbar spinal cord cell types and 38 neuron subtypes.
- Augur (applied to RNA velocity) robustly prioritized V2a and V1/V2b interneurons — subtypes known to receive proprioceptive afferent synapses and to control left-right (V2a) and flexor-extensor (V2b) alternation — plus Spp1-positive neurons associated with motor neurons.
- Immediate early gene induction (Fos) in V2a and V1/V2b interneurons, confirmed by RNAscope, verified their activation during TESS-enabled walking; non-prioritized interneurons showed minimal Fos. Viral tracing showed dense projections from prioritized interneurons onto motor neurons.
- Augur is computationally efficient (~49.7 min, 2.3 GB RAM for 22 datasets), scales to millions of cells, is robust to sequencing depth, batch effects, and hyperparameters, and works with 3' and full-length protocols. Available as an R package (github.com/neurorestore/Augur).

---

## Perspective

Augur provides a principled, modality-agnostic method to rank cell types by their molecular responsiveness to perturbation, overcoming the abundance bias inherent to DE-gene-counting approaches. Its application to the injured spinal cord is directly relevant to SCI repair: it identified the specific interneuron subtypes (V2a, V1/V2b) that mediate TESS-enabled locomotion after paralysis, linking single-cell transcriptomic states to functional circuit recruitment. A stated limitation is that cell-type-level inference aggregates continuous gradients of response intensity within cell populations. By pinpointing cell types underlying organism-level phenotypes, Augur can guide downstream causal experiments (e.g., choice of Cre lines or FACS gates) and, in the SCI context, help define therapeutic targets for neurostimulation-based recovery.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
