---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# A Single Cell Atlas of Spared Tissue Below a Spinal Cord Injury Reveals Cellular Mechanisms of Repair

## Citation (NLM)
Matson KJE, Russ DE, Kathe C, Maric D, Hua I, Krynitsky J, Pursley R, Sathyamurthy A, Squair JW, Courtine G, Levine AJ. A Single Cell Atlas of Spared Tissue Below a Spinal Cord Injury Reveals Cellular Mechanisms of Repair. bioRxiv. 2021 Apr 29. doi:10.1101/2021.04.28.441862

**DOI:** [https://doi.org/10.1101/2021.04.28.441862](https://doi.org/10.1101/2021.04.28.441862)

---

## Background
척수 손상(SCI) 후 병변 아래의 "보존된(spared)" 조직에는 회복을 지지하거나 증강할 수 있는 손상되지 않은 세포들이 존재하지만, 이 세포들을 표적화하려면 그들의 손상 반응과 복구 능력에 대한 이해가 필요하다. 급성 외상 후 뉴런, 성상교세포, 미세아교세포, 희소돌기아교세포, 혈관세포 등 다양한 세포 유형 간의 복잡한 반응 상호작용이 결과를 결정한다.

병변 중심부를 넘어, SCI 아래의 보존된 조직과 그 해부학적 재조직 및 회복 잠재력에 대한 관심이 대두되고 있으며, 이는 경막외 전기자극과 재활을 병용하는 치료법으로 뒷받침된다. 본 연구는 흉수 손상 후 요추 척수의 각 세포 유형이 시간에 따라 어떻게 변하는지 프로파일링하여 회복을 촉진하거나 제한하는 분자·세포 기전을 규명하고자 하였다.

---

## Key Experiment Methods
1. 마우스 흉수(T9)에 중증 타박 손상(90 kdyn impactor) 유발, 급성~만성 시점(1 dpi, 1 wpi, 3 wpi, 6 wpi)에 걸친 운동기능 추적; 비교를 위해 완전 절단 손상 사용.
2. 요추 척수 전체(조건당 3반복)에 대한 단일핵 RNA 시퀀싱(snRNA-Seq)으로 67,903개 핵 획득; 계층적 클러스터링으로 8개 주요 클래스와 39개 세포 유형 분류.
3. 고다중 면역조직화학 및 다중 RNA in situ hybridization(Agt, Gja1, Aqp4)으로 세포 유형 비율의 조직 내 검증.
4. Augur 분석으로 세포 유형의 섭동 반응성 순위화(클러스터 크기 비의존); 시점별 차등발현, GO 및 KEGG 경로 분석.
5. 마우스 척수 메타분석과의 label transfer로 뉴런 family 주석화; RAG(재생 연관 유전자) 발현 뉴런에 대한 RNAscope in situ(Sprr1a, Atf3)와 공간 및 삼중표지(Slc17a6/vGluT2, Vsx2/Chx10, Shox2) 분석.
6. 요추 척수(비손상 및 절단 후)에 AAV 매개 Igf1 및 Spp1(OPN) 과발현; 미세아교세포 확장, 인산화 IGF1R, Ki67 증식, 미엘린/분해 미엘린 제거 분석.

---

## Results
- 8개 주요 세포 클래스(뉴런, 성상교세포, 미세아교/조혈세포, 희소돌기아교 계열, 슈반세포, 내피세포, 주피세포, 상의세포, 연질막)와 39개 아형이 분리되었고, 전반적 세포 구성은 손상 후 비교적 안정적이었다.
- 첫 주 내 두 가지 예외: 미세아교/조혈세포 비율이 3배 증가하고 시퀀싱 기반 성상교세포 비율이 감소하였으나, 조직 내 검증에서 미세아교세포 증가는 실제였고 성상교세포 감소는 실제 세포 소실이 아닌 상대적 비율 변화를 주로 반영하였다.
- Augur는 1 dpi에서 미세아교세포를 가장 섭동 반응성이 높은 세포로 순위화하였고, 가장 큰 유전자 발현 변화는 1 dpi에 발생하였다(신경교 대사 폭증, 반응성 성상교세포 표지 Lcn2/Serpina3n, 혈관외 혈액 신호를 시사하는 거의 전반적인 Mt1/Fth1 금속결합 유도). 뉴런 스트레스/가소성 변화는 1-3 wpi에 나타나고 6 wpi에는 기저 수준으로 회귀하였다.
- 드물고 이질적인 상행 투사 뉴런 집단이 손상 후 RAG signature(Atf3, Sprr1a, Tnfrsf12a/Fn14, Sox11, Bdnf, Adcyap1, Gap43)를 유도하였다. RAG 발현 세포는 대부분 흥분성이었고 rostral-caudal 구배를 보였으며, 복측 RAG+ 뉴런은 거의 전부 흥분성이고 흔히 Shox2+(추정 척수소뇌로 뉴런)였다. 특이성이 높아 Vsx2+가 아닌 Shox2+ 뉴런만 RAG를 유도하였다. 타박과 완전 절단 모두에서 RAG 발현이 유발되었다.
- 질환 연관 미세아교세포(알츠하이머, ALS) 및 출생 후 미엘린 탐식 미세아교세포와 유사한 "trauma associated microglia"(TAM) 집단이 퇴행성 축삭의 백질로(적핵척수로, 피질척수로)를 따라 국소화하였고, 탐식(Cd68, Gpnmb, Itgax), 지질처리(Apoe, Lgals3, Fabp5), 영양(Igf1, Spp1/OPN) 유전자를 발현하였다.
- TAM은 Igf1과 Spp1(OPN)을 공동발현하는 유일한 세포였고, 활성(인산화) IGF1R과 Ki67 증식이 백질 미세아교세포 군집에 국소화하여 자가분비 자기증폭 회로를 뒷받침하였다. AAV Igf1/Spp1 과발현은 손상 및 비손상 척수 모두에서 TAM(탐식성 미세아교세포 결절)을 확장시키고 미엘린 잔해의 제거/분해를 유도하였다.

---

## Perspective
본 연구는 흉수 SCI 후 보존된 요추 척수의 세포 유형별 반응에 대한 참조 단일세포/핵 아틀라스를 제공하며, 제한적이지만 두 가지 내재적 복구 기전을 밝힌다: 드문 RAG 발현 친재생 뉴런 집단과 성장 억제성 미엘린 잔해를 제거할 수 있는 TAM 세포이다. 외인성 Igf1/Spp1 전달은 TAM 매개 미엘린 제거를 증폭시킬 수 있어 후보 치료 경로를 제시하며, 시간적으로 조절된 전달이 가장 효과적일 수 있다. TAM이 알츠하이머병 및 ALS의 미세아교세포와 유사하다는 점은 공유된 CNS 외상/질환 경로를 시사한다. 한계로는 핵 사용(낮은 심도, 전사후 정보 부재)과 단일세포 비율 변화에 대한 독립적 조직 내 검증의 필요성이 언급되었다. 프리프린트로서 동료심사를 거치지 않았다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
