---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
raw_data:
  - "GEO: GSE153737"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Diversified transcriptional responses of myeloid and glial cells in spinal cord injury shaped by HDAC3 activity

## Citation (NLM)
Wahane S, Zhou X, Zhou X, Guo L, Friedl MS, Kluge M, Ramakrishnan A, Shen L, Friedel CC, Zhang B, Friedel RH, Zou H. Diversified transcriptional responses of myeloid and glial cells in spinal cord injury shaped by HDAC3 activity. Sci Adv. 2021;7(9):eabd8811. doi:10.1126/sciadv.abd8811

**DOI:** [https://doi.org/10.1126/sciadv.abd8811](https://doi.org/10.1126/sciadv.abd8811)

---

## Background
선천 면역 반응은 척수손상(SCI) 후 신경 회복에 큰 영향을 미친다. CNS의 상주 골수계 세포인 미세아교세포(microglia)는 손상 후 수 분 내에 활성화되며, 혈액 유래 단핵구에서 기원한 대식세포와 함께 손상 활성화 미세아교세포/대식세포(IAM)를 형성한다. IAM의 지속적인 염증 표현형은 이차 신경 손상을 악화시키는 것으로 여겨진다. 핵심 질문 중 하나는 IAM이 알츠하이머병·ALS에서 관찰되는 신경퇴행 연관/질환 연관 미세아교세포(DAM)와 특징적 유전자 및 조절 기전을 공유하는가이다.

연구진은 앞서 SCI 후 IAM에서 히스톤 탈아세틸화효소 3(HDAC3)이 강하게 상향 조절되며, HDAC3 약물 억제가 전반적 염증 억제와 기능 회복 향상을 가져옴을 보고한 바 있다. 본 연구는 bulk 및 단일세포 수준에서 SCI 후 골수계·아교세포의 다양화된 전사 반응과 HDAC3가 이를 형성하는 정도를 규명한다.

---

## Key Experiment Methods
1. Cx3cr1CreER INTACT 마우스를 제작해 골수계 세포 핵을 특이적으로 GFP 표지; T8 등쪽기둥 절단 전 타목시펜 투여.
2. INTACT 기법으로 GFP 표지 골수계 핵을 면역정제 후 손상 3·7·14일(dpi)과 laminectomy 대조군에서 bulk RNA-seq(3중 반복).
3. 생물정보 분석: UMAP, k-means 군집, NMF, 계층적 유전자 군집, WGCNA, 차등 엑손 사용(대체 스플라이싱), IPA 상류 조절자 및 interactome 분석.
4. 손상 후 5dpi 척수에 대한 단일세포 RNA-seq(10X Genomics): CTRL, SCI, SCI+HDAC3 억제제(RGFP966) 3조건 비교(총 9937개 세포).
5. HDAC3 억제(RGFP966, 급성 vs 아급성 요법) 기능 연구, BMS(Basso Mouse Scale) 운동 점수 평가.
6. Slingshot 단일세포 궤적 분석; 면역조직화학(LPL, CD11c, SPP1, fibronectin, P2ry12, HDAC3)으로 검증.

---

## Results
- INTACT RNA-seq에서 시간적으로 구별되는 IAM 전사 프로그램 확인: 3dpi에는 증식/이동/ECM 및 인터페론 신호, 7dpi에는 이온채널/이동, 14dpi에는 ECM 재구성이 우세.
- 모든 시점에서 공유되는 131개 core IAM 유전자는 phagosome 및 지질 대사(Apoe, Lpl, Axl, Ctsb, Ctsd, Abca1/Abcg1)와 LXR/RXR·포식소체 성숙·콜레스테롤 경로에 농축; 두 번째 군집은 면역(IRF, TLR, TNF 신호) 관련.
- 다수의 염증 유전자 상향에도 불구하고 IAM은 전반적으로 회복(reparative)·항염증(M2 경향) 프로파일을 보임; DAM 표지 Trem2와 Tyrobp는 IAM에서 유의하게 상향되지 않아 IAM과 DAM을 구분.
- IAM은 광범위한 대체 스플라이싱(3dpi에 차등 엑손 최다)과 발생기 미세아교세포 유전자 프로그램의 부분적 재활성화를 보임.
- HDAC3는 IAM 프로그램의 상류 조절자들과 밀접히 상호작용; 급성 HDAC3 억제가 아급성보다 더 나은 BMS 운동 회복을 제공.
- scRNA-seq에서 9개 세포 군집 확인; SCI 후 면역·혈관 집단이 확장. 미세아교세포와 대식세포는 전사적으로 구별(916 DEGs)되며 HDAC3 억제는 두 집단에 다르게 작용(미세아교세포에서 55개 HDAC3 의존 손상반응 유전자, 증식/케모카인 활성 관련).
- 골수계 세포는 8개 하위군집(MG1-MG4, Mac1-Mac4)으로 분리. MG4는 증식성이며 Hdac3를 우선 발현; 궤적 분석은 MG3→MG1→MG2→MG4 진행을 보였고 HDAC3i는 이를 이동(시작점 MG3→MG4). 건강한 척수에서도 미세아교세포는 다양한 상태를 보임.
- 구별되는 상의세포(ependymal, Sox2·Foxj1·Riiad1) 집단이 SCI 후 확장하며 반응성 시그니처(ECM, Wnt, Hedgehog, PDGF-B)를 보였고, HDAC3 조절 상의세포 유전자의 78%가 HDAC3에 의해 억제됨.

---

## Perspective
본 연구는 SCI 후 다양화된 골수계·아교세포 전사 지형을 고해상도로 제시하고, HDAC3를 미세아교세포·대식세포·상의세포를 아우르는 광범위한 후성유전 조절자로 자리매김한다. IAM과 DAM의 구분(특히 Trem2/Tyrobp 미유도)은 손상 대 퇴행이 미세아교세포를 어떻게 재프로그래밍하는지 정교화한다. 소스 집단 역할의 즉시반응형 미세아교세포와 HDAC3 조절 증식성 아형의 발견은 골수 반응을 회복 방향으로 유도할 표적 노드를 시사한다. 한계로는 scRNA-seq 세포 빈도 추정의 근사성(포획 편향), 단일 손상 모델/시점, HDAC3와 특정 하위군집 간 상관적 연관 등이 있다. 세포형 특이적 HDAC3 조절을 활용한 향후 연구는 SCI 후 기능 회복을 향상시킬 수 있다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE153737

**본문에 인용된 기타 accession (외부·재사용 데이터):**
- GEO: GSE113566


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
