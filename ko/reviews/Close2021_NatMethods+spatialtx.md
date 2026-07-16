---
tags: [2026-07]
extract: 2026-07-16
---

# Spatially resolved transcriptomics in neuroscience

## Citation (NLM)
Close JL, Long BR, Zeng H. Spatially resolved transcriptomics in neuroscience. Nat Methods. 2021;18(1):23-25. doi:10.1038/s41592-020-01040-z

**DOI:** [https://doi.org/10.1038/s41592-020-01040-z](https://doi.org/10.1038/s41592-020-01040-z)

---

## Overview

이 글은 Nature Methods의 Comment(FOCUS) 기고로, 신경과학에서 공간 전사체학(spatially resolved transcriptomics)의 응용과 기술적 과제를 논한다. 뇌와 같은 복잡한 기관을 이해하려면 이를 구성하는 세포 유형의 census, 그 기능, 상호 관계를 파악해야 한다. 단일세포 RNA 시퀀싱(scRNA-seq)은 전사체 기반 세포 유형 분류를 가능하게 했으나, 조직을 해리하는 과정에서 해부학적·공간적 맥락을 상실한다.

공간 전사체학은 단일세포 전사체 프로파일을 연결성, 형태, 생리, 기능적 특성과 연계하면서 조직 내 세포 위치를 함께 제공하는 접근법으로 부상했다. 대부분의 기법은 다중화 형광 in situ 혼성화(FISH), in situ 시퀀싱, in situ 포획(ex situ 시퀀싱) 방식에 기반한다. 저자들은 이 기술이 신경계 세포 유형의 census 제공을 넘어, 분자 정체성·연결성·형태·생리를 통합하는 "로제타석" 역할을 할 잠재력을 강조한다.

---

## Key Topics

- **세포 유형 매핑**: 다중화 정도에 따른 방법 선택 — osmFISH(39유전자, 체감각피질 31세포유형), MERFISH/seqFISH(수백 유전자, 시상하부 시각전핵 70세포유형), pciSeq/STARmap(padlock probe 기반 in situ 시퀀싱), Slide-seq/Visium(전사체 규모, 큰 면적, 낮은 민감도·해상도).
- **뇌 세포 유형 아틀라스**: BRAIN Initiative Cell Census Network(BICCN), Human Cell Atlas가 포유류 뇌 세포 유형 아틀라스 구축을 추진. 일차 운동피질(primary motor cortex)이 첫 체계적 시도.
- **다중모달 대응(multimodal correspondence)**: 칼슘 이미징, 광유전학, Patch-seq 등 기능 측정 후 공간 전사체학으로 세포 유형을 사후 식별하여 회로 기능에 세포 유형별 해석 부여. IEG 발현을 신경 활동 대리지표로 활용.
- **연결성 매핑**: BARseq 등 바코드 기반 방법으로 축삭 투사 표적을 세포 정체성 유전자와 함께 판독, 밀집 세포 유형 지도에 장거리 투사 정보 추가.
- **기술적 과제**: mRNA를 개별 세포에 정확히 할당하는 세포 분할(segmentation) 문제, 확장성(수백~수천 유전자를 큰 시료에서 고민감도로 이미징), ExFISH 등 확장·투명화 기법.

---

## Key Findings

- 이미징 기반 방법은 높은 민감도와 단일세포 수준 공간 해상도를 제공하나 긴 이미징 시간 탓에 분석 면적이 작다. 반면 포획·시퀀싱 기반 방법(Visium, Slide-seq)은 큰 면적의 비편향 전사체 규모 프로파일링이 가능하나 민감도·해상도가 낮다.
- pciSeq, Baysor 등은 scRNA-seq 클러스터 데이터를 사전정보로 활용하여 mRNA를 세포에 확률적으로 할당.
- 다중 라운드 smFISH가 마우스와 인간 뇌 상층 뉴런의 진화적 차이를 기술하는 데 적용되어 종간 비교 가능성 시연.
- 인간 알츠하이머병 모델에서 식별된 plaque-induced genes를 인간 뇌 조직에서 in situ 시퀀싱으로 국재·확인.
- 궁극적으로 분자 유형·위치·기능 간 관계가 해상되면서 "세포 유형" 개념 자체가 변화할 것.

---

## Perspective

의의: 공간 전사체학이 신경계 세포 유형 census를 넘어 연결성·회로 기능과 통합되는 방향을 조망하며, 다양한 방법의 강점·약점(민감도 대 면적, 다중화 정도)을 실무적으로 정리했다. 한계: 대부분의 기법이 개발 실험실 외부에서 재현·출판된 사례가 적고, 세포 분할·확장성·상업화에 따른 사용성/재현성 문제가 남아 있다. 향후 방향: 고다중화·고해상도·고처리량 공간 전사체학을 통해 다양한 종·유전적 배경에서 세포 유형 변이 평가, 신경 발달 중 세포 상태·이동 추적, 행동의 세포 상관물 규명, 인간 질환·동물 모델의 세포 유형별 병리 변화 규명이 가능해질 전망이다.

---

## Key References

- Zeng H, Sanes JR (2017) Neuronal cell-type classification. *Nat Rev Neurosci* 18:530-546.
- Codeluppi S, et al. (2018) Spatial organization of the somatosensory cortex revealed by osmFISH. *Nat Methods* 15:932-935.
- Chen KH, et al. (2015) Spatially resolved, highly multiplexed RNA profiling in single cells (MERFISH). *Science* 348:aaa6090.
- Moffitt JR, et al. (2018) Molecular, spatial, and functional single-cell profiling of the hypothalamic preoptic region. *Science* 362:eaau5324.
- Wang X, et al. (2018) Three-dimensional intact-tissue sequencing of single-cell transcriptional states (STARmap). *Science* 361:eaat5691.
- Rodriques SG, et al. (2019) Slide-seq. *Science* 363:1463-1467.
- Chen X, et al. (2019) High-throughput mapping of long-range neuronal projection using in situ sequencing (BARseq). *Cell* 179:772-786.
- Chen WT, et al. (2020) Spatial transcriptomics and in situ sequencing to study Alzheimer's disease. *Cell* 182:976-991.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
