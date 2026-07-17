---
tags: [2026-07, Fibroblast]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# Uncovering a fibroblast differentiation-based keloid classification by integration of single-cell and bulk RNA sequencing

## Citation (NLM)

Zhang W, Lu J, Tong X, Xie S, Xian S, Liu Y, Yan J, Qian W, Sun H, Zhu Y, Jiang L, Guo X, Ding X, Li Y, Bai C, Huang R, Xia Z, Ji S. Uncovering a fibroblast differentiation-based keloid classification by integration of single-cell and bulk RNA sequencing. Commun Biol. 2025;8(1):1387. doi:10.1038/s42003-025-08741-1

**DOI:** [https://doi.org/10.1038/s42003-025-08741-1](https://doi.org/10.1038/s42003-025-08741-1)

---

## Background

켈로이드는 비정상적 상처 치유로 유발되는 진피 섬유증식성 질환으로, 인구의 약 4.5–16%에 영향을 미치며 인접 정상 피부를 침범하는 융기된 무정형 반흔으로 나타나 통증·소양감 및 기능적/미용적 손상을 유발한다. 수술 절제 단독 후 재발률은 70–100%이고, 기존 치료(스테로이드 주사, 냉동요법, 방사선요법, 레이저)는 불가피한 부작용을 동반한다. 유전·내분비·국소 조직 인자가 모두 관여하므로 켈로이드는 표현형이 이질적이며 균질한 종괴로 취급해서는 안 되지만, 진단적 분자 분류를 구축한 연구는 드물다. 비정상 증식과 과도한 콜라겐 침착을 주도하는 섬유아세포는 켈로이드 형성의 중심이며, 기존 scRNA-seq 연구(예: mesenchymal 섬유아세포가 확장된 4개 아집단 체계)가 그 이질성을 확립했다. 본 연구는 단일세포 및 bulk RNA-seq을 통합하여 켈로이드 섬유아세포 분화 궤적을 재구성하고, 섬유아세포 분화 기반 켈로이드 분자 분류를 도출하였다.

---

## Key Experiment Methods

**1. 켈로이드 및 정상 반흔 단일세포 지도**
- 켈로이드 3례, 정상 반흔 3례 scRNA-seq; QC 후 44,463개 세포(켈로이드 23,638; 정상 반흔 20,825)
- UMAP 클러스터링으로 18개 클러스터를 9개 주요 세포 유형으로 주석; 세포-세포 통신 분석(CellChat 방식)
- 섬유아세포 13,925개 추출, 6개 아형(fibroblast 1–6)으로 재클러스터링

**2. 궤적 분석 및 유전자 식별**
- Monocle 2 pseudotime 정렬(DDRTree)로 7개 분화 상태 규명; 섬유아세포 분화 관련 유전자(FDRG) 식별
- Monocle 유의 FDRG 14,467개를 RNA-seq + 임상 메타데이터(SAR 데이터베이스)의 단변량 Cox 회귀와 통합: 진단 유의 32개, 시간 유의 137개 DEG
- 교집합으로 25개 핵심 차등발현 FDRG(DEFDRG) 도출

**3. 합의 분류(FDBKC)**
- 25개 DEFDRG의 합의 클러스터링으로 환자를 3개 아형(k = 3)으로 계층화
- PCA 기반 섬유아세포 점수(FS)로 클러스터 명명: LFDC(낮음), MFDC(중간), HFDC(높은 섬유아세포 분화 분류)
- 면역 침윤 분석(23개 면역세포 유형); 단백질 시퀀싱 및 3개 공개 마이크로어레이 데이터셋(GSE188952, GSE7890, GSE44270)으로 검증

**4. Bulk 전사체 및 임상 모델**
- 켈로이드 37례, 건강 27례 bulk RNA-seq: 1,828개 DEG; 4개 차등발현 TF(HOXC9, LMO2, PDX1, RUNX1); GSVA hallmark 경로
- LASSO 로지스틱 회귀로 11개 DEFDRG 선택; train/test ROC(AUC train 0.995, test 0.868)
- 아형 특이적 조절 네트워크(DETF, 경로, 면역세포); Connectivity Map(CMap) 약물 예측

**5. 임상 검증**
- RNA-FISH(PECAM1/TPSB2 + COL1A1 + VIM)로 섬유아세포 발현 확인
- 켈로이드 환자 19명에서 MMP1, FOXC2, KLK6, TPSB2 IHC; Vancouver Scar Scale(VSS), 두께, 경도, 통증, 소양감, 혈관성과 상관 분석

---

## Results

**섬유아세포가 켈로이드 세포 구성과 통신을 지배**
9개 세포 유형에 걸친 44,463개 세포 중 내피세포와 섬유아세포가 모든 샘플에서 우세했다. 세포 통신 분석에서 섬유아세포는 가장 높은 통신 빈도와 outgoing 상호작용 강도를 가진 주요 상호작용자였고, 전체 통신 활성은 정상 반흔 대비 켈로이드에서 유의하게 증가했다.

**섬유아세포 아형 3이 POSTN/ASPN/COMP 시그니처와 함께 켈로이드에서 확장**
13,925개 섬유아세포는 6개 아형으로 분해되었다: fibroblast 1, 2는 정상 반흔에서, fibroblast 3은 켈로이드에서 우세했다. Fibroblast 3은 POSTN, ASPN, COMP(켈로이드 형성에 관여로 기존 보고)를 고발현하고, 타 아형과 가장 빈번히 상호작용(COL1A1/COL1A2가 핵심 연결자)했으며, 콜라겐 형성 및 ECM-수용체 상호작용 경로가 농축되어, 기존 켈로이드 scRNA-seq의 확장된 mesenchymal 섬유아세포를 재현했다.

**궤적 분석과 임상 통합으로 25개 DEFDRG 정의**
Monocle 2는 7개 분화 상태를 재구성했고 fibroblast 3은 중간-후기 pseudotime(States 3–6)에 위치했다. 14,467개 FDRG를 진단·시간 유의 DEG와 교차하여 임상적으로 관련된 25개 DEFDRG를 얻었으며, 대부분 양의 상관이었으나 KLK6와 TPSB2는 나머지와 음의 상관을 보였다.

**3개 분자 아형(LFDC/MFDC/HFDC)이 켈로이드 중증도를 계층화**
25개 DEFDRG의 합의 클러스터링으로 3개 아형이 생성되었다. PCA 섬유아세포 점수는 cluster 1(LFDC)에서 최저, cluster 2(MFDC)에서 중간, cluster 3(HFDC)에서 최고였다. FDBKC는 진단 및 시간과 유의하게 연관(P < 0.001)되어, 건강 샘플은 주로 cluster 1에, 켈로이드 샘플(0일 및 42일)은 주로 cluster 3에 속했다. 아형 마커는 LFDC(MMP1, F13A1), MFDC(FOXC2, MDK), HFDC(KLK6, TPSB2)였다. Bulk RNA-seq LASSO 모델(11개 DEFDRG)은 켈로이드 진단을 AUC 0.995(train)/0.868(test)로 예측했고, 고위험은 30세 미만, 여성, 긴 경과 시간, 켈로이드 진단과 연관되었다.

**조절 네트워크, 후보 약물 및 임상 상관**
RUNX1은 세 아형에 공통된 상류 전사인자였고 섬유화에 관여한다. 아형 특이적 허브로 CLEC11A/MDK(LFDC), PECAM1/LMO2(MFDC), KLK6/F13A1(HFDC; F13A1은 Wnt/β-catenin 신호와 연관)이 있었다. RNA-FISH로 켈로이드 섬유아세포가 PECAM1과 TPSB2를 발현함을 확인했다. CMap은 아형별 소분자 억제제를 제시했으며, HFDC에는 Ouabain(항섬유화·TGF-β 억제 활성이 보고된 Na⁺/K⁺-ATPase 억제제)이 부각되었다. 환자 19명(HFDC 12, MFDC 3, LFDC 4)의 IHC는 분류와 일치했다: MMP1은 LFDC, FOXC2는 MFDC, KLK6/TPSB2는 HFDC에서 최고였다. HFDC 켈로이드는 VSS 점수가 유의하게 높고, 더 두껍고(약 83%가 >2 mm), 더 단단하며, 통증·소양감·혈관 이상이 더 흔하여 HFDC가 가장 중증 아형임을 확인했다.

---

## Perspective

본 연구는 단일세포 궤적 분석, bulk 전사체, 임상 메타데이터, IHC 검증을 통합하여 질환 중증도를 추적하는 3단계 체계(LFDC/MFDC/HFDC)로, 최초의 섬유아세포 분화 기반 켈로이드 분자 분류(FDBKC)를 제시하였다.

첫째, 정적 바이오마커가 아닌 섬유아세포 분화 궤적에 분류를 정박함으로써, 분자 아형을 기계론적 축(섬유아세포 운명 결정)에 연결하고, 치료 잠재력을 지닌 내인성 발현·세포 기원 마커(MMP1, F13A1, FOXC2, MDK, KLK6, TPSB2)를 제공한다. 염증·섬유화 연관 KLK6와 비만세포 트립타제 TPSB2로 표지되는 HFDC 아형은 임상적으로 더 단단하고 두껍고 증상이 심한 켈로이드에 대응한다.

둘째, POSTN/ASPN/COMP mesenchymal 시그니처를 가진 fibroblast 아형 3의 반복적 식별은 독립적 켈로이드 및 교차조직 섬유아세포 지도와 수렴하여, 확장되고 분화가 진전된 mesenchymal 섬유아세포를 피부 섬유화의 핵심 병원성 집단으로 재확인한다. RUNX1은 피부 섬유화에서 조사할 가치가 있는 공유 상류 조절인자로 부상한다.

셋째, CMap이 제시한 억제제—특히 TGF-β/α-SMA 억제를 통한 HFDC용 Ouabain—는 본 저장소의 섬유화 및 항섬유화 주제와 부합하는 검증 가능한 정밀치료 가설을 제공하며, 분화 상태 틀은 연골 재생에 핵심인 탈분화/재분화 논리를 반영한다.

한계로는 작은 scRNA-seq 코호트(켈로이드 3례), 실험적 검증이 필요한 in silico 예측 의존, 기존 비만세포 연구와 불일치하는 면역 침윤 결과가 있으며, 저자들은 이를 제한된 샘플 크기와 개인차에 기인한다고 본다.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
