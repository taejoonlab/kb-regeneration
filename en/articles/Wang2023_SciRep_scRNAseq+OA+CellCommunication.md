---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p02.txt
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add Data Availability section"
---

# Probing the communication patterns of different chondrocyte subtypes in osteoarthritis at the single cell level using pattern recognition and manifold learning

## Citation (NLM)

Wang J, Liu C, Yang L, Chen H, Zheng M, Wan Y, Hong X, Li S, Han J, Luo R, Wan X, Zhang JV, Xu R. Probing the communication patterns of different chondrocyte subtypes in osteoarthritis at the single cell level using pattern recognition and manifold learning. _Sci Rep._ 2023 Sep 4;13(1):14467. doi: [10.1038/s41598-023-41874-z](https://doi.org/10.1038/s41598-023-41874-z). PMID: 37666903.

---

## Background

Osteoarthritis (OA) is a chronic joint disorder that disrupts joint tissue metabolism and is accompanied by inflammation and bone degeneration. Chondrocytes are the sole cell type in cartilage and differentiate and develop through quiescent, proliferative, prehypertrophic, hypertrophic, and ultimately calcified bone stages. Application of single-cell sequencing technology has identified 7 chondrocyte subpopulations: effector chondrocytes (ECs), fibrocartilage chondrocytes (FCs), hypertrophic chondrocytes (HTCs), homeostatic chondrocytes (HomCs), proliferative chondrocytes (ProCs), regulatory chondrocytes (RegCs), and prehypertrophic chondrocytes (preHTCs). While the functional characteristics of each subpopulation have been studied, **how these subpopulations interact and cooperate to promote OA progression in the OA microenvironment** remains unknown. This study is the first to elucidate intercellular communication patterns among chondrocyte subpopulations through network analysis and pattern recognition in a single-cell transcriptome dataset.

---

## Key Experiment Methods

**1. Single-cell dataset collection**

- Used 1,600 single-cell knee joint chondrocyte data from 10 OA patients (GSE104782)
- Extracted specimens containing full-thickness cartilage from the tibial plateau region
- Comparative analysis of chondroprogenitor differentiation time-course data (GSE160625, day 7/14/28/42)

**2. CellChat-based intercellular communication analysis**

- Constructed cell-cell communication networks using the R package CellChat
- Input normalized scRNA-seq average expression data (trimean) and cell annotation information
- Inferred communication probabilities based on ligand-receptor pairs using computeCommunProb
- Inferred signaling pathway-specific profiles using computeCommunProbPathway

**3. Communication pattern quantification**

- Derived communication roles (sender, receiver, mediator, influencer) of chondrocyte subpopulations using netAnalysis_computeCentrality
- Calculated incoming/outgoing signal patterns using selectK
- Computed the number of intercellular communication patterns using identifCommunicationPatterns
- Visualized specific pathways using netAnalysis_river and netAnalysis_dot

**4. Communication network comparison**

- Compared interaction numbers and strengths using compareInteractions
- Visualized interaction differences between cell groups using netVisual_diffInteraction
- Identified cell populations with significant differences between datasets using netAnalysis_signalingRole_scatter

**5. Manifold learning and quantitative contrast**

- Clustered similar signals using computeNetSimilarity, netEmbedding, and netClustering
- Identified conserved and specific communication pathways

---

## Results

**Interaction strength among chondrocyte subpopulations** Interaction strength was strong among ECs, FCs, and HTCs, moderate for preHTCs, ProCs, and HomCs, and weak for undefined and RegCs. Interactions between ProCs and preHTCs were not strong, but interactions within HTCs were very strong, suggesting transitional relationships among subpopulations.

**Incoming/Outgoing communication patterns** Undefined and RegC were "passive" cell types, and active cell types were classified into two groups:
- **Group 1** (incoming-dominant): preHTC, EC, ProC — receiving signals dominate, sending signals are auxiliary
- **Group 2** (outgoing-dominant): HomC, HTC, FC — sending signals dominate, receiving signals are auxiliary

**Signaling pathway redundancy and exclusivity** ProCs and preHTCs had nearly all pathways redundant, making them the most active subpopulations. In contrast, **ECs and FCs were a "mutually exclusive" pair**, with mostly non-overlapping active signaling pathways:
- EC outgoing: GAS, CHEMERIN, PTPRM, VEGF, WNT
- FC outgoing: COLLAGEN, LAMININ, MK, CXCL, ANGPTL, CADM
- EC incoming: CHEMERIN, PTPRM, FGF
- FC incoming: SEMA3, EPHA, CADM

**Multiple roles of preHTC** Analysis of 23 signaling pathways (COLLAGEN, LAMININ, THBS, GAS, MPZ, MK, TGFb, CHEMERIN, BMP, PROS, CXCL, SEMA3, FGF, ANGPTL, PTPRM, EPHA, PTH, ncWNT, JAM, VISFATIN, CADM, VEGF, WNT) revealed that **only preHTC performed all four roles: sender, receiver, mediator, and influencer.** In THBS, GAS, MPZ, and MK pathways, preHTC and FC were the main active cells, but FC was limited to influencer/sender roles, while preHTC performed multiple roles.

**Key ligand-receptor pairs** In the COLLAGEN pathway, ITGAV, ITGB1, ITGA10, COL4A1, COL4A2, and COL9A3 were the main ligand-receptor pairs, with COL4A1/COL4A2 primarily active in FC, EC, and HTC. In the LAMININ pathway, LAMB2, LAMC1, ITGA2, ITGAV, and ITGB1 were involved, with LAMC1 dominant in FC and ITGA2 dominant in EC and ProC. ITGB1 was broadly distributed across multiple subpopulations.

**Comparison of chondroprogenitor vs chondrocyte communication patterns** In chondroprogenitor differentiation time-course analysis, communication pathways strengthened and chondrocyte subpopulations became more distinct as maturation progressed. HMGB2/CDK1+ proliferative chondrocytes (ProCs) and CD24/SOX2+ hypertrophic chondrocytes (preHTCs) showed active input signals and moderate output signals. Many signals such as MK, ANGPTL, FGF, VISFATIN, BMP, WNT, GAS, TGFb, ncWNT, VEGF, and SEMA3 were commonly identified in both chondrocytes and chondroprogenitors, suggesting a continuous molecular process where differentiation and later-stage functions are not separated.

---

## Perspective

This study is the first to systematically analyze intercellular communication patterns among OA chondrocyte subpopulations at the single-cell level, with the following significance.

First, it identified preHTC as the only subpopulation performing **all four roles — sender, receiver, mediator, and influencer —** in chondrocyte communication, demonstrating that preHTC acts as a cell signaling hub in the OA microenvironment. preHTC ligand-receptors (ITGAV, ITGB1, ITGA10) are the most active, suggesting that preHTC-targeted therapy may be key to modulating OA progression.

Second, it discovered that ECs and FCs are a "mutually exclusive" pair using different signaling pathways. ECs are incoming-signal dominant (receiving-centered) and FCs are outgoing-signal dominant (sending-centered), suggesting these two subpopulations may play complementary roles contributing to cartilage homeostasis maintenance.

Third, COLLAGEN and LAMININ pathways were identified as core pathways in chondrocyte communication, reaffirming the importance of ECM-cell interactions in joint homeostasis repair and expansion. Integrin family receptors such as ITGAV, ITGB1, and ITGA10 are involved across multiple subpopulations, showing great potential as OA therapeutic targets.

Fourth, the pattern recognition and manifold learning-based approach presents a new research paradigm for single-cell communication analysis. This method can be applied to rapidly target dominant cell populations (ProCs, preHTCs) for selection as cell therapy替代 cells or to develop related inhibitors for blocking OA-related communication as a therapeutic strategy.

Future directions include validation in larger OA patient cohorts (including disease grading information), integrated analysis of chondrocyte spatial distribution and communication patterns using single-cell spatial transcriptomics and spatial proteomics technologies, and actual isolation of identified subpopulations by FACS/sorting and optimization for cell therapy application.

## Data Availability

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE104782, GSE160625


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
