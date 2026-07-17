---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
---

# Single-cell analysis of the cellular heterogeneity and interactions in the injured mouse spinal cord

## Citation (NLM)
Milich LM, Choi JS, Ryan C, Cerqueira SR, Benavides S, Yahn SL, Tsoulfas P, Lee JK. Single-cell analysis of the cellular heterogeneity and interactions in the injured mouse spinal cord. J Exp Med. 2021;218(8):e20210040. doi:10.1084/jem.20210040

**DOI:** [https://doi.org/10.1084/jem.20210040](https://doi.org/10.1084/jem.20210040)

---

## Background

척수 손상(SCI) 후 상처 치유 과정은 조직 항상성을 유지하고 손상을 제한하지만, 결국 재생과 복구에 부적합한 흉터 유사 환경을 형성한다. 이 과정은 손상 후 첫 7일 동안 매우 역동적이며 선천 면역 반응, 아교세포 증식/신경교증(gliosis), 단핵구-대식세포 분화, 섬유증, 혈관신생을 포함하여 치료적 개입 창을 제공한다. 적절한 병태생리를 표적화하는 데 있어 주요 장애물은 손상 부위의 큰 세포 이질성과 복잡한 세포 간 상호작용이었다.

기존 전사체 접근법(FACS, 세포유형 특이적 리보솜/핵 프로파일링)은 단일 세포 유형에 초점을 맞추었고 하위집단 이질성과 세포 상태 정보가 부족했다. 본 연구는 단일세포 RNA 시퀀싱(scRNA-seq)을 적용하여 손상되지 않은 및 손상된 마우스 척수를 구성하는 거의 모든 세포 유형을 프로파일링하고, 혈관신생·신경교증·섬유증 동안의 세포 상호작용을 분석할 수 있는 리소스를 제공한다.

---

## Key Experiment Methods

1. Infinite Horizon Impactor(65 kdyne)를 사용한 암컷 C57BL/6J 마우스의 중흉부(T8) 좌상 SCI.
2. 손상 전, 1, 3, 7 dpi에서 해리된 척수 조직의 scRNA-seq(총 66,178개 세포; anti-ACSA-2 비드를 이용한 성상세포 농축).
3. 클러스터링(UMAP), 차등 발현, SingleR 주석, GO 농축 분석으로 주요 세포 유형 및 하위유형 식별.
4. 알려진 리간드-수용체 쌍을 이용한 리간드-수용체 "상호작용 점수" 분석(CellPhoneDB 응용)으로 세포 신호전달 예측.
5. 미세아교세포(P2RY12/MSR1) 및 대식세포(CD63/CD11b/APOE) 하위유형의 유세포 분석 검증.
6. 공간적/시간적 검증을 위한 면역조직화학 및 RNAscope in situ hybridization(Apln, Crym, Osm, Itgam).
7. Postn-CreER; Rosa26-EYFP 마우스를 이용한 활성화 섬유아세포의 유전적 계통 추적.

---

## Results

- SCI 부위의 모든 주요 세포 유형(미세아교세포, 단핵구, 대식세포, 호중구, 수지상세포, 성상세포, 희소돌기아교세포, OPC, 섬유아세포, 주피세포, 상의세포, 내피세포)을 포괄하는 15개 클러스터를 식별; 많은 최상위 DEG는 비정형적(예: OPC의 Tnr)이고 시간적으로 특이적(예: 섬유아세포의 Postn)이었음.
- 골수계 분석: 4개 미세아교세포 하위유형(항상성, 염증성, 분열, 이동)과 대식세포 하위유형(주화성 유도 대 염증성)을 식별했으며, 이들은 M1/M2 명명법에 대응하지 않음; 말초 골수계 구성은 시간이 지남에 따라 친염증성 상태로 이동.
- 혈관 분석: 동맥·정맥·모세혈관·팁세포(tip cell) 내피 하위유형 식별; 팁세포(Apln+)는 손상되지 않은 척수에는 없었고 1 dpi에 정점에 이른 후 7 dpi에 대부분 사라짐.
- 혈관신생 신호전달: 팁세포는 Angpt2(혈관 불안정화)와 Plgf(혈관 형성)의 주요 공급원; Angpt1은 VSMC(1 dpi)에서 성상세포(3-7 dpi)로 이동하여 성상세포가 후기 혈관 안정화/성숙에 관여함을 시사.
- 대형아교세포 분석: 손상 유도 astroependymal 세포(Crym+, 1-3 dpi 존재)와 2개 OPC 하위유형 식별; OPC-B는 손상 후 나타나 성상세포/astroependymal 세포와 함께 클러스터링됨. 축삭 성장 억제 프로테오글리칸(Acan, Bcan, Ncan, Vcan)은 성상세포보다 OPC에서 우선적으로 발현됨.
- 신경교증/섬유증: 골수계 유래 oncostatin M(OSM) 신호가 성상세포와 섬유아세포의 OSMR/gp130으로 전달되는 것이 공통 활성화 기전으로 식별됨(7 dpi에서 조직학적으로 검증); 대식세포-섬유아세포 상호작용이 대식세포-성상세포보다 많았으며, Spp1과 Apoe 신호가 가장 높은 점수의 공유 경로였음.

---

## Perspective

본 연구는 급성 SCI 부위의 거의 모든 세포를 포착한 최초의 포괄적 scRNA-seq 아틀라스로, 상처 치유 과정을 편향을 줄여 평가할 수 있게 한다. 특정 골수계 하위유형에 의한 혈관신생·신경교증·섬유증의 뚜렷한 시간적 조절을 밝히고, 검증 가능한 가설(예: 골수계 주도 성상세포/섬유아세포 활성화 축으로서 OSM-gp130; 재혈관화에 대한 팁세포의 자가/주변분비 조절; 혈관 성숙에서 성상세포의 역할)을 생성한다. 이 데이터셋은 다른 외상성 CNS 질환에도 적용 가능한 귀중한 공동체 리소스이다.

한계: 신경세포와 림프구는 제외됨; 해리 편향으로 인해 세포 회수 수는 실제 생체 내 비율을 반영하지 않음(다만 집단 내 하위유형 비율은 정확해 보임); 일부 하위집단(염증성/분열 미세아교세포)은 부분적으로 해리 유도 스트레스를 반영하며, bulk RNA-seq 및 Allen Brain Atlas 데이터와의 비교로 완화됨. 리간드-수용체 상호작용 점수는 향후 실험적 검증이 필요한 예측 모델이다. 주요 치료적 과제는 유익한 상처 치유 기능(예: Vegfa, Spp1, Apoe)을 방해하지 않으면서 친염증성 대식세포 상태를 제한하는 것이다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
