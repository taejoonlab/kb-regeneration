---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
---

# Massively Parallel Single Nucleus Transcriptional Profiling Defines Spinal Cord Neurons and Their Activity during Behavior

## Citation (NLM)
Sathyamurthy A, Johnson KR, Matson KJE, Dobrott CI, Li L, Ryba AR, Bergman TB, Kelly MC, Kelley MW, Levine AJ. Massively Parallel Single Nucleus Transcriptional Profiling Defines Spinal Cord Neurons and Their Activity during Behavior. Cell Rep. 2018;22(8):2216-2225. doi:10.1016/j.celrep.2018.02.003

**DOI:** [https://doi.org/10.1016/j.celrep.2018.02.003](https://doi.org/10.1016/j.celrep.2018.02.003)

---

## Background
Understanding the cellular basis of behavior requires knowing which cell types exist in the nervous system and how they contribute to function. Spinal networks are essential for sensory processing and motor behavior, making the spinal cord a powerful system for identifying the cellular correlates of behavior. Although gene expression-based definitions of cell identity have been foundational to spinal cord biology for 30 years, three key limitations remained: there was no comprehensive census of adult spinal cord neuronal cell types, the unique gene expression profiles underlying their functional repertoires were unknown, and there was no unbiased approach to link specific cell types to a given neural function.

To address these gaps, the authors used massively parallel single nucleus RNA sequencing (snRNA-seq) to simultaneously provide a cell-type census of the adult mouse spinal cord and to overlay a map of the transcriptional signature of neuronal activity following behavior. Single nucleus profiling was chosen because it accurately permits cell-type analysis, avoids dissociation-induced transcriptional artifacts, and works with difficult-to-dissociate, frozen, and human biobank tissue.

---

## Key Experiment Methods
1. Adapted droplet-based Drop-Seq for single nuclei by increasing the detergent (sarkosyl) concentration in the lysis buffer, enabling snRNA-seq of the adult mouse lumbar spinal cord.
2. Prepared nuclei using a detergent-based (Triton X-100) sucrose/density-gradient protocol from rapidly dissected lumbar spinal cord (dorsal root ganglia removed).
3. Performed a barnyard (human/mouse mixing) experiment to estimate the doublet rate and confirm single-nucleus encapsulation.
4. Sequenced 17,354 nuclei from adult mouse lumbar spinal cord and used SC3 consensus clustering to identify major cell types and 43 neuronal populations (4,280 neuronal nuclei).
5. Characterized clusters by neurotransmitter status (excitatory, inhibitory, cholinergic markers), Euclidean-based hierarchical clustering, tSNE visualization, GO term analysis, and comparison with public gene expression databases to assign spatial location.
6. Applied snRNA-seq following two behaviors — rotarod locomotion (0 to 40 rpm over 5 min) and formalin hindpaw injection (pain assay) — and used Fos RNA as a transcriptional signature of neuronal activity.
7. Validated cluster-defining markers and behavior-associated activation using immunofluorescence and fluorescent in situ hybridization (including En1:Cre;Ai9 reporter mice).

---

## Results
- Seven major cell-type clusters were identified: neurons (52%), oligodendrocytes (16%), a mixed meningeal/Schwann population (14%), astrocytes (9%), vascular cells (5%), oligodendrocyte precursor cells (1%), and microglia (1%).
- The barnyard experiment showed a calculated doublet rate of 4.1%, confirming that single nuclei can be captured from difficult-to-dissociate and frozen (including human) spinal cord tissue.
- The 4,280 neuronal nuclei partitioned into 43 clusters: 23 predominantly excitatory (including 2 cholinergic), 18 predominantly inhibitory, and 2 mixed. By location, 55% were in 25 dorsal clusters, 34% in 13 ventral clusters, and 11% in 5 deep dorsal/intermediate clusters. Clusters were named by location (D, M, V) and neurotransmitter status (E, I, M, C).
- A major organizing principle emerged: dorsal clusters formed discrete, molecularly distinct groups (an outer ring in tSNE), whereas ventral clusters overlapped and shared markers. This was not a resolution artifact — ventral neurons actually had more genes per nucleus (2,465 ± 202) than dorsal neurons (1,346 ± 33).
- GO analysis showed neurotransmitter receptors/ion channels, transcription factors, and cAMP signaling components were over-represented among cluster-defining genes. Many clusters were partly defined by known markers, but new key genes and previously unrecognized populations were identified (detailed marker sets provided for cluster groups 1-7, e.g., Ebf2/Gabrg3, Sstr2/Grik2, Esrrg/Foxp2, Sox5/Kcnd3).
- Direct nuclei isolation did not induce Fos, but behavior did: Fos was expressed in more nuclei after rotarod (1.6%) or formalin (1.9%) versus baseline (0.48%), with significantly increased expression levels (p < 0.001, ANOVA).
- Locomotion (rotarod) activated ventral clusters VC-1 (Pitx2 V0c neurons), VC-2 (motoneurons), VE-4 (putative V2a), and VI-5 (putative V1/V2b), plus intermediate/dorsal clusters ME-1, MI-1, DE-5, DI-6, and DI-8 — expanding the known set of locomotion-associated neurons.
- Formalin (pain) activated predominantly dorsal clusters DI-2 (Gal, Sstr2), DI-3 (Nos1), DI-4 (Npy), as well as DI-8, DI-9, DE-7, VI-4, VC-1, VC-2, and MI-2, consistent with and extending known pain-responsive populations.

---

## Perspective
This work establishes an atlas of 43 adult mouse lumbar spinal cord neuronal populations, providing a cellular framework that integrates decades of single-marker studies and includes previously unrecognized cell types. The accompanying searchable database of gene expression per cluster is a resource for probing the molecular basis of functional heterogeneity. Conceptually, the study reveals distinct organizing principles between dorsal (discrete, adult marker-defined) and ventral (overlapping, developmentally defined) neuronal identity. By coupling snRNA-seq with behavior, the authors demonstrate an unbiased method to map activity-induced transcription to specific molecularly defined cell types.

Three limitations are noted: (1) fewer genes per nucleus were detected than with some other methods, though sufficient for clustering; (2) only the lumbar cord was characterized, so other segmental levels remain to be profiled; and (3) activity profiling detects only transcriptional responses above a threshold, so negative results must be interpreted cautiously. Because nuclei can be obtained from frozen and human biobank material, this approach can be extended to study disease, injury, degeneration, inflammation, and human biology, linking single nucleus gene expression to circuit- and system-level function.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
