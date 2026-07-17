---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-07
extract_file: extract/2026-06-07_p02.txt
raw_data:
  - "PRIDE/ProteomeXchange: PXD001952"
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# A proteomic analysis of chondrogenic, osteogenic and tenogenic constructs from ageing mesenchymal stem cells

## Citation (NLM)

Peffers MJ, Collins J, Loughlin J, Proctor C, Clegg PD. A proteomic analysis of chondrogenic, osteogenic and tenogenic constructs from ageing mesenchymal stem cells. _Stem Cell Res Ther._ 2016 Sep 9;7(1):133. doi: [10.1186/s13287-016-0384-2](https://doi.org/10.1186/s13287-016-0384-2).

---

## Background

Mesenchymal stem cells (MSCs) have the capacity to differentiate into musculoskeletal tissues such as cartilage, bone, and tendon, making them an important resource in regenerative medicine and tissue engineering. However, how the phenotype and differentiation capacity of MSCs change with donor age remains unclear. Age-related functional decline in MSCs from elderly patients could significantly impact tissue viability and quality in MSC-based therapies. Proteomics enables identification of the protein populations responsible for specific cellular phenotypes and provides insight into age-related changes in musculoskeletal tissues. This study systematically analyzed proteomic changes in chondrogenic, osteogenic, and tenogenic tissue-engineered constructs derived from human bone marrow MSCs of young and old donors using label-free LC-MS/MS.

---

## Key Experiment Methods

**1. Cell culture and differentiation**

- Human bone marrow MSCs from young (n=4, 21.8±2.4 years) and old (n=4, 65.5±8.3 years) donors cultured to passage 4
- Each donor differentiated into chondrogenic (3D pellet), osteogenic (2D monolayer), and tenogenic (3D fibrin gel, fixed with staples on SYLGARD-coated wells) constructs
- Harvested after 28 days; all cultures performed under 5% oxygen conditions

**2. Differentiation validation**

- Chondrogenic: Alcian Blue/Nuclear Fast Red staining, aggrecan/COL2A1/SOX9 qRT-PCR
- Osteogenic: Alizarin Red S staining (with quantification), RUNX2 qRT-PCR
- Tenogenic: Masson's Trichrome staining, TEM for collagen fiber alignment confirmation, COL1A1/SERPINF1/THBS4 qRT-PCR

**3. Protein extraction and sample preparation**

- Chondrogenic/osteogenic: guanidine hydrochloride extraction
- Tenogenic: 0.1% Rapigest™ extraction
- Quantified by Bradford assay, followed by in-solution trypsin digestion and C18 tip desalting

**4. LC-MS/MS and label-free quantification**

- NanoAcquity UPLC online LTQ-Orbitrap Velos mass spectrometer
- Feature alignment with ProgenesisQI™, peptide identification with PEAKS® 7 PTM (Uniprot human database, FDR 1%, minimum 2 peptides/protein)
- Differentially expressed (DE) protein criteria: FDR p<0.05, ±2-fold regulation

**5. Neopeptide analysis (tenogenic)**

- Semi-tryptic search with Mascot, e>0.001 conservatively applied threshold
- Fragmentation patterns of collagen, proteoglycans, and glycoproteins identified

**6. Functional analysis**

- GO, canonical pathway, and network analysis using PANTHER, DAVID bioinformatics 6.7, and Ingenuity Pathway Analysis (IPA)
- ECM protein classification using MatrisomeDB

**7. Western blotting validation**

- COMP, biglycan (tenogenic), and SOD1 (chondrogenic) quantified by automated western blotting (Wes Simple Western)
- Statistical analysis by Mann-Whitney test

---

## Results

**Construct characterization** Chondrogenic differentiation was confirmed by Alcian Blue staining and increased aggrecan/COL2A1/SOX9 expression, osteogenic differentiation by Alizarin Red S staining and increased RUNX2 expression, and tenogenic differentiation by Masson's Trichrome/TEM/COL1A1 expression. No qualitative differences in collagen alignment were observed between young and old MSC-derived constructs.

**Protein identification** 2,226 proteins were identified in chondrogenic, 2,233 in osteogenic, and 615 in tenogenic constructs. PCA analysis showed that proteins clustered by donor age (chondrogenic 71%, osteogenic 66%, tenogenic 83%).

**Age-related differentially expressed (DE) proteins** 128 DE proteins were identified in chondrogenic constructs (28 increased, 100 decreased in old), 207 in tenogenic (201 increased, 6 decreased in old), and 4 in osteogenic (by FDR criteria). The minimal age effect in osteogenic constructs was interpreted as due to the 2D culture system compared to 3D constructs.

**Gene Ontology and pathway analysis** Actin cytoskeleton organization, cell survival/death, antioxidant changes, and cytoskeletal changes were commonly affected across all construct types. Lipid metabolism (LXR/RXR activation, cholesterol biosynthesis) was the major pathway in chondrogenic constructs, glucose metabolism (glycolysis, gluconeogenesis) and protein metabolism in tenogenic, and mitochondrial dysfunction in osteogenic.

**Upstream regulator analysis** TGFβ and SMAD2/3/4 targets were predicted to be inhibited in chondrogenic constructs, while TGFβ was identified as an activated upstream regulator in tenogenic constructs. HIF1α targets showed inhibition in chondrogenic and activation patterns in tenogenic constructs.

**ECM matrisome changes** COL4A2, MMP14, MXRA5, and THBS1 showed age-related changes in both chondrogenic and tenogenic constructs. Neopeptides were significantly more abundant in tenogenic constructs from old MSCs (14±2.5 vs 2.5±1, p=0.049), suggesting increased ECM turnover.

**Western blotting validation** Consistent with mass spectrometry results, COMP and biglycan were higher in old tenogenic constructs (p=0.05), and SOD1 was higher in old chondrogenic constructs (p=0.05).

---

## Perspective

This study is the first comprehensive proteomic analysis to systematically elucidate the effect of donor age on the construct proteome in MSC-based musculoskeletal tissue engineering. Oxidative stress protection, cell death/survival, and cytoskeletal changes were commonly affected across all three differentiation lineages, while lipid metabolism (chondrogenic), glucose/protein metabolism (tenogenic), and mitochondrial dysfunction (osteogenic) were specifically affected in each lineage.

The markedly increased protein metabolism and ECM turnover in tenogenic constructs from old MSCs provides important insight into understanding the physiological remodeling mechanisms of aged tendons. Changes in lipid metabolism and signs of inflammaging in chondrogenic constructs are consistent with the characteristics of aged cartilage, suggesting that donor age should be considered when using allogeneic MSCs for cartilage therapy.

The minimal age effect observed in osteogenic constructs reflects the limitations of the 2D culture system, highlighting the need for proteomic analysis in 3D osteogenic models. The DE protein profiles identified in this study provide a useful guide for developing targeted intervention strategies focused on oxidative stress protection when developing MSC-based therapies for elderly populations.

## Data Availability

**Raw data generated by this study:**
- PRIDE/ProteomeXchange: PXD001952


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
