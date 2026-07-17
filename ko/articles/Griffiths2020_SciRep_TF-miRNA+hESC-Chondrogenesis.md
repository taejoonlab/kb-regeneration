---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# The Transcription Factor-microRNA Regulatory Network during hESC-chondrogenesis

## Citation (NLM)

Griffiths R, Woods S, Cheng A, Wang P, Griffiths-Jones S, Ronshaugen M, Kimber SJ. The Transcription Factor-microRNA Regulatory Network during hESC-chondrogenesis. _Sci Rep._ 2020 Mar 16;10(1):4744. doi: [10.1038/s41598-020-61734-4](https://doi.org/10.1038/s41598-020-61734-4). PMID: 32179778.

---

## Background

인간 배아줄기세포(hESC)와 유도만능줄기세포(iPSC)는 골관절염(OA) 및 스포츠 손상으로 인한 연골 결손 repair를 위한 무한한 세포원으로 잠재력이 크다. 그러나 hESC/iPSC의 연골세포 분화 효율 개선에는 연골형성(chondrogenesis)의 전사적·전사후적 조절 기전에 대한 이해가 필수적이다. miRNA는 골격 발달과 ECM 조절에서 핵심적 역할을 하며, miRNA 처리 억제는 마우스에서 연골 발달 결손과 연골세포 사멸을 유발한다. 기존 연골세포 분화 프로토콜은 배양체(embryoid body) 형성, MSC 유사 세포 유도, 또는 혈청 사용에 의존하였으나, 본 연구진은 혈청-free 3단계 2D 분화 프로토콜로 hESC로부터 연골전구세포(chondroprogenitor)를 유도하였다. 본 연구는 이 프로토콜의 각 단계에서 small RNA-seq과 whole transcriptome sequencing을 수행하여, hESC 연골형성 과정에서 miRNA와 전사인자(TF)가 어떻게 협력하여 유전자 발현을 조절하는지 시스템 생물학적 접근으로 규명하였다.

---

## Key Experiment Methods

**1. hESC 연골세포 분화 프로토콜(DDP)**

- HUES1, MAN7 두 hESC 라인 사용
- Stage 0(hESC) → Stage 1(primitive streak/mesendoderm, day 1-3: Wnt3a, Activin A, BMP4) → Stage 2(mesoderm, day 4-8: BMP4, Follistatin) → Stage 3(chondroprogenitor, day 9-14: GDF5, FGF2, NT4)
- 혈청-free 2D 배양, 각 단계 말기 샘플 수집

**2. Small RNA-seq 및 Whole transcriptome RNA-seq**

- Stage 0, 2, 3 샘플에서 small RNA 라이브러리 및 whole transcriptome 라이브러리 제작
- Illumina 시퀀싱; hg19 게놈 매핑
- 22,073개 전사체(17,835개 단백질 코딩 유전자) 및 1,052개 성숙 miRNA 검출
- DESeq2로 차등발현 분석(FDR < 0.05)

**3. 공발현 네트워크 분석(Co-expression network)**

- BioLayout3D로 Pearson's correlation > 0.98 기준 유전자·miRNA 클러스터링
- 6개 클러스터 동정; 각 클러스터의 GO term enrichment 분석

**4. 전사인자 표적 풍부 분석**

- 알려진 TF-표적 상호작용 데이터베이스로 각 클러스터 내 TF 표적 유전자 풍부도 평가(Fisher's Exact Test, odds ratio)

**5. miRNA 표적 풍부 분석**

- TargetScan(total context score < -0.3) + miRTarBase(luciferase 검증 상호작용만)로 고신뢰도 miRNA-표적 목록 생성
- 각 클러스터 내 miRNA 표적 풍부도 평가

**6. 단백질-단백질 상호작용(PPI) 네트워크**

- STRING 데이터베이스로 'ECM Organization' 클러스터 유전자의 PPI 네트워크 구축

---

## Results

**전사체·miRome의 단계별 변화** PCA에서 Stage 0→Stage 3으로 명확한 진행이 관찰되었고, Stage 2는 중간 단계로 더 큰 변이를 보였다. 두 hESC 라인 간 전사체 변화는 높은 상관관계를 보였으며, 479개 공통 상발현 유전자와 619개 공통 하발현 유전자가 확인되었다.

**차등발현 유전자** Stage 0 vs Stage 3에서 3,274개 유전자가 유의하게 조절되었다. 상발현 유전자에는 Hox genes(HOXA, C, D 클러스터), ECM 관련 유전자(LOX, DCN, MGP, COL15A1), 중배엽·사지 발달 TF(BARX2, HAND2, TBX2)가 포함되었다. 하발현 유전자는 다능성 관련 유전자(NANOG, POU5F1, NODAL, LEFTY1, ZSCAN10)였다.

**miRNA 변화** 208개 miRNA가 유의하게 변화하였다. 다능성 관련 miRNA(19번 염색체 클러스터 CM19C, miR-302 family)가 하발현되었고, Hox 클러스터 유래 miRNA 및 연골형성 관련 miRNA(miR-99a-5p, miR-143-5p, miR-181a-3p)가 상발현되었다. 전연골세포(prechondrocyte) miRNA(miR-99b-5p, miR-27b-3p)가 비대 연골세포(hypertrophic chondrocyte) miRNA(miR-20a-5p, miR-17-5p, miR-127-3p)보다 훨씬 높게 발현되어, 본 프로토콜이 전연골세포 특성을 유지함을 보였다.

**공발현 네트워크 6개 클러스터**
- Cluster 1: 다능성 유지(NANOG, POU5F1, NODAL, miR-302a)
- Cluster 2: 원시선 형성(primitive streak formation, miR-200, miR-141)
- Cluster 3: RNA polymerase II 전사 조절
- Cluster 4: **ECM organization**(fold enrichment 9.1, FDR=4.5E-24)
- Cluster 5: **사지 발달(limb development**, fold enrichment 19.4, FDR=9.5E-5)
- Cluster 6: 이온 수송

**TF 표적 풍부 분석** 'ECM Organization' 클러스터에서 77개 TF가 표적 풍부(odds ratio > 1, p < 0.001)를 보였고, 이 중 25개가 연골형성 중 상발현되었다. JUN(39개 표적)과 RELA(36개 표적)가 ECM 조절 유전자(TIMP1, LOX, TGM2, ADAM9, COL1A1, COL1A2, COL4A2, DCN, FN1, HSPG2)를 광범위하게 조절하였다. HOXA9/A10/D13, NFAT5도 상발현되었다.

**miRNA 표적 풍부 분석** 'ECM Organization' 클러스터에서 **miR-29c-3p**(odds ratio 33.5)와 **miR-140-3p**(odds ratio 23.7) 표적이 가장 풍부하였다. miR-29c-3p의 39개 확인된 표적 중 10개가 ECM organization 클러스터에 속하였다. miR-29c-3p는 분화 중 발현이 증가하였으나 표적 유전자 발현이 감소하지 않아, 전사체 안정화 또는 복잡한 조절 네트워크 관여를 시사하였다. **'Limb development' 클러스터에서 miR-134-5p** 표적이 5.5배 풍부하였고(HAND2, HOXB2, MEIS2, PBX1, TBX2), **miR-22-3p**가 ECM 유전자와 높은 공발현을 보였으며, 연골형성 조절인자 HDAC4와 SP1을 표적으로 하여 간접적으로 ECM 유전자를 조절할 가능성이 제시되었다.

**PPI 네트워크** 'ECM Organization' 클러스터 PPI 네트워크에서 IL6, IGF-1이 핵심 연결 유전자로 확인되었다. IGF-1 네트워크에 IGFBP3가 포함되었고, ADAM12가 IGFBP-3/5를 절단하여 IGF-1 생체 이용률을 증가시키는 기전이 시사되었다. TIMP1/TIMP3이 IL6와 양의 상관관계를 보였다.

---

## Perspective

본 연구는 hESC 연골형성 과정에서 전사체와 miRome의 통합 분석을 통해 TF-miRNA-ECM 조절 네트워크를 체계적으로 규명한 시스템 생물학적 연구로, 다음과 같은 의의를 갖는다.

첫째, 연골형성 중 ECM organization 클러스터가 TF(JUN, RELA, HOXA9/A10/D13, NFAT5)와 miRNA(miR-29c-3p, miR-140-3p, miR-22-3p)의 다중 조절을 받음을 보였다. 특히 miR-22-3p가 miR-140과 유사하게 HDAC4와 SP1을 표적으로 하여 연골 비대 억제 및 ECM 분해 방지에 기여할 가능성이 제시되어, **새로운 연골형성 조절 miRNA** 후보로 주목된다.

둘째, miR-29c-3p가 ECM organization 클러스터 유전자를 직접 조절하며, 발현 증가와 표적 발현 유지의 역설적 관계는 miRNA가 단순한 억제자가 아니라 전사체 안정화 또는 피드백 네트워크 구성 요소로 작용할 수 있음을 시사한다.

셋째, 본 프로토콜이 전연골세포(prechondrocyte) 특성을 유지하며(RUNX2 낮음, COL10A1 없음), 2D 배양임에도 불구하고 사지 발달 관련 Hox 유전자와 연골 발달 TF(SOX9, SOX5/6, DLX2, MSX1)가 적절히 조절되어, 인간 연골 발달의 in vitro 모델로서 타당성을 입증하였다.

넷째, IGF-1-IGFBP3-ADAM12 축과 IL6-TIMP 네트워크가 ECM 항상성 유지에서 핵심적임을 보여, OA 병리에서 ECM catabolism 조절의 잠재적 표적을 제시하였다.

향후 과제로는 miR-22-3p, miR-29c-3p의 기능적 검증(gain/loss-of-function), 3D 배양에서 연골세포 성숙도 향상(ACAN, COL2A1 고발현 유도), 그리고 iPSC로의 프로토콜 확장 및 OA 질환 모델링 적용이 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
