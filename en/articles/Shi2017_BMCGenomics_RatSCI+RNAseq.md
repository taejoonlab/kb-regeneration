---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
---

# Transcriptome profile of rat genes in injured spinal cord at different stages by RNA-sequencing

## Citation (NLM)
Shi LL, Zhang N, Xie XM, Chen YJ, Wang R, Shen L, Zhou JS, Hu JG, Lü HZ. Transcriptome profile of rat genes in injured spinal cord at different stages by RNA-sequencing. BMC Genomics. 2017;18:173. doi:10.1186/s12864-017-3532-x

**DOI:** [https://doi.org/10.1186/s12864-017-3532-x](https://doi.org/10.1186/s12864-017-3532-x)

---

## Background

Spinal cord injury (SCI) causes devastating loss of motor and sensory function and currently has no effective treatment. Pathological changes after traumatic SCI comprise the immediate primary injury and a subsequent secondary injury cascade that produces extensive temporal changes in gene expression across multiple biological processes. Because of this complexity, a global transcriptomic analysis is needed to understand SCI mechanisms and develop therapies.

Earlier cDNA microarray/genechip studies were limited in resolution, dynamic range, and accuracy. This study applied high-throughput RNA-sequencing (RNA-Seq) to profile temporal genome-wide gene expression in the injured adult rat spinal cord across acute, subacute, and chronic phases, aiming to identify the critical genes and pathways involved in SCI pathology. The rat contusion model was chosen because rat SCI pathology (cavity formation, scar/inflammatory response) is considered more similar to human SCI than the mouse model.

---

## Key Experiment Methods

1. Contusive SCI in 12 female Sprague-Dawley rats using the New York University Impactor (T9 laminectomy, 10 g rod dropped 25 mm); sham controls received laminectomy only.
2. BBB (Basso, Beattie, Bresnahan) locomotor rating scale assessed hindlimb function from before injury through 28 dpi.
3. Spinal cord segments (5 mm around epicenter) harvested from sham and acute (1 dpi), subacute (6 dpi), and chronic (28 dpi) phases (n = 3/group).
4. RNA-Seq: TRIzol RNA extraction, NEBNext Ultra library prep, paired-end sequencing on Illumina HiSeq (Novogene); 12 cDNA libraries.
5. Bioinformatics: TopHat/Bowtie alignment to reference genome, HTSeq counting, FPKM quantification, DESeq differential expression (adjusted P < 0.05), GO (GOseq) and KEGG (KOBAS) enrichment, hierarchical and K-means clustering.
6. qRT-PCR validation of ~10-13 selected DEGs (C1qb, Ccl2, Cxcl2, Enpp3, Il6, Lcn2, Ncf1, Pf4, Plau, Tspo) normalized to GAPDH.

---

## Results

- BBB scores: all injured rats scored 0 at 1 dpi, recovering to ~11.67 by 28 dpi, indicating a moderate injury.
- Differentially expressed genes (DEGs) vs sham: 1,797 (acute, 1 dpi; 1,223 up / 574 down), 6,590 (subacute, 6 dpi; 3,460 up / 3,130 down), and 3,499 (chronic, 28 dpi; 1,866 up / 1,633 down). The subacute phase (6 dpi) showed the largest transcriptional change.
- PCA showed low variance and tight clustering of biological replicates; qRT-PCR confirmed RNA-Seq expression patterns.
- Hierarchical and K-means clustering grouped 7,632 DEGs into 8 subclusters; most changing genes reached their expression extreme at 6 dpi.
- GO enrichment: DEGs most enriched in immune response, MHC protein complex, antigen processing/presentation, translation/ribosome, ion-gated channel activity, small GTPase signaling, and cytokine/chemokine activity.
- KEGG pathways: ribosome, antigen processing and presentation, retrograde endocannabinoid signaling, axon guidance, dopaminergic/glutamatergic/GABAergic synapses, and TNF, HIF-1, NF-κB, Toll-like receptor, NOD-like receptor, cAMP, calcium, oxytocin, Rap1, B cell receptor, and chemokine signaling.
- Confirmed known SCI genes (Socs3, Il17, Tnf, Il6, Il1b, CD44, Fgf2, Mmp9, Bax) and highlighted previously unreported candidates by phase: acute (Csf2rb, Plin2, Gadd45g, Sbno2, Flnc, Bcl3, Glipr2, Trib1), subacute (Plau, Hk3, Trem2), and chronic (Tnfaip6, Ncf1, Asb15, Cp, Acp5, Clec4a3).

---

## Perspective

- **Significance**: Provides a systematic, temporally resolved genome-wide RNA-Seq characterization of rat SCI across acute, subacute, and chronic phases, confirming known pathology genes and nominating many novel candidate genes and pathways (e.g., ribosome biogenesis, retrograde endocannabinoid, oxytocin, Rap1 signaling) as a foundation for future mechanistic and therapeutic studies.
- **Limitations**: Descriptive/correlative bioinformatic study without functional validation of the novel candidates; small sample size (n = 3/group) and high early mortality; species and method differences complicate direct comparison with prior mouse/microarray data.
- **Future directions**: Functional interrogation of the newly implicated genes and pathways in SCI progression and repair; leverage the rat model (more human-like pathology) for mechanistic and therapeutic development.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
