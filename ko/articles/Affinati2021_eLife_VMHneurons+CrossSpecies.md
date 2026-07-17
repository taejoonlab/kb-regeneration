---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Cross-species analysis defines the conservation of anatomically segregated VMH neuron populations

## Citation (NLM)
Affinati AH, Sabatini PV, True C, Tomlinson AJ, Kirigiti M, Lindsley SR, Li C, Olson DP, Kievit P, Myers MG, Rupp AC. Cross-species analysis defines the conservation of anatomically segregated VMH neuron populations. eLife. 2021;10:e69065. doi:10.7554/eLife.69065

**DOI:** [https://doi.org/10.7554/eLife.69065](https://doi.org/10.7554/eLife.69065)

---

## Background

배쪽안쪽시상하부핵(ventromedial hypothalamic nucleus, VMH)은 주로 글루탐산성 뉴런으로 구성되며 공포(panic), 생식, 공격성, 포도당 항상성, 에너지 소비 등 다양한 행동과 생리 기능을 조절한다. VMH의 해부학적 하위영역(배내측 VMHDM, 중심 VMHC, 배외측 VMHVL)은 각각 여러 출력을 매개하므로, 기능적으로 구별되는 다수의 뉴런 아형이 존재할 것으로 추정된다. 그러나 기존 기능 연구 대부분은 Nr5a1(SF1)이나 전사체적으로 구별되는 세포유형과 반드시 일치하지 않는 단일 후보 유전자에 의존하였다.

VMH 세포 지형을 비편향적이고 유전적으로 조작 가능한 방식으로 정의하고 종간 보존성을 검증하기 위해, 저자들은 마우스에서 translating ribosome affinity purification with RNA-sequencing(TRAP-seq)과 단일핵 RNA 시퀀싱(snRNA-seq)을 결합하고, 마카크 원숭이 VMH snRNA-seq를 추가하여 종간 비교를 수행하였다.

---

## Key Experiment Methods

1. 미세절제한 마우스 VMH의 snRNA-seq(10X Genomics; 10 샘플, QC 통과 핵 약 42,040개, 뉴런 21,585개가 37개 집단 형성).
2. Nr5a1-Cre;Rosa26eGFP-L10a TRAP-seq로 광범위 VMH 농축 전사체(4492 유전자)를 정의하고 VMH 클러스터 식별; snRNA-seq "pseudo-TRAP"와 비교.
3. VMH 뉴런의 반복적 하위 클러스터링으로 24개 집단 도출 후, CELLEX 마커 분석과 계층적 클러스터링, silhouette/상관 지표로 단순화된 6개 클래스 체계 정의.
4. 교차(intersectional) Lepr 지향 TRAP-seq(Slc17a6Flpo;LeprCre;RCFLeGFP-L10a)로 글루탐산성 Lepr 발현 VMH 뉴런을 분리하여 VMHLepr 클래스 확인.
5. 마카크(Macaca mulatta) VMH snRNA-seq 및 종간 통합(Seurat CCA/anchors), Allen Brain Atlas ISH 및 RNAScope ISH(Acvr1c, Slc17a8, Lepr)로 검증.

---

## Results

- Nr5a1-Cre TRAP-seq와 snRNA-seq를 결합하여 VMH 뉴런을 포함하는 6개 집단을 식별하였고, Nr5a1 음성 클러스터도 발생기 Nr5a1-Cre 표지에 의해 VMH(추정 VMHVL)로 확인되었다.
- TRAP-seq와 snRNA-seq(pseudo-TRAP)는 대체로 일치했으나 각 방법 특이적 전사체를 포착했으며, 농축은 주로 발현 수준의 함수였다.
- 하위 클러스터링으로 24개 전사체 정의 VMH 뉴런 집단이 도출되었고, 이들은 뚜렷한 해부학적 분포를 갖는 6개 클래스로 수렴하였다: 배내측 3개(VMHLepr, VMHFezf1, VMHNfib), 배외측 2개(VMHDlk1, VMHEsr1), 그리고 전외측 "tuberal" 글루탐산성 클래스 1개(VMHFoxp2).
- 클래스 특이 마커(Dlk1, Esr1, Nfib, Foxp2, Fezf1, Lepr)는 서로 다른 해부학적 구획에 매핑되며, VMHNfib는 가장 배내측이면서 전사체적으로 가장 뚜렷하게 구별되었다.
- 교차 Lepr TRAP-seq로 Lepr 발현 VMH 뉴런이 VMHLepr 클러스터에 특이적으로 매핑됨을 확인(상위 공유 유전자 Gpr149, Rai14, Tnfrsf8)하여, 전사체·기능적으로 독특한 Lepr 클래스를 뒷받침하였다(에너지 소비에는 관여하나 포도당/공포 반응에는 관여하지 않는다는 기존 결과와 일치).
- 마카크 snRNA-seq는 7개 집단을 산출했고, LEPR·FOXP2·NFIB·ESR1로 표지되는 클래스는 명확한 마우스 상동체를 가졌다. 마카크 VMHQRFPR 집단은 밀접히 관련된 마우스 VMHDlk1 및 VMHFezf1 클래스에 대응하였다.
- 마우스-마카크 통합 결과 주요 VMH 클래스가 유전자 발현과 해부학적 분포에서 보존됨을 보였고, ISH로 마카크 VMHDM에서 ACVR1C와 LEPR 공발현, SLC17A8이 가장 배내측(VMHNFIB 유사) 세포를 표지함을 확인하였다.

---

## Perspective

본 연구는 VMH의 복잡한 24개 뉴런 집단을 마우스와 마카크 사이에서 보존되는 유전적·해부학적으로 조작 가능한 6개 클래스로 축약한 비편향적 종간 아틀라스를 제공하며, VMH 아형을 선택적으로 조작·연구할 마커를 제시한다. 설치류와 영장류에서 뚜렷한 Lepr/LEPR 클래스가 보존된다는 점은, VMH 대사 기능 연구와 비만·당뇨 치료 표적 발굴에서 마우스를 대리 모델로 활용하는 것을 뒷받침한다. 한계로는 종간 상동성 판정이 전사체 상관에 의존한다는 점(일부 마커 유전자가 종간 상이, 예: DLK1/FEZF1 대 QRFPR), 절제 편향으로 외부 VMHVL 중심 데이터(Kim et al.) 통합이 필요했던 점, 그리고 새로 정의된 여러 클래스(예: VMHFoxp2, VMHNfib)의 생리 기능이 아직 검증되지 않은 점이 있다. 향후 이들 클래스를 기능적으로 표적하는 연구가 필요하다. 참고로 척수/재생 지식베이스에서는 본 논문을 CNS/신경계 단일핵 아틀라스로 포함하며, 방법론(TRAP-seq + snRNA-seq 통합, 종간 보존성 분석)은 신경계 아틀라싱 전반에 응용 가능하다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
