---
tags: [2026-07, Fibroblast, RawDataAvailable]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
raw_data:
  - "ArrayExpress: E-MTAB-10324, E-MTAB-10316, E-MTAB-10315"
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Cross-tissue organization of the fibroblast lineage

## Citation (NLM)

Buechler MB, Pradhan RN, Krishnamurty AT, Cox C, Karabacak Calviello A, Wang AW, Yang YA, Tam L, Caothien R, Roose-Girma M, Modrusan Z, Arron JR, Bourgon R, Müller S, Turley SJ. Cross-tissue organization of the fibroblast lineage. Nature. 2021;593(7860):575-579. doi:10.1038/s41586-021-03549-5

**DOI:** [https://doi.org/10.1038/s41586-021-03549-5](https://doi.org/10.1038/s41586-021-03549-5)

---

## Background

Fibroblasts are non-haematopoietic structural cells that define organ architecture, produce and remodel extracellular matrix (ECM), support tissue-resident cells, and have central roles in fibrosis, cancer, autoimmunity, and wound healing. Single-cell studies had documented fibroblast heterogeneity within individual tissues, but the field lacked a characterization of fibroblasts at single-cell resolution *across* tissues in health and disease. Because subtypes of fibroblasts drive disease in arthritis, cancer, and fibrotic indications such as idiopathic pulmonary fibrosis (IPF), understanding whether fibroblast phenotypes are context-specific or broadly conserved has direct therapeutic relevance. By analogy to macrophages—which combine a lineage-wide core signature with tissue-specific programming—the authors hypothesized that fibroblast heterogeneity is promoted by tissue type at steady state and by disease context during perturbation, and set out to define the organizing principles of the fibroblast lineage.

---

## Key Experiment Methods

**1. Steady-state mouse fibroblast atlas**
- Integrated 28 scRNA-seq datasets (from own lab and public repositories) across 16 unperturbed mouse tissues, n = 120,583 PDGFRα+ fibroblasts
- Removed non-fibroblasts, corrected cross-laboratory batch effects; graph-based clustering into 10 clusters
- Cross-validated with bulk RNA-seq and ATAC-seq on FACS-sorted fibroblasts from multiple tissues

**2. Cluster annotation and lineage inference**
- Annotated clusters by dominant marker (Pi16+, Col15a1+, Ccl19+, Coch+, Comp+, Cxcl12+, Fbln1+, Bmp4+, Npnt+, Hhip+) and >200 DEGs each
- Assigned functional identities (FRCs, red-pulp, MSC/osteolineage, intestinal, alveolar, peribronchial fibroblasts)
- Slingshot pseudotime trajectory inference with the Pi16+ cluster as root

**3. DptIRESCreERT2 lineage-tracing mouse**
- Used surface markers LY6C and SCA1 to distinguish Pi16+ (LY6C+SCA1+), Col15a1+ (LY6C−SCA1+), and specialized (SCA1−) fibroblasts across 11 tissues by flow cytometry
- Generated DptIresCreERT2;Rosa26LSLYFP mouse; tamoxifen chow 14 days to irreversibly mark Dpt+ cells and progeny with YFP
- RNAscope for Dpt and Pi16 in lung and small intestine; compared with Ccl19YFP and Grem1CreERT2 reporters

**4. Perturbed-state mouse atlas**
- Integrated 17 scRNA-seq datasets across 13 perturbed tissues (infection, injury, cancer, fibrosis, metabolic, arthritis), n = 99,596 cells; 10 clusters
- Identified perturbation-specific activated clusters (Cxcl5+, Adamdec1+, Lrrc15+); validated Grem1 in DSS colitis by RNAscope
- Subcutaneous tumour model in DptIresCreERT2 mouse to test whether universal fibroblasts give rise to LRRC15+ myofibroblasts

**5. Human fibroblast atlases and cross-species comparison**
- scRNA-seq of pancreatic tumour and normal adjacent tissue (3 patients, n = 21,262 cells); defined a human universal fibroblast module from normal-fibroblast cluster c8
- Inferred universal-fibroblast abundance across 12 GTEx tissues (n = 5,961 samples)
- Integrated a human perturbed-state atlas (PDAC, colitis, NSCLC, IPF, COVID-19; n = 10,355 cells, 6 clusters) and mapped human disease signatures onto mouse clusters

---

## Results

**Two universal and multiple specialized fibroblast subtypes at steady state**
The steady-state mouse atlas resolved 10 clusters. Nearly all tissues contributed to the Pi16+ and Col15a1+ clusters, marking them as *universal*. Pi16+ fibroblasts (Pi16, Dpp4, Ly6c1) resembled adventitial stromal cells in vascular niches; Col15a1+ fibroblasts (Col4a1, Hspg2, Col15a1) associated with basement membrane. Both expressed elevated stemness genes (Cd34, Ly6a/SCA1). The remaining clusters were tissue-specialized (e.g., Ccl19+ FRCs, Cxcl12+ MSC/osteolineage, Npnt+ alveolar, Hhip+ peribronchial). Slingshot trajectories emerged from Pi16+, passed through Col15a1+, and ended at specialized clusters, suggesting a developmental hierarchy.

**Dpt marks universal fibroblasts and lineage-tracing confirms the hierarchy**
Flow cytometry sorted PDGFRα+ fibroblasts into Pi16+, Col15a1+, and specialized groups across 11 tissues. Dermatopontin (Dpt) expression was inversely correlated with specialization and enriched in both universal subtypes. In DptIresCreERT2;Rosa26LSLYFP mice, PDGFRα+ fibroblasts robustly expressed YFP (recombination efficiency 28.7% in lymph node to 83.7% in heart), while other cell types did not. YFP+ fibroblasts were enriched for Pi16/Col15a1 and depleted for Ccl19/Npnt, confirming that Dpt+ cells are transcriptionally distinct from specialized fibroblasts; the authors termed them Dpt+Pi16+ and Dpt+Col15a1+ universal fibroblasts.

**Universal fibroblasts persist in perturbation and give rise to activated myofibroblasts**
The perturbed-state mouse atlas retained universal Pi16+ and Col15a1+ clusters (highest Dpt) alongside perturbation-specific activated clusters: Cxcl5+ (early muscle injury, PI3K/TNF/NFκB), Adamdec1+ (colitis, Il11/Grem1, MAPK), and Lrrc15+ myofibroblasts (arthritis, wound, fibrosis, PDAC; high Cthrc1, Acta2, Postn, Adam12, collagens, TGFβ). Universal Dpt+Pi16+ fibroblasts maintained the highest stemness scores, and lineage inference traced trajectories from Dpt+Pi16+ through Dpt+Col15a1+ to activated clusters. In a subcutaneous tumour model, 52 ± 7% of LRRC15+ myofibroblasts were YFP+, showing that Dpt+ cells marked before tumour implantation differentiate into LRRC15+ myofibroblasts.

**Fibroblast states are conserved between mouse and human**
In human pancreatic tissue, the normal-fibroblast cluster c8 shared 12 of its top 20 upregulated genes with mouse Dpt+Pi16+ or Dpt+Col15a1+ clusters, defining a human universal module co-expressed in 12 GTEx tissues. Human fibroblast activation was negatively correlated with the universal module (r = −0.54), mirroring the mouse lineage relationship. The human c3 CAF signature and signatures from rheumatoid arthritis, interstitial lung disease, IPF, and ulcerative colitis all localized to the mouse Lrrc15+ myofibroblast cluster, and cells previously described as "inflammatory fibroblasts" aligned with universal clusters—suggesting they are universal fibroblasts that have not fully transitioned. The human perturbed-state atlas confirmed LRRC15+ and ADAMDEC1+ populations but revealed an additional COVID-19-enriched COL3A1+ myofibroblast subset absent from the mouse atlas.

---

## Perspective

This study reframes the fibroblast lineage around a small set of organizing principles: two universal transcriptional subtypes (Dpt+Pi16+ and Dpt+Col15a1+) that act as resource cells, from which specialized (steady-state) and activated (perturbed-state) fibroblasts arise across tissues and species.

First, the concept of universal Dpt+ fibroblasts as a lineage-wide reservoir provides a unifying framework for the intra-tissue heterogeneity documented piecemeal in prior studies, and the DptIRESCreERT2 knock-in mouse offers a genetic tool to prospectively track and manipulate this reservoir.

Second, the demonstration that universal fibroblasts give rise to LRRC15+ myofibroblasts—the pathogenic, collagen- and TGFβ-high, Postn/Adam12-expressing state shared across arthritis, cancer, and fibrosis—connects a conserved developmental origin to fibrotic disease. This is directly relevant to the vault's fibrosis and cartilage/musculoskeletal themes, as the same universal-to-activated trajectory operates in tendon, bone, and other connective tissues represented in the atlas.

Third, the mouse–human conservation and the panel of human disease orthologues make the mouse perturbed-state atlas a reference for interpreting human fibroblast subtypes, while the unique COVID-19 COL3A1+ myofibroblast highlights that indication-specific or signal-duration differences can still generate species- or disease-specific states.

Open questions the authors raise include the spatial dynamics among subtypes, why two universal subtypes exist (possibly a division of labour), and which niche or immune cues drive specialization and activation—each a foothold for therapeutic targeting of pathogenic fibroblast states.


## Data Availability

**Raw data generated by this study:**
- ArrayExpress: E-MTAB-10324, E-MTAB-10316, E-MTAB-10315

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE93326


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
