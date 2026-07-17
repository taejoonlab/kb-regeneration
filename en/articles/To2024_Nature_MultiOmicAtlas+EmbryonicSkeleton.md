---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# A multi-omic atlas of human embryonic skeletal development

## Citation (NLM)

To K, Fei L, Pett JP, et al. A multi-omic atlas of human embryonic skeletal development. Nature. 2024;635:657-667. doi:10.1038/s41586-024-08189-z

**DOI:** [https://doi.org/10.1038/s41586-024-08189-z](https://doi.org/10.1038/s41586-024-08189-z)

---

## Background

Human embryonic skeletal development begins between 5 and 11 post-conception weeks (PCW) and proceeds via two major ossification mechanisms: intramembranous ossification of the calvaria and endochondral ossification of the limbs and skull base. Synovial joints begin to form at 5–6 PCW through interzone condensation, with joint cavitation occurring at 7–8 PCW. To date, a comprehensive description of human embryonic skeletal development at the single-cell and epigenomic level has been lacking, and the region-specific fate determination and regulatory networks of skeletal progenitor cells remain largely unknown. The authors aimed to characterize the cellular landscape and regulatory principles of human embryonic skeletal development using a multi-omic approach combining snRNA-seq, snATAC-seq (10X Multiome), and spatial transcriptomics.

---

## Key Experiment Methods

**1. Multiome (snRNA-seq + snATAC-seq)**
- Collected hip, knee, shoulder, and cranial (anterior/posterior calvaria, skull base) samples from 12 donors at 5–11 PCW
- Captured 336,162 nuclei-competent droplets using the 10X Genomics Multiome platform
- Integrated snRNA·snATAC analysis using MultiVI and inferred transcription factor regulatory networks with SCENIC+

**2. High-resolution spatial transcriptomics**
- Generated high-resolution spatial maps of embryonic forelimb/hindlimb knee and shoulder joints (5.7–7.3 PCW) using 155-plex in situ sequencing (ISS)
- Analyzed spatial transcriptomes of the 9 PCW coronal suture and frontal bone using 10X Visium CytAssist
- ISS-Patcher (novel tool): developed a KNN-based method to assign cell labels from high-dimensional droplet data to low-dimensional ISS data

**3. OrganAxis spatial trajectory analysis**
- A novel spatial annotation tool defining a continuous maturation axis from the suture to the bone front
- Zonation of the frontal bone along the anteroposterior axis: suture zone → osteogenic front → osteogenic zone

**4. SNP2Cell tool development**
- A tool linking cell-type-specific gene regulatory networks (GRNs) to polygenic traits (GWAS)
- Cell-type-specific enrichment analysis of genetic variants associated with osteoarthritis (OA) and craniosynostosis

**5. Schwann cell–chondrocyte lineage analysis**
- Predicted a non-canonical differentiation trajectory from Schwann cell progenitors (SCP) → SOX9+ enSC → chondrocytes using RNA velocity and pseudotime trajectory analysis
- Validated co-localization of MPZ+SOX9+ cells in the hip joint by RNA-ISH (RNAscope)

**6. Craniosynostosis in silico simulation**
- Predicted the effects of TWIST1, MSX2, and LMX1B knockout on ossification using CellOracle transcription factor perturbation simulations

---

## Results

**Interzone zonation during joint formation**
Seven subpopulations (Early IZ, Articular IZ, Fibro IZ, GDF5hi IZ, Hypertrophic IZ1/2, Dermal IZ) were identified within the InterzoneChon (GDF5+PITX2+) population. Spatial analysis revealed enrichment of chondrogenic transcription factors in the center of the interzone and enrichment of RUNX2 in the surrounding cartilage scaffold, demonstrating that regional compartmentalization (zonation) between ossification suppression and chondrogenesis is established from the early stages of joint formation. Joint cavitation occurs after this compartmentalization at 7–8 PCW.

**Fibroblast lineage map**
HIC1+Mes was identified as an early fibroblast progenitor, with RNA velocity predicting differentiation trajectories into tenocytes, synovial fibroblasts, dermal fibroblasts, and myofibroblasts. After 8 PCW, FibroPRO2 (PI16+DPT+) emerged and connected to adult pro-adventitial fibroblasts.

**Regulatory networks of intramembranous and endochondral ossification**
In the cranium, an intramembranous ossification trajectory of CranialMes → SutureMes1/2 → HHIP+PreOB → osteoblasts → osteocytes was constructed, and in the limbs, an endochondral ossification trajectory of LimbMes → Preosteoblast → osteoblasts. SCENIC+ analysis identified a double-negative regulatory network in the suture region where the anti-osteogenic activity of TWIST1, LMX1B, and ALX4 indirectly suppresses RUNX2 and HHIP expression (Fig. 2h). ATAC coverage and predicted enhancer loops at the RUNX2 and HHIP loci supported this regulatory architecture.

**Coupling of angiogenesis and ossification**
A spatial signaling network was identified in which suture progenitors (SutureMes) and HHIP+PreOB secrete VEGFA/VEGFB, and tip cells promote osteoblast differentiation via NOTCH signaling. Endothelial FGF2 and RSPO3 signaling were predicted to support osteoblast differentiation and osteocyte mineralization.

**Chondrocyte diversity and non-canonical origin**
Twelve chondrocyte subpopulations showed region-specific abundance (ArticularChon1/2, RestingChon, CyclingChon, DLK1+Chon, HyperChon, ChondroPro1/2, FacialChon, MandibularChon, PAX7+Chon, InterzoneChon). Notably, the SOX9+ enSC (SOX9+ endoneurial Schwann cells) population co-expressed classical Schwann cell markers (MPZ, SOX10) and cartilage markers (COL2A1, ACAN), and MPZ+SOX9+ co-localization was validated within hip joint cartilage by RNA-ISH. This suggests that Schwann cells may represent a non-canonical origin for chondrocytes in the human embryo.

**GWAS linkage: osteoarthritis and craniosynostosis**
Knee OA signals were enriched in chondrogenic cells (ArticularChon), while hip OA signals were enriched in osteogenic cells (Preosteoblast). Using SNP2Cell, RUNX2, NFATC1/2/4, and TEAD1 were identified as key regulators in hip OA-associated GRNs. Thirteen of 22 craniosynostosis genes were enriched in intramembranous ossification progenitors (SutureMes, HHIP+PreOB), and in silico knockout simulations of TWIST1, MSX2, and LMX1B predicted strong differentiation velocity changes in SutureMes2.

---

## Perspective

This study provides the most comprehensive multi-omic atlas of human embryonic skeletal development, with the following transformative contributions.

First, based on paired snRNA+snATAC data from 336,162 nuclei, over 100 fine clusters were defined and an integrated regulatory network spanning both intramembranous and endochondral ossification pathways was presented. The HHIP+PreOB and TWIST1-LMX1B anti-osteogenic network represents a key mechanism for maintaining open sutures.

Second, the first evidence that the Schwann cell lineage can serve as a non-canonical cellular origin for human embryonic cartilage was provided through RNA-ISS and RNA-ISH. This contributes to expanding the paradigm of developmental biology.

Third, novel computational tools including ISS-Patcher, OrganAxis, and SNP2Cell were developed, establishing a framework for integrating spatial transcriptomics with GWAS data to elucidate development–disease connections. In particular, in silico gene knockout simulations for craniosynostosis enable prediction of disease-relevant cell states.

Fourth, OA GWAS signals were linked to embryo joint-specific GRNs, supporting the developmental origin hypothesis for adult disease. The finding that knee and hip OA are associated with distinct developmental cell types is important for precision therapeutic target discovery.

Future challenges include lineage tracing experiments to quantify the contribution of SOX9+ enSC to chondrocytes, studies on innervation of the embryonic skeleton, and functional validation of in silico disease predictions.


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
