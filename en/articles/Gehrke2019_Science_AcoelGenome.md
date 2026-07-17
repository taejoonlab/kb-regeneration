---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p03.txt
---

# Acoel genome reveals the regulatory landscape of whole-body regeneration

## Citation (NLM)
Gehrke AR, Neverett E, Luo YJ, Brandt A, Ricci L, Hulett RE, Gompers A, Ruby JG, Rokhsar DS, Reddien PW, Srivastava M. Acoel genome reveals the regulatory landscape of whole-body regeneration. Science. 2019;363(6432):eaau6173. doi:10.1126/science.aau6173

**DOI:** [https://doi.org/10.1126/science.aau6173](https://doi.org/10.1126/science.aau6173)

---

## Background
Many animals can heal wounds, but some can reconstruct their entire bodies from small fragments (whole-body regeneration). This process requires the interplay of wound signaling, stem cell dynamics, and positional identity, which have mostly been studied at the protein-coding level. How the noncoding genome responds to wounding to control gene expression and launch regeneration was largely unknown. To map the regulatory logic, the authors sequenced the genome of the highly regenerative acoel worm *Hofstenia miamia* (three-banded panther worm), which occupies a key phylogenetic position as the likely sister lineage (Xenacoelomorpha) to all other bilaterians (Nephrozoa), and applied chromatin profiling to identify regulatory regions active during regeneration.

---

## Key Experiment Methods
1. Whole-genome sequencing/assembly of *Hofstenia miamia* (~89.6× Illumina paired-end and mate-pair; Chicago method; validated with Oxford Nanopore long reads and REAPR); gene prediction with Augustus.
2. ATAC-seq on wound sites from head and tail fragments at 0, 3, 6, 12, 24, 48 hours post-amputation (hpa) to identify regeneration-responsive chromatin.
3. chromVAR analysis of 386 transcription-factor binding motifs to rank chromatin "variability" and identify dynamic TF motifs.
4. RNA interference (RNAi) knockdown of egr (and runt, deaf1) plus RNA-seq at 0, 1, 3, 6, 12 hpa to define wound-induced genes and Egr targets.
5. In situ hybridization to validate wound-induced expression and RNAi phenotypes.
6. ATAC-seq in egr-RNAi animals to define the Egr "regeneration cistrome"; PIQ footprinting (chromatin opening index) to assess pioneer-factor activity and RUNT binding; comparative ATAC-seq in planarian *Schmidtea mediterranea*.

---

## Results
- The *Hofstenia* genome assembly totals ~950 Mb (53% repetitive), with 22,632 gene models and 90% of expected metazoan BUSCO genes; contains a standard animal gene complement.
- Regeneration induced ~18,000 dynamic chromatin changes, mostly in introns and intergenic regions, with most peaks opening within the first 6 hpa and closing by 24–48 hpa.
- The EGR (early growth response) binding motif was the single most variably accessible motif during regeneration. *Hofstenia* has a single egr ortholog, wound-induced by 1 hpa across multiple cell types (epidermis, muscle, neurons, neoblasts).
- egr-RNAi animals completely failed to regenerate blastemas (no new heads or tails, 100%, n=150), identifying egr as a master regulator.
- RNA-seq identified 61 wound-induced genes; 12 of 13 validated wound-induced genes failed to upregulate at 6 hpa under egr-RNAi. Regeneration-responsive chromatin peaks bearing EGR sites failed to open in egr-RNAi, indicating direct regulation.
- Egr showed pioneer-factor-like behavior: high chromatin opening index (top 5 of 439 motifs), switching chromatin from closed to open; an autoregulatory loop exists at the egr locus.
- The GRN was extended: Egr directly activates the TFs runt and deaf1; runt-RNAi blocked regeneration and Runt directly controls neuregulin-1 (nrg-1), establishing an egr→runt→nrg-1 cascade.
- In planarian, the EGR motif is likewise among the most variably accessible, and homologs of the Egr-controlled GRN are conserved/required across planarians, sea stars, and vertebrates.

---

## Perspective
This study establishes the first chromatin-level gene regulatory network for launching whole-body regeneration and identifies Egr as a putative pioneer factor acting as a master control gene. By viewing regeneration through an epigenomic lens, the approach (genome-wide chromatin accessibility + functional RNAi) provides a template for comparing regeneration pathways across distantly related animals and can be extended to additional model and emerging systems. Conservation of the EGR-controlled network across planarians, sea stars, and vertebrates raises the open question of whether these regeneration networks are ancestrally conserved or convergently evolved. Relevance to the knowledgebase: Egr/neuregulin homologs are implicated in vertebrate neural and axolotl limb regeneration, linking this invertebrate regulatory logic to CNS/appendage regeneration.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
