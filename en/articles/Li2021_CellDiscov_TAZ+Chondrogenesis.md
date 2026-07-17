---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add Data Availability section"
---

# TAZ is required for chondrogenesis and skeletal development

## Citation (NLM)

Li Y, Yang S, Qin L, Yang S. TAZ is required for chondrogenesis and skeletal development. _Cell Discov._ 2021 Apr 19;7(1):26. doi: [10.1038/s41421-021-00254-5](https://doi.org/10.1038/s41421-021-00254-5).

---

## Background

The Hippo signaling pathway is a conserved pathway involved in organ size control, tissue regeneration, cell proliferation, apoptosis, autophagy, and carcinogenesis. TAZ (Transcriptional coactivator with PDZ-binding motif) is a key downstream effector of the Hippo pathway, known to maintain the balance between osteoblast differentiation (interacting with Runx2) and adipocyte differentiation inhibition (suppressing PPARγ). YAP, a paralog of TAZ, has been reported to regulate multiple stages of chondrocyte differentiation, but the role of TAZ in chondrogenesis and cartilage development remains unknown. Systemic TAZ knockout mice exhibited small body size and ossification defects, but the effects of chondrocyte lineage-specific TAZ deletion have not been studied. This study generated chondrocyte lineage-specific TAZ knockout mice (Col2-Cre;TAZf/f) using Col2a1-Cre to elucidate the role and molecular mechanisms of TAZ in chondrocyte proliferation, differentiation, maturation, and skeletal development.

---

## Key Experiment Methods

**1. Generation of Col2-Cre;TAZf/f conditional knockout mice**

- Breeding of TAZf/f mice with Col2a1-Cre transgenic mice
- Analysis of neonatal, 1-month, and 4-month-old mice

**2. Skeletal staining and micro-CT analysis**

- Alizarin Red/Alcian blue whole-body skeletal staining
- Micro-CT: quantification of BV/TV, Tb.Th, Tb.N, Tb.Sp in femurs of 1-month-old mice

**3. Histology**

- Safranin O/fast green, H&E, Alcian blue staining
- Growth plate (resting, proliferative, pre-hypertrophic, hypertrophic zones) length measurement
- Articular cartilage thickness measurement
- Von Kossa staining (mineralization), Calcein double labeling (MAR, BFR)

**4. Primary chondrocyte culture and micromass culture**

- Primary chondrocyte isolation from limb embryos of E15.5 WT and Col2-Cre;TAZf/f mice
- Chondrogenic differentiation induced by micromass culture (7-10 days)
- WST-1 proliferation assay, colony formation assay

**5. Gene manipulation experiments**

- TAZ knockdown with shTAZ lentivirus
- TAZ overexpression with pCDNA3.1-TAZ
- Sox5 manipulation with shSox5, GFP-Sox5
- Runx2 overexpression

**6. Molecular mechanism analysis**

- Co-IP: confirmation of TAZ-Sox5 interaction
- Immunofluorescence: intracellular localization of TAZ, Sox5, Runx2, Col10a1
- ChIP assay: TAZ/TEAD1-Sox5 promoter binding, TAZ/Runx2-Col10a1 promoter binding
- Sox5 protein stability analysis with cycloheximide (CHX) treatment
- qRT-PCR: chondrogenic differentiation markers (Col2a1, Col9a1, Col10a1, Acan, Mmp13, Runx2, Ihh, etc.)

**7. TUNEL and BrdU analysis**

- TUNEL staining: apoptosis quantification
- BrdU labeling: proliferating cell quantification

**8. Fracture healing model**

- Closed femoral fracture model in 3-month-old mice
- X-ray, micro-CT, Alcian blue staining, and gene expression analysis at 2 weeks post-fracture

---

## Results

**TAZ expression gradually increases during chondrogenesis**

In publicly available data (GSE30138) heatmap of mouse limb development (E9.5-E13.5), TAZ-related genes (CTGF, CYR61) were upregulated, while TAZ activity inhibitors (MST1, LATS1, MOB1) were decreased. In WT mouse tibial growth plates, TAZ expression gradually increased from E16.5 to P1. In micromass culture, TAZ protein and mRNA expression peaked at days 7-10 alongside chondrogenic differentiation markers (MMP13, Runx2, Ihh, Col2a1, Col10a1, Aggrecan). In contrast, TAZ expression gradually decreased in articular cartilage from 1 month to 4 months.

**TAZ deficiency impairs growth plate and articular cartilage development**

Col2-Cre;TAZf/f neonates exhibited growth retardation and short limbs, with Alizarin Red/Alcian blue staining revealing impaired skull development, hypoplastic ribs/sternum, and short limb skeletons. Histologically, the proliferative, pre-hypertrophic, and hypertrophic zones of the growth plate were all shortened. In 1-month-old TAZ-deficient mice, articular cartilage thickness was greater than controls, but at 4 months, articular cartilage damage was clearly observed. TAZ deficiency reduced Col2a1, Col9a1, Col10a1, Acan, and Mmp13 expression.

**TAZ deficiency impairs bone development**

Micro-CT showed reduced bone mass in 1-month-old Col2-Cre;TAZf/f mice, with decreased BV/TV (1.77-fold), Tb.N (1.65-fold), Tb.Th (1.59-fold), and increased Tb.Sp (1.74-fold). Von Kossa staining revealed markedly reduced long bone mineralization in E18.5 TAZ-deficient mice. Calcein labeling showed decreased bone formation rate (BFR) and mineral apposition rate (MAR).

**TAZ is required for chondroprogenitor cell proliferation**

The proliferation rate of TAZ-deficient chondrocytes was significantly reduced at D1, D2, and D3. TAZ silencing with shTAZ suppressed proliferation, while TAZ overexpression promoted it. Colony number was also reduced in TAZ deficiency. In vivo BrdU labeling showed significantly reduced proliferating cells in the tibial growth plates of 10-day-old Col2-Cre;TAZf/f mice. TUNEL staining showed decreased apoptosis in the articular cartilage of 1-month-old TAZ-deficient mice.

**TAZ cooperates with TEAD1 to regulate Sox5 expression**

Co-IP confirmed that TAZ and Sox5 bind within the nucleus. Sox5 silencing reduced TAZ target genes (Cyr61, CTGF, BDNF), and Sox5 overexpression restored proliferation in TAZ-silenced cells. Sox5 expression was markedly reduced in cartilage of TAZ-deficient mice. In vitro, TAZ overexpression upregulated Sox5 and increased Sox5 protein stability upon CHX treatment. ChIP assay showed that the TAZ/TEAD1 complex binds to the Sox5 promoter, and this binding was reduced upon TAZ deficiency or TEAD1 silencing.

**TAZ deficiency blocks chondrocyte maturation by suppressing Col10a1 expression**

In micromass culture, chondrogenic nodule formation was reduced in TAZ-deficient chondrocytes. Col10a1 expression was significantly suppressed upon TAZ deficiency or silencing, and increased with TAZ overexpression. Runx2 expression was also reduced in TAZ-deficient chondrocytes. Runx2 overexpression increased Col10a1, but this effect was blocked by TAZ silencing and enhanced by TAZ overexpression. ChIP assay confirmed that the TAZ/Runx2 complex binds to three binding sites in the Col10a1 promoter.

**TAZ deficiency impairs fracture healing**

Callus formation was severely impaired 2 weeks post-fracture in Col2-Cre;TAZf/f mice, with micro-CT showing reduced bone surface area and volume of callus tissue. Alcian blue staining revealed a reduced cartilage area. Sox5, Col2a1, Col9a1, Col10a1, and aggrecan expression were all reduced in fracture calluses. Immunofluorescence showed decreased Runx2 and Col10a1+ signals.

---

## Perspective

This study is the first to demonstrate that TAZ is essential for chondrocyte proliferation, differentiation, maturation, and skeletal development. TAZ promotes chondroprogenitor cell proliferation by regulating Sox5 expression and stability in cooperation with TEAD1, and promotes chondrocyte maturation by binding to Runx2 to induce Col10a1 expression. TAZ deficiency leads to impaired growth plate development, articular cartilage damage, reduced bone mass, and impaired fracture healing, progressing to a spontaneous OA-like phenotype. Although both YAP and TAZ are Hippo pathway effectors, they exhibit opposite expression patterns during chondrocyte differentiation: YAP decreases while TAZ increases. Furthermore, TAZ deficiency downregulates Col10a1 and Mmp13, whereas YAP deficiency upregulates them. The different expression patterns of Col10a1 and Mmp13 at 1 month versus 4 months suggest a complex relationship between cartilage development and OA pathology. TAZ holds potential as a therapeutic target for bone and cartilage diseases such as fracture healing, heterotopic ossification, and OA, and further research is needed to understand how the Hippo-YAP/TAZ pathway precisely regulates chondrocyte, osteoblast, and adipocyte lineages.

## Data Availability

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE3013832, GSE30318


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
