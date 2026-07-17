---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
---

# Dissecting human embryonic skeletal stem cell ontogeny by single-cell transcriptomic and functional analyses

## Citation (NLM)

He J, Yan J, Wang J, Zhao L, Xin Q, Zeng Y, Sun Y, Zhang H, Bai Z, Li Z, Ni Y, Gong Y, Li Y, He H, Bian Z, Lan Y, Ma C, Bian L, Zhu H, Liu B, Yue R. Dissecting human embryonic skeletal stem cell ontogeny by single-cell transcriptomic and functional analyses. _Cell Res._ 2021 Jul;31(7):742-757. doi: [10.1038/s41422-021-00467-z](https://doi.org/10.1038/s41422-021-00467-z).

---

## Background

골격줄기세포(SSCs)는 생후 쥐의 성장판, 골막, 두개골에서 동정되었으며, 연골세포, 조골세포, 조혈 기질로 분화할 수 있으나 지방세포로는 분화하지 않는 특징을 가진다. 인간 SSCs도 17주 태아(fetal) 장골 성장판에서 보고되었다. 그러나 인간 배아 초기 골형성 단계에서 SSCs가 언제, 어디서 출현하며 어떤 계통 발생(ontogeny)을 거치는지는 알려지지 않았다. 사지 발달에서 척추동물 부속골격의 가장 초기 전구세포는 사지 돌기(limb bud) 내에서 형성되며, 전-후축(AP)은 SHH 신호에 의해, 근위-원위축(PD)은 FGF 신호에 의해 조절된다. 인간 배아 골격 발생의 세포 이질성과 계층적 분화 경로를 단일세포 수준에서 규명하는 것은 골격 재생 및 세포 치료 개발에 필수적이다. 본 연구는 5주 및 8주 인간 배아 사지 돌기와 장골, 두개골을 단일세포 RNA 시퀀싱(scRNA-seq)으로 분석하여 인간 배아 골격줄기/전구세포의 시공간적 발생 지도를 작성하고자 하였다.

---

## Key Experiment Methods

**1. 인간 배아 샘플 수집**

- 5주 수정 후(WPC) 상하지 사지 돌기(limb bud, n=3 배아)
- 8 WPC 전지 장골(forelimb/hindlimb long bones, n=3 배아)
- 8 WPC 두개골(calvaria, n=2 배아)
- 정상 핵형 확인(CNV score 계산)

**2. 단일세포 RNA 시퀀싱(scRNA-seq)**

- 10× Genomics 3′ droplet 기반 플랫폼
- 유세포 분류로 live single cells 선별
- 5 WPC limb bud: 19,890세포, 8 WPC long bones: 15,680세포, 8 WPC calvaria: 7,287세포
- CCA로 배치 효과 보정, Seurat로 클러스터링
- UMAP 시각화

**3. 계통 발생 궤적 분석**

- RNA velocity로 pseudotime 분석
- PAGA(Partition-based graph abstraction)로 세포 집단 간 연결성 분석
- Slingshot으로 분화 trajectory 시뮬레이션
- Diffusion map 분석

**4. 전사인자 조절 네트워크 분석**

- SCENIC(Single-Cell rEgulatory Network Inference and Clustering)로 regulon 활동성(AUC score) 평가
- GENIE3로 전사인자-표적 유전자 네트워크 추론

**5. 종간 비교**

- 마우스 E11.5 limb bud 및 E15.5 장골 scRNA-seq 데이터와 SciBet 알고리즘으로 비교

**6. eSSPCs 분리 및 기능 분석**

- 유세포 분류: PDGFRAlow/−PDPN−, PDGFRAlow/−PDPN+CADM1−, PDGFRAlow/−PDPN+CADM1+
- CFU-F colony formation assay 및 mesenchymal sphere culture
- Serial passaging으로 자가재생 능력 확인
- In vitro 삼계통 분화(지방, 조골, 연골)
- In vivo 신장 피막 하 이식(immunodeficient NOG 마우스, 8주 후 Movat pentachrome, collagen I/II 면역형광)

**7. 면역형광**

- FOXP1, FOXP2, CADM1, PDPN 등 마커 단백질 발현 위치 확인

---

## Results

**Limb bud와 장골 통합 분석: 16개 세포 집단**

5 WPC limb bud과 8 WPC 장골을 통합 분석하여 16개 세포 집단을 동정하였다:
- PRRX1+ limb bud mesenchyme 3개 아집단(LBM1-3): PDGFRA 발현 수준이 다른 성숙 단계의 간엽전구세포
- OCPs(Osteo-chondrogenic progenitors, cluster 4): PRRX1+, SOX9low, PDGFRAhi — limb bud과 장골에 균등 분포
- EPCAM+ 상피세포, GYPA+ 적혈구(limb bud 우세)
- SIX1+ 근전구세포, CDH5+ 내피세포, CD68+ 대식세포
- RUNX2+ 조골전구세포, OSR2+NOV+ 연골막 간엽 기질세포(PMSCs), SOX9+ 연골아세포/연골세포, MYOG+ 근세포, SOX10+ Schwann 세포(long bones 우세)

RNA velocity와 PAGA 분석에서 OCPs가 limb bud 간엽전구세포(PRRX1+)를 long bones의 PMSCs/연골아세포/연골세포(SOX9+) 및 조골전구세포(RUNX2+)로 연결하는 핵심 역할을 함이 확인되었다.

**Limb bud 간엽의 공간적 이질성 규명**

5 WPC limb bud에서 4개 간엽 아집단을 PD축과 AP축을 따라 배열하였다:
- LBM3(근위): 3′ HOX 유전자(HOX2-6) 발현, MEIS2+
- LBM1/LBM2(원위): 5′ HOX 유전자(HOX9-11) 발현, HOXD13+
- LBM2는 가장 원위에 위치하며 가장 높은 증식률(G2/M 세포 비율 높음)을 보여 AER 하방의 progress zone에 해당
- OCP는 3′ 및 5′ HOX 유전자를 모두 발현하여 응축 간핵(core condensed mesenchyme)에 해당

GSVA 분석에서 근위/핵심 간엽(LBM3/OCP)은 retinoic acid 및 PDGF 신호가, 원위 간엽(LBM1/2)은 Hedgehog, FGF, TGFβ, Notch 신호가 풍부하였다. SCENIC 분석에서 MSX1/PITX1 regulon이 LBM1/2에, PBX1/SOX9 regulon이 LBM3/OCP에 풍부하였으며, OCP 특이적 regulon으로 ZMIZ1과 KDM5A가 동정되었다.

**장골에서 배아 골격줄기/전구세포(eSSPCs) 동정**

8 WPC 장골의 골연골 계통 세포(OCLCs)를 7개 아집단으로 분류하였다:
- LBDMC(Limb bud-derived mesenchymal cells, cluster 2): TWIST2hi
- BMSCs(cluster 1): CXCL12+, PDGFRA+
- **eSSPCs(Embryonic skeletal stem/progenitor cells, cluster 3)**: GAS2+, 중심에 위치, 줄기세포 증식 관련 유전자 풍부
- 조골전구세포, PMSCs, 연골아세포, 연골세포

RNA velocity에서 eSSPCs가 조골전구세포, 연골아세포/연골세포, PMSCs로 향하는 강한 분기 흐름을 보였다. LBDMC는 eSSPC와 BMSC의 상류에 위치하여 두 분화 경로를 형성하였다. SCENIC 분석에서 eSSPCs는 **FOXP1 및 FOXP2 regulon**이高度로 풍부하였다. 면역형광에서 FOXP1/2+ 세포가 8 WPC 장골의 연골막(perichondrium) 및 일차 골화 중심(POC) 내부에서 확인되었다.

**CADM1이 eSSPCs의 표면 마커로 동정**

eSSPCs에서 세포부착분자 CADM1이 선별적으로 발현되었다. FOXP1/2 결합 모티프가 CADM1의 cis-조절 요소에서 풍부하였다. Schwann 세포도 CADM1을 발현하므로, PDPN을 추가로 활용하여 eSSPCs(PDPN+CADM1+)와 Schwann 세포(PDPN−CADM1+)를 구분하였다. 면역형광에서 PDPN+CADM1+ 세포가 연골막 및 POC 내부에 위치하였다.

**eSSPCs의 자가재생 및 골연골 분화 능력**

유세포 분류에서 PDGFRAlow/−PDPN+CADM1+ 세포는 PDGFRAlow/−PDPN+CADM1− 및 PDGFRAlow/−PDPN− 세포에 비해 CFU-F colony 형성 효율이 현저히 높았다(69.33 vs 25.67 vs 4.67 colonies per 4.5×10³ cells). Mesenchymal sphere 형성도 유사한 경향이었다. PDGFRAlow/−PDPN+CADM1+ 세포는 serial passaging 후에도 eSSPC 면역표현형을 유지하였다. In vitro 분화에서 골형성 및 연골형성은 가능하였으나 지방형성은 불가능하였다. In vivo 신장 피막 하 이식 8주 후 osteo-chondrogenic 분화가 확인되었으나, 골수 미세환경 재구성은 관찰되지 않았다(성장판 인간 SSCs와 기능적 차이).

**두개골에서 신경능선 유래 골격 전구세포(NCDCs) 동정**

8 WPC 두개골 scRNA-seq에서 12개 세포 집단이 확인되었다: NGFR+ cranial neural crest(NC), GJA1+ VLMCs, migratory NC(mig_NC), **NCDC(Neural crest-derived cells, BMP4+FOXC2+)**, RUNX2+ 조골전구세포, OSR2+ PMSCs, SOX9+ 연골세포 등. NCDC는 long bone eSSPCs와 유사한 표면 마커(PDGFRAlow/−PDPN+CADM1+)를 공유했으며, 시상봉합(sagittal suture) 외층에 위치하였다. Slingshot 분석에서 FOXC1+ NC 계통과 TWIST2+ 중배엽 계통이 DLX5+ 조골전구세포로 수렴하였으며, NCDC가 mig_NC에서 조골전구세포로의 전환에 핵심 역할을 하였다. SCENIC 분석에서 NCDCs도 FOXP1/2/4 regulon이 풍부하였다.

---

## Perspective

본 연구는 인간 배아 골격 발생의 단일세포 전사체 지도를 최초로 작성하여, limb bud 간엽의 공간적 이질성, OCPs의 출현, 그리고 장골과 두개골에서 각각 다른 발생 기원을 가진 골격줄기/전구세포 집단을 규명하였다. 장골의 eSSPCs는 연골막에 위치하며 CADM1/PDPN으로 동정 가능하고, FOXP1/2 전사 네트워크에 의해 조절되며, 골연골 계통으로 분화하지만 지방세포나 조혈 기질로는 분화하지 않는다. 두개골의 NCDCs는 신경능선 유래로, intramembranous 골화를 매개하며 FOXP1/2/4 regulon을 공유한다. FOXP 전사인자 가족이 연골막 골격전구세포에서 Runx2와 상호작용하여 전활성화를 억제함으로써 미분화 상태를 유지한다는 기존 보고와 일치하여, FOXP 가족이 인간 배아 골격줄기세포 유지에 근본적 역할을 함이 시사된다. CADM1은 골육종 진단 마커로 알려져 있었으나, 본 연구에서 배아 골격줄기세포 마커로서의 새로운 기능이 규명되었다. eSSPCs가 골수 미세환경을 재구성하지 못하는 것은 성장판 SSCs와 기능적 차이가 있음을 보여주며, 이는 골격 발달 단계와 구획에 따라 SSCs의 이질성이 있음을 강조한다. 본 연구에서 동정된 인간 배아 골격줄기/전구세포와 분자 마커는 골절 비유합, 골다공증, 두개안면 결손 등 골격 질환의 세포 치료 및 조직 공학에 중요한 자원을 제공한다. 향후 유전자 추적(lineage-tracing) 연구를 통해 eSSPCs와 생후 성장판·골막·혈관주위 SSCs 간의 관계를 규명하고, 유도형 Cre 모델을 이용한 기능적 검증이 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
