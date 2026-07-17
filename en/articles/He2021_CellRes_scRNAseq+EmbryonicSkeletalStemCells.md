---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
---

# Dissecting human embryonic skeletal stem cell ontogeny by single-cell transcriptomic and functional analyses

## Citation (NLM)

He J, Yan J, Wang J, Zhao L, Xin Q, Zeng Y, Sun Y, Zhang H, Bai Z, Li Z, Ni Y, Gong Y, Li Y, He H, Bian Z, Lan Y, Ma C, Bian L, Zhu H, Liu B, Yue R. Dissecting human embryonic skeletal stem cell ontogeny by single-cell transcriptomic and functional analyses. _Cell Res._ 2021 Jul;31(7):742-757. doi: [10.1038/s41422-021-00467-z](https://doi.org/10.1038/s41422-021-00467-z).

---

## Background

Skeletal stem cells (SSCs) have been identified in the growth plate, periosteum, and skull of postnatal mice, and are characterized by their ability to differentiate into chondrocytes, osteoblasts, and hematopoietic stroma, but not adipocytes. Human SSCs have also been reported in the 17-week fetal long bone growth plate. However, when and where SSCs emerge during early human embryonic bone formation and what ontogeny they undergo remain unknown. In limb development, the earliest progenitors of the vertebrate appendicular skeleton form within the limb bud, with the anterior-posterior (AP) axis regulated by SHH signaling and the proximal-distal (PD) axis by FGF signaling. Elucidating the cellular heterogeneity and hierarchical differentiation pathways of human embryonic skeletal development at the single-cell level is essential for skeletal regeneration and cell therapy development. This study aimed to construct a spatiotemporal developmental map of human embryonic skeletal stem/progenitor cells by analyzing 5- and 8-week human embryonic limb buds, long bones, and calvaria using single-cell RNA sequencing (scRNA-seq).

---

## Key Experiment Methods

**1. Human embryonic sample collection**

- 5-week post-conception (WPC) upper and lower limb buds (n=3 embryos)
- 8 WPC forelimb/hindlimb long bones (n=3 embryos)
- 8 WPC calvaria (n=2 embryos)
- Normal karyotype confirmation (CNV score calculation)

**2. Single-cell RNA sequencing (scRNA-seq)**

- 10× Genomics 3′ droplet-based platform
- Live single cell sorting by flow cytometry
- 5 WPC limb bud: 19,890 cells; 8 WPC long bones: 15,680 cells; 8 WPC calvaria: 7,287 cells
- Batch effect correction by CCA, clustering with Seurat
- UMAP visualization

**3. Ontogeny trajectory analysis**

- Pseudotime analysis by RNA velocity
- Cell population connectivity analysis by PAGA (Partition-based graph abstraction)
- Differentiation trajectory simulation with Slingshot
- Diffusion map analysis

**4. Transcription factor regulatory network analysis**

- Regulon activity evaluation (AUC score) using SCENIC (Single-Cell rEgulatory Network Inference and Clustering)
- Transcription factor-target gene network inference with GENIE3

**5. Cross-species comparison**

- Comparison with mouse E11.5 limb bud and E15.5 long bone scRNA-seq data using the SciBet algorithm

**6. eSSPC isolation and functional analysis**

- Flow cytometry sorting: PDGFRAlow/−PDPN−, PDGFRAlow/−PDPN+CADM1−, PDGFRAlow/−PDPN+CADM1+
- CFU-F colony formation assay and mesenchymal sphere culture
- Self-renewal capacity confirmed by serial passaging
- In vitro trilineage differentiation (adipogenic, osteogenic, chondrogenic)
- In vivo subrenal capsule transplantation (immunodeficient NOG mice, 8 weeks post-transplantation, Movat pentachrome, collagen I/II immunofluorescence)

**7. Immunofluorescence**

- Confirmation of marker protein expression localization: FOXP1, FOXP2, CADM1, PDPN, etc.

---

## Results

**Integrated analysis of limb bud and long bones: 16 cell populations**

Integrated analysis of 5 WPC limb bud and 8 WPC long bones identified 16 cell populations:
- PRRX1+ limb bud mesenchyme 3 subpopulations (LBM1-3): mesenchymal progenitor cells at different maturation stages with varying PDGFRA expression levels
- OCPs (Osteo-chondrogenic progenitors, cluster 4): PRRX1+, SOX9low, PDGFRAhi — evenly distributed in limb buds and long bones
- EPCAM+ epithelial cells, GYPA+ erythrocytes (limb bud predominant)
- SIX1+ muscle progenitor cells, CDH5+ endothelial cells, CD68+ macrophages
- RUNX2+ osteoprogenitor cells, OSR2+NOV+ perichondrial mesenchymal stromal cells (PMSCs), SOX9+ chondroblasts/chondrocytes, MYOG+ myocytes, SOX10+ Schwann cells (long bones predominant)

RNA velocity and PAGA analysis confirmed that OCPs play a key role connecting limb bud mesenchymal progenitor cells (PRRX1+) to long bone PMSCs/chondroblasts/chondrocytes (SOX9+) and osteoprogenitor cells (RUNX2+).

**Spatial heterogeneity of limb bud mesenchyme elucidated**

Four mesenchymal subpopulations were arrayed along the PD and AP axes in 5 WPC limb buds:
- LBM3 (proximal): 3′ HOX gene (HOX2-6) expression, MEIS2+
- LBM1/LBM2 (distal): 5′ HOX gene (HOX9-11) expression, HOXD13+
- LBM2 is located most distally and shows the highest proliferation rate (high G2/M cell proportion), corresponding to the progress zone beneath the AER
- OCP expresses both 3′ and 5′ HOX genes, corresponding to the core condensed mesenchyme

GSVA analysis showed that proximal/core mesenchyme (LBM3/OCP) was enriched for retinoic acid and PDGF signaling, while distal mesenchyme (LBM1/2) was enriched for Hedgehog, FGF, TGFβ, and Notch signaling. SCENIC analysis revealed MSX1/PITX1 regulons enriched in LBM1/2 and PBX1/SOX9 regulons enriched in LBM3/OCP, with ZMIZ1 and KDM5A identified as OCP-specific regulons.

**Identification of embryonic skeletal stem/progenitor cells (eSSPCs) in long bones**

Osteo-chondrogenic lineage cells (OCLCs) in 8 WPC long bones were classified into 7 subpopulations:
- LBDMC (Limb bud-derived mesenchymal cells, cluster 2): TWIST2hi
- BMSCs (cluster 1): CXCL12+, PDGFRA+
- **eSSPCs (Embryonic skeletal stem/progenitor cells, cluster 3)**: GAS2+, centrally located, enriched for stem cell proliferation-related genes
- Osteoprogenitor cells, PMSCs, chondroblasts, chondrocytes

RNA velocity showed strong branching flow from eSSPCs toward osteoprogenitor cells, chondroblasts/chondrocytes, and PMSCs. LBDMCs were positioned upstream of both eSSPCs and BMSCs, forming two differentiation pathways. SCENIC analysis revealed that eSSPCs were highly enriched for **FOXP1 and FOXP2 regulons**. Immunofluorescence confirmed FOXP1/2+ cells in the perichondrium and primary ossification center (POC) of 8 WPC long bones.

**CADM1 identified as a surface marker for eSSPCs**

The cell adhesion molecule CADM1 was selectively expressed in eSSPCs. FOXP1/2 binding motifs were enriched in cis-regulatory elements of CADM1. Since Schwann cells also express CADM1, PDPN was additionally used to distinguish eSSPCs (PDPN+CADM1+) from Schwann cells (PDPN−CADM1+). Immunofluorescence showed PDPN+CADM1+ cells located in the perichondrium and within the POC.

**Self-renewal and osteo-chondrogenic differentiation capacity of eSSPCs**

In flow cytometry sorting, PDGFRAlow/−PDPN+CADM1+ cells showed significantly higher CFU-F colony formation efficiency compared to PDGFRAlow/−PDPN+CADM1− and PDGFRAlow/−PDPN− cells (69.33 vs 25.67 vs 4.67 colonies per 4.5×10³ cells). Mesenchymal sphere formation showed a similar trend. PDGFRAlow/−PDPN+CADM1+ cells maintained eSSPC immunophenotype after serial passaging. In vitro differentiation demonstrated osteogenic and chondrogenic potential but not adipogenic potential. In vivo subrenal capsule transplantation at 8 weeks confirmed osteo-chondrogenic differentiation, but bone marrow microenvironment reconstitution was not observed (a functional difference from growth plate human SSCs).

**Identification of neural crest-derived skeletal progenitor cells (NCDCs) in calvaria**

scRNA-seq of 8 WPC calvaria identified 12 cell populations: NGFR+ cranial neural crest (NC), GJA1+ VLMCs, migratory NC (mig_NC), **NCDC (Neural crest-derived cells, BMP4+FOXC2+)**, RUNX2+ osteoprogenitor cells, OSR2+ PMSCs, SOX9+ chondrocytes, etc. NCDCs shared surface markers with long bone eSSPCs (PDGFRAlow/−PDPN+CADM1+) and were located in the outer layer of the sagittal suture. Slingshot analysis showed that FOXC1+ NC lineage and TWIST2+ mesodermal lineage converged on DLX5+ osteoprogenitor cells, with NCDCs playing a key role in the transition from mig_NC to osteoprogenitor cells. SCENIC analysis revealed that NCDCs were also enriched for FOXP1/2/4 regulons.

---

## Perspective

This study is the first to construct a single-cell transcriptome map of human embryonic skeletal development, elucidating the spatial heterogeneity of limb bud mesenchyme, the emergence of OCPs, and skeletal stem/progenitor cell populations with distinct developmental origins in long bones and calvaria. Long bone eSSPCs are located in the perichondrium, can be identified by CADM1/PDPN, are regulated by the FOXP1/2 transcriptional network, and differentiate into osteo-chondrogenic lineages but not adipocytes or hematopoietic stroma. Calvarial NCDCs are neural crest-derived, mediate intramembranous ossification, and share FOXP1/2/4 regulons. These findings are consistent with previous reports that FOXP transcription factors interact with Runx2 in perichondrial skeletal progenitor cells to suppress transactivation and maintain an undifferentiated state, suggesting that the FOXP family plays a fundamental role in maintaining human embryonic skeletal stem cells. CADM1 was previously known as an osteosarcoma diagnostic marker, but this study reveals its novel function as an embryonic skeletal stem cell marker. The inability of eSSPCs to reconstitute the bone marrow microenvironment demonstrates functional differences from growth plate SSCs, emphasizing the heterogeneity of SSCs across skeletal developmental stages and compartments. The human embryonic skeletal stem/progenitor cells and molecular markers identified in this study provide important resources for cell therapy and tissue engineering in skeletal diseases such as fracture nonunion, osteoporosis, and craniofacial defects. Future lineage-tracing studies are needed to elucidate the relationship between eSSPCs and postnatal growth plate, periosteal, and perivascular SSCs, along with functional validation using inducible Cre models.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
