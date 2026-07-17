---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# 성체 아홀로틀 사지 재생 과정에서 단일세포 RNA-seq으로 밝힌 새로운 미토콘드리아 관련 근골격 세포 집단

## Citation (NLM)

Qin T, Fan CM, Wang TZ, Sun H, Zhao YY, Yan RJ, Yang L, Shen WL, Lin JX, Bunpetch V, Cucchiarini M, Clement ND, Mason CE, Nakamura N, Bhonde R, Yin Z, Chen X. Single-cell RNA-seq reveals novel mitochondria-related musculoskeletal cell populations during adult axolotl limb regeneration process. Cell Death Differ. 2020. doi:10.1038/s41418-020-00640-8

**DOI:** [https://doi.org/10.1038/s41418-020-00640-8](https://doi.org/10.1038/s41418-020-00640-8)

---

## Background

아홀로틀(axolotl)은 절단 후 사지 전체와 주요 장기를 재생할 수 있는 대표적인 표피형 재생(epimorphic regeneration) 모델이다. 절단 후 형성되는 블라스테마(blastema)는 잃어버린 구조를 스스로 패터닝하여 복원하는 전구세포 풀이며, 계통 추적 연구를 통해 블라스테마 세포가 진피 섬유아세포, 슈반세포, 근원세포 등 중배엽 조직에서 유래함이 밝혀졌다. 기존 전사체·단백체 연구는 *cirbp*, *kazald1* 등 핵심 유전자와 초기 종양유전자 발현 폭증을 보고했으나, 블라스테마를 구성하는 세포 집단, 세포외기질(ECM)의 역할, 재생을 이끄는 세포-세포 상호작용은 충분히 규명되지 않았다.

본 연구는 성체 아홀로틀 사지 재생의 시간 경과에 걸쳐 대규모 단일세포 RNA 시퀀싱(scRNA-seq)을 적용하여 편향 없는 세포 지도를 구축하고, 세포 이질성 해상, 분화 궤적 재구성, 재생 특이적 세포 집단 발굴을 목표로 한다.

---

## Overview

저자들은 절단 후 0, 3, 7, 21일(dpa)의 아홀로틀 원위 사지 조직을 단일세포로 분리하여 scRNA-seq(Fluidigm C1)를 수행하고, 품질관리 후 938개 세포를 분석하였다. Seurat 클러스터링으로 7개 세포 클러스터를 정의하고, 리간드-수용체 연결성 지도와 Monocle 유사시간 궤적으로 재생 과정의 세포 동역학을 재구성하였다. 면역염색, RNA FISH, 투과전자현미경(TEM)으로 주요 발견을 검증하였다.

핵심 성과는 재생 단계에 특이적으로 풍부해지는 새로운 미토콘드리아 관련 클러스터를 발견하고, 이 집단이 에너지 공급을 통해 재생을 지지함을 제시한 것이다. 또한 COL1+/COL2+ 근골격 세포의 탈분화·재분화 동역학을 단일세포 수준에서 기술하고, 연골세포 유래 ECM이 정단 상피모(AEC)와의 상호작용을 통해 블라스테마 형성에 기여함을 규명하였다.

---

## Key Topics

- **재생 시간 경과 단일세포 지도 구축**: 0/3/7/21 dpa에 걸친 938개 세포의 scRNA-seq, DE 유전자 및 GSEA 분석.
- **7개 세포 클러스터 정의**: general, 미토콘드리아(*CYTB*, *ATP6*), 결합조직/CT(*FBN2*, *MDK*), 연골세포(*COL2A1*, *MATN1*), 염증(*CCL5*, *PTPRC*), 증식(*SLC2A8*, *PIF1*), 정단 상피모/AEC(*KRT12*, *KRT8*).
- **미토콘드리아 클러스터의 재생 특이성**: 재생 단계에서 강하게 증가, TCA 회로·세포분열·세포사멸 조절 경로 상향, TOMM20·TEM으로 검증.
- **클러스터 간 미세환경 상호작용**: 928개 리간드-수용체 쌍, 연골세포(C3)→AEC(C6)의 강한 ECM·성장인자 신호.
- **유사시간 분화 궤적**: 증식 클러스터는 원시 상태, 연골세포는 궤적 말단; FGF·BMP 상향.
- **근골격 세포의 탈분화·재분화**: COL2A1+ 비율의 급감(3·7 dpa) 후 재증가(21 dpa).
- **COL2-미토콘드리아 하위집단(COL2-mito)**: ATP 합성효소·미토콘드리아 리보솜 유전자, ATP 대사·상처 반응 기능, 블라스테마 상단/AEC 하부 국소화.

---

## Key Findings

- 재생 단계(3, 7, 21 dpa)에서 특이적으로 풍부해지는 미토콘드리아 클러스터는 미토콘드리아 유전자를 제외했을 때 신경/줄기세포 재생·발생 및 프로그램된 세포사 조절 관련 기능을 보였고, GSEA에서 TCA 회로와 세포분열(ROBO, RHO GTPase, JNK/Nrage) 경로가 상향되었다. 이는 재생이 에너지를 공급하는 특정 세포 집단에 의존함을 시사한다.
- 연골세포 클러스터(C3)는 AEC(C6)로 가장 강한 신호를 보냈으며, ECM(COL1A1, COL3A1, MATN1)과 성장인자(ITGB1, EGFR, BMPR2, VEGF) 상호작용이 풍부하여 연골 유래 ECM이 AEC 이동·형태형성과 블라스테마 형성을 촉진함을 제시하였다. 염증 클러스터는 3 dpa에 연결성이 가장 강해 초기 염증의 역할을 지지하였다.
- COL1A1/2+ 및 COL2A1+ 근골격 세포는 절단 후 발현이 급감했다가(COL2A1+ 72%→9%→2%) 21 dpa에 재증가(43%)하는 탈분화·재분화 동역학을 보였고, 이는 in vitro 연골세포 탈분화 특징(COL1 상향, COL2 하향)과 일치하였다.
- COL2+ 세포를 6개 하위집단으로 세분화한 결과, 미토콘드리아 클러스터에 완전히 포함되는 COL2-mito 하위집단(ATP5F1A/B, 미토콘드리아 리보솜 유전자)과 HOXA13·HAND2를 발현하는 CT 전구세포, FBN1+ 성숙 CT가 분지 궤적을 따라 구분되었다. RNA FISH + TOMM20 공동염색으로 COL2-mito 세포가 블라스테마 상단과 AEC 하부에 위치함을 확인하였다.

---

## Perspective

본 연구는 성체 아홀로틀 사지 재생의 근골격 세포 지형을 단일세포 수준에서 해상한 최초의 지도를 제공하고, 단순한 분화 상태가 아니라 에너지를 공급하는 지지세포로서의 재생 특이적 미토콘드리아 관련 집단(COL2-mito 포함)을 제안하였다. 또한 COL1+/COL2+ 근골격 세포의 탈분화·재분화를 단일세포 수준에서 입증하고, 연골 유래 ECM이 AEC와 연골세포를 잇는 매개체로 작용함을 부각하였다.

한계로는 Fluidigm C1 플랫폼 특성상 세포 수가 938개로 적고, 탈분화를 유전적 계통 추적이 아닌 클러스터·마커 기반 추론으로 제시했으며, 아홀로틀 참조 자원이 불완전하다는 점이 있다. 향후 미토콘드리아 및 COL2-mito 집단의 기능·계통 추적 검증, 더 깊은 시퀀싱, 그리고 이러한 에너지 공급 집단이나 ECM-상피 상호작용을 포유류 조직 재생 촉진에 응용할 수 있는지에 대한 연구가 요구된다.

---

## Key References

- Nowoshilow S, et al. (2018) The axolotl genome and the evolution of key tissue formation regulators.
- Gerber T, et al. (2018) Single-cell analysis uncovers convergence of cell identities during axolotl limb regeneration.
- Leigh ND, et al. (2018) Single-cell transcriptomic analysis of regenerating and homeostatic axolotl limb tissue.
- Bryant DM, et al. (2017) *cirbp* 및 *kazald1* 등 블라스테마 상향 유전자 규명.
- Kragl M, et al. (2009) Cells keep a memory of their tissue origin during axolotl limb regeneration.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
