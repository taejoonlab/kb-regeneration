---
tags: [2026-07, Fibroblast]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# Single-cell RNA-seq reveals fibroblast heterogeneity and increased mesenchymal fibroblasts in human fibrotic skin diseases

## Citation (NLM)

Deng CC, Hu YF, Zhu DH, Cheng Q, Gu JJ, Feng QL, Zhang LX, Xu YP, Wang D, Rong Z, Yang B. Single-cell RNA-seq reveals fibroblast heterogeneity and increased mesenchymal fibroblasts in human fibrotic skin diseases. Nat Commun. 2021;12(1):3709. doi:10.1038/s41467-021-24110-y

**DOI:** [https://doi.org/10.1038/s41467-021-24110-y](https://doi.org/10.1038/s41467-021-24110-y)

---

## Background

Fibrotic skin diseases—including scleroderma, hypertrophic scar, keloid, and graft-versus-host disease—affect millions worldwide and are characterized by fibroblast hyperproliferation and excessive accumulation of extracellular matrix (ECM) in the dermis. Fibroblasts are the central cell type driving skin fibrosis, exhibiting increased proliferation, migration, invasion, and ECM deposition largely under the influence of fibrogenic growth factors such as TGFβ, FGF, PDGF, VEGF, and POSTN. Although fibroblasts were long assumed to be a uniform spindle-shaped population, accumulating evidence shows they are morphologically and functionally heterogeneous. Single-cell RNA-seq (scRNA-seq) has resolved fibroblast subgroups in normal dermis and in some fibrotic diseases (lung fibrosis, systemic sclerosis, Dupuytren's disease), but fibroblast heterogeneity in fibrotic skin diseases had not been characterized. This study used scRNA-seq to dissect fibroblast heterogeneity in keloid, a paradigm of fibrotic skin disease.

---

## Key Experiment Methods

**1. scRNA-seq of keloid and normal scar dermis**
- Collected keloid tissue (3 patients) and normal scar tissue (3 patients); used dermis only after removing epidermis and adipose tissue
- Enzymatically dissociated with dispase II and collagenase IV; profiled on 10× Genomics Chromium (3′ v2 chemistry), ~8,000 cells per run
- Sequenced on Illumina HiSeq X / NovaSeq (PE150); processed with Cell Ranger, aligned to GRCh38
- Obtained transcriptomes of 40,655 cells (keloid 21,488; normal scar 19,167)

**2. Cell clustering and lineage annotation**
- Unsupervised UMAP clustering yielded 21 cell clusters, assigned to 9 lineages using marker genes
- Fibroblast lineage identified by COL1A1; endothelial lineage by ENG
- Compared cell-lineage proportions and number of differentially expressed genes between keloid and normal scar

**3. Fibroblast subclustering and subpopulation classification**
- Reclustered all fibroblasts into 13 subclusters (sC1–sC13)
- Assigned four subpopulations by established markers: secretory-papillary (sC6, sC7), secretory-reticular (sC5), mesenchymal (sC1, sC4), pro-inflammatory (sC2, sC3, sC9)
- ARACNe/MARINa master-regulator analysis; GO and GSEA enrichment

**4. Validation and cell–cell communication analysis**
- Immunofluorescence staining of ADAM12 and NREP to identify mesenchymal fibroblasts in situ
- ACTA2 analysis to assess myofibroblast overlap with the mesenchymal subpopulation
- CellPhoneDB 2.0 ligand–receptor interaction analysis between fibroblast subpopulations and other cells

**5. Functional study of mesenchymal fibroblasts**
- Flow-sorted CD90+CD266+/CD9− (mesenchymal) vs. other keloid fibroblasts; validated by qRT-PCR, western blot, RNA-seq
- Treated other fibroblasts with mesenchymal-fibroblast supernatant ± POSTN-neutralizing antibody OC-20, assaying collagen I/III
- Diffusion-pseudotime and RNA velocity analysis of sC1 vs. sC4
- Reanalyzed a published scleroderma scRNA-seq dataset for cross-disease validation

---

## Results

**Fibroblasts undergo the greatest transcriptional change in keloid**
Nine cell lineages were resolved across 40,655 cells. Keloid showed increased proportions of endothelial and smooth-muscle cells (consistent with keloid angiogenesis) and a relatively decreased fibroblast proportion. Among all lineages, fibroblasts showed the largest number of differentially expressed genes between keloid and normal scar, indicating that fibroblasts undergo the most significant changes during fibrotic progression.

**Keloid fibroblasts partition into four subpopulations with expanded mesenchymal cells**
Fibroblasts resolved into 13 subclusters grouping into the four canonical subpopulations. The mesenchymal subpopulation (sC1, sC4) specifically expressed COL11A1 and POSTN, while pro-inflammatory fibroblasts showed globally reduced collagens and papillary fibroblasts expressed COL13A1/COL18A1/COL23A1. Compared with normal scar, the mesenchymal subpopulation was increased in keloid whereas secretory-papillary, secretory-reticular, and pro-inflammatory subpopulations were decreased. Keloid mesenchymal fibroblasts also upregulated skeletal-development, ossification, and osteoblast-differentiation genes (COL11A1, COMP, POSTN), showing both a proportional expansion and an identity shift.

**Mesenchymal fibroblasts carry a skeletal/osteogenic signature and overlap with myofibroblasts**
Differentially expressed genes in mesenchymal fibroblasts included secreted proteins (POSTN, COMP, COL11A1, COL12A1, COL5A2) and membrane proteins (SDC1, ADAM12, CD266/TNFRSF12A up; CD9 down). GO/GSEA linked them to collagen organization, wound healing, skeletal development, and osteoblast differentiation. Master transcription factors of osteogenesis, chondrogenesis, and tendon/ligament differentiation—SCX, CREB3L1, RUNX2—were enriched in this subpopulation. Immunofluorescence confirmed increased ADAM12+/NREP+ cells in keloid. Myofibroblasts (ACTA2+) were increased in keloid (26.0% vs 13.3%) and were enriched within the mesenchymal subpopulation, though only part of mesenchymal fibroblasts were α-SMA positive.

**Mesenchymal fibroblasts dominate keloid cell communication and drive collagen via POSTN**
CellPhoneDB showed that in normal scar the most abundant interactions involved secretory-reticular fibroblasts, whereas in keloid mesenchymal fibroblasts became the dominant communicators. TGFβ1–TGFβR1/R2 signaling was most markedly increased, NOTCH (JAG1-NOTCH1) was up, anti-fibrotic FGF2 interactions were down, and POSTN signaling was altered specifically in mesenchymal fibroblasts. Flow-sorted CD266+/CD9− fibroblasts confirmed the mesenchymal identity (high POSTN, ASPN, COMP, COL11A1; ECM/skeletal/chondrocyte-development enrichment). Supernatant from these cells raised collagen I and III in other fibroblasts, an effect blocked by the POSTN-neutralizing antibody OC-20, demonstrating that mesenchymal fibroblasts promote collagen overexpression partly through POSTN.

**sC4 is a less-differentiated mesenchymal precursor and the mechanism generalizes to scleroderma**
Pseudotime and RNA velocity indicated that sC4 fibroblasts—significantly increased in keloid and expressing higher POSTN, ADAM12, COL11A1—are at an earlier differentiation stage than sC1 and can give rise to sC1. Reanalysis of scleroderma scRNA-seq revealed an increased cluster 7 expressing POSTN, ADAM12, COMP, and NREP that was most analogous to keloid mesenchymal fibroblasts, and immunofluorescence confirmed increased ADAM12+/NREP+ cells in scleroderma, indicating that mesenchymal fibroblast expansion is a broad mechanism of skin fibrosis.

---

## Perspective

This study provides the first single-cell atlas of fibroblast heterogeneity in a human fibrotic skin disease and defines an expanded mesenchymal fibroblast subpopulation as a central driver of collagen overexpression.

First, it establishes that fibrotic skin disease fibroblasts recapitulate the four subpopulations of normal dermis but with a disease-specific expansion of the mesenchymal subset, a pattern shared between keloid and scleroderma and therefore likely general to skin fibrosis.

Second, the strong skeletal-development, ossification, and osteoblast/chondrocyte-differentiation signature of these mesenchymal fibroblasts (POSTN, COMP, COL11A1; SCX, RUNX2) draws a direct molecular link between skin fibrosis and osteogenic/chondrogenic programs—a connection of particular interest for the vault's cartilage-regeneration and ectopic-ossification themes, where the same mesenchymal-progenitor transcription factors govern lineage choice.

Third, the functional demonstration that mesenchymal fibroblasts drive collagen production in neighboring fibroblasts through POSTN, together with increased TGFβ1 and POSTN-ITGAV/ITGB5 signaling, nominates POSTN and the mesenchymal subpopulation as therapeutic targets. The authors propose that inhibiting or eliminating mesenchymal fibroblasts (e.g., POSTN small-molecule inhibitors) before or after conventional keloid therapies may reduce the high recurrence rate.

Limitations include the small patient number, mature keloids only, and the unresolved origin of the sC4 precursor, which the authors plan to trace with transgenic lineage-tracing models.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
