---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
---

# Mapping molecular landmarks of human skeletal ontogeny and pluripotent stem cell-derived articular chondrocytes

## Citation (NLM)

Ferguson GB, Van Handel B, Bay M, Fiziev P, Org T, Lee S, Shkhyan R, Banks NW, Scheinberg M, Wu L, Saitta B, Elphingstone J, Larson AN, Riester SM, Pyle AD, Bernthal NM, Mikkola HK, Ernst J, van Wijnen AJ, Bonaguidi M, Evseenko D. Mapping molecular landmarks of human skeletal ontogeny and pluripotent stem cell-derived articular chondrocytes. _Nat Commun._ 2018 Sep 7;9(1):3634. doi: [10.1038/s41467-018-05573-y](https://doi.org/10.1038/s41467-018-05573-y).

---

## Background

Tissue-specific gene expression defines cellular identity and function, but molecular-level knowledge of human early development is limited, hindering cell-based therapeutic applications. In mouse models, Sox9+ skeletal progenitor cells have been reported to differentiate into cartilage, bone, ligament, and tendon, but information on human musculoskeletal development beyond anatomical techniques and key regulatory gene analysis is lacking. Humans and mice differ significantly in growth plate development, tissue thickness, mechanical forces, and regenerative potential, and understanding inter-species transcriptomic and regulatory network differences is essential for advancing regenerative medicine. This study performed transcriptomic analysis of five musculoskeletal cell types (chondrocytes, osteoblasts, myoblasts, ligament cells, tendon cells) from 17-week fetuses and defined tissue-specific gene modules using WGCNA. Additionally, four stages of human chondrogenesis (embryonic 5-6 weeks, fetal 17 weeks, juvenile, adult) and two stages of pluripotent stem cell (PSC)-derived chondrocytes (d14, d60) were compared to elucidate the transcriptomic and epigenomic features of cartilage specification and maturation, and to identify functionally distinct chondrocyte subpopulations within adult articular cartilage.

---

## Key Experiment Methods

**1. Fetal musculoskeletal cell isolation and RNA sequencing**

- Isolation of 17 WPC human fetal knee chondrocytes, femoral osteoblasts, quadriceps myoblasts, anterior/posterior cruciate ligament cells, and Achilles tendon cells
- Flow cytometry: LIN− (CD45−CD235a−CD31−) gating
- Chondrocytes: LIN−CD34−BMPR1B+, osteoblasts: LIN−ALP+, myoblasts: LIN−CD146+CD56+, ligament/tendon cells: LIN−
- RNA-seq performed

**2. WGCNA (Weighted Gene Co-expression Network Analysis)**

- Tissue-specific gene module definition from 17 WPC 5-tissue transcriptomes
- Developmental stage-specific module definition from 4-stage human chondrogenesis transcriptomes
- GO analysis, OPOSSUM transcription factor binding motif analysis

**3. Human-mouse chondrogenesis comparison**

- Isolation and RNA-seq of E16.5 mouse embryo and 2-month adult chondrocytes (LIN−ALP−BMPR1B+)
- Inter-species differential expression analysis, mean enrichment plot, volcano plot

**4. PSC-derived chondrocyte analysis**

- Transcriptome analysis of chondrocytes at day 14 (d14) and day 60 (d60) after mesoderm induction from PSCs
- Hierarchical clustering with in vivo chondrogenesis stages, Spearman correlation analysis, GO comparison

**5. ITGA4-based chondrocyte subpopulation analysis**

- Classification of 4 populations from adult porcine articular cartilage based on ITGA4 and BMPR1B expression: ITGA4+BMPR1B+, ITGA4+BMPR1B−, ITGA4−BMPR1B+, ITGA4−BMPR1B−
- Western blotting: SOX9, GLI1, pSTAT3, RUNX2 protein quantification
- RNA-seq and pairwise differential expression analysis
- In vitro chondrogenic/osteogenic differentiation evaluation

**6. Chromatin state analysis (ChIP-Seq)**

- ChIP-Seq for H3K27ac, H3K27me3, H3K4me1, H3K4me3 in fetal chondrocytes, adult articular chondrocytes, PSC-derived d14/d60 chondrocytes, and H1-hESC
- 12 chromatin states defined by ChromHMM
- Chromatin state distribution analysis in promoter proximal regions of WGCNA module genes

**7. In vivo transplantation experiments**

- Transplantation of 5-6 WPC primary pre-chondrocytes and PSC-derived d14/d60 cells into nude rat flanks
- Transplantation of d60 PSC-derived chondrocyte aggregates into rat distal femoral osteochondral defects

---

## Results

**Transcriptome profiling of 5 fetal musculoskeletal tissues**

Hierarchical clustering of 5,000 highly expressed genes revealed broad similarity between chondrocytes and ligament cells, and Spearman correlation analysis showed that intra-articular ligament cells had the highest correlation with chondrocytes. This is consistent with mouse Sox9-CreERT2 lineage tracing reports showing that cartilage, ligament, and tendon originate from Sox9+ mesenchymal progenitor cells.

**Tissue-specific gene module definition by WGCNA**

Thirteen gene modules were defined from 17 WPC 5 tissues: modules corresponding to each tissue were identified, including brown (osteoblasts), yellow (chondrocytes), and turquoise (myoblasts). Key regulators such as SOX9, RUNX2, and MYOD1 were verified to be correctly assigned to their respective modules. GO terms and transcription factor binding motifs were identified for each module.

**Transcriptomic dynamics of human chondrogenesis**

Analysis of 4 human chondrogenesis stages (embryonic 5-6 weeks, fetal 17 weeks, juvenile, adult) revealed:
- **Fetal vs adult**: Fetal chondrocytes were enriched for ECM organization, cell adhesion, and collagen metabolism genes, indicating active matrix deposition. Adult chondrocytes were enriched for metabolism, cell death, and interferon signaling genes.
- **Fetal vs embryonic**: Fetal chondrocytes were enriched for chondrogenic characteristics, whereas embryonic pre-chondrocytes retained muscle, nerve, and bone lineage-related transcripts, showing high transcriptional plasticity. Embryonic gene promoters were enriched for neural (SOX2) and cartilage (SOX5/9) SOX family and cardiac (NKX2.5) transcription factor motifs.
- **Juvenile vs adult**: Juvenile chondrocytes were more proliferative, while adults showed increased epigenetic and post-transcriptional regulation.

**Human-mouse chondrogenesis comparison**

Hierarchical clustering and PCA revealed substantial transcriptomic differences between humans and mice. Core chondrogenic genes (COL2A1, SOX9, ACAN, etc.) showed high inter-species conservation (except Col10a1), but mouse chondrocytes were enriched for WNT, AKT, MAPK signaling and cell cycle genes, suggesting more active proliferation. Human chondrocytes showed upregulation of oxidative metabolism and ribosome biogenesis genes. This suggests that while core chondrogenic programs are conserved, signaling and proliferation differences may underlie the divergent articular cartilage regenerative potential between humans and mice.

**In vitro maturation of PSC-derived chondrocytes**

Comparison of d14 and d60 PSC-derived chondrocytes showed that d60 cells were more similar to in vivo-derived cells (fetal, adult). Genes enriched in d60 significantly overlapped with genes enriched in fetal vs embryonic and adult vs fetal comparisons. d14 cells were enriched for broad developmental potential-related genes including cell cycle, cardiovascular development, and neural development. This demonstrates that the maturation of PSC-derived chondrocytes broadly mirrors natural in vivo cartilage specification.

**ITGA4 defines a unique chondrocyte subpopulation in adult articular cartilage**

Among CAMs enriched in embryonic chondrocytes and PSC d14 cells and decreased in fetal/adult stages, only ITGA4 was included in the embryonic module. IHC showed ITGA4 expressed in a minority of cells in the superficial zone of adult tibial plateau articular cartilage, while BMPR1B was more broadly expressed in the superficial and transitional zones.

Analysis of 4 populations based on ITGA4 and BMPR1B expression in adult porcine cartilage revealed:
- **ITGA4+BMPR1B+ cells**: Enriched for SOX9, GLI1, RUNX2, and pSTAT3 proteins, showing enrichment of osteo-chondral progenitor cell markers. RNA-seq identified 38 population-specific genes, with GO analysis revealing enrichment for cell cycle, mitosis, and proliferation terms. Showed strong osteogenic differentiation capacity in vitro and could also undergo chondrogenic differentiation. Exhibited fibroblast-like morphology.
- **ITGA4−BMPR1B+ cells**: Mainly located in the transitional zone, showed the strongest cartilage matrix production capacity. Low osteogenic differentiation capacity.
- **ITGA4+BMPR1B− cells**: Enriched for superficial zone PRG4/lubricin expression.
- **ITGA4−BMPR1B− cells**: Located in the deep zone, reflecting a terminally differentiated state with minimal osteogenic/chondrogenic differentiation capacity.

**Epigenomic regulation of in vivo and in vitro chondrogenesis**

ChromHMM defined 12 chromatin states. In fetal chondrocytes, promoter proximal regions of cartilage and ligament module genes were enriched for active promoter (AP) and promoter proximal (PP) states, while osteoblast/myoblast/tendon module genes were enriched for polycomb repressed (PR) states. The SOX9, COL2A1, and ACAN loci were enriched for H3K4me3 and H3K27ac active markers and absent of H3K27me3 repressive markers. NANOG and DPPA4 were in PR state enriched for H3K27me3. In H1-hESC, the SOX9 locus had a bivalent signature that resolved to an active state upon cartilage specification.

**In vivo transplantation: maturation is required for functional chondrogenesis**

5-6 WPC primary pre-chondrocytes and PSC d14 cells failed to form cartilage anlagen in nude rat flanks, whereas 17 WPC primary chondrocytes and PSC d60 cells formed cartilage anlagen. Transplantation of d60 PSC-derived chondrocyte aggregates into rat osteochondral defects resulted in robust regeneration of COL2+ human cartilage, with PRG4, ITGA4+, and BMPR1B+ cells arranged in the superficial zone in a zonal structure similar to normal adult articular cartilage.

---

## Perspective

This study provides the first comprehensive transcriptomic and epigenomic resource of human musculoskeletal development, systematically elucidating the molecular landmarks of cartilage specification and maturation. It was revealed that embryonic pre-chondrocytes establish cartilage identity through a "progressive silencing" process that gradually silences muscle, nerve, and bone lineage genes. Core chondrogenic genes are highly conserved between humans and mice, but differences in proliferation and signaling may underlie divergent regenerative potential. The transcriptomic plasticity of PSC-derived chondrocytes reflects the natural process of in vivo cartilage specification, with d60 cells representing a developmental stage between fetal and adult. ITGA4 serves as a key marker defining functionally distinct chondrocyte subpopulations within adult articular cartilage, with ITGA4+BMPR1B+ cells possessing osteo-chondral progenitor characteristics and proliferative potential, making them important targets for cartilage regeneration and tissue engineering. Chromatin state analysis demonstrates that the accumulation of active histone modifications at cartilage genes and acquisition of repressive states at other lineage genes is synchronized with cartilage maturation, emphasizing that epigenomic regulation is essential for maintaining chondrocyte identity. The gene modules, chromatin state maps, and ITGA4-based chondrocyte subpopulation information generated in this study can serve as essential comparative resources for disease modeling, regenerative medicine, and tissue engineering.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
