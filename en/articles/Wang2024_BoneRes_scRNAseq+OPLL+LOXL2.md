---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p02.txt
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Sorafenib inhibits ossification of the posterior longitudinal ligament by blocking LOXL2-mediated vascularization

## Citation (NLM)

Wang L, Jiang W, Zhao S, Xie D, Chen Q, Zhao Q, Wu H, Luo J, Yang L. Sorafenib inhibits ossification of the posterior longitudinal ligament by blocking LOXL2-mediated vascularization. _Bone Res._ 2024 Mar 26;12(1):24. doi: [10.1038/s41413-024-00327-7](https://doi.org/10.1038/s41413-024-00327-7).

---

## Background

Ossification of the posterior longitudinal ligament (OPLL) is a degenerative hyperostotic disease of the spine, in which the soft and elastic posterior longitudinal ligament (PLL) transforms into bone, causing restricted spinal mobility and nerve compression. OPLL predominantly occurs in the cervical spine and has a high prevalence in East Asia (1.9–4.3% in Japan). Histologically, OPLL progresses through endochondral ossification, with avascular ligament tissue being replaced by highly vascularized bone tissue. Vascular invasion serves as an important biological process of abnormal osteogenesis in OPLL progression. The lysyl oxidase family member LOXL2 is known to be involved in regulating vascular formation through collagen scaffolding, tumor vasculogenic mimicry, and fibrotic diseases, but its role in OPLL remains uncharacterized. This study aimed to characterize the molecular features, cellular composition, and their evolution during OPLL at single-cell resolution using bulk and single-cell RNA sequencing, and to validate the role of LOXL2 in endothelial-like differentiation of ligament cells and the OPLL-inhibitory effect of sorafenib.

---

## Key Experiment Methods

**1. Clinical specimen analysis**

- Ossification assessment by lateral X-ray, 3D CT, and MRI in OPLL patients
- Disease severity measured by modified JOA and NDI scales, correlation analysis with spinal canal occupancy ratio
- H&E, SOFG staining, COLII/COLX/SP7/BGLAP/RUNX2/MMP1 immunostaining to confirm endochondral ossification features

**2. Bulk RNA-seq**

- Paired comparison of ossified (OPLL) vs non-ossified (non-OPLL) ligament from 4 OPLL patients
- HISAT2 alignment, DEG analysis by edgeR (paired design)
- GO, KEGG, GSEA (Hallmark gene sets), STRING PPI network analysis
- Hub gene identification by 5 centrality methods (MCC, DMNC, EPC, MNC, ClusteringCoefficient)

**3. Single-cell RNA sequencing (scRNA-seq)**

- 51,245 cells profiled from posterior longitudinal ligaments of 3 OPLL and 2 non-OPLL patients (30,628 non-OPLL, 20,617 OPLL)
- 13 clusters identified by UMAP: ligament cells (ligament_1-4), endothelial cells (EC_1-2), pericytes, monocyte-macrophages, T cells, B cells, plasma cells
- Ligament cells, pericytes, and endothelial cells extracted and re-clustered into 9 subclusters

**4. RNA velocity and differentiation trajectory analysis**

- Dynamic trajectory confirmed by UMAP embedding of RNA velocity
- Undifferentiated state evaluated by CytoTRACE
- Ligament-to-vascular differentiation trajectory reconstructed with Monocle3 using C6 (progenitor) as starting point
- 10 gene modules identified by Louvain community analysis, pathway enrichment by ReactomePA

**5. In vitro capillary formation assay (Matrigel)**

- Tube formation evaluated in Matrigel for HUVECs (positive control), hUC-MSCs, and ligament cells
- Effects of VEGFA (100 ng/mL) and PDGF-BB (100 ng/mL) stimulation analyzed
- Inhibition experiments with bevacizumab (VEGFA antibody) and imatinib (PDGFR inhibitor)
- CD31, EMCN, LOXL2, VEGFA, PDGFB expression analyzed in ligament cells on Matrigel (qPCR)

**6. In vivo vascular network formation assay**

- Ligament cell + Matrigel gel spheres injected subcutaneously in nude mice
- Functional blood vessels confirmed by ink perfusion through the left ventricle
- Human-specific CD31 immunohistochemistry, UEA I (human endothelial-specific) and GS-B4 (mouse endothelial-specific) lectin staining

**7. LOXL2 functional studies**

- Tube formation impact assessed by LOXL2 overexpression (OE)
- Enzyme activity dependence confirmed by BAPN treatment (pan-Lox(L) inhibitor, 2 mmol/L)
- HIF1A pathway analysis

**8. Sorafenib treatment experiments**

- OPLL progression inhibitory effect of sorafenib evaluated in BMP-induced and enpp1-deficient animal models
- Effect on normal bone mass confirmed

---

## Results

**OPLL exhibits endochondral ossification features** Ossified tissue from OPLL patients showed mature bone, Haversian canals, trabecular and bone marrow structures. Proteoglycan-rich cartilage and hypertrophic chondrocytes were observed at the junction, with high COLII/COLX expression in junctional cartilage. Osteoblast markers SP7, BGLAP, and RUNX2 were increased at ossification sites. MMP1 was elevated at both junction and ossification sites. Spinal canal occupancy ratio showed negative correlation with JOA score (r=-0.66) and positive correlation with NDI score (r=0.56).

**Angiogenesis pathway upregulated in OPLL** 677 DEGs (371 upregulated, 306 downregulated) were identified between OPLL vs non-OPLL by bulk RNA-seq. GO analysis revealed enrichment in extracellular matrix organization, angiogenesis, skeletal system development, and cartilage development. GSEA identified angiogenesis pathway as a major biological process (NES=1.89, adj P<0.001). LOXL2, TGFBI, and PCOLCE were identified as top hub genes in the PPI network. LOXL2 upregulation and angiogenesis/hypoxia pathway activation were also confirmed in hypertrophic ligament microarray (GSE113212).

**Increased LOXL2 and H-type vessels in OPLL** LOXL2 expression was elevated in OPLL tissue and ligament cells. LOXL2+ cells were primarily localized at the junction between ossified and non-ossified regions. CD31+EMCN+ type H vessels were increased at ossification sites and within the bone marrow cavity at the junction. Ligament cells possessed trilineage differentiation capacity and expressed MSC surface markers (CD73+, CD90+, CD105+, CD45−).

**Single-cell analysis: endothelial differentiation trajectory of ligament cells** RNA velocity and CytoTRACE analysis from 9 subclusters with C6 (progenitor, PRG4+) as starting point confirmed differentiation into C6→C4/C9 (endothelial), C2/C5 (chondrocytes), and C8 (osteoblasts). Module 4 (endothelial markers PECAM1, EMCN, etc., VEGF signaling) and Module 5 (LOXL2, HIF1A, RNA splicing, heat shock response) progressively increased during endothelial differentiation. LOXL2 and HIF1A showed an initial increase followed by decrease pattern during endothelial differentiation.

**Endothelial-like differentiation capacity of ligament cells** In Matrigel assay, ligament cells spontaneously formed capillary-like structures similar to HUVECs, whereas hUC-MSCs only showed cell aggregation. During tube formation, ligament cells showed increased LOXL2, VEGFA, and PDGFB expression, and elevated osteoblast marker SP7, suggesting coupling of vascularization and ossification. In vivo, ligament cell + Matrigel gel spheres showed ink particle deposition, with ink located within human-specific CD31-positive areas. UEA I (human) positive and GS-B4 (mouse) negative staining confirmed functional blood vessel formation derived from ligament cells. VEGFA and PDGF-BB promoted capillary formation, which was inhibited by bevacizumab and imatinib.

**LOXL2 regulates endothelial differentiation via HIF1A pathway** LOXL2 OE increased capillary formation, but BAPN (enzyme activity inhibitor) treatment had no effect, indicating that LOXL2-mediated vascularization regulation is independent of its enzyme activity.

**Sorafenib inhibits OPLL** Sorafenib effectively inhibited LOXL2-mediated vascular morphogenesis. In BMP-induced and enpp1-deficient animal models, sorafenib significantly suppressed OPLL progression by blocking the coupling of vascularization and ossification, without affecting normal bone mass.

---

## Perspective

This study elucidated at single-cell resolution that the LOXL2-HIF1A-VEGFA/PDGF-BB axis mediates endothelial-like differentiation and vascularization of ligament cells in OPLL pathogenesis, and that this process is closely coupled with ossification. The finding that LOXL2's vascularization regulatory function is independent of its enzyme activity suggests a non-canonical function of LOXL2, providing important insight for developing new therapeutic targets.

Sorafenib, a broad-spectrum tyrosine kinase inhibitor, effectively blocked OPLL progression by inhibiting LOXL2-mediated vascular morphogenesis without affecting normal bone mass, demonstrating its potential as an OPLL-specific therapeutic agent. This suggests that therapeutic strategies targeting the coupling of vascularization and ossification could be applicable not only to OPLL but also to other heterotopic ossification diseases.

The significance of this study includes: (1) construction of the first single-cell atlas of OPLL, (2) elucidation of endothelial-like differentiation capacity of ligament cells and the regulatory mechanism of LOXL2, and (3) preclinical validation of sorafenib as an OPLL therapeutic agent. Future studies should include in-depth molecular mechanism analysis of LOXL2-HIF1A interaction, long-term safety and clinical trials of sorafenib, and development of LOXL2-specific inhibitors.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
