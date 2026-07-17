---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
raw_data:
  - "GEO: GSE120678"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Mesenchymal Precursor Cells in Adult Nerves Contribute to Mammalian Tissue Repair and Regeneration

## Citation (NLM)
Carr MJ, Toma JS, Johnston APW, Steadman PE, Yuzwa SA, Mahmud N, Frankland PW, Kaplan DR, Miller FD. Mesenchymal Precursor Cells in Adult Nerves Contribute to Mammalian Tissue Repair and Regeneration. Cell Stem Cell. 2019;24(2):240-256. doi:10.1016/j.stem.2018.10.024

**DOI:** [https://doi.org/10.1016/j.stem.2018.10.024](https://doi.org/10.1016/j.stem.2018.10.024)

---

## Background

Peripheral innervation is essential for tissue repair and regeneration across species: in amphibians nerves are required for limb regeneration, and in non-regenerative mammals they support repair of the heart, bone, and digit tip. These pro-regenerative effects were thought to arise mainly through axon-secreted ligands and factors released by dedifferentiated Schwann cells. However, peripheral nerves also contain mesenchymal cells within the epineurium, perineurium, and endoneurium, whose contribution to repair had not been characterized.

This study tests the hypothesis that injured peripheral nerves act as a reservoir of mesenchymal precursor-like cells that migrate into adjacent damaged tissue and contribute directly to repair, thereby helping to explain the nerve dependence of mammalian regeneration.

---

## Key Experiment Methods

1. Immunostaining of PdgfraEGFP/+ mouse sciatic nerves (uninjured vs. 9-day post-axotomy) for PDGFRa, CD34, Thy1, S100b, and other markers, with EdU labeling to assess injury-induced proliferation.
2. High-throughput droplet-based single-cell RNA sequencing (Drop-seq) of ~4,300 cells from 9-day injured distal sciatic nerve and ~2,000 cells from uninjured control nerve, with t-SNE clustering, differential expression, hierarchical clustering, Cyclone cell-cycle prediction, and random-forest cluster validation.
3. Combined reanalysis of control and injured Pdgfra-positive transcriptomes (with mutual nearest neighbors batch correction) to compare mesenchymal populations.
4. In vitro differentiation assays (osteogenic, adipogenic, chondrogenic) of postnatal and adult nerve cells, including PdgfraCreERT;R26-LSL-TdT lineage-tagged sorted cells.
5. Transplantation of genetically tagged nerve segments next to femur periosteal scratch injuries in NOD-SCID mice.
6. Neural crest lineage tracing with Wnt1Cre, Wnt1CreERT2, and DhhCre driving R26-LSL-TdT in adult digit tip amputation and skin wound models, plus CLARITY 3D imaging and denervation experiments.

---

## Results

- Pdgfra-EGFP-positive mesenchymal cells populate all nerve compartments; after axotomy their endoneurial density increases ~3-fold and they proliferate (EdU+), whereas uninjured contralateral nerves have no proliferating Pdgfra+ cells.
- scRNA-seq of injured nerve identified four transcriptionally distinct Pdgfra-positive mesenchymal populations: precursor-like endoneurial cells (clusters 2/5, expressing Sox5/6/8, Sox9, Etv1, Alpl, Col2a1 and MSC/osteochondrogenic genes), differentiating nerve-stump cells (clusters 1/3/6, Dlk1, Runx2, Tnc), epineurial cells (clusters 4/7, Gsn, Ly6c1, Dpt), and perineurial cells (cluster 8, Glut1/Slc2a1, Itgb4).
- Comparing control and injured nerves, perineurial and epineurial cells co-clustered regardless of injury, whereas endoneurial cells were transcriptionally altered by injury (upregulating Aldh1a2, C3, Ccl2, Wif1, etc.), becoming more precursor-like; a distinct nerve-stump cluster appeared only after injury.
- Nerve mesenchymal cells differentiated down osteogenic, adipogenic, and chondrogenic lineages in culture, confirmed with PdgfraCreERT-TdT lineage tagging; transplanted tagged nerves contributed TdT+/ALPL+/osteocalcin+ cells to femur repair callus in vivo.
- Endoneurial mesenchymal cells are neural crest-derived (Wnt1Cre-TdT+, ~65% of Sox9+ cells). During digit tip regeneration, ~21% of Pdgfra-EGFP+ blastema cells were Wnt1Cre-TdT+, and by 28 DPA neural crest-derived cells occupied ~32% of regenerated bone lacunae.
- DhhCre lineage tracing corroborated the neural crest contribution; control experiments (EdU, Wnt1 qRT-PCR/FISH, inducible Wnt1CreERT2) ruled out expansion of resident osteocytes or de novo Wnt1 induction, and denervation greatly reduced neural crest-derived cell density in regenerated tissue.

---

## Perspective

The work establishes that peripheral nerves supply neural crest-derived mesenchymal precursor cells that migrate into injured tissue and contribute directly to bone (digit tip regeneration, femur repair) and dermal repair, offering a cellular explanation for the long-observed nerve dependence of mammalian tissue regeneration. Because nerves innervate nearly every tissue, this reservoir could have broad implications for regenerative medicine. Limitations include reliance on lineage-tracing mouse models and relatively shallow early scRNA-seq, and the digit tip/bone context means direct relevance to CNS/spinal cord regeneration is indirect. Future directions include defining the signals that mobilize and instruct these precursors, and testing whether nerve-derived mesenchymal cells can be harnessed to enhance repair in poorly regenerating tissues.

## Data Availability

**Raw data generated by this study:**
- GEO: GSE120678


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
