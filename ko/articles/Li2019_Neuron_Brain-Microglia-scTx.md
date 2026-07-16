---
tags: [2026-07]
extract: 2026-07-16
---

# Developmental Heterogeneity of Microglia and Brain Myeloid Cells Revealed by Deep Single-Cell RNA Sequencing

## Citation (NLM)
Li Q, Cheng Z, Zhou L, Darmanis S, Neff NF, Okamoto J, Gulati G, Bennett ML, Sun LO, Clarke LE, Marschallinger J, Yu G, Quake SR, Wyss-Coray T, Barres BA. Developmental Heterogeneity of Microglia and Brain Myeloid Cells Revealed by Deep Single-Cell RNA Sequencing. Neuron. 2019;101(2):207-223.e10. doi:10.1016/j.neuron.2018.12.006

**DOI:** [https://doi.org/10.1016/j.neuron.2018.12.006](https://doi.org/10.1016/j.neuron.2018.12.006)

---

## Background

뇌 실질의 대식세포인 미세아교세포(microglia)는 여러 신경계 질환과 연관되며, 신경발생·시냅스 가지치기 등 신경 발생 과정에도 능동적으로 참여하는 것으로 알려져 있다. 그러나 생리적 조건, 특히 비면역 기능을 다수 수행하는 발생 단계에서의 분자 이질성은 거의 알려지지 않았다. 기존 벌크 RNA-seq 연구는 일반 표면 마커에 의존하여 발생 중 일시적으로 존재하는 집단을 놓칠 수 있었고, 성체 뇌 영역 간에 분자적으로 정의되는 미세아교세포 아형이 존재하는지도 불명확했다.

이를 규명하기 위해 저자들은 편향 없는 심층 단일세포 RNA 시퀀싱(scRNA-seq)으로 마우스 뇌 영역과 발생 단계에 걸쳐 미세아교세포 및 관련 골수세포를 프로파일링하여, 얕은 방법으로는 놓칠 미세한 차이를 해상하고자 했다.

---

## Key Experiment Methods

1. **심층 Smart-seq2 scRNA-seq**: 인덱스 정렬된 선천면역세포를 세포당 100만 리드 이상으로 시퀀싱(총 1,922세포, QC 통과 1,816세포). E14.5, P7, 성체(P60) 단계. ERCC 스파이크인으로 거의 단일분자 수준 민감도(R=0.98) 확인.
2. **영역별 샘플링**: P7·P60에서 6개 영역(피질, 소뇌, 해마, 선조체, 후각망울, 맥락총)에서 골수세포 분리. FACS 게이팅(E14.5: c-Kit/CD45, P7/P60: CD45low/hi CD11b+).
3. **비지도 클러스터링**으로 15개 클러스터 도출(미세아교세포 7, 맥락총 대식세포 2, 단핵구 3, 기타 3); 차등발현으로 클러스터 마커 정의.
4. **세포주기 유사시간(pseudotime) 재구성**: 세포주기 효과 회귀 제거 후 HeLa 유래 보존 세포주기 유전자를 시드로 사용, 분열 미세아교세포의 위상 특이 유전자 세트 구축.
5. **영역별 벌크 RNA-seq**: TMEM119 항체로 정렬한 항상성 미세아교세포로 교차 검증.
6. **검증**: RNAscope in situ, 면역조직화학, FACS(GPNMB+CLEC7A+ 정렬), pH 민감 비드 식균 분석, Trem2−/−·Apoe−/− 마우스 분석.

---

## Results

- 발생 단계에 걸쳐 **15개의 뚜렷한 클러스터** 확인; 미세아교세포 클러스터는 tSNE 상에서 발생 단계별로 분리되어 점진적 유전자발현 변화를 반영.
- **맥락총 대식세포**는 출생 후 전사 전환을 겪어 P7(세포내이입·수송 유전자)과 성체(MHC-II 고발현; 마커 H2-Eb1, Lilra5) 클러스터로 분리.
- **성체 항상성 미세아교세포는 영역 간 전사체 이질성이 제한적**; 영역 간 차등발현 유전자 20개 미만. 한 클러스터의 차이는 주로 즉각초기유전자(IEG)로, 조직에서는 Fos/Egr1 음성이어 분리 과정 인공산물로 해석.
- 분열 P7 미세아교세포에 대한 **위상 특이 세포주기 유전자 세트** 도출(P7-C0 315개, P7-C1 347개), 신규 주기적 발현 유전자 포함(Ankle1, Lig1, Eri1 등).
- **PAM(proliferative-region-associated microglia) 발견**: 발생 중 뇌량과 소뇌 백질에 존재하는 P7 아집단으로, DAM 유사 시그니처(Spp1, Gpnmb, Igf1, Clec7a, Lpl, Itgax, Apoe) 발현. 아메바형 형태, 대사 활성 높음(산화적 인산화, 해당작용, 지질대사, 리소좀 유전자).
- **PAM은 일시적으로 출현**(약 P7 정점, P14까지 소실)하며, 퇴행성 DAM과 달리 **TREM2-APOE 축에 비의존적**.
- **PAM은 수초화 중 새로 형성된(죽어가는, cCASP3+/MBP+) 희소돌기아교세포를 식균**하며, 별아교세포도 소량 식균, OPC(PDGFRA+)는 대상 아님.

---

## Perspective

본 연구는 발생 전반에 걸친 뇌 골수세포의 고해상도 심층 scRNA-seq 아틀라스(brainrnaseq.org에 통합)를 제공하여, 성체 항상성 미세아교세포는 매우 균일한 반면 초기 출생 후 미세아교세포는 이질적임을 확립했다. 질병연관 미세아교세포(DAM)를 닮은 발생 단계 미세아교세포 상태인 PAM의 발견은, 발생 유전자 프로그램이 노화·신경퇴행에서 재활성화된다는 개념을 뒷받침하며 질병 병태생리 이해의 창을 제공한다.

척수/CNS 재생 관점에서 PAM 표현형과 DAM 유사 시그니처는 이후 핵심 참조점이 되었으며(동일 연구실의 신생아 척수 복구 연구 등), 발생 단계 미세아교세포 상태를 복구·식균 기능과 연결한다. 한계로는 plate 기반 Smart-seq2의 처리량(droplet 대비 적은 세포 수), 제한된 뇌 영역만 분석하여 추가 이질성(예: 중뇌)을 놓칠 가능성, 식균 추론의 상관적 성격이 있다. PAM이 식균에 전사적으로 선소인된 아집단인지, 식균 행위 자체로 전환된 것인지 규명하는 기능 연구가 향후 필요하다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
