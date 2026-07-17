---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Emergence of Neuronal Diversity during Vertebrate Brain Development

## Citation (NLM)
Raj B, Farrell JA, Liu J, El Kholtei J, Carte AN, Navajas Acedo J, Du LY, McKenna A, Relić Đ, Leslie JM, Schier AF. Emergence of Neuronal Diversity during Vertebrate Brain Development. Neuron. 2020;108(6):1058-1074. doi:10.1016/j.neuron.2020.09.023

**DOI:** [https://doi.org/10.1016/j.neuron.2020.09.023](https://doi.org/10.1016/j.neuron.2020.09.023)

---

## Background
The vertebrate brain develops from a limited pool of embryonic neural progenitor cells that cycle through rounds of proliferation, diversification, and terminal differentiation into an extensive catalog of neuronal and glial cell types. A central goal in developmental neurobiology is to understand how neuronal complexity arises through molecular specification and commitment. Classic approaches (genetic markers, perturbations, fate mapping) have recently been complemented by single-cell genomics in the developing nervous system, including spinal cord, cortex, olfactory system, cerebellum, and retina.

However, existing datasets are limited: they focus on specific brain regions, survey few time points, or do not enrich for neural cell types, thereby missing transitions and cellular diversity. This work addresses the need for a large-scale neurodevelopmental single-cell resource profiling whole-brain development across closely spaced embryonic and post-embryonic stages, and asks how embryonic neural progenitors are molecularly related to post-embryonic progenitors.

---

## Key Experiment Methods
1. Single-cell RNA-seq (10X Genomics Chromium) of 223,037 cells (~220,000 reported) across 12 stages of zebrafish development, from 12 hours post fertilization (hpf) to 15 days post fertilization (dpf).
2. Tissue enrichment: dissection of whole heads from 12 hpf to 3 dpf, and brains + eyes specifically from 5 dpf to 15 dpf, to enrich for brain cell types.
3. Per-stage Louvain clustering identifying 815 clusters across all 12 time points; cluster classification by comparison of enriched markers with ZFIN database annotations and literature.
4. In situ hybridization and smFISH validation of novel markers (e.g., sdpra/cavin2a in trigeminal placode, sox1a in hypothalamus, ompa in retinal horizontal cells).
5. An optimized scGESTALT CRISPR-Cas9 lineage recorder with improved barcode expression and recovery to query early lineage segregation.
6. Reconstruction of cell specification trajectories (retina, hypothalamus) and comparison of early versus late neural progenitor landscapes.

---

## Results
- Generated a developmental single-cell catalog of ~220,000 zebrafish brain/head cells across 12 stages, characterizing known and novel markers for ~800 clusters.
- Cell type complexity increased with developmental time; clusters corresponded to neural progenitors (sox19a), dozens of neuron subtypes (elavl3, gad2, slc17a6b), eye cells, radial glia (mfge8a, s100b), neural crest (sox10), oligodendrocytes (mbpa), blood, cartilage, pharyngeal arches, sensory placodes, and epidermal cells.
- A subsetted neural dataset diversified from an initial 21 clusters at 12 hpf to 98 clusters by 15 dpf; most clusters could be uniquely identified by minimal sets of 2-3 markers. Cycling progenitors, differentiating progenitors, and newborn neurons could not be unambiguously separated by minimal marker sets due to shared pan-neuronal/pan-progenitor signatures.
- Early brain regions established by 12 hpf expand and diversify: e.g., a single optic vesicle cluster becomes 18 retinal cell types, and a single ventral diencephalon cluster becomes 7 hypothalamus cell types by 15 dpf; an exception is loss of hindbrain rhombomeres (r1-r7).
- Most embryonic neural progenitor states are transitory and transcriptionally distinct from post-embryonic progenitors; late larval progenitor states are maintained as distinct.
- 68% (5 dpf) and 74% (8 dpf) of 15 dpf neuron clusters had closely matching counterparts at earlier larval stages, relevant to behavioral studies.
- Trajectory reconstruction revealed that late-stage retinal neural progenitors transcriptionally overlap cell states observed in the embryo, revealing gene expression cascades and distinct specification programs.

---

## Perspective
This NeuroResource provides a large-scale, temporally dense single-cell atlas of vertebrate (zebrafish) brain development at unprecedented scale and resolution, laying a foundation for detailed analysis of neuronal diversification. It defines and enables manipulation of specific neuron subsets and clarifies the poorly understood relationship between embryonic and post-embryonic neural progenitors, showing that many embryonic progenitor states are transitory. The optimized scGESTALT lineage recorder extends lineage-tracing capability. Limitations include the inability of minimal marker sets to resolve closely related progenitor/newborn-neuron states, and sampling constraints across time points. As a comparative regeneration/development resource, the atlas is directly relevant to understanding CNS neurogenesis and to informing strategies to manipulate neural cell fates.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
