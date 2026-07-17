---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# Genomic Rewiring of SOX2 Chromatin Interaction Network during Differentiation of ESCs to Postmitotic Neurons

## Citation (NLM)
Bunina D, Abazova N, Diaz N, Noh KM, Krijgsveld J, Zaugg JB. Genomic Rewiring of SOX2 Chromatin Interaction Network during Differentiation of ESCs to Postmitotic Neurons. Cell Syst. 2020;10(6):480-494. doi:10.1016/j.cels.2020.05.003

**DOI:** [https://doi.org/10.1016/j.cels.2020.05.003](https://doi.org/10.1016/j.cels.2020.05.003)

---

## Background

Cellular differentiation requires coordinated changes in chromatin organization, transcription, and protein production. Cell-type-specific gene expression is driven by transcription factors (TFs) through gene regulatory networks, and TF binding is modulated by chromatin accessibility, histone modifications, and the availability of interaction partners. To understand differentiation at the molecular level, one must resolve not only each regulatory layer but also the interplay among them.

Most prior studies of neuronal differentiation profiled only one or two regulatory layers, and protein-chromatin association (ChIP-seq) is typically measured for a limited set of factors, ignoring interaction partners that modulate TF activity. Although interactomes of pluripotency TFs (OCT4, SOX2, NANOG) have been characterized, they provided no direct evidence of functional interaction on chromatin. Here the authors apply a hypothesis-free, multi-omic approach—proteome, transcriptome, and chromatin accessibility—across differentiation of mouse ESCs to postmitotic glutamatergic neurons to uncover general principles of regulatory rewiring, focusing on SOX2.

---

## Key Experiment Methods

1. Differentiation of mouse ESCs to postmitotic glutamatergic neurons (Bibel protocol; ~84-88% neurons by day 10), sampling ESCs (day 0), exit from pluripotency (day 2-4, LiF removal), neural progenitors (day 6-8, retinoic acid), and mature neurons (day 10-12).
2. ATAC-seq (chromatin accessibility), RNA-seq (transcriptome), and TMT-labeled LC-MS proteomics at multiple time points; verification of neuronal purity by absence of contaminant markers.
3. Multi-Omics Factor Analysis (MOFA) to infer latent factors; k-means clustering of RNA/protein log2 fold changes; Fisher's exact tests for cross-layer and cross-time associations.
4. diffTF to estimate differential TF activity from aggregate chromatin accessibility at binding sites; TF footprinting.
5. SOX2 ChIP-seq at day 0 and day 10 (combined with published ESC datasets); integration with public histone marks (H3K4me1/3, H3K27ac, H3K36me3, H3K27me3, H3K9me3) to classify SOX2-bound regulatory groups; differential binding and motif analysis.
6. SOX2 ChIP-SICAP (selective isolation of chromatin-associated proteins) and ChIP-MS to define the chromatin-bound SOX2 protein interactome in ESCs vs. neurons.
7. Integration with public ChIP-seq (ChIP-Atlas) for co-occupancy analysis; CRISPR validation of SOX2/ATRX function at three genomic loci.

---

## Results

- MOFA identified three latent factors: LF1 (shared across all three layers) separated early from late differentiation; LF2 captured RNA changes (progenitor-to-neuron, synapse/action potential/cell cycle); LF3 captured early ATAC changes.
- Nearly all ATAC peaks (111,200/117,852) and genes (15,645/18,877) were differential in at least one comparison, but only 440 proteins (<10%) were differentially expressed. RNA and protein showed concerted dynamics; promoter accessibility was largely uncorrelated with expression (many promoters accessible long before gene induction), while intragenic/enhancer elements were highly dynamic.
- Cross-time associations: chromatin changes occurred early while transcriptome/proteome changes increased toward the final progenitor-to-neuron step; accessibility at day 4 was coupled to RNA at day 8, and RNA patterns established at exit of pluripotency/neuronal induction coupled to protein expression at the following stage.
- diffTF found 296 TFs significantly changing activity; a "neuronal TF" group (e.g., SOX5, EBF1) increased and a "pluripotency TF" group (e.g., MYC, NRF1) decreased. Known repressors Zeb1 and Msx1 showed anticorrelation of activity and expression.
- SOX2 was a notable exception: its motif was enriched in neuronal-cluster promoters, yet diffTF activity and RNA declined during differentiation (consistent with pluripotency role with NANOG/OCT4). Unlike OCT4 (which disappeared at exit of pluripotency), SOX2 protein remained highly expressed in postmitotic neurons.
- SOX2 relocated from ESC enhancers to neuronal promoters: of 14,362 SOX2 peaks, ESC-specific peaks were enriched for OCT4:SOX2 motif and distal/intronic elements; neuron-specific peaks were enriched for HOX and ARID3B motifs, located at promoters, and near "neuron fate commitment"/"forebrain development" genes. SOX2 bound only regions already accessible in ESCs, indicating it is not a pioneer factor in neurons.
- ChIP-SICAP identified 92 (ESC) and 105 (neuron) chromatin-associated SOX2 interactors (57 shared), enriched for TFs, coTFs, and epigenetic remodelers. OCT4/SALL4/RIF1 were ESC-specific; neuronal interactors included FABP7, TOP2B, CTBP2. A stem cell-to-neuronal factor transition was observed (e.g., TRIM28 ESC-preferring; ADNP, MYEF2 neuron-preferring), with association changes largely tracking protein expression (R=0.7).
- Co-occupancy analysis: most ESC SOX2 peaks were co-bound by another TF (OCT4 98%, KDM1A 79%, SMAD2 68%, SALL4 59%, etc.); in neurons only ATRX (49%) and KDM1A (46%) substantially overlapped, and only ATRX interacted with SOX2 on chromatin (ChIP-SICAP), making ATRX the major direct chromatin-associated SOX2 interactor in neurons. SOX2-ATRX co-binding correlated with increased active enhancer marks and higher expression of nearby genes, validated at three loci by CRISPR.

---

## Perspective

This study demonstrates the value of integrated multi-omics (transcriptome, proteome, chromatin accessibility) for dissecting gene regulation during neuronal differentiation, revealing that the pluripotency factor SOX2 is genomically "rewired"—relocating from OCT4-co-bound ESC enhancers to neuronal promoters—driven by a shift in its chromatin-bound protein interactome from pluripotency factors to the chromatin remodeler ATRX. The finding that SOX2 binds only pre-accessible regions in neurons (non-pioneer) and that SOX2-ATRX co-binding activates neuronal genes provides mechanistic insight into how a single TF acquires divergent, cell-state-specific functions.

Relevance to the knowledgebase lies in the neuronal differentiation paradigm and SOX2's role in neurodevelopment (forebrain, dorsal spinal cord development among enriched GO terms). Limitations include the small number of TFs quantified by proteomics (43 of 352, necessitating diffTF inference), reliance on public ChIP-seq for co-occupancy (data available for only a subset of interactors), functional validation limited to three CRISPR loci, and the use of an in vitro glutamatergic neuron model rather than in vivo spinal/brain tissue. Broader mapping of interactor genomic localization and in vivo confirmation are future directions.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
