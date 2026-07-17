---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# Transcriptional dynamics of tail regeneration in Xenopus tropicalis

## Citation (NLM)
Chang J, Baker J, Wills A. Transcriptional dynamics of tail regeneration in Xenopus tropicalis. Genesis. 2017;55(1-2):e23015. doi:10.1002/dvg.23015

**DOI:** [https://doi.org/10.1002/dvg.23015](https://doi.org/10.1002/dvg.23015)

---

## Background

Unlike mammals, many amphibians rapidly and completely regenerate complex tissues, including whole appendages. After tail amputation, Xenopus tropicalis tadpoles regenerate muscle, spinal cord, cartilage, vasculature, and skin, all correctly patterned in three dimensions within days. X. tropicalis is a powerful regeneration model because it has a small, fully sequenced diploid genome, produces large clutches, and loses regenerative competence at metamorphosis, allowing molecular hallmarks of regeneration to be identified.

Prior work showed that tail regeneration requires temporally regulated developmental signaling (FGF, Wnt, BMP, Notch, Shh, Hox) together with stress responses including membrane-potential changes, apoptosis, reactive oxygen species, and innate immune recruitment. To integrate these processes over time, the authors performed a time-resolved RNA-Seq analysis of the first 72 hours of tail regeneration.

---

## Key Experiment Methods

1. Stage 41 X. tropicalis tadpoles were anesthetized and tail tips amputated at roughly half the distance from tail tip to anus.
2. Regenerating tissue (250 um adjoining the amputation plane, including all new tissue) was collected at 0, 6, 15, 24, and 72 hours post amputation (hpa), with independent clutches as biological replicates.
3. RNA was isolated and TruSeq libraries were sequenced on the Illumina HiSeq platform (20-150 million reads per library).
4. Reads were mapped to the Xentr9.0 genome (Tophat), counted with HTSeq, and analyzed for differential expression across all pairwise time-point comparisons with DESeq2 (FDR < 0.05).
5. Fuzzy c-means clustering (FANNY, R cluster package) with a gap-statistic-selected number of groups was applied after regularized-log transformation to identify covariant temporal expression patterns.
6. Gene ontology enrichment (EnrichR) was used to functionally annotate each temporal cluster.

---

## Results

- Of 18,396 gene models in the current X. tropicalis annotation, 3,897 were differentially expressed between at least two time points.
- Fuzzy c-means clustering resolved 8 dominant temporal expression patterns comprising 1,942 unique genes (~50% of differentially expressed genes).
- The predominant early pattern (Cluster IV, peak at 6 hpa) was enriched for cell movement/communication, most strongly "microtubule-based process" (dyneins, kinesins, tubulins, MAP1B/MAP1A, RACGAP1, ARMC4) plus "neurotransmitter transport" and "synapse organization," suggesting neuronal-type cellular communication machinery is upregulated earlier than previously known.
- Shortly after (Cluster III), pattern-specification and developmental signaling genes (axis specification, anterior-posterior patterning, endoderm development) emerge following an initial wave of wound healing and cellular reorganization.
- Reactive oxygen species and innate immune activity peaked at 15 hpa (Cluster VI), which also unexpectedly enriched for ncRNA and rRNA processing, hinting at a broader regulatory role for RNA metabolism in regeneration.
- Clusters I/II contained genes highly expressed at 0 hpa then downregulated (enriched for ionic transport and lipid biosynthesis); Clusters VII/VIII showed late (72 hpa) prioritization of innate immune and wound-response signaling, including myeloid transcription factors Spi1 and SpiB.
- Nearly all hox genes (anterior, medial, posterior across all four clusters) were significantly upregulated at 15 or 24 hpa, consistent with known roles of posterior Hox genes in appendage regeneration.

---

## Perspective

This transcriptome time course provides a fine-grained temporal map of tail regeneration in X. tropicalis and a deep resource for the regeneration community, refining the windows during which patterning signals, bioelectrical/ROS signaling, apoptosis, and immune responses act. A notable new finding is the early (6 hpa) enrichment of cytoskeletal and neuronal communication machinery, and a suggested regulatory role for RNA processing/non-coding RNAs. As a Letter, the study is descriptive and hypothesis-generating: it does not include functional validation, uses whole-tissue (not cell-type-resolved) profiling, and lacks replicates at the 6 and 15 hpa points. The identified candidate factors and temporal clusters point to specific avenues for future mechanistic study of regenerative competence, including spinal cord regrowth within the regenerating tail.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
