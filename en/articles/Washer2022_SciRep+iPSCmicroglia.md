---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
---

# Single-cell transcriptomics defines an improved, validated monoculture protocol for differentiation of human iPSC to microglia

## Citation (NLM)
Washer SJ, Perez-Alcantara M, Chen Y, Steer J, James WS, Trynka G, Bassett AR, Cowley SA. Single-cell transcriptomics defines an improved, validated monoculture protocol for differentiation of human iPSC to microglia. Sci Rep. 2022;12:19454. doi:10.1038/s41598-022-23477-2

**DOI:** [https://doi.org/10.1038/s41598-022-23477-2](https://doi.org/10.1038/s41598-022-23477-2)

---

## Background

Microglia are the resident macrophages of the brain parenchyma, responsible for homeostatic functions including clearance of apoptotic cells and misfolded proteins and synaptic pruning during neurodevelopment. They are genetically implicated in several neurodegenerative disorders (Alzheimer's, Parkinson's, and motor neuron disease/ALS), with many high-risk genes (TREM2, CD33, APOE, LRRK2, C9orf72) expressed in microglia. Because fresh primary human microglia are difficult to access and rodent microglia differ from human, human induced pluripotent stem cell (iPSC)-derived microglia have become a key in vitro model.

Numerous iPSC-to-microglia protocols exist but use divergent combinations of growth factors and media supplements (IL-34, TGF-β1, M-CSF, GM-CSF, CD200, CX3CR1, B27, N-2) and substrates, often adopting components from earlier protocols without systematic testing, and many require co-culture, organoid integration, or xenotransplantation. This study systematically dissects which medium components, growth factors, and coatings are actually essential to generate transcriptionally and functionally authentic microglia in monoculture, building on the Haenseler et al. (2017) protocol (which was optimized for neuronal co-culture), and validates results across two independent laboratories.

---

## Key Experiment Methods

1. iPSC differentiation to primitive macrophage/microglia precursors (PreMac) via embryoid bodies (BMP4/VEGF/SCF), hemogenic endothelium, and bulk myeloid "Factory" differentiation (IL-3/M-CSF); three healthy-donor lines (KOLF2.1S, SFC841, SFC856) plus 19 pooled HipSci lines.
2. Systematic triage of 15 maturation-medium combinations of single-letter-coded factors: I (IL-34), T (TGF-β1), M (M-CSF), G (GM-CSF), C (CD200/CX3CL1), B (β-mercaptoethanol), N (N-2), F (FBS); Haenseler IGBN medium as baseline.
3. Comparison of tissue-culture substrates: TC-treated plastic, Geltrex, and fibronectin coating.
4. qPCR panels of microglial identity markers and perivascular macrophage markers (F13A1, LYVE1, COLEC12, CD163), with GeNorm housekeeper selection and Bonferroni correction.
5. Single-cell RNA-seq (10x Genomics 5' v2; Seurat, SCTransform, UMAP; donor demultiplexing with cellSNP-lite/Vireo) on six media conditions, with singleR label transfer against fetal macrophage precursor and mouse-xenograft iPSC-microglia reference datasets, plus PCA against external bulk/pseudobulk datasets.
6. Functional phagocytosis assays with three cargoes: fluorescent amyloid-β aggregates, AF488-labeled silica beads, and a novel double-fluorescent (mCherry-eGFP) SH-SY5Y neuroblastoma reporter line for efferocytosis/phagolysosomal acidification.
7. Cross-lab validation using shared iPSC lines, basal media, growth factors, and reagent suppliers.

---

## Results

- Of the initial 15 media, IL-34 alone was insufficient for microglial survival; co-supplementation with low-dose GM-CSF (IG) or with M-CSF supported survival. Removal of N-2 and/or β-mercaptoethanol had no effect on microglial morphology, survival, or gene expression, confirming these are neuron-support components redundant in monoculture. CX3CL1/CD200 addition had no transcriptional or morphological effect; FBS was detrimental (induced fibroblast expansion).
- TGF-β1 was the key driver of microglial identity: it downregulated perivascular macrophage markers (F13A1/LYVE1/COLEC12) and upregulated microglial genes (CX3CR1, MERTK, OLFML3, P2RY12). M-CSF (replacing GM-CSF) promoted a more macrophage-like identity with weaker microglial signal than TGF-β1.
- Medium composition, not substrate coating, was the dominant driver of transcriptional clustering, though microglial identity genes were enhanced when cells were cultured on a matrix (fibronectin/Geltrex).
- Co-supplementation of TGF-β1 with M-CSF (ITM) gave the strongest microglial identity signal but caused poor adherence and reduced retention/reproducibility. Adding low-dose GM-CSF (ITMG) restored cell retention and yield while maintaining microglial identity.
- scRNA-seq and singleR label transfer confirmed that TGF-β1-containing media (ITM ADMEM, ITMG) produced cells most classified as microglia/microglial precursors with fewest perivascular macrophages; ITMG and ITM ADMEM had the highest transcriptomic similarity and most differentially expressed genes vs. baseline IGBN.
- The optimized defined medium ITMG (IL-34 + TGF-β1 + M-CSF + low-dose GM-CSF) was selected for its combination of microglial-like transcriptome, improved survival/retention, and cross-differentiation reproducibility.
- Functionally, ITMG-matured microglia were phagocytically competent, taking up amyloid-β aggregates, silica beads, and dead SH-SY5Y neurons (with phagolysosomal acidification) comparably to the baseline IGBN medium.

---

## Perspective

This work provides a systematically validated, defined monoculture medium (ITMG) for generating human iPSC-microglia that are transcriptionally close to primary/xenografted microglia and phagocytically functional, without the need for neuronal co-culture or xenotransplantation. By showing that several long-adopted components (N-2, β-mercaptoethanol, CX3CL1/CD200) are redundant and that TGF-β1 is the pivotal identity driver, the study rationalizes and simplifies microglial differentiation and improves scalability for disease modeling and drug/phenotypic screening in neuroinflammation and neurodegeneration.

Limitations include reliance on a small number of healthy-donor iPSC lines and a defined marker panel, and the monoculture context lacks the neuronal, astrocytic, and vascular cues of the in vivo CNS niche—so ITMG microglia, while improved, remain an approximation of the fully mature in vivo state. The relevance to spinal cord/CNS regeneration lies in providing a reproducible source of authentic human microglia, the innate immune cells central to CNS injury response, neuroinflammation, and repair. Future directions noted include applying the protocol across disease genotypes and integrating it into more complex multicellular or organoid systems.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
