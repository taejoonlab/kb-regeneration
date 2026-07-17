---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
---

# Single nucleus RNA-sequencing defines unexpected diversity of cholinergic neuron types in the adult mouse spinal cord

## Citation (NLM)
Alkaslasi MR, Piccus ZE, Hareendran S, Silberberg H, Chen L, Zhang Y, Petros TJ, Le Pichon CE. Single nucleus RNA-sequencing defines unexpected diversity of cholinergic neuron types in the adult mouse spinal cord. Nat Commun. 2021;12(1):2471. doi:10.1038/s41467-021-22691-2

**DOI:** [https://doi.org/10.1038/s41467-021-22691-2](https://doi.org/10.1038/s41467-021-22691-2)

---

## Background

Motor control in vertebrates relies on cholinergic neurons of the spinal cord, comprising three main types: skeletal motor neurons (MNs), visceral (pre-ganglionic autonomic) motor neurons, and cholinergic interneurons. Although studied for over a century, the full heterogeneity of these neurons and their distinct adult functional roles remained undefined. Defining subtypes is clinically important because motor neuron diseases such as spinal muscular atrophy and ALS selectively affect some MN subtypes (e.g., fast-firing alpha MNs degenerate early while gamma MNs and slow alpha MNs are relatively resistant).

Cholinergic neurons are rare among all spinal cord cells and, together with the large size of motor neurons, have been poorly captured by prior single-cell approaches. The authors developed a targeted single-nucleus RNA-sequencing (snRNAseq) strategy to enrich and comprehensively classify adult mouse spinal cholinergic neurons and build a transcriptomic atlas (available at www.spinalcordatlas.org).

---

## Key Experiment Methods

1. **Genetic labeling and nuclear enrichment**: Chat-IRES-Cre::CAG-Sun1-sfGFP mice permanently mark cholinergic nuclei with a nuclear-envelope-tethered GFP.
2. **Regional dissection**: spinal cords separated into cervical, thoracic, and lumbar/sacral regions and processed separately, with differential barcoding to map cell types along the rostrocaudal axis.
3. **Nuclei isolation and FACS**: density-gradient centrifugation, then fluorescence-activated cell sorting of GFP+/DRAQ5+ singlet nuclei.
4. **snRNAseq**: 10X Genomics Chromium platform, Illumina HiSeq sequencing; 34,231 nuclei characterized, filtered to 16,042 Chat-expressing cholinergic nuclei.
5. **Clustering and marker analysis**: identification of transcriptomic clusters and top markers; sub-clustering of skeletal MNs, alpha MNs, interneurons, and visceral MNs.
6. **Validation**: multiplexed fluorescent in situ hybridization (RNAScope/ISH), immunostaining (SV2B protein), C-bouton/VGLUT1 anatomical criteria, and retrograde tracing (FastBlue) from specific muscles.

---

## Results

- After removing 22 contaminating non-cholinergic clusters (leaky/developmental Cre), 16,042 Chat+ nuclei resolved into **21 transcriptionally distinct subtypes**—far more diversity than previously described. No sex-specific differences were observed.
- **Three main classes** were assigned by markers and location: cholinergic interneurons (Pax2; clusters I1–I8), visceral MNs (Zeb2; V1–V10), and skeletal MNs (S1–S3). **Tns1** emerged as a selective skeletal MN marker (ventral horn, co-expressed with Chat and Prph); **Fbn2** as a general visceral MN marker (including a Zeb2-negative cluster, V8); **Slc6a1** marks a set of interneurons.
- **Skeletal MNs**: S2 (Rbfox3+) = alpha, S3 (Esrrg/Gfra1+) = gamma, and S1 expressing both alpha and gamma markers = possible beta ("Type 3") MNs. Novel specific markers: Sv2b, Stk32a, Glis3 (alpha), Nrp2 (gamma), Gpr149 (Type 3). Sv2b/Stk32a are more restricted and specific than Rbfox3; SV2B validated at protein level.
- **Alpha MN subtypes**: re-clustering yielded 8 subtypes with regional patterning. Cpne4 marks digit-innervating MNs; Erbb4 marks phrenic (diaphragm-innervating) MNs; Grm5 relatively enriched in soleus-projecting MNs—linking transcriptomic identity to muscle target.
- **Cholinergic interneurons**: 8 clusters. Pitx2+ partition cells split into I5 (Tox+) and I6 (Tox−). A rare cluster I8 co-expresses Piezo2 and Reln near the central canal—the surprising expression of the mechanosensitive channel Piezo2 in central cholinergic interneurons.
- **Visceral MNs**: 16 sub-clusters distinguished by transcription factors, neuropeptides (Ccbe1, Sst, Penk), and ECM proteins. Strikingly, visceral MNs were abundant not only in thoracic and lumbar/sacral cord but also in the caudal cervical region (canonically thought devoid of them). Cluster distribution was highly region-specific (e.g., Dach2/Gpc3/Sema5a in C/T; Sst in L/S sacral bladder/bowel pre-ganglionic neurons; Bnc2 only cervical), indicating anatomic-transcriptomic specialization for organ control.

---

## Perspective

This study provides a comprehensive transcriptomic atlas of adult mouse spinal cholinergic neurons, revealing unexpected diversity across all three classes and delivering new, more selective markers (e.g., Tns1 for skeletal MNs; Sv2b/Stk32a for alpha MNs; Fbn2 for visceral MNs). By identifying markers for the diaphragm-innervating (phrenic) alpha MN subtype—whose loss is ultimately fatal in ALS—the work offers tools for studying differential MN vulnerability in degenerative disease and for selectively targeting subsets of motor neurons.

Limitations: subtype assignments (especially alpha/beta/gamma) rest on marker expression and anatomy; definitive characterization of the putative beta ("Type 3") MNs requires electrophysiology, which was not performed. Some embryonic markers were not maintained in the adult. Future directions include electrophysiological correlation of firing properties with transcriptomic subtypes, functional study of Piezo2 in central cholinergic neurons, and exploiting the atlas to dissect cell-type susceptibility in motor neuron disease.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
