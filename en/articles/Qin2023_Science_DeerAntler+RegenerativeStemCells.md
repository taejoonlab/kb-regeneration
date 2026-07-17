---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
---

# A population of stem cells with strong regenerative potential discovered in deer antlers

## Citation (NLM)

Qin T, Zhang G, Zheng Y, et al. A population of stem cells with strong regenerative potential discovered in deer antlers. Science. 2023;381(6657):eadd0488. doi:10.1126/science.add0488

**DOI:** [https://doi.org/10.1126/science.add0488](https://doi.org/10.1126/science.add0488)

---

## Background

Deer antlers are the only mammalian model of complete organ regeneration that occurs repeatedly on an annual cycle, providing clinically important insights into long bone development and regeneration. Each spring, after the hard antler detaches from the pedicle, the bony and cartilaginous tissues of the antler regenerate completely from the pedicle periosteum. Antlers elongate over 3–4 months from late spring to early summer at a remarkable growth rate of approximately 2.75 cm/day, the fastest bone growth rate among medium-to-large mammals. Previous studies have largely remained at the histological and morphological level, and the cellular and molecular mechanisms enabling homeostasis and rapid growth remained unclear. The authors sought to identify the stem cell population driving antler regeneration and its spatiotemporal dynamics by combining single-cell transcriptomic analysis (scRNA-seq) with functional experiments.

---

## Key Experiment Methods

**1. Single-cell transcriptomic atlas construction**
- scRNA-seq performed across 8 time points encompassing the entire antler regeneration cycle (10 days before casting, 0, 2, 5, 10, 45, 60, and 90 days after casting)
- Analysis of 74,730 cells total
- De novo construction of a chromosome-level reference genome for male sika deer for high-confidence genomic analysis

**2. Cell population classification and developmental trajectory analysis**
- Seurat-based unsupervised clustering identified 8 cell populations (PRRX1+ mesenchymal cells, SOX9+ chondroblasts, PHEX+ osteoblasts, COL3A1+ fibroblasts, CHAD+ chondrocytes, ACTA2+ pericytes, PECAM1+ endothelial cells, PTPRC+ immune cells)
- Monocle 2 pseudotime analysis to reconstruct cell fate decision pathways
- Differentiation trajectory: PMC (PRRX1+ mesenchymal cells) → chondroblasts → chondrocytes

**3. Ectopic antler regeneration experiment (nude mouse)**
- Transplantation of cell masses from day 0 and day 5 post-casting into immunodeficient mouse calvaria
- Confirmation of transplanted cell origin using tdTOMATO-labeled mice

**4. ABPC phenotype and functional analysis**
- FACS isolation of CX43+FGFR2+ ABPCs
- In vitro: CFU-F (fibroblast colony formation), trilineage differentiation (osteogenic/chondrogenic/adipogenic) assessment
- In vivo: Subrenal capsule transplantation in immunodeficient mice, bone regeneration assessment in rabbit femoral condyle defect model

**5. Spatial heterogeneity analysis of rapidly growing antlers**
- Isolation of 5 tissue layers (mesenchymal layer, precartilaginous layer, cartilaginous layer, prehypertrophic layer, hypertrophic layer) from the antler growth center (AGC) at day 60 for scRNA-seq and bulk RNA-seq
- Cross-comparison analysis with mouse embryonic limbs

**6. Immunohistochemistry**
- IHC confirmation of key cell markers (PRRX1, POSTN, SOX9, CX43, FGFR2, etc.)

---

## Results

**Homeostatic presence of PRRX1+ mesenchymal cells (PMCs)**
PMCs were present in the pedicle periosteum from before antler regeneration (10 days before casting), suggesting a stem cell-based regeneration mechanism, distinct from the dedifferentiation process observed in salamander limb regeneration.

**Discovery of antler blastema progenitor cells (ABPCs)**
A new cell population (PMC4, TNN+PTN+TNC+DLX5+) derived from PMC2 (periosteal mesenchymal progenitor) emerged at day 5 post-casting. These cells exhibited markedly higher fibroblast colony-forming capacity, maintained self-renewal ability upon passaging, showed superior osteochondrogenic differentiation compared to bone marrow stromal cells (BMSCs), but lacked adipogenic differentiation capacity. These cells could be isolated using CX43+FGFR2+ surface markers, and the authors termed them "antler blastema progenitor cells" (ABPCs).

**Blastema conservation**
The day 5 post-casting tissue met the definition of a blastema. Cross-species comparison revealed that ABPC-like cells were found in regenerating mouse terminal phalanges (P3) but not in non-regenerating middle phalanges (P2), salamander limbs, or zebrafish tail fins. This suggests that ABPCs may be a cell population specialized for mammalian appendage regeneration.

**In vivo regenerative capacity confirmed**
Subrenal capsule transplantation of CX43+FGFR2+ cells resulted in significantly larger areas of cartilage and bone formation compared to BMSCs at 8 weeks (p<0.001). In a rabbit femoral condyle cartilage defect model, CX43+FGFR2+ cells achieved higher bone volume fraction (BV/TV) and trabecular number (Tb.N) than BMSCs.

**Spatial cellular architecture of the rapidly growing AGC**
The antler growth center (AGC) displayed a clear spatial cell differentiation gradient, from the distal mesenchymal layer (ABPC 49.96% + perichondral cell 29.68%) to the proximal hypertrophic cartilage layer (osteoblasts 63.87%). Wnt pathway genes (WNT10B, WNT10A, WNT6) were highly expressed in the precartilaginous layer, while mineralization-related genes such as MMP9 and MMP12 were highly expressed in the hypertrophic layer. One hundred fifty-one highly expressed genes were shared with the mouse embryonic limb growth plate, suggesting that the AGC utilizes molecular mechanisms similar to mammalian limb development.

---

## Perspective

This study provides a comprehensive single-cell atlas of the deer antler regeneration process and represents a landmark discovery of a novel regenerative progenitor population, ABPCs (CX43+FGFR2+), with functional validation. The key significance is as follows.

First, ABPCs are a unique stem cell population that possesses only osteochondrogenic (bipotential) differentiation capacity without adipogenic potential, exhibiting superior proliferation and differentiation abilities compared to conventional BMSCs, making them a candidate cell therapy for bone and cartilage regeneration.

Second, ABPCs demonstrate that the blastema is a conserved biological feature in mammalian appendage regeneration. ABPCs are present only in regenerating mouse terminal phalanges (P3) and absent in non-regenerating sites (P2), providing important insights into the cellular basis of mammalian regenerative capacity.

Third, the spatial transcriptomic map of the AGC shows that antlers follow a differentiation gradient similar to the embryonic long bone growth plate, but are enriched in angiogenesis-related genes, distinguishing them from typical avascular cartilage.

Fourth, technology to convert human mesenchymal cells into ABPC-like cells could open innovative possibilities for future limb regeneration or skeletal damage regenerative medicine.

Future challenges include in-depth investigation of the molecular regulatory mechanisms of ABPCs, resolution of immune rejection and safety issues in xenotransplantation, and review of ethical and legal considerations.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
