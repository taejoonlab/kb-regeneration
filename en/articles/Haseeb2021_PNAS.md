---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
---

# SOX9 keeps growth plates and articular cartilage healthy by inhibiting chondrocyte dedifferentiation/osteoblastic redifferentiation

## Citation (NLM)
Haseeb A, Kc R, Angelozzi M, de Charleroy C, Rux D, Tower RJ, Yao L, Pellegrino da Silva R, Pacifici M, Qin L, Lefebvre V. SOX9 keeps growth plates and articular cartilage healthy by inhibiting chondrocyte dedifferentiation/osteoblastic redifferentiation. Proc Natl Acad Sci USA. 2021;118(8):e2019152118. doi:10.1073/pnas.2019152118

**DOI:** [https://doi.org/10.1073/pnas.2019152118](https://doi.org/10.1073/pnas.2019152118)

---

## Background

Cartilage is essential for vertebrate development and adult survival. The growth plate (GP) is responsible for skeletal growth and closes at puberty, while articular cartilage (AC) maintains the structural and functional integrity of joints throughout life. SOX9 is known as a key transcription factor for embryonic chondrogenesis, but its postnatal role has been unclear. Heterozygous SOX9 mutations in humans cause campomelic dysplasia, with surviving patients exhibiting dwarfism and scoliosis. SOX9 is also known to be downregulated in osteoarthritis (OA). While lineage tracing studies have shown that chondrocytes can transdifferentiate into osteoblasts, whether this process involves transdifferentiation or dedifferentiation-redifferentiation has been unclear. The central question of this study is whether SOX9 acts as a gatekeeper inhibiting this cellular plasticity.

---

## Key Experiment Methods

- **Conditional knockout mice**: *Sox9*^fl/fl^; *AcanCreERT2*; *R26*^tdT^ mice used. Tamoxifen intraperitoneal injection to induce adult chondrocyte-specific *Sox9* deletion. *Sox8/Sox9* double knockout mice also analyzed in parallel.
- **Histological analysis**: Safranin O/Fast Green staining, H&E staining to evaluate growth plate and articular cartilage structure.
- **Osteoarthritis model (DMM surgery)**: Destabilization of the medial meniscus. OA severity quantified by OARSI 6-grade scale.
- **Cell proliferation and apoptosis analysis**: EdU incorporation (proliferation), TUNEL assay (apoptosis).
- **Laser capture microdissection + RNA-seq**: Growth plate and articular cartilage captured by laser for transcriptome analysis (Illumina NovaSeq; ≥50M reads/sample).
- **RNA in situ hybridization (RNAscope)**: Visualization of Acan, Ihh, Col10a1, Runx2, Sp7, Bglap, Nt5e, Sox4, etc. in tissues.
- **Immunohistochemistry**: Analysis of SOX9, RUNX2, osteocalcin, pSMAD2/3, pSMAD1/5/9 protein expression.
- **Single-cell RNA-seq (scRNA-seq)**: 10× Genomics Chromium platform. Single-cell isolation from distal femur/proximal tibia epiphyses after digestion. UMAP and pseudotemporal trajectory analysis by Seurat v3 and Monocle 3.
- **Primary chondrocyte culture experiments**: *Sox9*^fl/fl^ rib chondrocytes infected with Ad-GFP or Ad-CRE adenovirus. TGFβ1 (5 ng/mL) or BMP2 (200 ng/mL) treatment followed by qRT-PCR and Western blot analysis.

---

## Results

### SOX9 expression decreases with growth plate regression and articular cartilage aging
- In 4-week-old mice, the growth plate is large with abundant SOX9 expression, but in adult/aged mice, the growth plate is greatly reduced with decreased SOX9 expression.
- Articular cartilage also shows markedly decreased SOX9 expression with aging.

### SOX9 is essential for maintaining growth plate patency and articular cartilage integrity
- *Sox9* deletion: growth plate began to close within 2 weeks; proteoglycan loss and hypertrophic zone loss.
- Articular cartilage also lost proteoglycans but initially maintained structure.
- In the DMM surgery model, *Sox9* deletion mice developed more severe OA (OARSI score 4 vs. control 2).

### SOX9 is required for growth plate chondrocyte proliferation and survival but not for articular chondrocytes
- Sox9-deficient growth plate chondrocytes (GPCs): proliferation arrest (EdU↓), increased apoptosis (TUNEL↑), accompanied by MMP13 signaling.
- Sox9-deficient articular chondrocytes (ACCs): no changes in proliferation or apoptosis.

### SOX9 is essential for robust expression of the cartilage gene program
- Sox9 deletion led to significant downregulation of pan-cartilaginous and growth plate markers including Col2a1, Acan, Hapln1, Fgfr3, Ihh, Col10a1.
- Sox8 did not compensate for Sox9 deficiency.

### SOX9 supports the articular program in weight-bearing regions and suppresses OA genes
- Articular cartilage-specific markers including Prg4, Smoc2, Clu were specifically lost in the medial femoral condyle and tibial plateau (weight-bearing regions).
- The articular cartilage program in non-weight-bearing regions was SOX9-independent.
- OA-related gene changes in Sox9-deficient articular cartilage: Timp3, Frzb downregulation; Adamts5, Vcan, Tnc, Ctsb upregulation.

### SOX9 inhibits osteoblastogenesis in growth plate and articular chondrocytes
- Runx2, Sp7 RNA increased in GP growth plate chondrocytes within 4-7 days of Sox9 deletion; RUNX2 and osteocalcin protein detected after 10 days.
- Same induction of osteoblast markers in weight-bearing region ACCs of articular cartilage.
- Bglap (osteocalcin) upregulation confirmed (mature osteoblast marker).
- 30-40% of tdTomato+ cells in endochondral bone were confirmed as GPC-derived osteocytes.

### Chondrocytes transit through a skeletal progenitor stage when converting to osteoblasts (dedifferentiation/redifferentiation)
- scRNA-seq UMAP: Sox9-deficient GPCs skip late proliferative, prehypertrophic, and hypertrophic stages, converting through terminal GPC → mesenchymal progenitor → OB progenitor → pre-OB → OB pathway.
- RNA in situ: sequential expression of Mgp, Nt5e (CD73), Sox4, Mmp13, Ibsp, Postn, Col3a1, Sp7, Col1a1 after Sox9 deletion.
- Confirmed that these cells reside within the original cartilage matrix → demonstrating conversion of chondrocytes themselves, not invading progenitor cells.
- No expression of Sox2, Nanog, Oct4 (pluripotency markers) → not dedifferentiation to pluripotent stage.

### TGFβ and BMP signaling contribute to chondrocyte fate conversion
- Sox9 deletion decreased pSMAD2/3 (TGFβ signaling) in articular cartilage; Tgfbr3 downregulated.
- Sox9 deletion increased pSMAD1/5/9 (BMP signaling); BMP inhibitor genes (Chrdl2, Grem1, Nog, Bambi) downregulated.
- Primary chondrocyte experiments: TGFβ1 synergized with Sox9 deletion to increase Col3a1 (progenitor marker); BMP2 greatly increased SP7 protein expression upon Sox9 deletion → increased BMP signaling contributes to chondrocyte-to-osteoblast conversion.

---

## Perspective

- This study demonstrates that SOX9 is essential not only during embryogenesis but also postnatally for maintaining growth plate patency and articular cartilage homeostasis.
- Chondrocytes can convert to osteoblasts through a pathway of dedifferentiation → skeletal progenitor stage → redifferentiation when Sox9 expression decreases, and SOX9 serves a gatekeeping role in inhibiting this conversion.
- This cellular plasticity mechanism provides new insights into osteoarthritis pathology, particularly the finding that decreased SOX9 in weight-bearing regions leads to osteoblast conversion and cartilage damage, which is noteworthy as a mechanism of OA progression.
- The study suggests a hypothesis that the combination of increased BMP signaling and mechanical stimulation may cause heterotopic ossification (similar to fibrodysplasia ossificans progressiva).
- Maintaining SOX9 expression or blocking the osteoblast conversion pathway may represent OA therapeutic strategies. Elucidating the relationship between growth plate closure regulators (such as estrogen) and SOX9 expression remains an important future challenge.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
