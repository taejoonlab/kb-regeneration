---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Craniofacial chondrogenesis in organoids from human stem cell-derived neural crest cells

## Citation (NLM)
Foltz L, Avabhrath N, Lanchy JM, Levy T, Possemato A, Ariss M, Peterson B, Grimes M. Craniofacial chondrogenesis in organoids from human stem cell-derived neural crest cells. iScience. 2024 Apr 19;27(4):109585. doi:10.1016/j.isci.2024.109585

**DOI:** [https://doi.org/10.1016/j.isci.2024.109585](https://doi.org/10.1016/j.isci.2024.109585)

---

## Background

Craniofacial reconstruction is required for congenital anomalies, head and neck cancer treatment, and traumatic facial injuries, but graft rejection and donor site morbidity remain problematic. Stem cell-based craniofacial cartilage regeneration holds transformative potential to address these issues. Unlike articular cartilage, craniofacial cartilage originates from the neural crest, and human-specific knowledge of the signaling pathways regulating chondrocyte differentiation remains incomplete. This study aimed to generate self-organizing craniofacial cartilage organoids from human embryonic stem cell (hESC)- and induced pluripotent stem cell (iPSC)-derived neural crest stem cells (NCSCs) and to comprehensively characterize the differentiation mechanisms using snRNA-seq and proteomics.

---

## Key Experiment Methods

1. **NCSC differentiation protocol**: hESC/iPSC → neuroectoderm (dual SMAD inhibition: LDN193189 + SB431542) → NCSC specification (CHIR99021/WNT activation, Shh, FGF8, ascorbic acid, BDNF) → p75/NGFR MACS selection → monolayer culture on Poly-L-ornithine/laminin/fibronectin-coated dishes. NCSCs were maintained in FGF2/EGF maintenance medium.

2. **Organoid formation**: Upon reaching confluence, NCSCs spontaneously aggregated and detached from the dish surface, forming floating organoids. Production could be maintained for up to 1 year.

3. **snRNA-seq (single nuclei RNA sequencing)**: 10x Genomics-based. Analyzed NCSC (day 1), day 28, and day 87 differentiated cells. Seurat clustering, UMAP/t-SNE visualization.

4. **TMT mass spectrometry (TMT-MS)**: Total proteome and PTM (phosphorylation/acetylation/methylation) profiling of hESC (WA09), neural stem cells (NSC), NCSC, and cartilage organoids. BioPlanet pathway analysis and Pathway Crosstalk Network (PCN) construction.

5. **Histochemical staining**: H&E, Safranin O, Toluidine Blue, Weigert's resorcin-fuchsin (elastic fibers). Immunofluorescence: COL2A1, COL1A1, SOX9, COMP, MATN1, DCX, PTPRZ1, DDR1/2, PDGFRA, DCN, TNC, etc.

6. **Ligand–receptor interaction analysis**: Autocrine/paracrine signaling between cell populations analyzed using the connectome package.

---

## Results

**1. NCSC→chondrocyte organoid differentiation established** Organoids up to 1 cm in diameter formed through spontaneous aggregation of NCSC monolayers. Histological staining revealed elastic cartilage features: cell nuclei within lacunae, Safranin O/Toluidine Blue-positive matrix, and Weigert's resorcin-fuchsin-positive elastic fibers. Structure resembled human auricular cartilage.

**2. Cell population identification** snRNA-seq identified 6 clusters: NCSC, chondrocytes, mesenchymal cells, neuroblasts, and melanocytes. The chondrocyte cluster showed high expression of collagen genes (COL2A1, COL11A1, etc.), proteoglycan genes (ACAN, VCAN), and elastic fiber synthesis genes (ELN, FBN1, LOX). Immunofluorescence showed COL2A1 localized to the organoid core and COL1A1 to the periphery.

**3. Proteomics** TMT-MS identified 11,064 proteins. Cartilage organoids showed significant upregulation of 25 cartilage markers and 131 ECM proteins compared to NCSCs. Collagen X (COL10A1) was undetected, indicating maintenance of an elastic cartilage phenotype without hypertrophic differentiation. BioPlanet pathway analysis revealed enrichment of ECM organization, TGF-β regulation of ECM, and chondroitin sulfate/dermatan sulfate biosynthesis.

**4. Mesenchyme–chondrocyte interactions** Day 28 snRNA-seq identified two progenitor populations: mesenchymal cells (neural crest-like) and nascent chondrocytes. Connectome analysis revealed paracrine signaling from mesenchyme (EGF, PTN, WNT3, WNT7B secretion) to chondrocytes, as well as autocrine chondrocyte-to-chondrocyte signaling (ECM-integrin/DDR feedforward). PTPRZ1+ mesenchyme was confined to the outer layer of mature organoids, transitioning to COL2A1+ chondrocytes in the core.

**5. Autocrine role of ECM** A feedforward mechanism was identified in which ECM components secreted by chondrocytes directly reinforce the chondrocyte phenotype via integrin/receptor signaling. COL2A1-integrin α5, collagen receptor DDR2, and proteoglycan signaling pathways were identified. ECM removal led to loss of the cartilage phenotype, demonstrating that ECM is essential for cell fate determination beyond its role as a structural support.

---

## Perspective

This study is the first to generate self-organizing craniofacial cartilage organoids from human neural crest stem cells and to comprehensively characterize the cellular and molecular mechanisms of craniofacial chondrogenesis using snRNA-seq and total proteome analysis.

Key significance: (1) It presents a differentiation pathway specific to neural crest-derived cartilage, distinct from conventional mesoderm-derived cartilage; (2) paracrine signaling between mesenchyme and chondrocytes as well as ECM-based autocrine feedforward signaling were identified as drivers of cartilage formation; (3) organoids maintained an elastic cartilage phenotype without hypertrophic differentiation over extended culture, demonstrating their potential as a suitable cell source for craniofacial reconstruction.

Future challenges include: (1) in vivo safety and functional validation after organoid transplantation, (2) complete characterization of the neural crest origin of mesenchymal cells and their properties as progenitors, (3) disease modeling and drug screening for craniofacial malformations using patient-specific iPSC-derived organoids, and (4) systematic comparison with mesoderm-derived cartilage formation protocols for articular cartilage regeneration.


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
