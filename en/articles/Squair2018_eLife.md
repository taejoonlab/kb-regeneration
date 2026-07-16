---
tags: [2026-07]
extract: 2026-07-16
---

# Integrated systems analysis reveals conserved gene networks underlying response to spinal cord injury

## Citation (NLM)
Squair JW, Tigchelaar S, Moon KM, Liu J, Tetzlaff W, Kwon BK, Krassioukov AV, West CR, Foster LJ, Skinnider MA. Integrated systems analysis reveals conserved gene networks underlying response to spinal cord injury. eLife. 2018;7:e39188. doi:10.7554/eLife.39188

**DOI:** [https://doi.org/10.7554/eLife.39188](https://doi.org/10.7554/eLife.39188)

---

## Background

Spinal cord injury (SCI) is a devastating neurological condition with no effective treatments to restore function; hemodynamic management and surgical decompression give only marginal benefit. A central obstacle is the fragmentary understanding of the coordinated pathophysiological processes triggered by CNS injury — the immune response, multiple forms of cell death, neuronal growth suppression, and inhibitory glial scar formation — which are rarely studied in an integrated manner.

Decades of small-scale experiments have implicated individual genes, but with high false-positive and false-negative rates and experimental biases. This study applies a systems biology approach to integrate the curated SCI literature with unbiased, genome-wide expression data from the human spinal cord, aiming to reveal a gene regulatory network signature of the SCI response and to nominate biomarkers of injury severity and functional recovery.

---

## Key Experiment Methods

1. Systematic literature review of >500 (556) SCI manuscripts, curating a set of 695 unique human genes implicated by small-scale experiments (mapping rat/mouse/rabbit genes to human orthologs via seven databases with majority voting).
2. Validation of literature-curated (LC) genes via shared Gene Ontology terms, protein-protein interactions and largest connected component in multiple human interactomes, protein-complex co-membership, and recovery by the DIAMOnD disease-gene prediction algorithm.
3. Weighted gene coexpression network analysis (WGCNA) of RNA-seq from 71 post-mortem human spinal cords (GTEx), yielding 15 modules; reproducibility tested in an independent microarray dataset (n=33) and conservation in mouse (n=414) and rat (n=267) via Zsummary.
4. Enrichment testing of LC genes within modules (Fisher's exact test), with robustness checks (seed removal, random gene addition).
5. Meta-analysis of five mouse/rat SCI transcriptomic datasets for consensus module differential expression, including acute/subacute/chronic time points.
6. Functional/cell-type characterization via GO, MSigDB enrichment maps, and meta-analysis of CNS cell-type transcriptomic/proteomic profiles (including single-cell data).
7. Prospective validation: contusion SCI (T10) in rats (moderate/severe/sham, n=5/group) with RNA-seq and quantitative proteomics of spinal cord; biomarker analysis of M3 hub genes.
8. Reanalysis of neurotrophin-3 (NT-3) treatment and STAT3 knockout datasets to test module reversal with recovery.

---

## Results

- Literature curation yielded 695 SCI-associated genes (559 upregulated, 213 downregulated, 8 differentially phosphorylated); LC genes were functionally coherent, sharing GO terms, forming enriched PPIs and a larger-than-random connected component, and were preferentially recovered by DIAMOnD.
- WGCNA of human spinal cord gave 15 modules; five (M2, M3, M7, M8, M12) were most reproducible and most conserved in mouse and rat, indicating the spinal cord transcriptome architecture is substantially conserved across species.
- Two modules, M3 and M7, were significantly and robustly enriched for LC SCI genes; their eigengenes were highly correlated and they clustered together.
- Meta-analysis identified consensus upregulated modules (M3, M6, M7, M11) and downregulated modules (M1, M2) after SCI; M2, M3, M7 showed the strongest differential expression. M9 was downregulated acutely but upregulated chronically, implicating it in the acute-to-chronic transition.
- Cell-type characterization: M1 = oligodendrocyte (myelination), M2 = neuronal (synaptic transmission), M3 = microglia/vascular endothelial (inflammatory response, response to wounding), M7 = microglial (immune response), M9 = astrocyte (oxidation-reduction, CNS development/neurogenesis).
- M3 was the sole module positively correlated with injury severity; its eigengene most strongly tracked severity (mouse ρ=0.79). A prospective rat contusion RNA-seq study reproduced the consensus signature and confirmed severity dependence (ρ=0.94), extending to the proteomic level.
- Six M3 hub genes (Anxa1, Colgalt1, Ifngr2, Shc1, Sod2, Tbc1d2b) stratified rats by severity with >90% accuracy; annexin A1 (Anxa1) discriminated moderate vs severe injury with perfect (RNA) / 93% (protein) accuracy, consistent with prior SCI biomarker reports.
- Treatments promoting recovery reversed the signature: NT-3 downregulated M3 (and upregulated neurogenesis-associated M9), and STAT3 knockout (which increases axonal dieback) showed opposite module regulation, highlighting M3 as a predictor of functional recovery.

---

## Perspective

This study provides a systems-level, evolutionarily conserved map of the coordinated molecular response to spinal cord injury by integrating decades of small-scale literature with genome-wide human spinal cord coexpression networks and validating in independent rodent transcriptomic and proteomic data. Its central contribution is the identification of a conserved, reproducible microglia/inflammation-associated module (M3) whose expression scales with injury severity and reverses with recovery-promoting treatments, nominating M3 hub genes — especially annexin A1 — as candidate objective biomarkers of SCI severity, which could address the reliance of clinical trials on variable neurological assessments. Highly relevant to the knowledgebase's core focus on spinal cord injury and repair. Limitations acknowledged include the assumption that healthy human spinal cord transcriptome organization is informative about traumatic pathophysiology, the possibility that individual genes diverge between human and rodent even where systems-level conservation holds, and the need for human studies to conclusively validate Anxa1 as a severity biomarker.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
