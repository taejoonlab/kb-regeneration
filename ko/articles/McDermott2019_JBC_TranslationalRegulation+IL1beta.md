---
tags: [2026-06, Chondrocyte]
extract: 2026-06-08
log:
  - "2026-06-08 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · removed duplicate footer"
---

# Translational regulation contributes to the secretory response of chondrocytic cells following exposure to interleukin-1β

## Citation (NLM)
McDermott BT, Peffers MJ, McDonagh B, Tew SR. Translational regulation contributes to the secretory response of chondrocytic cells following exposure to interleukin-1β. J Biol Chem. 2019;294(35):13027-13039. doi:10.1074/jbc.RA118.006865

**DOI:** [https://doi.org/10.1074/jbc.RA118.006865](https://doi.org/10.1074/jbc.RA118.006865)

---

## Background

골관절염(OA)은 관절 연골의 세포외 기질(ECM) 파괴를 특징으로 하는 만성 질환으로, 염증성 사이토카인이 중요한 역할을 한다. IL-1β와 TNFα는 MMP 계열 단백질분해효소의 발현을 유도하여 연골 파괴를 촉진한다. 전사체 연구는 OA 병리 이해에 크게 기여했지만, mRNA 안정성(post-transcriptional regulation)과 번역 조절(translational regulation)이 세포 표현형에 미치는 영향은 상대적으로 덜 연구되었다. 특히, 연골세포에서 IL-1β 자극 시 단백질 번역이 전사체 수준에서 어떻게 변화하는지는 리보솜 프로파일링(ribosome profiling)을 통해 연구된 바 없다. 본 연구에서는 SW1353 연골육종 세포주를 모델로 IL-1β 자극이 번역 조절에 미치는 영향을 리보솜 프로파일링과 프로테오믹스를 결합하여 분석하였다.

---

## Key Experiment Methods

1. **세포 배양 및 IL-1β 처리**: SW1353 연골육종 세포주를 10 ng/mL IL-1β로 3시간(리보솜 프로파일링용) 또는 24시간(프로테오믹스용) 처리. 일차 인간 관절 연골세포(HAC)도 비교 실험에 사용.
2. **리보솜 프로파일링(Ribo-Seq)**: ARTseq Ribosome Profiling kit 사용. cycloheximide 처리로 번역 중지 후, nuclease로 리보솜-보호 mRNA 단편(RPF) 추출. rRNA 제거 후 RNA-seq 라이브러리 제작, Illumina HiSeq2500 시퀀싱.
3. **RiboGalaxy 파이프라인**: Cutadapt, Bowtie, riboSeqR을 통해 서열 정렬 및 triplet periodicity 분석. baySeq으로 차등 번역 분석.
4. **프로테오믹스 분석**: 세포층(cellular proteome) 및 조건 배지(secretome)에 대해 in-solution trypsin 소화 후 LC-MS/MS. Label-free 정량은 PEAKS 7 소프트웨어로 분석.
5. **ELISA**: CCL2 및 IL-6의 분비량 측정 (시간 및 농도 의존적). 일차 연골세포와 비교.
6. **Western blot**: SOD2 단백질 발현 확인, 항-SOD2 항체 사용.
7. **ROS 검출**: CM-H₂DCFDA 형광 염료로 IL-1β 처리 후 세포 내 활성산소(ROS) 수준 측정.

---

## Results

- 리보솜 프로파일링 데이터의 triplet periodicity 분석에서 대부분의 read가 28-mer로 frame 1에 정렬되어 번역 중인 mRNA의 정확한 포획 확인.
- 차등 번역 분석(q < 0.001) 결과, 상위 200개 전사체 중 대부분(n=108)이 IL-1β 처리 후 번역 증가. 번역 감소 전사체는 ZC3H12A, PIM1, TNFAIP2의 일부 변이체 등 4개에 불과.
- STRING 분석: 차등 번역 전사체의 18.5%가 염증 관련 유전자(NFKB1, TNFAIP2, MMP13, CCL2, CCL7), 31.5%가 리보솜 관련 유전자.
- 분비 단백질체(secretome) 분석에서도 유사한 염증 단백질 군집 확인.
- 흥미로운 패턴 발견: CCL2, CCL7, NFKBIZ의 경우 총 mRNA 수준은 감소했으나 RPF 수준은 증가 → 전사 억제와 번역 증가가 동시에 발생하는 '전사-번역 해리' 현상.
- 일부 유전자(TNFAIP2, SOX9)의 3'-UTR에서 리보솜 점유 증가 관찰 → 번역 조절의 새로운 기전 가능성 제시.
- SOD2가 번역 수준에서 가장 크게 증가한 유전자 중 하나 (RPF 55→1509, 총 RNA 변화 없음). Western blot 및 ROS assay로 검증: IL-1β는 신속하게 ROS를 유도하고, 이후 SOD2 발현 증가가 ROS를 감소시키는 redox 조절 기전 확인.
- SW1353과 일차 연골세포 모두 농도 및 시간 의존적으로 CCL2와 IL-6 분비 증가, 일차 세포가 더 낮은 IL-1β 농도(0.1 ng/mL)에 반응.

---

## Perspective

- 본 연구는 연골세포 유형에서 처음으로 리보솜 프로파일링을 적용하여 IL-1β 사이토카인 자극에 대한 번역 수준의 신속한 반응을 규명.
- 염증 반응의 상당 부분이 전사 조절이 아닌 번역 조절을 통해 매개됨을 입증. 특히 CCL2/CCL7 케모카인의 번역 증가는 신속한 세포 간 신호전달을 가능케 하는 생리적 기전일 가능성.
- IL-1β는 NF-κB 활성화 → ROS 증가 → SOD2 번역 증가의 redox 조절 경로를 유도하며, 이는 연골세포의 산화 스트레스 방어 기전임.
- SW1353 세포주는 일차 연골세포와 유사한 IL-1β 반응성을 보이나, 기질 성분 발현이 낮고 저농도 사이토카인에 대한 민감도가 낮은 한계 존재.
- 향후 연구 과제: 3'-UTR 리보솜 점유의 기능적 의미, mTOR/4E-BP1 경로를 통한 번역 조절 기전, in vivo 조직에서의 번역 조절 확인.
- 사이토카인 신호에 대한 연골세포의 급속 번역 반응이 건강한 조직 항상성 유지에 어떤 역할을 하는지가 핵심 미해결 질문.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*
