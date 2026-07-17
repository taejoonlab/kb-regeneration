---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
raw_data:
  - "GEO: GSE172207"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Cross-species analysis defines the conservation of anatomically segregated VMH neuron populations

## Citation (NLM)
Affinati AH, Sabatini PV, True C, Tomlinson AJ, Kirigiti M, Lindsley SR, Li C, Olson DP, Kievit P, Myers MG, Rupp AC. Cross-species analysis defines the conservation of anatomically segregated VMH neuron populations. eLife. 2021;10:e69065. doi:10.7554/eLife.69065

**DOI:** [https://doi.org/10.7554/eLife.69065](https://doi.org/10.7554/eLife.69065)

---

## Background

The ventromedial hypothalamic nucleus (VMH), composed predominantly of glutamatergic neurons, controls diverse behaviors and physiologic functions (panic, reproduction, aggression, glucose homeostasis, energy expenditure). Its anatomic subdivisions (dorsomedial VMHDM, central VMHC, ventrolateral VMHVL) each mediate multiple outputs, implying the existence of multiple functionally distinct neuron subtypes. Most prior functional studies relied on the marker Nr5a1 (SF1) or single candidate genes that do not necessarily align with transcriptionally distinct cell types.

To define the VMH cellular landscape in an unbiased and genetically tractable manner, and to test its conservation across species, the authors combined translating ribosome affinity purification with RNA-sequencing (TRAP-seq) and single-nucleus RNA-sequencing (snRNA-seq) in mouse, adding snRNA-seq of macaque VMH for cross-species comparison.

---

## Key Experiment Methods

1. snRNA-seq (10X Genomics) of microdissected mouse VMH (10 samples; ~42,040 QC-passed nuclei; 21,585 neurons in 37 populations).
2. Nr5a1-Cre;Rosa26eGFP-L10a TRAP-seq to define a broad VMH-enriched transcriptome (4492 enriched transcripts) and identify VMH clusters; comparison to snRNA-seq "pseudo-TRAP".
3. Iterative subclustering of VMH neurons into 24 populations, then hierarchical clustering with CELLEX marker analysis and silhouette/correlation metrics to define a simplified 6-class scheme.
4. Intersectional Lepr-directed TRAP-seq (Slc17a6Flpo;LeprCre;RCFLeGFP-L10a) to isolate glutamatergic Lepr-expressing VMH neurons and confirm the VMHLepr class.
5. Macaque (Macaca mulatta) VMH snRNA-seq and cross-species integration (Seurat CCA/anchors), plus validation by Allen Brain Atlas ISH and RNAScope ISH (Acvr1c, Slc17a8, Lepr).

---

## Results

- Combining Nr5a1-Cre TRAP-seq with snRNA-seq identified six neuron populations containing VMH neurons; Nr5a1-negative clusters were still identified as VMH by developmental Nr5a1-Cre labeling (presumptive VMHVL).
- TRAP-seq and snRNA-seq (pseudo-TRAP) were largely concordant but each captured method-specific transcripts; enrichment was largely a function of expression level.
- Subclustering yielded 24 transcriptionally defined VMH neuron populations that collapsed into six maximally distinct classes with circumscribed anatomic distributions: three dorsomedial (VMHLepr, VMHFezf1, VMHNfib), two ventrolateral (VMHDlk1, VMHEsr1), and one anterolateral "tuberal" glutamatergic class (VMHFoxp2).
- Class-specific markers (Dlk1, Esr1, Nfib, Foxp2, Fezf1, Lepr) map to distinct anatomic compartments; VMHNfib is the most dorsomedial and transcriptionally distinct.
- Intersectional Lepr TRAP-seq confirmed that Lepr-expressing VMH neurons map specifically onto the VMHLepr cluster (top shared genes Gpr149, Rai14, Tnfrsf8), supporting a transcriptionally and functionally unique Lepr class (consistent with prior roles in energy expenditure but not glucose/panic).
- Macaque snRNA-seq yielded seven populations; classes marked by LEPR, FOXP2, NFIB, ESR1 had clear mouse orthologs. A macaque VMHQRFPR population corresponded to the closely related mouse VMHDlk1 and VMHFezf1 classes.
- Mouse-macaque integration showed conserved major VMH classes in gene expression and anatomic distribution; ISH confirmed ACVR1C co-expression with LEPR in macaque VMHDM and SLC17A8 marking of the dorsomedial-most (VMHNFIB-like) cells.

---

## Perspective

This work provides an unbiased, cross-species atlas that reduces the VMH's complex 24 neuron populations to six genetically and anatomically tractable classes conserved between mouse and macaque, offering markers to selectively manipulate and study VMH subtypes. The conservation of a distinct Lepr/LEPR class in rodent and primate supports use of the mouse as a surrogate for studying VMH metabolic function and identifying potential therapeutic targets for obesity and diabetes. Limitations include reliance on transcriptomic correlation for cross-species orthology (some marker genes vary across species, e.g., DLK1/FEZF1 vs QRFPR), a dissection bias that required integrating external VMHVL-focused data (Kim et al.), and the fact that physiologic functions for several newly defined classes (e.g., VMHFoxp2, VMHNfib) remain untested. Future work targeting these classes functionally is needed. Note: within the spinal cord/regeneration knowledgebase this is included as a single-nucleus atlas of the CNS/nervous system, with methodology (TRAP-seq + snRNA-seq integration, cross-species conservation) transferable to neural atlasing more broadly.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE172207

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE93374


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
