---
tags: [2026-07, Tenocyte]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# RSPO2 defines a distinct undifferentiated progenitor in the tendon/ligament and suppresses ectopic ossification

## Citation (NLM)

Tachibana N, Chijimatsu R, Okada H, Oichi T, Taniguchi Y, Maenohara Y, Miyahara J, Ishikura H, Iwanaga Y, Arino Y, Nagata K, Nakamoto H, Kato S, Doi T, Matsubayashi Y, Oshima Y, Terashima A, Omata Y, Yano F, Maeda S, Ikegawa S, Seki M, Suzuki Y, Tanaka S, Saito T. RSPO2 defines a distinct undifferentiated progenitor in the tendon/ligament and suppresses ectopic ossification. Sci Adv. 2022;8(33):eabn2138. doi:10.1126/sciadv.abn2138

**DOI:** [https://doi.org/10.1126/sciadv.abn2138](https://doi.org/10.1126/sciadv.abn2138)

---

## Background

Ectopic endochondral ossification in the tendon/ligament is caused by repetitive mechanical overload or inflammation and is common in athletes and manual workers, as well as in spinal ligament diseases such as ossification of the posterior longitudinal ligament (OPLL). The pathological process is thought to begin with a failed injury-repair response that proceeds through chondrocyte differentiation, hypertrophy, and replacement by osteoblasts. Tendon stem/progenitor cells (TSPCs), defined by co-expression of Tppp3 and Pdgfra, contribute to tissue repair, and a subset expresses lubricin (proteoglycan 4, PRG4). A prior GWAS identified R-spondin 2 (RSPO2) — a secreted activator of canonical WNT signaling — as an OPLL susceptibility gene, and RSPO2 is known to suppress the early stage of endochondral ossification. However, the characteristics of Prg4+ cells in tendon/ligament and their link to ectopic ossification were unknown. This study characterizes the Prg4+ TSPC population and identifies RSPO2 as a marker of a distinct undifferentiated progenitor that restrains ectopic ossification.

---

## Key Experiment Methods

**1. Mouse Achilles tendon puncture (ATP) ectopic ossification model**
- Achilles tendons of mice punctured with a 27-gauge needle at five sites to induce ectopic endochondral ossification by minimal invasion
- Micro-CT for bone-volume quantification (ossification detected 8–12 weeks post-ATP)
- Immunohistochemistry time course for SOX9, COL2, PRG4, RSPO2 (positive-cell rates)

**2. Single-cell RNA-seq (scRNA-seq) of Prg4+ cells**
- Prg4-CreERT2;R26-tdTomato mice given tamoxifen 3 and 4 days after ATP; tdTomato+ cells profiled 1 week post-ATP
- Seurat clustering (10 clusters; secondary analysis of mesenchymal clusters → 7 clusters); CytoTRACE for differentiation state
- Validation against deposited burn/tenotomy heterotopic ossification data (GSE126060)
- FACS isolation of tdTomato+ vs tdTomato− cells to confirm Prg4/Rspo2 expression

**3. Cluster characterization and trajectory analysis**
- Marker profiling (Prg4, Rspo2, Tppp3, Pdgfra, Itga6, Tspan15, Procr, Col15a1, Fst, Runx2, Scx, Mkx, Tnmd, Col2a1, Acan, Sox9)
- GO enrichment (clusterProfiler); diffusion-map and Monocle2 pseudotime; scTensor cell–cell interaction analysis
- SCENIC transcription-factor regulon analysis to identify upstream regulators

**4. Rspo2 gain-of-function and antibody in vivo**
- Cre-dependent CAG-EGFP-Rspo2 transgenic mice crossed with Prg4-CreERT2 for tendon-specific overexpression; bone volume and Sox9/Col2a1 mRNA assessed
- Intraperitoneal anti-RSPO2 antibody vs vehicle after ATP

**5. Human ligament cell and clinical specimen analysis**
- RNA-seq/qRT-PCR of human primary ligament cells during chondrogenic differentiation; comparison with deposited human MSC chondrogenesis data
- In vitro treatment with recombinant human RSPO2 and LiCl (WNT activator); Alcian blue, COL2A1/ACAN, AXIN2, TOPflash reporter
- RSPO2 mRNA and protein comparison in spinal ligaments from OPLL vs cervical spondylotic myelopathy (CSM) patients

**6. Upstream signaling in human ligament cells**
- IL-1β stimulation ± IKK inhibitor Bay11-7085; cyclic tensile stress loading ± Bay11-7085 or Rac1 inhibitors (EHT1864, NSC23766); IκB phosphorylation by Western blot

---

## Results

**Ectopic endochondral ossification and early chondrogenic markers in the ATP model**
Micro-CT detected ectopic ossification 8–12 weeks after Achilles tendon puncture. SOX9 and COL2 expression rose as early as 1 week, with COL2+ cell rates remaining elevated versus sham throughout, indicating that ectopic chondrogenic differentiation initiates within the first week after injury.

**Rspo2 marks a distinct Prg4+ progenitor cluster**
scRNA-seq of Prg4-CreERT2;R26-tdTomato ATP tendons identified two Prg4+ clusters. Rspo2 was specifically expressed in cluster 6, whereas the other Prg4+ cluster (cluster 7) lacked Rspo2 but expressed chondrogenic/ossification markers (Col2a1, Acan, Sox9), defining it as a chondrogenic progenitor. The Rspo2+ cluster was rarely present at day 0 and emerged after invasion. FACS-sorted tdTomato+ ATP cells strongly expressed Rspo2, Pdgfra, Tppp3, and Procr, while sham cells did not.

**The Rspo2+ cluster is an undifferentiated progenitor**
Cluster 6 expressed stem-cell markers (Pdgfra, Tppp3, Itga6, Tspan15, Procr) but no specific differentiation-tendency GO terms; "ossification" was enriched only in the chondrogenic cluster 7. Diffusion-map and Monocle2 pseudotime placed the Rspo2+ cluster at the most undifferentiated position, upstream of Tppp3+Pdgfra+Rspo2− and of the tenogenic/chondro-osteogenic trajectories.

**RSPO2 inhibits ectopic ossification via suppression of chondrogenic differentiation**
Cell–cell interaction analysis ranked the Rspo2–Lgr6 pair highly from the Rspo2+ cluster to the chondrogenic progenitor. Rspo2 overexpression in Prg4+ cells (CAG-EGFP-Rspo2) significantly reduced ectopic bone volume and lowered Sox9 and Col2a1 mRNA, with suppressed COL2 protein. Conversely, anti-RSPO2 antibody increased bone mass and Sox9/Col2a1 expression, confirming that RSPO2 protein inhibits ectopic endochondral ossification by suppressing chondrogenic differentiation.

**RSPO2 suppresses chondrogenic differentiation of human ligament cells and is reduced in OPLL**
During chondrogenic differentiation of human ligament cells, RSPO2 was downregulated alongside AXIN2 (canonical WNT readout) and MSC markers ENG/NT5E. Recombinant human RSPO2 and LiCl both reduced Alcian blue staining and COL2A1/ACAN while increasing AXIN2 and TOPflash activity, consistent with WNT-mediated anti-chondrogenic action. In patients, both RSPO2 mRNA and RSPO2+ cell rates were significantly lower in OPLL ligaments than in CSM ligaments, and RSPO2+ cells localized to the boundary between COL2+ and degenerated regions but not within ossification lesions.

**RSPO2 is induced by inflammation and mechanical loading via NF-κB**
SCENIC identified Rela (NF-κB) among the regulators of the Rspo2+ cluster. IL-1β markedly induced RSPO2 in human ligament cells, and this was blocked by the IKK inhibitor Bay11-7085. Cyclic tensile stress likewise induced RSPO2 (with increased IκB phosphorylation), and this induction was abolished by Bay11-7085 and by two Rac1 inhibitors, indicating a Rac1–NF-κB pathway analogous to gremlin-1 induction in chondrocytes.

---

## Perspective

This study identifies RSPO2 as the defining marker of a distinct undifferentiated Tppp3+Pdgfra+Prg4+ progenitor subpopulation in the tendon/ligament and demonstrates that RSPO2 protein restrains ectopic endochondral ossification through canonical WNT-mediated suppression of chondrogenic differentiation.

First, it resolves the heterogeneity of Prg4+ TSPCs into two functionally opposed populations — an Rspo2+ undifferentiated progenitor and an Rspo2− chondrogenic progenitor — and positions the Rspo2+ cluster upstream in the differentiation trajectory, supporting a role in appropriate tendon/ligament repair rather than pathological ossification.

Second, the convergent mouse (overexpression and antibody), human ligament cell, and clinical OPLL data provide a coherent mechanistic link between reduced RSPO2 and the ectopic ossification seen in OPLL, a spinal ligament disease, connecting tendon/ligament progenitor biology to a clinically relevant pathology.

Third, by showing that inflammation (IL-1β) and mechanical loading induce RSPO2 via Rac1–NF-κB, the work embeds RSPO2 within the injury/mechanical-overload signaling that drives ectopic ossification. Because RSPO2 suppresses the same early chondrogenic program (Sox9, Col2a1) that governs cartilage differentiation, these findings are directly relevant to cartilage regeneration and to the balance between chondrogenic and non-chondrogenic fates in connective-tissue progenitors.

Limitations include the absence of scRNA-seq on human ligaments (surgical specimens are rare), the inability to profile mouse ligaments due to insufficient cell yield, and the undetermined origin and ultimate fate of the RSPO2+ population; aging as a contributing factor was also not examined. Nonetheless, the study advances understanding of tendon/ligament homeostasis and nominates RSPO2/WNT signaling as a therapeutic axis for ectopic ossification.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
