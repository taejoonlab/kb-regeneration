---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
---

# Probing the communication patterns of different chondrocyte subtypes in osteoarthritis at the single cell level using pattern recognition and manifold learning

## Citation (NLM)

Wang J, Liu C, Yang L, Chen H, Zheng M, Wan Y, Hong X, Li S, Han J, Luo R, Wan X, Zhang JV, Xu R. Probing the communication patterns of different chondrocyte subtypes in osteoarthritis at the single cell level using pattern recognition and manifold learning. _Sci Rep._ 2023 Sep 4;13(1):14467. doi: [10.1038/s41598-023-41874-z](https://doi.org/10.1038/s41598-023-41874-z). PMID: 37666903.

---

## Background

골관절염(OA)은 만성 관절 장애로 관절 조직 대사를 교란하며 염증과 골 퇴행을 동반한다. 연골세포(chondrocyte)는 연골의 유일한 세포 유형으로, 휴지기(quiescent), 증식기(proliferative), 전비대(prehypertrophic), 비대기(hypertrophic), 최종적으로 골로 석회화되는 단계로 분화·발달한다. 단일세포 시퀀싱 기술의 적용으로 연골세포의 7개 아집단이 동정되었다: effector chondrocytes(ECs), fibrocartilage chondrocytes(FCs), hypertrophic chondrocytes(HTCs), homeostatic chondrocytes(HomCs), proliferative chondrocytes(ProCs), regulatory chondrocytes(RegCs), prehypertrophic chondrocytes(preHTCs). 각 아집단의 기능적 특징은 연구되었으나, **OA 미세환경에서 이들 아집단이 어떻게 상호작용하고 협력하여 OA 진행을 촉진하는지**는 알려지지 않았다. 본 연구는 단일세포 전사체 데이터셋에서 네트워크 분석과 패턴 인식을 통해 연골세포 아집단 간의 세포 간 통신 패턴을 최초로 규명하였다.

---

## Key Experiment Methods

**1. 단일세포 데이터셋 수집**

- OA 환자 10명의 무릎 관절 연골세포 1,600개 단일세포 데이터(GSE104782) 사용
- 경골 플랫폼(tibial plateau) 영역에서 연골 전층 포함 시편 추출
- 연골전구세포(chondroprogenitor) 분화 시간 경과 데이터(GSE160625, day 7/14/28/42) 비교 분석

**2. CellChat 기반 세포 간 통신 분석**

- R package CellChat으로 세포-세포 통신 네트워크 구축
- 정규화된 scRNA-seq 평균 발현 데이터(trimean)와 세포 주석 정보 입력
- computeCommunProb로 ligand-receptor 쌍 기반 통신 확률 추론
- computeCommunProbPathway로 신호전달 경로별 프로파일 추론

**3. 통신 패턴 정량화**

- netAnalysis_computeCentrality로 세포 아집단의 통신 역할(sender, receiver, mediator, influencer) 도출
- selectK로 incoming/outgoing 신호 패턴 계산
- identifCommunicationPatterns로 세포 간 통신 패턴 수 계산
- netAnalysis_river, netAnalysis_dot으로 특정 경로 시각화

**4. 통신 네트워크 비교**

- compareInteractions로 상호작용 수와 강도 비교
- netVisual_diffInteraction으로 세포 그룹 간 상호작용 차이 시각화
- netAnalysis_signalingRole_scatter로 데이터셋 간 유의한 차이 세포 집단 동정

**5. Manifold learning 및 정량적 대비**

- computeNetSimilarity, netEmbedding, netClustering으로 유사 신호 클러스터링
- 보존된(conserved) 및 특이적(specific) 통신 경로 동정

---

## Results

**연골세포 아집단 간 상호작용 강도** ECs, FCs, HTCs 간 상호작용 강도가 강하였고, preHTCs, ProCs, HomCs는 중간, undefined 및 RegCs는 약하였다. ProCs와 preHTCs 간 상호작용은 강하지 않았으나, HTCs 내 상호작용은 매우 강하여 아집단 간 전이 관계가 있음을 시사하였다.

**Incoming/Outgoing 통신 패턴** Undefined 및 RegC는 "수동적" 세포 유형이었고, 활성 세포 유형은 두 그룹으로 분류되었다:
- **Group 1**(incoming 우세): preHTC, EC, ProC — 수신 신호가 우세하고 발신 신호는 보조적
- **Group 2**(outgoing 우세): HomC, HTC, FC — 발신 신호가 우세하고 수신 신호는 보조적

**신호전달 경로 중복 및 배타성** ProCs와 preHTCs는 거의 모든 경로가 중복되어 가장 활성적인 아집단이었다. 반면 **ECs와 FCs는 "상호 배타적(mutually exclusive)"** 쌍으로, 활성 신호전달 경로가 대부분 중복되지 않았다:
- EC outgoing: GAS, CHEMERIN, PTPRM, VEGF, WNT
- FC outgoing: COLLAGEN, LAMININ, MK, CXCL, ANGPTL, CADM
- EC incoming: CHEMERIN, PTPRM, FGF
- FC incoming: SEMA3, EPHA, CADM

**preHTC의 다중 역할** 23개 신호전달 경로(COLLAGEN, LAMININ, THBS, GAS, MPZ, MK, TGFb, CHEMERIN, BMP, PROS, CXCL, SEMA3, FGF, ANGPTL, PTPRM, EPHA, PTH, ncWNT, JAM, VISFATIN, CADM, VEGF, WNT) 분석에서 **preHTC만이 sender, receiver, mediator, influencer의 모든 역할**을 수행하였다. THBS, GAS, MPZ, MK 경로에서 preHTC와 FC가 주요 활성 세포였으나, FC는 influencer/sender 역할에 국한된 반면 preHTC는 다중 역할을 수행하였다.

**핵심 ligand-receptor 쌍** COLLAGEN 경로에서 ITGAV, ITGB1, ITGA10, COL4A1, COL4A2, COL9A3이 주요 리간드-수용체 쌍이었고, COL4A1/COL4A2는 FC, EC, HTC에서 주로 활성이었다. LAMININ 경로에서 LAMB2, LAMC1, ITGA2, ITGAV, ITGB1이 관여하였고, LAMC1은 FC에서, ITGA2는 EC와 ProC에서 우세하였다. ITGB1은 여러 아집단에 광범위하게 분포하였다.

**연골전구세포 vs 연골세포 통신 패턴 비교** 연골전구세포 분화 시간 경과 분석에서 성숙 단계가 진행될수록 통신 경로가 강해지고 연골세포 아집단이 뚜렷해졌다. HMGB2/CDK1+ 증식 연골세포(ProCs)와 CD24/SOX2+ 비대 연골세포(preHTCs)가 활성 입력 신호와 중간 강도 출력 신호를 showed. MK, ANGPTL, FGF, VISFATIN, BMP, WNT, GAS, TGFb, ncWNT, VEGF, SEMA3 등 많은 신호가 연골세포와 연골전구세포에서 공통적으로 확인되어, 분화와 후기 기능이 분리되지 않는 연속적 분자 과정임을 시사하였다.

---

## Perspective

본 연구는 OA 연골세포 아집단 간의 세포 간 통신 패턴을 단일세포 수준에서 체계적으로 분석한 최초의 연구로, 다음과 같은 의의를 갖는다.

첫째, preHTC가 연골세포 통신에서 **sender, receiver, mediator, influencer의 모든 역할**을 수행하는 유일한 아집단임을 밝혀, preHTC가 OA 미세환경에서 세포 간 신호 중추(hub)로 작용함을 입증하였다. preHTC의 ligand-receptor(ITGAV, ITGB1, ITGA10)가 가장 활성적이어서, preHTC 표적 치료가 OA 진행 조절에 핵심적일 수 있다.

둘째, ECs와 FCs가 "상호 배타적" 쌍으로, 서로 다른 신호전달 경로를 사용함이 발견되었다. EC는 incoming 신호 우세(수신 중심), FC는 outgoing 신호 우세(발신 중심)로, 이 두 아집단이 상보적 역할을 수행하여 연골 항상성 유지에 기여할 가능성이 시사되었다.

셋째, COLLAGEN과 LAMININ 경로가 연골세포 통신의 핵심 경로로 확인되어, 관절 항상성 repair 및 확장에서 ECM-세포 간 상호작용의 중요성을 재확인하였다. ITGAV, ITGB1, ITGA10 등 integrin 계열 수용체가 여러 아집드에 걸쳐 관여하여, OA 치료 표적으로서 잠재력이 크다.

넷째, 패턴 인식과 manifold learning 기반 접근법이 단일세포 통신 분석의 새로운 연구 패러다임을 제시하였다. 이 방법은 우세 세포 집단(ProCs, preHTCs)을 신속하게 타겟팅하여 세포 치료 대체 세포로 선별하거나, 관련 억제제 개발로 OA 관련 통신을 차단하는 치료 전략에 적용 가능하다.

향후 과제로는 더 큰 OA 환자 코호트(질환分级 정보 포함)에서의 검증, 단일세포 공간 전사체(spatial transcriptome) 및 공간 단백질체 기술을 통한 연골세포 공간 분포와 통신 패턴의 통합 분석, 그리고 FACS/sorting으로 동정된 아집단의 실제 분리 및 세포 치료 적용 최적화가 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
