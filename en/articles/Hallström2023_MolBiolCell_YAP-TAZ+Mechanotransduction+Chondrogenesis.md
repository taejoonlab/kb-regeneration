---
tags: [2026-06, Chondrocyte]
extract: 2026-06-08
log:
  - "2026-06-08 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Microenvironmental mechanoactivation through Yap/Taz suppresses chondrogenic gene expression

## Citation (NLM)
Hallström GF, Jones DL, Locke RC, Bonnevie ED, Kim SY, Laforest L, Cruz Garcia D, Mauck RL. Microenvironmental mechanoactivation through Yap/Taz suppresses chondrogenic gene expression. *Mol Biol Cell*. 2023 Jun 1;34(7):ar73. doi:10.1091/mbc.E22-12-0543

**DOI:** [https://doi.org/10.1091/mbc.E22-12-0543](https://doi.org/10.1091/mbc.E22-12-0543)

---

## Background

The chondrocyte phenotype is maintained when cells are round with a cortical actin cytoskeleton. However, in monolayer culture, chondrocytes rapidly dedifferentiate, accompanied by increased cell size and formation of large actin stress fibers driven by Rho signaling. Although the impact of Rho on chondrocyte phenotype is well established, the underlying molecular mechanisms remain incompletely understood. Yap is a transcriptional coactivator regulated by Rho in the mechanotransduction pathway and has been reported to suppress chondrogenesis in vivo. This study aimed to elucidate how the relationship between the mechanotransduction pathway Rho and Yap regulates chondrogenic gene expression.

---

## Key Experiment Methods

1. **Cell culture and chondrogenic differentiation**: ATDC5 chondrogenic progenitor cells were cultured as high-density monolayers and induced to differentiate with chondrogenic medium (CM) containing TGF-β3 (10 ng/mL).

2. **Pharmacological modulation of Rho signaling**: Cells were treated with the Rho inhibitor C3 transferase (0.3 μg/mL) and the Rho activator LPA (50 or 20 μM), and changes in chondrogenic marker expression (Sox9, Col2a1, Acan) were analyzed by qRT-PCR.

3. **siRNA-based Yap/Taz knockdown**: ATDC5 cells were transfected with siRNA targeting Yap1 and Wwtr1 (Taz), and chondrogenic marker expression was assessed on day 5. Single and double knockdown conditions were compared.

4. **RNA-seq analysis**: Transcriptomes were sequenced on a NovaSeq 6000 under conditions including C3 treatment, LPA treatment, siY/T treatment, and various substrate stiffness conditions (5 kPa, 55 kPa polyacrylamide hydrogels, glass). DESeq2 and Gene Ontology analyses were performed.

5. **Substrate stiffness experiments**: PA hydrogels of 5 kPa (similar to cartilage pericellular matrix) and 55 kPa were fabricated, coated with fibronectin, and seeded with cells. Yap nuclear/cytoplasmic ratio and chondrogenic marker expression were analyzed.

6. **Immunofluorescence staining and imaging**: Cells were stained for F-actin (phalloidin), YAP, and collagen VI. Yap nuclear/cytoplasmic localization was quantified by confocal microscopy. Cell and nuclear areas were measured using CellProfiler.

7. **Western blot**: SOX9, YAP/TAZ, and collagen VI protein expression were evaluated and quantified using an Odyssey infrared imaging system.

8. **Statistical analysis**: Nonparametric one-way ANOVA (Kruskal-Wallis with Dunn's test), nonparametric t-test (Mann-Whitney), and parametric one-way ANOVA were used as appropriate.

---

## Results

**Inverse correlation between Rho signaling and chondrogenic gene expression**: C3 (Rho inhibition) significantly increased Sox9, Col2a1, and Acan expression, while LPA (Rho activation) decreased them. RNA-seq analysis revealed that Rho inhibition broadly upregulated additional chondrogenic genes including Gdf5, Nkx3-2, Col6a1–3, Col9a2, and Col11a1. Conversely, LPA treatment increased the expression of catabolic matrix proteins such as MMP-3, -9, -10, -12, and -13.

**Yap/Taz suppress chondrogenesis**: Double knockdown of Yap and Taz (siY/T) significantly increased chondrogenic marker expression, with similar effects observed even in non-chondrogenic basal medium (BM), establishing Yap/Taz as major negative regulators of chondrogenesis. siY/T-treated cells showed significantly reduced cell and nuclear area.

**Soft substrates promote chondrogenesis**: On 5 kPa soft substrates, YAP nuclear localization was markedly reduced compared to glass, with significant increases in Col2a1, SOX9, and COLVI expression. The 55 kPa substrate showed intermediate effects. RNA-seq revealed that both 5 kPa and 55 kPa substrates upregulated chondrogenic genes including Gdf5, Col6, Col9, Col11, Trpv4, and Prg4.

**Integrative analysis**: Twenty-seven genes were commonly upregulated across four chondrogenesis-promoting conditions (C3, siY/T, 5 kPa, 55 kPa), including Col2a1, Col9a2, Col11a1, Trpv4, Gdf5, and Sox6. GO analysis identified terms related to cartilage development, cartilage condensation, ossification, ECM organization, and chondrocyte differentiation.

**Yap/Taz mediate Rho signaling downstream of chondrogenic regulation**: On 55 kPa substrates, C3 treatment reduced YAP nuclear localization and increased chondrogenic markers, whereas LPA treatment had the opposite effect. In the siY/T knockdown background, LPA treatment no longer suppressed chondrogenic gene expression, and additional C3 treatment produced no further increase, demonstrating that Rho signaling regulates chondrogenesis primarily through the Yap/Taz pathway.

---

## Perspective

This study comprehensively elucidated the molecular mechanism by which the mechanical environment of chondrocytes regulates chondrogenic gene expression via Yap/Taz. In low mechanoactivation environments (Rho inhibition, soft substrates), YAP nuclear localization decreases, activating the SOX9-dependent chondrogenic program; in high mechanoactivation environments (Rho activation, stiff substrates), YAP translocates to the nucleus and suppresses chondrogenesis.

The substantial overlap in chondrogenic gene programs induced by various conditions (C3, siY/T, soft substrates) suggests that these pathways share common downstream mechanisms. Notably, the finding that siY/T can induce chondrogenesis even in non-chondrogenic medium highlights Yap/Taz as a master switch in chondrocyte fate determination.

Future studies should employ ChIP-seq to determine whether Yap acts as a direct transcriptional repressor via TEAD binding sites in the SOX9 promoter or as a transcriptional activator at anti-chondrogenic loci. The findings of this study provide an important foundation for developing cartilage regeneration strategies using small molecules or biomaterials that target the Rho/Yap/Taz pathway.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*
