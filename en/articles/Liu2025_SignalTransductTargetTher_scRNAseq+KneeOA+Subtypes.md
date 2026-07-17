---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
raw_data:
  - "GEO: GSE267616"
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Single-cell transcriptomics reveals novel chondrocyte and osteoblast subtypes and their role in knee osteoarthritis pathogenesis

## Citation (NLM)

Liu Y, Da W, Xu MJ, Xiao CX, Deng T, Zhou SL, Chen XT, Zhou YJ, Tang L, Nie Y, Zeng Y, Xie HQ, Shen B. Single-cell transcriptomics reveals novel chondrocyte and osteoblast subtypes and their role in knee osteoarthritis pathogenesis. _Signal Transduct Target Ther._ 2025 Feb 12;10(1):40. doi: [10.1038/s41392-025-02136-8](https://doi.org/10.1038/s41392-025-02136-8).

---

## Background

Knee osteoarthritis (KOA) is a major disease affecting the quality of life in middle-aged and elderly populations, and its increasing incidence in younger patients has emerged as a public health concern. The pathogenesis of KOA is multifactorial and affects the entire joint, with pathological remodeling of subchondral bone serving as a key mediator of overlying cartilage degeneration. Hypermetabolism of subchondral bone and decreased calcium/collagen ratio lead to under-mineralization, and increased mechanical loading causes microfractures at the cartilage-subchondral bone junction, resulting in tidemark disruption, vascular invasion, and exacerbated cartilage degeneration. Single-cell RNA sequencing (scRNA-seq) is a powerful tool for elucidating cellular heterogeneity and molecular mechanisms in KOA, but existing studies have been limited to either subchondral bone or cartilage alone, with few integratively analyzing crosstalk between the two tissues. This study developed a novel postmenopausal KOA mouse model combining estrogen deficiency and increased mechanical loading, constructed a single-cell atlas of the osteochondral complex (femoral condyle), and aimed to identify novel chondrocyte and osteoblast subpopulations and their roles in KOA pathogenesis.

---

## Key Experiment Methods

**1. Postmenopausal KOA mouse model construction**

- 6 groups: normal male (MN), bipedal walking male (MB), normal female (FN), bipedal walking female (FB), ovariectomized female (FO), bipedal walking + ovariectomized female (FBO)
- 3-week-old C57 mice underwent tail and forelimb amputation; bilateral ovariectomy performed in half of females at 10 weeks of age
- Monthly KOA phenotype evaluation from 10 to 22 weeks of age

**2. Histology and imaging analysis**

- H&E, Safranin O/Fast Green (SO&FG) staining, Collagen II/Aggrecan immunohistochemistry
- TEM for ultrastructural observation of chondrocytes and osteoblasts
- Micro-CT quantification of BV/TV, BMD, Tb.Th, Tb.Sp
- Body composition analysis (BMD, bone mineral content, fat mass, lean mass) using InAlyzer

**3. Gait analysis and finite element analysis (FEA)**

- Stride length, walking speed, stance time, step cycle, and asymmetry index measured using CatWalk
- 3D reconstruction from micro-CT DICOM data followed by FEA for stress distribution analysis on cartilage surface and subchondral bone

**4. Single-cell RNA sequencing (scRNA-seq)**

- 10 femoral condyles isolated from 5 mice per group at 22 weeks, scRNA-seq using STRT strategy
- CD45+ cells sorted by flow cytometry, then CD45+ and CD45− cells mixed at 1:1 ratio
- 65,491 cells analyzed after quality control from 82,083 total cells; 15 cell types and 26 clusters identified

**5. In vitro mechanical stretching model**

- Chondrocytes stretched for 24 hours using IonOptix C-Pace EM stretch system
- Analysis of PIEZO1, ADAMTS5, MMP13, COL2A1, ACAN, SOX9 expression

**6. ANGPTL7 and SPARC functional experiments**

- ANGPTL7 knockdown/overexpression in human chondrocytes, tube formation assay with HUVECs co-culture (FGF2, FGFR2 inhibitor Alofanib treatment)
- Sparc knockdown/overexpression in MC3T3 osteoblast-like cells, bone mineralization assessed by Alizarin Red staining (ARS)

**7. Clinical specimen validation**

- Immunohistochemistry for ANGPTL7 and SPARC in tibial plateau specimens from KOA patients and normal donors, correlation analysis with OARSI score

---

## Results

**Pathological subchondral bone remodeling in clinical KOA patients** The medial tibial plateau showed more severe cartilage damage and pronounced subchondral bone hyperplasia/sclerosis compared to the lateral side. BV/TV, Tb.N, and Tb.Th were increased but BMD was decreased, indicating under-mineralization. Vascular invasion into cartilage was observed in early KOA, and cartilage-like tissue was deposited within subchondral bone trabeculae in late KOA. Type H vessel (CD31hiEMCNhi) density was significantly increased in the KOA group.

**Validation of bipedal walking postmenopausal KOA model** The FBO group showed the most pronounced cartilage thickness reduction, increased OARSI score, and Collagen II/Aggrecan loss at 22 weeks. TEM revealed chondrocyte mitochondrial swelling, endoplasmic reticulum expansion, and nuclear envelope widening. FBO mice exhibited shortened stride length, reduced walking speed, and prolonged stance time, with decreased BV/TV, BMD, Tb.Th and increased Tb.Sp in subchondral bone. Both TRAP+ osteoclasts and osteocalcin+ osteoblasts were increased, indicating simultaneous activation of bone resorption and formation.

**Mechanical stress and cartilage degeneration** The "mechanical stimulus response" pathway AUCell score was significantly higher in chondrocytes and osteoblasts of FBO and FB groups, with increased Piezo1 expression. FEA showed the highest cartilage and subchondral bone stress in the FBO group. In the in vitro stretching model, chondrocytes became elongated with increased ADAMTS5/MMP13 expression and decreased COL2A1/ACAN/SOX9 expression.

**Single-cell atlas and cell type identification** 15 cell types were identified from 65,491 cells (chondrocytes 16,378, endothelial cells 553, osteoblasts 2,203, progenitor cells 5,461, etc.). Chondrocytes in the FBO group showed altered genes related to oxidative stress, angiogenesis, aging, and ECM regulation abnormalities.

**Identification of 3 novel chondrocyte subpopulations** 6 subpopulations were identified from 16,378 chondrocytes: Smoc2+ angiogenic chondrocytes (AngC-1), Angptl7+ angiogenic chondrocytes (AngC-2), prehypertrophic chondrocytes, aging chondrocytes, Col1a1+ osteogenic chondrocytes, and inflammatory chondrocytes. AngC-2 (Angptl7+) was increased in the FBO group and was confirmed to promote angiogenesis through interaction with endothelial cells via the FGF2-FGFR2 ligand-receptor pair. In vitro, ANGPTL7 overexpression exacerbated cartilage degeneration, while knockdown increased COL2A1/ACAN/SOX9 and decreased ADAMTS5/MMP13. ANGPTL7+ chondrocytes promoted the tube formation capacity of HUVECs, and this effect was attenuated by the FGFR2 inhibitor Alofanib.

**Sparc+ osteoblasts inhibit bone mineralization** In the FBO group, bone mineralization-inhibiting genes such as Sparc, Ecm1, Mgp, and Srgn were upregulated, while osteogenic differentiation-related genes such as Runx2, Ibsp, Alpl, and Bmp2 were downregulated. Osteoblasts were divided into two subpopulations; Sparc+ OB5 showed high Sparc/Bglap/Col1a1 but low Runx2/Alpl/Timp2, associated with insufficient osteogenic differentiation and mineralization. In vitro, Sparc knockdown increased COL1A1, OCN, ALP and expanded ARS-positive area, while overexpression inhibited osteogenic differentiation.

**Positive correlation between ANGPTL7 and SPARC expression and KOA progression** ANGPTL7 (chondrocytes) and SPARC (osteoblasts) expression was significantly increased in tibial plateau specimens from KOA patients compared to normal controls, and the proportion of positive cells showed a positive correlation with OARSI score.

---

## Perspective

This study developed a novel postmenopausal KOA mouse model combining estrogen deficiency and increased mechanical loading, and through single-cell transcriptomic analysis of the osteochondral complex, identified 3 novel chondrocyte subpopulations (Smoc2+, Angptl7+, Col1a1+) and dysfunctional osteoblasts (Sparc+) that are critical in KOA pathogenesis.

The mechanism by which Angptl7+ chondrocytes interact with endothelial cells via FGF2-FGFR2 signaling to mediate subchondral bone angiogenesis and Type H vessel increase, leading to recruitment of osteoprogenitor cells and promoted bone formation, but with insufficient mineralization due to Sparc+ osteoblast dysfunction resulting in weakened mechanical support, provides an integrated explanation of the pathological cartilage-subchondral bone interaction in KOA.

The increased expression of ANGPTL7 and SPARC in clinical KOA specimens and their positive correlation with disease severity (OARSI score) suggest that these cell subpopulations could serve as novel therapeutic targets for KOA. Therapeutic strategies targeting the Angptl7+ chondrocyte-endothelial cell axis for angiogenesis inhibition, or promoting mineralization through functional improvement of Sparc+ osteoblasts, could be developed as KOA treatment approaches.

Limitations of this model include the long duration required for model construction (3 to 22 weeks), the possibility that single-cell results may be limited to KOA subtypes characterized by subchondral bone remodeling, and the need for long-term observation of late-stage KOA subchondral bone remodeling.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE267616


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
