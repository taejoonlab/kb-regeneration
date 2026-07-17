---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
---

# Nuclear microRNA 9 mediates G-quadruplex formation and 3D genome organization during TGF-β-induced transcription

## Citation (NLM)

Cordero J, Swaminathan G, Rogel-Ayala DG, Rubio K, Elsherbiny A, Mahmood S, Szymanski W, Graumann J, Braun T, Günther S, Dobreva G, Barreto G. Nuclear microRNA 9 mediates G-quadruplex formation and 3D genome organization during TGF-β-induced transcription. _Nat Commun._ 2024 Nov 27;15(1):10711. doi: [10.1038/s41467-024-54740-x](https://doi.org/10.1038/s41467-024-54740-x). PMID: 39604334.

---

## Background

진핵세포에서 3차원(3D) 게놈 조직화는 전사 조절에 필수적이다. 인핸서-프로모터 상호작용은 chromatin looping을 통해 세포 유형 특이적 유전자 발현을 조절하며, G-quadruplex(G4)와 같은 비정형 DNA 2차 구조는 프로모터에서 유전자 발현 증가와 관련된다. 그러나 **G4가 promoter-distal 조절 요소(super-enhancer, SE)와 chromatin looping에서 어떤 역할을 하는지**는 알려지지 않았다. miRNA는 주로 세포질에서 번역 억제를 통해 작용한다고 알려졌으나, 성숙 miRNA가 세포핵에서도 발견되며 핵 내 기능은 제한적으로 연구되었다. 본 연구는 TGF-β1 신호전달에 반응하는 유전자에서 성숙 miR-9가 핵 내 프로모터 및 super-enhancer에 풍부하게 존재하며, G4 형성, 프로모터-super-enhancer looping, H3K4me3 broad domain 유지에 필수적임을 규명하였다.

---

## Key Experiment Methods

**1. 세포 분획 및 miR-9 핵 내 위치 확인**

- MLg(마우스 폐 섬유아세포), MFML4, MLE-12(폐 상피), NMuMG, hLF(사람 폐 섬유아세포) 세포주 사용
- 세포질/핵 분획 후 TaqMan assay로 성숙 miR-9 정량
- RNA FISH로 miR-9 핵 내 국소화 시각화; antagomiR로 miR-9 loss-of-function(LOF) 유도

**2. ChIRP-seq (Chromatin Isolation by RNA Purification)**

- 생물인산화 miR-9 antisense oligonucleotide로 endogenous miR-9 + 결합 크로마틴 침전
- MLg 및 MLE-12 세포에서 게놈-wide miR-9 결합 프로파일 분석
- 대조군: miR-let7d 특이적 probe

**3. CUT&Tag 및 ChIP-seq**

- H3K4me3, H3K27ac, G4 항체로 CUT&Tag 수행(Ctrl vs miR-9-LOF)
- Pol II, Pol II S5p, ATAC-seq, G4P ChIP-seq, G4access 데이터 분석
- ROSE 알고리즘으로 super-enhancer(SE) vs typical enhancer(TYE) 분류

**4. RNA-seq 및 PRO-seq/GRO-seq**

- miR-9-LOF MLg 세포 total RNA-seq로 전사체 변화 분석
- PRO-seq, GRO-seq으로 nascent RNA 정량

**5. G4 Ch-RIP 및 miR-Pd (miRNA pulldown)**

- G4 특이적 항체로 chromatin-RNA immunoprecipitation 후 TaqMan으로 miR-9 정량
- 핵 분획에서 생물인산화 miR-9로 pulldown 후 mass spectrometry로 결합 단백질 동정

**6. H3K4me3 HiChIP-seq**

- H3K4me3 항체로 in situ Hi-C library + ChIP 결합
- Ctrl/miR-9-LOF × 비처리/TGF-β1 처리(4조건) chromatin conformation 분석

---

## Results

**miR-9의 핵 내 존재 및 프로모터 결합** miR-9는 모든 분석 세포주의 세포질과 핵에서 검출되었으며, 섬유아세포에서 상피세포보다 핵 내 상대 수준이 높았다. IPF(특발성 폐섬유화증) 환자 hLF에서는 miR-9가 주로 핵에 위치하여 병적 핵 이동 가능성을 시사하였다. ChIRP-seq에서 miR-9는 프로모터, TTS, 인트론 영역에 풍부하게 결합하였고, MLg와 MLE-12에서 결합 부위가 달라 세포 유형 특이적 조절을 시사하였다.

**miR-9가 H3K4me3 broad domain 및 기초 전사에 필수** H3K4me3 CUT&Tag에서 Ctrl MLg 세포의 H3K4me3 broad domain 중 60.8%가 miR-9와 풍부하게 오버랩되었고, miR-9-LOF 시 broad domain이 27.6%→22.1%로 감소하며 medium/narrow domain으로 전환되었다(promoter에서 유의). miR-9-LOF로 3,320개 전사체가 유의하게 변화했고, 이 중 73.5%(2,439개)가 발현 감소하였다. H3K4me3 broad domain 내 유전자가 가장 큰 전사 감소를 보였다. Pol II, Pol II S5p, PRO-seq, GRO-seq, ATAC-seq, H3K4me3 ChIP-seq 모두 miR-9 표적 유전자 TSS에서 기초 전사 활성을 확인하였다.

**miR-9가 G4 형성에 필수** miR-9 표적 유전자 TSS에서 G-rich motif가 풍부하였고, G4P ChIP-seq 및 G4access 데이터에서 G4 풍부함이 확인되었다. G4 CUT&Tag에서 miR-9-LOF 시 게놈-wide G4 수준이 유의하게 감소하였다. G4 Ch-RIP으로 miR-9가 G4와 직접 결합함이 확인되었으며, miR-9-LOF로 이 상호작용이 소실되었다. miR-Pd mass spectrometry에서 핵 내 miR-9 결합 단백질 169개(MLg) 및 233개(MLE-12)가 동정되었고, 이 중 20개(MLg) 및 58개(MLE-12)가 G4 상호작용 단백질로 보고되었다. GSEA에서 G4 상호작용(p=1.23E-4), 크로마틴(p=1.5E-3), RNA 처리(p=1.65E-49) pathway가 풍부하였다.

**miR-9가 super-enhancer에서 G4 및 H3K27ac 유지** Alluvial plot에서 miR-9와 G4가 MED1, H3K27ac 풍부 SE locus에서 공동 풍부함을 보였다. 3,583개 공통 locus 중 95.5%(3,423개)가 eRNA database에 enhancer RNA로 등록되었다. ROSE 분석에서 Ctrl MLg 세포의 SE 1,649개가 miR-9-LOF 시 1,084개로 유의 감소(p=9.9E-142). SE 중 25.5%가 miR-9 풍부(TYE는 4%). miR-9-LOF 시 SE에서 H3K27ac breadth가 유의하게 감소하였고, SE와 TYE 모두에서 H3K27ac 및 G4 수준이 감소하였다. G4 CUT&Tag의 ROSE 분석에서 G4 포함 SE가 1,753개에서 937개로 유의 감소(p=2.5E-35)하였다.

**TGF-β1 유도 전사에서 miR-9가 프로모터-SE looping 매개** GSEA에서 miR-9 풍부 + nascent RNA locus가 "TGFB cell response"(p=7.55E-09), "TGFB"(p=2.61E-08), "Cell proliferation"(p=4.66E-08)에 풍부하였다. TGF-β1 처리 시 miR-9, G4, H3K4me3 수준이 miR-9 의존적으로 증가하였다. H3K4me3 HiChIP-seq에서 TGF-β1 처리 시 chromatin interaction hub가 유의하게 증가했고, 이 중 65.1%가 miR-9 풍부하였다. miR-9-LOF는 TGF-β1 유도 효과를 상쇄하였다. k-means clustering에서 cluster 1과 4가 TGF-β1 반응성 chromatin interaction을 보였고, 이 locus들이 miR-9 표적 유전자(Zdhhc5, Ncl, Lzts2, Hdac7)를 포함하였다. **프로모터-SE 간 chromatin loop이 TGF-β1 처리 시 miR-9 의존적으로 증가**함이 확인되었다. ChIP qPCR로 TGF-β1 처리 시 프로모터와 SE에서 H3K4me3 및 G4 수준이 증가하고, miR-9-LOF로 이 효과가 감소함이 확인되었다. qRT-PCR로 miR-9 표적 유전자 발현이 TGF-β1 처리 시 miR-9 의존적으로 증가함이 확인되었다.

---

## Perspective

본 연구는 성숙 miRNA가 핵 내에서 3D 게놈 조직화와 전사 활성화에 직접 관여함을 최초로 규명한 획기적인 연구로, 다음과 같은 의의를 갖는다.

첫째, miR-9가 프로모터와 super-enhancer에 직접 결합하여 G4 형성을 매개하고, 이를 통해 H3K4me3 broad domain 유지 및 프로모터-SE chromatin looping을 조절함을 보였다. 이는 miRNA가 cytoplasmic 번역 억제뿐만 아니라 **핵 내 chromatin 구조 조절자**로서 기능할 수 있음을 입증한다.

둘째, TGF-β1 신호전달 경로(암 및 섬유화의 핵심 경로)에서 miR-9가 전사 활성화의 필수 구성 요소로 작용함을 보였다. IPF 환자 폐 섬유아세포에서 miR-9의 핵 내 축적이 관찰되어, miR-9 핵 이동이 섬유화 병리와 연관될 가능성이 시사되었다.

셋째, miR-9가 SE 형성과 유지에 관여하며, G4가 SE의 구조적 요소로 작용함을 보였다. miR-9-LOF 시 SE 수가 34% 감소하고 G4 포함 SE가 47% 감소하여, miR-9-G4-SE 축이 전사 조절의 핵심 모듈임을 입증하였다.

넷째, miR-Pd mass spectrometry로 핵 내 miR-9 결합 단백질 다수를 동정하였고, 이 중 상당수가 G4 상호작용 단백질로, miR-9가 단백질 복합체를 매개로 chromatin 구조를 조절할 가능성을 제시하였다.

향후 과제로는 miR-9의 핵 내 이동 메커니즘(확장된 nuclear shuttling motif의 기능적 검증), miR-9가 G4 형성을 촉진하는 분자적 기전(DNA vs RNA G4 구분), 그리고 miR-9-G4 축을 표적으로 한 섬유화·암 치료 전략 개발이 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
