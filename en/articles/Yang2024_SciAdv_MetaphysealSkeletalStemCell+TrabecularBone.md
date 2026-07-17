---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Identification of the metaphyseal skeletal stem cell building trabecular bone

## Citation (NLM)
Yang G, He Q, Guo X, Li RY, Lin J, Lang Y, Tao W, Liu W, Lin H, Xing S, Qi Y, Xie Z, Han JDJ, Zhou B, Teng Y, Yang X. Identification of the metaphyseal skeletal stem cell building trabecular bone. Sci Adv. 2024;10(8):eadl2238. doi:10.1126/sciadv.adl2238

**DOI:** [https://doi.org/10.1126/sciadv.adl2238](https://doi.org/10.1126/sciadv.adl2238)

---

## Background

Skeletal stem cells (SSCs) possess self-renewal capacity and multilineage differentiation potential, contributing to bone development and homeostasis. Although various SSC populations have been reported at different anatomical sites, the SSC population specific to the metaphysis and its characteristics have not been fully elucidated. Previous studies have shown that hypertrophic chondrocytes (HCs) can transdifferentiate into osteoblasts and bone marrow stromal cells (BMSCs), but the hierarchy of HC-derived cells and the molecular mechanism of this transdifferentiation remain unclear. This study aimed to identify a new SSC population, termed metaphyseal SSC (mpSSC), located in the metaphysis directly beneath the growth plate, and to elucidate the process by which HC-derived cells form trabecular bone.

---

## Key Experiment Methods

- **scRNA-seq**: Analysis of 5,861 non-hematopoietic/non-endothelial cells and 1,998 ZsGreen+ HC progeny from distal femur/proximal tibia of P7.5 Col10a1-ZsGreen mice. 10x Genomics, Illumina.
- **Genetically engineered mouse lines**: Generation of multiple CRISPR gene-edited mice including Col10a1-Cre, Col10a1-memG-mitoS-DD-Cre-DD, Sstr2-CreERT2, Sstr2-CreXER, Pdgfrb-LSL-Dre, Ihh-Dre knock-in.
- **Lineage tracing**: Sequential dual recombination tracing using Col10a1-Cre;Pdgfrb-LSL-Dre;ROSA26-LSL-EYFP/RSR-tdTomato (CPYT) mice. Confetti2 clonal analysis, Col2a1-CreERT;ROSA26-nTnG single-cell clone tracing.
- **Immunofluorescence (IF)**: Multi-IF staining to analyze expression of markers including Sstr2, Pdgfrb, Kitl, Ncad, Pdpn.
- **In vitro CFU-F and multilineage differentiation**: Successful CFU-F formation from CPYT bone marrow mononuclear cells, assessment of trilineage (chondrogenic, osteogenic, adipogenic) differentiation.
- **Renal capsule transplantation**: FACS-sorted tdTomato+Pdgfrb+Kitl- mpSSCs transplanted under the renal capsule of immunodeficient mice; bony organoid formation confirmed after 4 weeks.
- **Bone defect transplantation model**: mpSSCs transplanted into bone defect sites; self-renewal and differentiation assessed after 14 days.
- **Micro-CT**: Evaluation of trabecular bone parameters (BMD, BV/TV, Tb.N, Tb.Th, Tb.Sp).
- **Hgs conditional knockout**: Col10a1-Cre;Hgsfl/fl mice to analyze the effect of HC-specific Hgs deletion on mpSSC conversion and trabecular bone formation.

---

## Results

### Discovery of Sstr2+/Pdgfrb+Kitl- mpSSCs
- scRNA-seq identified cluster 1 (mpSSC) among 14 skeletal cell clusters: specifically marked by Sstr2 alone or a Pdgfrb+Kitl- combination.
- mpSSCs are localized to the metaphyseal zone (MPZ) directly beneath the hypertrophic layer of the growth plate.
- Partial overlap with the CD200+CD51+Thy1-Ly51-CD105- signature.

### mpSSCs are direct progeny of HCs
- scRNA-seq of Col10a1-ZsGreen HC progeny: differentiation trajectory of HC → mpSSC → tBMSC → RetiC/OLC.
- Slingshot pseudotime confirmed HC → mpSSC → tBMSC differentiation continuum. SCENT analysis showed mpSSCs have the highest differentiation entropy.
- Col2a1-CreERT;nTnG clonal tracing demonstrated in vivo single HC → Sstr2+ mpSSC conversion.
- Acan-CreERT2;nTnG short-term tracing: 51.4% of HC progeny were Sstr2+ mpSSCs.
- Renal capsule transplantation confirmed HC tissue converted to tdTomato+Pdgfrb+ cells.

### mpSSCs exhibit in vivo SSC function
- Ihh-Dre;Sstr2-CreERT2;Confetti2 clonal analysis: Sstr2+ cells possess self-renewal (maintenance of Sstr2+ cells within Confetti+ clones) and multilineage differentiation (Sstr2+ → BMSC, OLC).
- CPYT mice: EYFP+tdTomato+ (cells with HC→Pdgfrb expression history) differentiated into Sstr2+ mpSSCs, Sstr2-Pdgfrb+ BMSCs, Ncad+ OLCs, and Pdpn+ osteocytes.
- Maintenance of Sstr2+ cells after P30 indicates long-term self-renewal capacity.

### In vitro/ex vivo SSC function
- CPYT bone marrow CFU-F: Only EYFP+tdTomato+ cells formed CFU-Fs (EYFP+tdTomato- cells could not). Among 30 clones, 9 showed trilineage differentiation, with 3 maintaining capacity after 2 passages.
- FACS-sorted tdTomato+Pdgfrb+Kitl- mpSSCs → renal capsule transplantation: bony organoid formation (Sox9+ cartilage, Ncad+ OLCs, Pdgfrb+/Kitl+ stromal cells).
- Bone defect transplantation: mpSSCs regenerated their own compartment (maintaining tdTomato+Pdgfrb+Kitl-) and generated diverse progeny.

### mpSSCs generate the majority of HC progeny
- CPYT mouse time-series analysis: P1 EYFP+tdTomato+:EYFP+tdTomato- = 1:2.19 → by P7, 77.1% reversal → by P30, 96.7%.
- Trabeculae: EYFP+tdTomato+ cells constituted 80.0% (P7) → 99.5% (P30), indicating mpSSCs drive the majority of HC progeny and trabecular bone formation.
- Ki67+ proliferating cells were enriched in the EYFP+tdTomato+ population. Ki67+ ratio among Sstr2+ cells decreased with age (P7: 38.2% → P180: 9.0%).

### Hgs is a key regulator of HC→mpSSC conversion
- HC-1 cluster GO/KEGG analysis: enrichment of endosomal transport pathway → identified Hgs (hepatocyte growth factor-regulated tyrosine kinase substrate) expression.
- Col10a1-Cre;Hgsfl/fl: HC-specific Hgs deletion resulted in 76.4% reduction of Sstr2+ mpSSCs. Total EYFP+tdTomato+ (cells with Pdgfrb expression history) also decreased.
- Hgs deletion did not affect proliferation/apoptosis of HC progeny → specifically impaired HC→mpSSC conversion.
- Instead, EYFP+tdTomato-Ncad+ OLCs (direct HC→OLC conversion pathway) increased 1.36-fold → compensatory mechanism.

### Hgs deletion impairs trabecular bone formation
- P30 Hgs KO mice: marked reduction in BMSC and OLC populations.
- Micro-CT: significant decrease in BMD, BV/TV, Tb.N, Tb.Th; increase in Tb.Sp.
- Partial recovery by P90 → suggests compensation by other SSC populations (e.g., periosteal-derived).
- Hgs deletion in BMSCs (Lepr-Cre) showed normal phenotype → HC-specific phenomenon.

---

## Perspective

- This study identified a new SSC population, mpSSC (Sstr2+/Pdgfrb+Kitl-), derived from HCs and localized to the metaphysis, and demonstrated that they are the primary cellular source of postnatal trabecular bone formation.
- It established the differentiation hierarchy of HC→mpSSC→tBMSC/OLC and demonstrated that HC dedifferentiation into mpSSCs is a core process of endochondral ossification.
- It discovered that the Hgs/endosomal transport pathway is essential for HC→mpSSC conversion, and that impairment of this pathway leads to trabecular bone formation defects.
- It proposes that previously reported BMSC populations (Gli1+, Lepr+, Grem1+, Osterix+, etc.) are downstream progeny of mpSSCs, providing an integrated framework for understanding SSC hierarchy.
- It suggests new targets (mpSSC, Hgs pathway) for understanding the pathological mechanisms and developing therapeutic strategies for trabecular bone diseases such as osteoporosis and osteogenesis imperfecta.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
