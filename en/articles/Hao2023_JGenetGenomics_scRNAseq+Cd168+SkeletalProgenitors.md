---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add Data Availability section"
---

# Single-cell transcriptomic analysis identifies a highly replicating Cd168+ skeletal stem/progenitor cell population in mouse long bones

## Citation (NLM)

Hao RC, Li ZL, Wang FY, et al. Single-cell transcriptomic analysis identifies a highly replicating Cd168+ skeletal stem/progenitor cell population in mouse long bones. _J Genet Genomics._ 2023;50(8):597-607. doi: [10.1016/j.jgg.2023.04.004](https://doi.org/10.1016/j.jgg.2023.04.004).

---

## Background

Skeletal stem/progenitor cells (SSPCs) are tissue-specific stem cells within the skeletal system capable of osteogenesis and chondrogenesis, playing critical roles in bone development, homeostasis, and regeneration. However, SSPC populations exhibit high heterogeneity in their spatiotemporal distribution and regenerative capacity, and a comprehensive understanding of this diversity remains lacking. Recent advances in single-cell RNA sequencing (scRNA-seq) have revealed the characteristics of various SSPC populations, but an integrative analysis spanning the entire developmental trajectory from the embryonic limb bud to the adult long bone has not been performed. Cd168 (also known as hyaluronic acid-mediated motility receptor, RHAMM/HMMR) is known to promote cell proliferation, transformation, and migration, and has recently been reported to be expressed on the surface of mesenchymal stem cells (MSCs) and contribute to chondrogenesis. This study aimed to identify a novel highly proliferative Cd168+ SSPC population in mouse long bones through integrative scRNA-seq analysis and to elucidate their developmental distribution and role in bone regeneration.

---

## Key Experiment Methods

**1. scRNA-seq data integration analysis**
- Utilization of public datasets (GSE154247, etc.): mouse limb buds (E11.5, E13.5, E15.5, E18.5) and postnatal long bone stromal cells (3-week, 12-week)
- Batch effect correction using Harmony algorithm; total of 14,116 single cells selected
- Identification of 10 cell clusters by Seurat unsupervised clustering
- Differentiation trajectory reconstruction with Monocle3; transcription factor activity analysis with SCENIC
- Cell cycle stage (G1/G2M/S) and proliferation scoring using CellCycleScoring function

**2. Cell subpopulation characterization**
- Subcluster analysis of 12 osteochondral lineage cells (OCLC)
- Annotation into LBM (limb bud mesenchyme), chondrocytes (5 clusters: embryonic chondrocytes, proliferative OCP, Prg4+ articular chondrocytes, Prkg2+ growth plate chondrocytes, Col10a1+ prehypertrophic chondrocytes), Lepr+ MSCs, and osteoblast lineage (2 clusters)
- Identification of Cd168+ proliferative osteochondral progenitor population

**3. Flow cytometry**
- Cell isolation from 12-week-old adult mouse long bones by mechanical/enzymatic digestion
- Measurement of Cd45⁻Ter119⁻Cd31⁻Cd168⁺ cell proportion

**4. Immunofluorescence staining and histology**
- Safranin O/Fast Green staining for cartilage morphology observation
- Multiplex immunofluorescence staining using anti-HMMR, anti-SOX9, anti-RUNX2, anti-Collagen type 2 antibodies
- Spatiotemporal protein expression analysis at embryonic (E11.5, E13.5, E15.5, E18.5) and postnatal (3-week, 12-week) time points
- Fracture healing model: Cd168+ cell distribution in callus at post-fracture day (PFD) 7, 14, 21

**5. Fracture healing model**
- Transverse complete fracture induced in left femur of 10-week-old female mice
- Fracture created with micro-scissors after intramedullary K-wire fixation
- Non-hematopoietic stromal cell (Cd45⁻Ter119⁻) isolation at PFD14 for scRNA-seq analysis
- Cluster connectivity assessment using partition-based graph abstraction (PAGA) analysis

---

## Results

**Construction of a single-cell atlas of mouse long bone development** Integrative analysis of 14,116 cells identified 10 cell clusters: limb bud mesenchymal cells (LBM, Prrx1/Osr2), chondrocytes (Acan/Sox9), osteochondral progenitors (OCP, Runx2/Sp7/Alpl), endothelial cells, perivascular cells, MSCs (Lepr/Pdgfra), apical ectodermal ridge (AER, Fgf8), skeletal muscle cells, immune cells, and epithelial cells.

**OCLC heterogeneity and developmental trajectory** Reanalysis centered on chondrogenic lineage cells (OCLC) revealed 12 clusters. Tracking cluster distribution across developmental stages showed that mesenchymal cells predominated at the early limb bud stage (E11.5), which then differentiated into chondrocytes as precartilaginous condensation progressed, and contributed to long bone longitudinal growth through growth plate hypertrophic chondrocytes. Lepr+ MSCs appeared as early as E11.5, expanded substantially after birth, and became the major SSPC population in adult bone marrow. Monocle3 trajectory analysis recapitulated two fate bifurcation points: osteogenesis and chondrogenesis.

**Identification of Cd168+ proliferative SSPC population** Cell cycle analysis revealed high proliferation scores in early limb bud cells and osteochondral stem/progenitor cells. Notably, an actively proliferating cell population with even higher proliferation scores than other osteochondral progenitors was identified. Cd168 was discovered as the marker gene for this population. GO analysis showed enrichment of genes involved in sequential processes of skeletal system development, mesenchyme, cartilage, and bone development.

**Spatiotemporal distribution of Cd168+ cells** Flow cytometry showed that Cd45⁻Ter119⁻Cd31⁻Cd168⁺ cells constituted 0.16–0.18% of total long bone-released cells. Immunofluorescence staining revealed Cd168+ cells in the limb bud mesenchymal condensation at E11.5, the cartilaginous condensation at E13.5, the primary ossification center at E15.5, and the articular surface and diaphysis at E18.5. Postnatally, they were found in the superficial zone of articular cartilage and the growth plate, but were not observed in the periosteum or endosteum. Cd168 co-localized with Sox9 and Runx2, suggesting osteochondrogenic capacity.

**Role of Cd168+ cells in fracture healing** Analysis of fracture datasets revealed that chondrocytes, fibroblasts, and OCP significantly increased at PFD14, while Lepr+ MSCs decreased. The OCP1 cluster specifically correlated with the proliferative osteochondral population from the developmental dataset. Cd168 expression increased during fracture healing and co-localized with Sox9 and Runx2. PAGA and differentiation trajectory analyses (RNA velocity, CytoTRACE) indicated that Cd168+ osteochondral progenitors differentiate into regenerated chondrocyte populations. Immunofluorescence staining detected Cd168+ cells co-labeled with Sox9/Runx2 in the center of the fracture callus at PFD7 and PFD14, confirming direct involvement in the fracture healing process.

---

## Perspective

This study performed the first integrative scRNA-seq analysis encompassing the entire developmental trajectory of mouse long bones from the embryonic limb bud to the adult long bone, elucidating the spatiotemporal heterogeneity and developmental trajectories of osteochondral lineage cells at single-cell resolution. Through a cell cycle analysis-based strategy, **Cd168** was identified as a novel surface marker of highly proliferative osteochondral progenitors, and this population was demonstrated to contribute to embryonic and postnatal long bone development as well as fracture healing by differentiating into chondrocytes.

The discovery of Cd168+ SSPCs presents a new SSPC population distinct from previously known bone marrow (Lepr+), sub-growth plate (Grem1+/PTHrP+), and periosteal (aSMA+/Ctsk+) SSPC populations. Their localization in the superficial zone of articular cartilage and the growth plate proliferative zone suggests potential roles in articular cartilage homeostasis and long bone growth regulation.

Future challenges include (1) cell fate mapping and self-renewal capacity validation using Cd168-CreERT2 lineage tracing mouse models, (2) transplantation and differentiation functional analysis of FACS-sorted Cd168+ cells, (3) elucidation of Cd168+ SSPC roles in various pathological models (osteoarthritis, osteoporosis), and (4) characterization of the LBM2 limb bud mesenchymal population. This study suggests the potential of Cd168+ SSPCs as a novel cell therapy target for skeletal system diseases.

## Data Availability

**Other accessions referenced in the text (reused/external data):**
- GEO: GSE154247


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
