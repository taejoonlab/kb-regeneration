---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p02.txt
---

# Comparison of the major cell populations among osteoarthritis, Kashin-Beck disease and healthy chondrocytes by single-cell RNA-seq analysis

## Citation (NLM)

Wang X, Ning Y, Zhang P, Poulet B, Huang R, Gong Y, Hu M, Li C, Zhou R, Lammi MJ, Guo X. Comparison of the major cell populations among osteoarthritis, Kashin-Beck disease and healthy chondrocytes by single-cell RNA-seq analysis. _Cell Death Dis._ 2021 Jun 3;12(6):551. doi: [10.1038/s41419-021-03832-3](https://doi.org/10.1038/s41419-021-03832-3).

---

## Background

Kashin-Beck disease(KBD)는 중국 북서부 등 특정 지역에서 풍토적으로 발생하는 만성 퇴행성 골연골 질환으로, 초기에는 손가락의 단축 및 비대, 진행기에는 관절 기형, 운동 제한, 왜소증을 특징으로 한다. 골관절염(OA)은 노인에서 가장 흔한 퇴행성 관절 질환이다. 두 질환 모두 세포외기질(ECM) 분해, 연골 병변, 프로테오글리칸 및 콜라겐 감소 등의 유사한 병리소견을 보이지만, 발병 연령, 증상, X-ray 소견이 다르며 병인도 상이하다. KBD는 주로 연골 심층(deep zone)에서 연골세포 괴사가 시작되는 반면, OA는 표층(superficial zone)에서 진행성 퇴행이 시작된다. 그러나 연골세포 이질성(heterogeneity)을 고려한 비교 연구는 부족하여, 두 질환의 연골세포 집단 수준 차이는 명확히 규명되지 않았다. 본 연구는 단일세포 RNA 시퀀싱(scRNA-seq)을 통해 KBD, OA, 건강한 연골의 주요 세포 집단을 체계적으로 비교하고 질환 특이적 세포 집단 및 마커를 동정하고자 하였다.

---

## Key Experiment Methods

**1. 연골 샘플 수집 및 연골세포 분리**

- KBD 환자, OA 환자, 건강한 대조군(외상/절단 환자)의 슬관절 관절연골 수집
- KBD는 중국 국가진단기준(WS/T 207-2010), OA는 Modified Outerbridge Classification에 따라 진단
- 0.25% trypsin(30분) → 0.2% type II collagenase(12-16시간) 효소 소화
- 70 μm nylon 필터 여과 후 single-cell suspension 준비

**2. 단일세포 RNA 시퀀싱(scRNA-seq)**

- 10× Chromium Single Cell 3′ Library V2 플랫폼 사용
- Illumina NovaSeq6000으로 시퀀싱(세포당 ≥57,374 reads, PE150)
- 총 16,375세포 분석(KBD 6,140, OA 5,834, healthy 4,401)
- Seurat 3.0으로 클러스터링(유전자 수 <200 또는 >상위 1%, 미토콘드리아 비율 >25%인 세포 제외)
- t-SNE 및 UMAP 시각화

**3. 세포 분화 궤적 분석**

- Monocle로 pseudotime trajectory 재구성
- PAGA(Partition-based graph abstraction) 분석

**4. 마커 유전자 검증**

- 면역조직화학(IHC): SH3BGRL3, IGFBP5, BIRC5, SOX9, EIF5A, CDC20, MT-ND1, MT1X, AEBP1, CHI3L1, STEAP1, CENPW, PTTG1 등
- qRT-PCR: MT-ND1, MT1X, AEBP1, CHI3L1 등

**5. WGCNA 및 세포 유형 주석**

- WGCNA(R 패키지)로 유전자 공발현 네트워크 분석
- SingleR로 참조 데이터셋(Human Primary Cell Atlas, blueprint_encode) 기반 세포 유형 주석

---

## Results

**건강한 연골에서 7개 세포 집단 동정**

건강한 인간 연골에서 scRNA-seq 분석을 통해 7개 세포 집단이 확인되었다:
1. 섬유연골세포-1(FCs-1): SH3BGRL3, S100A6, MYL9
2. 섬유연골세포-2(FCs-2): IGFBP5, LMCD1
3. 연골전구세포-1(CPCs-1): CDC20, UBE2C, CENPF, CKAP2
4. 조절 연골세포(RegCs): EIF5A, PGK1, ANXA1, TUBA1A
5. 비후전 연골세포(preHTCs): SOX9, COL9A3, COL11A1
6. 항상성 연골세포(HomCs): TXNIP, IFITM3, GDF15, TIMP1
7. 연골전구세포-2(CPCs-2): KIAA0101, BIRC5, CDKN3, TMN1

Pseudotime 분석에서 CPCs-1/2가 뿌리(root)에 위치하고, FCs-1/RegCs가 운명1(fate 1), FCs-2/preHTCs/HomCs가 운명2(fate 2)로 분기하였다. IHC에서 FCs는 표층/중층, CPCs는 중층/심층, RegCs는 표층, preHTCs는 표층/심층에 주로 분포하였다.

**KBD, OA, healthy 연골의 통합 분석: 10개 집단 + 1개 신규 집단**

세 군을 통합 분석한 결과 10개 기존 집단과 **미토콘드리아 연골세포(MTCs)**라는 신규 집단이 확인되었다:
- PreHTCs: 3개 아집단(S100A4hi, COL9A3hi, AKR1C1hi)
- RegCs: 2개 아집단(CTNNB1hi, CHI3L1hi)
- MTCs(신규): 2개 아집단(MT-ND1hi, MT-CO1hi) — 미토콘드리아 전자전달 및 과산화수소 반응 관련 유전자 발현
- FCs: 2개 아집단(IGFBP5hi, COL14A1hi)

CPC 세포(cluster 8)는 정상 연골에만 존재하고 OA 및 KBD에서는 대부분 소실되었다.

**KBD에서 확장된 세포 집단: HomCs 및 MTCs**

HomCs(MT1X, MT2A, MT1E, ATF5, DDIT3 발현)와 MTCs(MT-ND1, MT-ATP6, MT-ND2, MT-ND3 발현)가 KBD에서 현저히 확장되었다. IHC에서 MTCs는 중층/심층에, HomCs는 표층에 주로 분포하였다. qRT-PCR에서 MT-ND1과 MT1X 발현이 KBD 환자에서 증가하여 scRNA-seq 결과와 일치하였다. 금속조절단백질(metallothionein, MT)은 금속 독성 제거, 항산화, 면역 방어, 세포 분화에 관여하며 세포 내 ROS 수준 조절에 중요하므로, HomCs는 KBD에서 산화 스트레스에 대한 보호적 역할을 할 가능성이 있다.

**OA에서 확장된 세포 집단: RegCs**

CHI3L1, AEBP1, PLIN2, STEAP1 발현으로 동정된 RegCs가 OA에서 현저히 확장되었다. IHC에서 AEBP1은 표층/중층에서, CHI3L1과 STEAP1은 표층/중층/심층에서 OA 연골에서 상향조절되었다. qRT-PCR에서 AEBP1과 CHI3L1 발현이 OA 환자에서 증가하였다.

**Pseudotime 궤적: KBD와 OA의 분기**

Monocle 분석에서 정상 연골 세포가 궤적 시작점에 위치하고, 두 개의 운명으로 분기하였다: 운명1은 주로 KBD 세포로, 운명2는 주로 OA 세포로 채워졌다. 운명1(KBD)에서 FN1, CHI3L2, RGCC, COL9A3, MDFI가 현저히 상향조절되었고, 운명2(OA)에서 HMOX1, COL1A1, WISP2, CD9, PCOLCE, IGF1, VCAN, PCSK5, SPP1가 상향조절되었다. 이는 두 질환이 초기 분기점에서부터 다른 유전자 프로그램을 활성화함을 시사한다.

**재클러스터링 분석**

PreHTCs, HTCs, RegCs, effector chondrocytes(ECs)를 재클러스터링하여 HTC-A(IGF2, SLC5A3), HTC-B(MMP3, GDF5), PreHTCs(S100A4, HLA-B), ECs(MIA, PLA2G2A), RegCs(CHI3L1, AEBP1)로 세분화하였다. FCs를 재클러스터링하여 RPS4Y1hi, COL3A1hi, FGF1+, IGFBP6+, COL14A1+ 아집단을 확인하였다. KBD와 OA 각각을 따로 분석했을 때 ECs는 두 질환에서 동일한 마커 패턴(MIA, S100B, FRZB, C2orf82, S10A1)을 보였으나, KBD의 HTCs는 IBSP, MMP13, RUNX2, TMEM119로 정의되었다.

---

## Perspective

본 연구는 KBD와 OA 연골의 단일세포 전사체를 체계적으로 비교하여, 두 질환이 연골세포 집단 수준에서 뚜렷한 차이를 보임을 처음으로 증명하였다. KBD에서는 미토콘드리아 기능 및 산화 스트레스 반응과 관련된 HomCs와 MTCs가 확장되어, 미토콘드리아 기능장애와 미토콘드리아 매개 세포사멸이 KBD 병리기전의 핵심임을 시사한다. OA에서는 CHI3L1+ RegCs가 확장되어 염증 및 조직 재모델링 반응이 두드러졌다. CPCs가 정상 연골에서만 풍부하게 존재하고 질환 연골에서 소실된 것은 연골 재생 능력의 상실과 연관될 수 있다. 이러한 질환 특이적 세포 집단과 마커 유전자는 KBD와 OA의 분자 수준 감별 진단 및 표적 치료 개발에 중요한 자원을 제공한다. 특히 MTCs와 HomCs는 KBD의 풍토적 특성(셀레늄 결핍, 곰팡이 독소 등)과 산화 스트레스 간의 연결고리를 규명하는 단서가 될 수 있다. 본 연구의 한계로는 샘플 크기가 작고(각 군 3쌍), OA 샘플이 모두 여성에서 수집되어 성별 편향의 가능성이 있으며, 향후 더 큰 코호트와 유도형 Col2-CreERT 모델을 이용한 검증이 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
