---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Single-cell RNA Seq reveals cellular landscape-specific characteristics and potential etiologies for adolescent idiopathic scoliosis

## Citation (NLM)

Yang Y, Yang M, Shi D, et al. Single-cell RNA Seq reveals cellular landscape-specific characteristics and potential etiologies for adolescent idiopathic scoliosis. JOR Spine. 2021;4(4):e1184. doi:10.1002/jsp2.1184

**DOI:** [https://doi.org/10.1002/jsp2.1184](https://doi.org/10.1002/jsp2.1184)

---

## Background

Adolescent idiopathic scoliosis (AIS) is a three-dimensional spinal deformity characterized by structural curvature, axial rotation, and sagittal plane deformation, affecting 0.47–5.2% of adolescents. Progression leads to reduced quality of life and socioeconomic burden, yet its etiology remains unclear, with proposed factors including genetic, environmental, hormonal, metabolic, biochemical, and neurological causes. Asymmetric spinal growth and low bone density have been highlighted as major etiological factors, but previous bulk tissue analyses have failed to capture cellular heterogeneity. The authors aimed to compare the cellular landscape of vertebral cancellous bone between AIS patients and normal controls using high-resolution single-cell RNA sequencing (scRNA-seq) and to identify lineage-specific differentiation defects in bone development.

---

## Key Experiment Methods

**1. Clinical specimens and single-cell isolation**
- Collected vertebral cancellous bone from 3 AIS patients (female, 12–15 years) and 3 non-AIS spinal trauma patients (female, 10–14 years)
- Developed a modified enzymatic digestion protocol (DNase II + Collagenase IV) adapted from tibial tissue dissociation for cancellous bone single-cell suspension (first developed in this study)
- Confirmed 65–80% viability by Calcein-AM/Draq7 staining

**2. scRNA-seq library preparation and sequencing**
- Used the BD Rhapsody system for microwell-based single-cell capture of >200,000 cells
- 150 bp paired-end sequencing on HiSeq X
- Obtained 2,226 cells from AIS patients and 2,241 cells from controls (mean 947–767 genes/cell detected)

**3. Bioinformatics analysis**
- Seurat v2.0.1: t-SNE dimensionality reduction, unsupervised clustering (11 principal components, resolution 1.5)
- Monocle 2: pseudotime trajectory reconstruction
- GO/KEGG enrichment: Fisher's exact test + FDR (BH method) correction
- Cell–cell communication: ligand–receptor pair database-based network construction

---

## Results

**Identification of 11 cell populations**
t-SNE analysis identified 11 major cell populations: B lymphocytes (BLC), T lymphocytes (TLC), mesenchymal stem cells (MSC), chondroprogenitor cells (CPC), neutrophils (NP), osteoblasts (OB), monocytes (MC), chondrocytes (CC), dendritic cells (DC), osteoclasts (OC), and hematopoietic stem cells (HSC). GO analysis validated the functional identity of each population.

**Increased immune cells**
Total immune cell numbers were significantly increased in AIS patients compared to controls, suggesting that the immune microenvironment may be involved in AIS pathogenesis.

**Osteoblast lineage differentiation defect**
MSCs were classified into three subtypes (MSC-LOXL2, MSC-IGFBP5, MSC-GJA1). MSC-LOXL2 (423 cells) and MSC-GJA1 (182 cells) were detected only in controls, while MSC-IGFBP5 was found exclusively in AIS (181/220 cells, 82%), constituting the majority of the AIS MSC population. Pseudotime analysis revealed that in controls, normal osteoblast differentiation proceeded as MSC-LOXL2 → MSC-GJA1 → OB-DPT/OB-OLFML2B; however, in AIS, MSC-IGFBP5 failed to differentiate into osteoblasts, with increased cell proliferation arrest and cell death. Consequently, AIS osteoblast numbers (OB-DPT: 2, OB-OLFML2B: 9) were markedly lower than in controls (303 and 259, respectively), providing a cellular basis for low bone density.

**Chondrocyte lineage differentiation defect**
CPCs were divided into two subtypes: CPC-SLC2A1 and CPC-PCNA. CPC-PCNA (high expression of abnormal cell cycle and DNA damage-related genes such as PCNA, CCNE1) was observed exclusively in AIS patients (42 cells). CPC-SLC2A1 was greatly increased in AIS (350 vs. 114). Both chondrocyte subtypes (CC-MPP13, CC-MT1G) were absent in AIS and present only in controls (254 and 189 cells, respectively), confirming a differentiation defect from CPC to chondrocyte in AIS. This suggests a possible mechanism of spinal growth impairment through abnormal endochondral ossification.

**Osteoclast lineage**
AIS monocyte (MC) numbers were increased (45 vs. 8), but OC-BIRC3 was decreased in AIS. Pseudotime analysis showed that AIS MCs were predominantly biased toward OC-CRISP3 differentiation.

**Immune cell–bone development cell interactions**
MSC-IGFBP5 showed lymphocyte-mediated inflammation and immune surveillance evasion via LTβR interactions (LTβ-LTβR: B-IGHM, TNF-LTβR: T-GNLY) and HLAE-NKG2A immune tolerance evasion signaling. In CPC-PCNA, immune-related ligand–receptor pairs such as IDE-CCL3 and NECTIN1-CD96 were enriched. Pathway analysis identified NF-κB pathway upregulation and TGF-β pathway downregulation in AIS MSCs as molecular mechanisms underlying the osteoblast differentiation defect. In CPCs, sustained HIF-1α pathway activation was hypothesized to impair chondrocyte differentiation through glycolysis–oxidative phosphorylation imbalance.

---

## Perspective

This study presents the first single-cell-level cellular landscape of vertebral cancellous bone from AIS patients, with the following key contributions.

First, the conventional soft tissue dissociation protocol, which was unsuitable for tibial tissue, was modified and optimized for cancellous bone, establishing a technical foundation for hard tissue single-cell analysis. This method can be applied to various bone disease studies in the future.

Second, AIS-specific MSC (MSC-IGFBP5) and CPC (CPC-PCNA) subtypes were discovered, and their differentiation failure into osteoblasts and chondrocytes, respectively, was demonstrated at single-cell resolution. These are key findings explaining the cellular and molecular mechanisms underlying low bone density and asymmetric spinal growth in AIS.

Third, cell–cell communication analysis between immune cells and bone development cells revealed potential immunopathogenic mechanisms in AIS, including lymphocyte-mediated MSC inflammatory responses, HIF-1α pathway homeostasis disruption, and NF-κB/TGF-β pathway imbalance. This opens the possibility of reconceptualizing AIS not simply as a skeletal deformity but as an immune–skeletal interaction disorder.

Future challenges include in vivo confirmation and lineage tracing of MSC-IGFBP5 and CPC-PCNA, functional validation of the proposed immune pathogenic mechanisms, generalization of results in larger cohorts, and development of novel therapeutic strategies targeting the differentiation defects identified in this study.


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
