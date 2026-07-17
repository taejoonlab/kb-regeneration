---
tags: [2026-07]
extract: 2026-07-16
---

# Diversified transcriptional responses of myeloid and glial cells in spinal cord injury shaped by HDAC3 activity

## Citation (NLM)
Wahane S, Zhou X, Zhou X, Guo L, Friedl MS, Kluge M, Ramakrishnan A, Shen L, Friedel CC, Zhang B, Friedel RH, Zou H. Diversified transcriptional responses of myeloid and glial cells in spinal cord injury shaped by HDAC3 activity. Sci Adv. 2021;7(9):eabd8811. doi:10.1126/sciadv.abd8811

**DOI:** [https://doi.org/10.1126/sciadv.abd8811](https://doi.org/10.1126/sciadv.abd8811)

---

## Background

미세아교세포(microglia)는 중추신경계(CNS)의 상주 골수계(myeloid) 세포로 항상성 유지에 기여하며, 손상 시 수 분 내에 활성화되어 혈액 유래 대식세포와 함께 선천 면역 반응(손상 활성화 미세아교세포/대식세포, IAM)을 구성한다. IAM의 지속적 염증 표현형은 척수손상(SCI) 후 이차적 신경 손상을 악화시키는 것으로 여겨지므로, 이러한 반응의 다양성과 조절 기전을 이해하는 것은 신경 회복 연구의 핵심이다. 중요한 미해결 질문은 IAM이 신경퇴행(알츠하이머병, ALS 등)에서 기술된 질환 연관 미세아교세포(DAM)와 대표 유전자 및 조절 기전을 공유하는지 여부이다.

면역 활성화는 염색질 변형에 의해 조절되는 대규모 유전자 재프로그래밍을 요구한다. 저자들은 앞선 연구에서 SCI 후 IAM에서 히스톤 탈아세틸화효소 3(HDAC3)이 상향 조절되며, HDAC3 약리학적 억제가 염증을 억제하고 회복을 개선함을 보인 바 있다. 본 연구는 골수계 특이적 벌크 전사체 분석과 단일세포 RNA-seq을 결합하여 SCI에 대한 골수계 및 신경교세포 반응의 시간적·세포유형별 다양성을 규명하고 HDAC3 영향의 범위를 매핑한다.

---

## Key Experiment Methods

1. Cx3cr1CreER INTACT 마우스 모델에서 tamoxifen으로 골수계 핵막에 GFP 표지를 유도; 해리 유발 인위적 변화를 피하기 위해 급속 냉동 척수 조직에서 GFP 표지 핵을 INTACT(특정 세포유형 태깅 핵 분리) 면역정제.
2. T8 등쪽 기둥 절단 후 3, 7, 14일차(dpi)의 정제된 골수계 핵에 대한 벌크 RNA-seq(3중 cDNA 라이브러리), laminectomy만 시행한 대조군과 비교; qRT-PCR 특이성 대조.
3. 분석: UMAP, k-means 클러스터링, 비음수 행렬 분해(NMF), 계층적 유전자 클러스터링, 가중 유전자 공발현 네트워크 분석(WGCNA), 차등 엑손 사용(대체 스플라이싱), GO/IPA, GSEA(M1 vs M2 분극), 상류 조절자 및 인터랙토옴 분석.
4. IAM 시그니처를 공개된 DAM 시그니처 및 신경퇴행 연관 미세아교 유전자 세트(connectivity map)와 비교.
5. 특이적 HDAC3 억제제 RGFP966(HDAC3i)를 이용한 기능 회복 연구; 급성(2, 24, 48시간) 대 아급성 요법을 Basso Mouse Scale(BMS) 점수로 비교.
6. 5 dpi 손상 척수(T8 타박상)의 단일세포 RNA-seq(10X Genomics), 세 조건(CTRL 무손상 참조, SCI, SCI_HDAC3i)에서 총 9937개 세포; 비지도 클러스터링·서브클러스터링과 Slingshot 단일세포 궤적 분석.
7. 면역조직화학 검증(IBA1, Tmem119, LPL, CD11c, P2ry12, SPP1, FN, HDAC3 등).

---

## Results

- INTACT 벌크 RNA-seq은 시간적으로 구별되는 IAM 전사 프로그램을 보였고 3-dpi 표본이 가장 발산적이었다. 네 개 유전자 클러스터가 증식/이동/ECM(3 dpi 상승), 대사/RNA 처리(3 dpi 하강), 신경세포 상호작용(7 dpi 하강, 14 dpi 상승), 신경계 발생/ECM(전 시점 하강)에 매핑됨. WGCNA는 103개 모듈을 식별했고 그중 13개가 이들 클러스터에 유의하게 농축됨.
- 모든 시점에 공유되는 131개 핵심 IAM 유전자(104개 상승, 27개 하강)는 파고솜 및 지질 대사 경로에 농축되었고, DAM 마커 Apoe·Lpl과 Axl, Ctsb, Ctsd, Grn, Abca1, Abcg1, 면역/ECM 유전자(Spp1, Fn1, Ccl3, Csf1, Igf1)를 포함. 전압 개폐성 Ca2+ 채널 유전자(Cacnab2, Hcn1, Slc24a2, Trpc5)는 하향 조절됨.
- IAM과 DAM은 11개 유전자(면역, 청소, 조직 복구)를 공유. 주목할 점으로 DAM 마커 Trem2와 Tyrobp는 IAM에서 유의하게 상승하지 않아 신경퇴행 연관 미세아교세포와 핵심적으로 구별됨.
- 다수 염증 유전자의 상향 조절에도 불구하고 IAM은 우세한 전염증 프로파일을 보이지 않음: 57개 전염증 유전자 중 9개만 유의 상승했고, GSEA는 전 시점에 걸쳐 전반적으로 복구적(M2 경향) 프로파일을 시사. 시간 분해 사건: 3 dpi 세포주기+인터페론 신호, 7 dpi 이동+이온 채널 변화, 14 dpi ECM 재구성+LXR/RXR. IAM은 광범위한 대체 스플라이싱을 사용했고 3 dpi에서 최대(1361개 차등 엑손).
- IAM 프로그램의 상류 조절자(CSF2, LPS, IL-6, IFN, TGFβ1; 음성 조절자로 p53/CDKN1A; 전사인자 NFκB·STAT·IRF 계열)는 인터랙토옴 분석에서 HDAC3와 연결됨. 급성 HDAC3i(RGFP966)는 아급성 요법보다 BMS 운동 회복을 더 개선.
- 5 dpi scRNA-seq은 9개 세포 클러스터(희소돌기아교세포, 골수계, 내피, 신경세포, 성상교세포, 호중구, OPC, 주피세포, OPC/Oligo 전이 클러스터)를 식별. SCI는 면역·혈관 집단과 OPC/Oligo 전이 클러스터를 확장; HDAC3i는 분포를 소폭 이동(호중구 클러스터 축소, 신경/희소돌기 소폭 확장). Hdac3 mRNA는 세포 간 이질적이며 SCI로 변하지 않아 HDAC3 단백질의 전사 후 조절을 시사.
- 미세아교세포와 대식세포는 손상 후에도 전사적으로 구별됨(둘 사이 916개 DEG). HDAC3 의존성은 세포유형별로 상이: 미세아교세포에서는 증식·케모카인/사이토카인 활성·시냅스 형성·PI3K/AKT, 대식세포에서는 이물질 대사·백혈구 이동·생존. HDAC3 의존 유전자의 약 20%가 공유됨(주화성, 케모카인, RANKL, p38 MAPK).
- 골수계 세포는 4개 미세아교(MG1–MG4) 및 4개 대식세포(Mac1–Mac4) 아형으로 분해되어 각기 특화된 기능 수행: MG1 면역/항상성, MG2 파고사이토시스/지질 대사(반응성, TyroBP/TGFβ), MG3 즉시반응(BDNF 신호, IEG Fos/Jun/Egr1), MG4 증식성(Cdk1, Top2a, p53 신호; Hdac3 우선 발현). 네 개 MG 상태 모두 건강한 척수에도 존재하여 기저 미세아교 이질성을 드러냄.
- SCI는 MG1과 MG2를 확장(MG2가 미세아교 중 5%→22%로 가장 크게 증가)하고 MG3·MG4를 축소. Slingshot 궤적은 MG3→MG1→MG2→MG4; HDAC3i는 시작점을 MG3에서 MG4로 이동(궤적 MG4→MG2→MG1→MG3)시켜 HDAC3가 증식과 케모카인/RANKL 활성화를 제어함과 일치.
- 대식세포 아형(Mac1이 약 75%로 우세)은 IAM·DAM 특징을 모두 지님; IAM/DAM 핵심 시그니처는 주로 Mac1과 반응성 미세아교 아집단 MG2에 농축되어 파고사이토시스 및 잔해 청소로의 기능적 수렴을 부각.
- 별개의 상의세포(ependymal) 집단(Sox2, Foxj1, Riiad1)이 신경세포에서 분리됨; SCI는 신경세포 집단을 축소했으나 반응성 상의세포를 현저히 확장(ECM 조직화; Wnt, Hedgehog, PDGF-B 신호). HDAC3i는 448개 상의세포 유전자에 영향, 78%가 HDAC3에 의해 억제됨(Frizzled/인테그린 결합, 콜라겐 생합성).

---

## Perspective

본 연구는 척수손상에 대한 선천 면역 및 신경교세포 반응의 벌크(골수계 특이 INTACT)와 단일세포 아틀라스를 통합적으로 제공하며, HDAC3를 미세아교세포·대식세포·상의세포에 걸쳐 작용하는 광범위한 후성유전 조절자로 위치시킨다. 개념적으로 중요한 발견은 다음과 같다: (1) 손상 활성화 미세아교세포는 순수 전염증이 아니라 전반적으로 복구적 프로파일을 취함; (2) IAM과 DAM은 지질 대사/파고사이토시스 핵심을 공유하나 Trem2/Tyrobp 사용에서 차이; (3) 미세아교 이질성(MG1–MG4)은 건강한 척수에도 존재하며, 즉시반응 MG3가 소스 상태로, 증식성 MG4가 HDAC3를 우선 발현; (4) 급성 투여 시 가장 효과적인 HDAC3 억제가 미세아교 전환 궤적을 재편하고 운동 회복을 개선. 이는 HDAC3를 SCI 후 선천 면역 반응 조율을 위한 치료 표적으로 제시한다.

한계로는 해리 취약성과 포획 효율에 의해 편향될 수 있는 세포유형 빈도 추정, 두 가지 SCI 모델 사용(INTACT는 등쪽 기둥 절단 vs scRNA-seq는 타박상), 단일 scRNA-seq 시점(5 dpi), 말초 대식세포보다 미세아교세포를 우선 표지하는 tamoxifen 방식, 그리고 HDAC3 조절이 주로 전사 후 수준으로 보이는 점(mRNA 변화 없이 단백질 상승) 등이 있다. 향후 방향으로는 각 신경교 아형에서 HDAC3의 기전적 표적 규명과 기능 회복 극대화를 위한 HDAC3i 투여 시점 최적화가 포함된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
