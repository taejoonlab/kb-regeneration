---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
---

# Temporal single-cell transcriptomes of zebrafish spinal cord pMN progenitors reveal distinct neuronal and glial progenitor populations

## Citation (NLM)
Scott K, O'Rourke R, Winkler CC, Kearns CA, Appel B. Temporal single-cell transcriptomes of zebrafish spinal cord pMN progenitors reveal distinct neuronal and glial progenitor populations. bioRxiv. 2021 Apr 29. doi:10.1101/2021.04.28.441874

**DOI:** [https://doi.org/10.1101/2021.04.28.441874](https://doi.org/10.1101/2021.04.28.441874)

---

## Background
bHLH 전사인자 Olig2로 표지되는 복측 척수 pMN 전구세포는 운동뉴런을 먼저 생성한 뒤 희소돌기아교 전구세포(OPC)를 순차적으로 생성하며, 일부 OPC는 수초형성 희소돌기아교세포로 분화하고 일부는 유지된다. 분화된 세포 유형의 분자적 프로파일은 많이 알려져 있으나, 이들을 생성하는 전구세포에 대해서는 덜 알려져 있다.

계보 추적 및 이전 제브라피시 fate mapping/time-lapse 이미징(Ravanelli and Appel, 2015)은 운동뉴런과 OPC가 서로 다른 시점에 olig2 발현을 시작하는 별개의 pMN 전구세포에서 유래함을 시사하였다. 본 연구는 단일세포 RNA 시퀀싱을 이용해 발생 중 제브라피시 척수에서 운동뉴런 및 OPC 전구세포의 발생 기원과 전사 프로파일을 규명하고자 하였다.

---

## Key Experiment Methods
1. 24, 36, 48 hpf Tg(olig2:EGFP) 배아의 몸통/꼬리에서 olig2:EGFP+ 세포를 FACS로 분리(운동신경형성, OPC 특성화, 희소돌기아교세포 분화 개시 포착).
2. 단일세포 RNA 시퀀싱(10X Genomics Chromium; Illumina NovaSeq 6000)과 개별 단계 및 통합 데이터셋의 비지도 Seurat 클러스터링; 알려진 표지 유전자로 클러스터 정체 규명.
3. MEP 신경교 vs 두개 운동뉴런 전구세포 구분 및 희소돌기아교 계보 내 개재뉴런 전구세포와 Pre-OPC 분리를 위한 하위 클러스터링.
4. 궤적 분석: RNA velocity(velocyto/scVelo)와 Slingshot pseudotime; 계보별 차등발현 유전자에 대한 GAM 모델.
5. 36 및 40 hpf 배아에서 ascl1a, neurog1, gsx2, sox10, olig1에 대한 형광 in situ RNA hybridization(RNAScope Multiplex Fluorescent V2)으로 전구세포 집단을 in vivo 검증.

---

## Results
- 통합 scRNA-seq(28개 클러스터)는 신경 전구세포에서 분화세포로의 진행을 포착하였고, 대부분 뉴런/뉴런 전구세포, 약 24% 전구세포, 약 10% 신경교 계보였다. 긴 EGFP 잔존성이 olig2– elavl4+ 유사분열후 뉴런을 설명하였다.
- pMN 세포는 두 개의 별개 전구세포 집단으로 구성되었다: sox19a+ neurog1+ 뉴런 전구세포(운동뉴런 계보 연관)와 sox19a+ neurog1– Pre-OPC 전구세포(희소돌기아교 계보 연관).
- 48 hpf에서 OPC(sox10+, sox5, sox9a/b, olig1)와 수초형성전 희소돌기아교세포(tcf7l2, myrf)가 별개 클러스터를 형성하였고, 척수 손상 후 새 뉴런을 생성하는 것으로 알려진 방사교세포(sox19a+ pcna– gfap+)가 존재하였다. Pre-OPC 특성 세포는 48 hpf에 부재하여 더 이른 시기에 발생하고 OPC 형성 후 고갈됨을 시사하였다.
- 36 및 24 hpf에서 Pre-OPC는 nkx2.2a, 낮은 olig1, Pre-OPC 표지 ascl1a와 gsx2를 발현하였다. 24 hpf에서 Pre-OPC는 덜 성숙한 Pre-OPC1(낮은 olig2, 배측 표지 pax6a/dbx1a/irx3a)과 더 성숙한 Pre-OPC2(높은 olig2/olig1/nkx2.2)로 나뉘었고, RNA velocity가 Pre-OPC1→Pre-OPC2 전이를 예측하였다.
- RNA velocity와 Slingshot은 운동뉴런과 희소돌기아교세포의 별개 발생 궤적을 뒷받침하였다. 뉴런 계보는 isl1, mnx1, neurod4를 발현한 반면, 희소돌기아교 계보는 sox9b, prdm8, olig1, nkx2.2a를 발현하고 olig2를 유지하였다.
- gsx2는 Pre-OPC1/2에서만 배타적으로 발현되며 neurog1과 상호 배타적이었다. FISH로 복측 척수에서 ascl1a+ neurog1+ gsx2– 뉴런 pMN 전구세포와 ascl1a+ neurog1– gsx2+ Pre-OPC를 확인하였고, 대부분의 sox10+ 세포가 gsx2를 발현함(일부는 olig1도)을 확인하였다.

---

## Perspective
본 연구는 제브라피시 pMN 전구세포의 발생 단일세포 아틀라스를 제공하며, 운동뉴런과 희소돌기아교세포가 OPC 특성화 이전에 조기 특성화되는 전사적으로 별개의 전구세포 집단에서 유래함을 입증한다. gsx2를 Pre-OPC의 표지로 동정하여 희소돌기아교 계보 형성의 최초 단계를 탐구할 새로운 도구를 제공하며, 저자들은 Gsx2가 OPC 형성을 제한하는 마우스 피질 선행 연구와 gsx2의 역할을 연관짓는다. Pre-OPC1 집단은 pMN 도메인으로 복측 이동하는 배측 모집 전구세포를 나타낼 수 있다. 재생 지식베이스 관점에서, 규명된 전구세포 이질성과 (척수 손상 후 뉴런을 생성할 수 있는) 방사교세포는 CNS 복구와 직접적으로 관련된다. 프리프린트로서 동료심사를 거치지 않았다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
