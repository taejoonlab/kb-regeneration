---
tags: [2026-07, Fibroblast]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# Single-cell RNA-seq reveals fibroblast heterogeneity and increased mesenchymal fibroblasts in human fibrotic skin diseases

## Citation (NLM)

Deng CC, Hu YF, Zhu DH, Cheng Q, Gu JJ, Feng QL, Zhang LX, Xu YP, Wang D, Rong Z, Yang B. Single-cell RNA-seq reveals fibroblast heterogeneity and increased mesenchymal fibroblasts in human fibrotic skin diseases. Nat Commun. 2021;12(1):3709. doi:10.1038/s41467-021-24110-y

**DOI:** [https://doi.org/10.1038/s41467-021-24110-y](https://doi.org/10.1038/s41467-021-24110-y)

---

## Background

경피증(scleroderma), 비후성 반흔, 켈로이드, 이식편대숙주병 등 섬유화 피부질환은 전 세계 수백만 명에게 영향을 미치며, 섬유아세포(fibroblast)의 과증식과 진피 내 세포외기질(ECM)의 과도한 축적을 특징으로 한다. 섬유아세포는 피부 섬유화를 주도하는 핵심 세포로, TGFβ, FGF, PDGF, VEGF, POSTN 등의 섬유화 성장인자의 영향 아래 증식·이동·침윤 및 ECM 침착이 증가한다. 오랫동안 섬유아세포는 균일한 방추형 세포집단으로 여겨졌으나, 형태적·기능적으로 이질적(heterogeneous)임이 밝혀지고 있다. Single-cell RNA-seq(scRNA-seq)은 정상 진피 및 일부 섬유화 질환(폐 섬유화, 전신경화증, 뒤퓌트렌 구축)에서 섬유아세포 아군을 규명했으나, 섬유화 피부질환에서의 이질성은 규명되지 않았다. 본 연구는 섬유화 피부질환의 대표 질환인 켈로이드를 scRNA-seq으로 분석하여 섬유아세포 이질성을 규명하였다.

---

## Key Experiment Methods

**1. 켈로이드 및 정상 반흔 진피의 scRNA-seq**
- 켈로이드 조직(환자 3명)과 정상 반흔 조직(환자 3명) 수집; 표피와 지방조직을 제거한 진피만 사용
- dispase II 및 collagenase IV로 효소 분해; 10× Genomics Chromium(3′ v2)으로 회당 약 8,000개 세포 프로파일링
- Illumina HiSeq X / NovaSeq(PE150) 시퀀싱; Cell Ranger로 처리하고 GRCh38에 정렬
- 총 40,655개 세포의 전사체 확보(켈로이드 21,488; 정상 반흔 19,167)

**2. 세포 클러스터링 및 계통 주석**
- 비지도 UMAP 클러스터링으로 21개 클러스터 확보, 마커 유전자를 이용해 9개 계통으로 분류
- 섬유아세포 계통은 COL1A1, 내피세포 계통은 ENG로 확인
- 켈로이드와 정상 반흔 간 세포계통 비율 및 차등발현 유전자 수 비교

**3. 섬유아세포 서브클러스터링 및 아집단 분류**
- 전체 섬유아세포를 13개 서브클러스터(sC1–sC13)로 재클러스터링
- 기존 마커를 이용해 4개 아집단 배정: secretory-papillary(sC6, sC7), secretory-reticular(sC5), mesenchymal(sC1, sC4), pro-inflammatory(sC2, sC3, sC9)
- ARACNe/MARINa 마스터 조절인자 분석; GO 및 GSEA 농축 분석

**4. 검증 및 세포-세포 상호작용 분석**
- ADAM12 및 NREP 면역형광 염색으로 조직 내 mesenchymal fibroblast 확인
- ACTA2 분석으로 mesenchymal 아집단과 근섬유아세포(myofibroblast)의 중첩 평가
- CellPhoneDB 2.0으로 섬유아세포 아집단과 타 세포 간 리간드-수용체 상호작용 분석

**5. Mesenchymal fibroblast 기능 연구**
- CD90+CD266+/CD9−(mesenchymal) vs. 기타 켈로이드 섬유아세포를 유세포 분류; qRT-PCR, western blot, RNA-seq으로 검증
- Mesenchymal fibroblast 상층액 ± POSTN 중화항체 OC-20으로 타 섬유아세포 처리 후 collagen I/III 측정
- sC1 vs. sC4의 diffusion-pseudotime 및 RNA velocity 분석
- 공개된 경피증 scRNA-seq 데이터 재분석으로 질환 간 검증

---

## Results

**섬유아세포가 켈로이드에서 가장 큰 전사체 변화를 겪음**
40,655개 세포에서 9개 계통이 규명되었다. 켈로이드에서는 내피세포와 평활근세포 비율이 증가(켈로이드 혈관신생과 일치)하고 섬유아세포 비율은 상대적으로 감소하였다. 모든 계통 중 섬유아세포가 켈로이드와 정상 반흔 사이에서 가장 많은 차등발현 유전자를 보여, 섬유화 진행 중 섬유아세포가 가장 큰 변화를 겪음을 시사하였다.

**켈로이드 섬유아세포는 4개 아집단으로 나뉘며 mesenchymal 세포가 확장됨**
섬유아세포는 13개 서브클러스터로, 이는 다시 4개 표준 아집단으로 묶였다. Mesenchymal 아집단(sC1, sC4)은 COL11A1과 POSTN을 특이적으로 발현하였고, pro-inflammatory 아집단은 콜라겐이 전반적으로 감소, papillary 아집단은 COL13A1/COL18A1/COL23A1을 발현하였다. 정상 반흔과 비교해 켈로이드에서는 mesenchymal 아집단이 증가하고 secretory-papillary, secretory-reticular, pro-inflammatory 아집단은 감소하였다. 켈로이드 mesenchymal 섬유아세포는 골격 발생·골화·조골세포 분화 유전자(COL11A1, COMP, POSTN)도 상향조절되어, 비율 확장과 정체성 변화가 모두 일어남을 보였다.

**Mesenchymal fibroblast는 골격/골형성 시그니처를 지니며 근섬유아세포와 중첩됨**
Mesenchymal 섬유아세포의 차등발현 유전자에는 분비 단백질(POSTN, COMP, COL11A1, COL12A1, COL5A2)과 막 단백질(SDC1, ADAM12, CD266/TNFRSF12A 증가; CD9 감소)이 포함되었다. GO/GSEA는 이들을 콜라겐 조직화, 상처 치유, 골격 발생, 조골세포 분화와 연결하였다. 골형성·연골형성·건/인대 분화의 마스터 전사인자 SCX, CREB3L1, RUNX2가 이 아집단에 농축되었다. 면역형광에서 켈로이드의 ADAM12+/NREP+ 세포 증가가 확인되었다. 근섬유아세포(ACTA2+)는 켈로이드에서 증가(26.0% vs 13.3%)하고 mesenchymal 아집단에 집중되었으나, mesenchymal 섬유아세포의 일부만 α-SMA 양성이었다.

**Mesenchymal fibroblast가 켈로이드 세포 통신을 주도하고 POSTN을 통해 콜라겐을 유도**
CellPhoneDB 분석 결과, 정상 반흔에서는 secretory-reticular 섬유아세포가 가장 활발히 상호작용한 반면 켈로이드에서는 mesenchymal 섬유아세포가 지배적 통신자로 전환되었다. TGFβ1–TGFβR1/R2 신호가 가장 뚜렷이 증가했고, NOTCH(JAG1-NOTCH1)는 증가, 항섬유화 FGF2 상호작용은 감소했으며, POSTN 신호는 mesenchymal 섬유아세포에서 특이적으로 변화하였다. 유세포 분류된 CD266+/CD9− 섬유아세포는 mesenchymal 정체성(POSTN, ASPN, COMP, COL11A1 고발현; ECM/골격/연골세포 발생 농축)을 확인시켰다. 이들 세포의 상층액은 타 섬유아세포에서 collagen I과 III을 증가시켰고, 이 효과는 POSTN 중화항체 OC-20으로 차단되어, mesenchymal 섬유아세포가 부분적으로 POSTN을 통해 콜라겐 과발현을 촉진함을 입증하였다.

**sC4는 덜 분화된 mesenchymal 전구체이며 기전은 경피증에도 일반화됨**
Pseudotime 및 RNA velocity 분석에서 sC4 섬유아세포(켈로이드에서 유의하게 증가, POSTN·ADAM12·COL11A1 고발현)는 sC1보다 초기 분화 단계에 있으며 sC1로 분화할 수 있음이 시사되었다. 경피증 scRNA-seq 재분석에서 POSTN, ADAM12, COMP, NREP를 발현하는 cluster 7이 증가했고, 이는 켈로이드 mesenchymal 섬유아세포와 가장 유사했으며, 면역형광으로 경피증의 ADAM12+/NREP+ 세포 증가가 확인되어, mesenchymal 섬유아세포 확장이 피부 섬유화의 광범위한 기전임을 보였다.

---

## Perspective

본 연구는 인간 섬유화 피부질환의 섬유아세포 이질성에 대한 최초의 단일세포 지도를 제시하고, 확장된 mesenchymal 섬유아세포 아집단을 콜라겐 과발현의 핵심 동인으로 규명하였다.

첫째, 섬유화 피부질환의 섬유아세포는 정상 진피의 4개 아집단을 재현하되 mesenchymal 아군의 질환 특이적 확장을 보이며, 이 양상이 켈로이드와 경피증에 공유되므로 피부 섬유화 전반의 일반 기전일 가능성이 높음을 확립하였다.

둘째, 이들 mesenchymal 섬유아세포의 강한 골격 발생·골화·조골/연골세포 분화 시그니처(POSTN, COMP, COL11A1; SCX, RUNX2)는 피부 섬유화와 골형성/연골형성 프로그램을 직접 연결한다. 이는 동일한 mesenchymal 전구체 전사인자가 계통 결정을 지배하는 본 저장소의 연골 재생 및 이소성 골화 주제에 특히 흥미로운 연결점이다.

셋째, mesenchymal 섬유아세포가 POSTN을 통해 인접 섬유아세포의 콜라겐 생성을 유도한다는 기능적 증명과 TGFβ1 및 POSTN-ITGAV/ITGB5 신호 증가는 POSTN과 mesenchymal 아집단을 치료 표적으로 지목한다. 저자들은 기존 켈로이드 치료 전후에 mesenchymal 섬유아세포를 억제·제거(예: POSTN 소분자 억제제)하면 높은 재발률을 줄일 수 있다고 제안한다.

한계로는 적은 환자 수, 성숙 켈로이드만 사용한 점, sC4 전구체의 기원이 미해결인 점이 있으며, 저자들은 형질전환 계통추적 모델로 이를 규명할 계획이다.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
