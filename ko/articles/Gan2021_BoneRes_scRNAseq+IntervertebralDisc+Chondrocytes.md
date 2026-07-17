---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
---

# Spatially defined single-cell transcriptional profiling characterizes diverse chondrocyte subtypes and nucleus pulposus progenitors in human intervertebral discs

## Citation (NLM)

Gan Y, He J, Zhu J, Xu Z, Wang Z, Yan J, Hu O, Bai Z, Chen L, Xie Y, Jin M, Huang S, Liu B, Liu P. Spatially defined single-cell transcriptional profiling characterizes diverse chondrocyte subtypes and nucleus pulposus progenitors in human intervertebral discs. _Bone Res._ 2021 Oct 11;9(1):37. doi: [10.1038/s41413-021-00163-z](https://doi.org/10.1038/s41413-021-00163-z).

---

## Background

퇴행성 추간판 질환(DDD)은 요통의 주요 원인으로 전 세계적으로 막대한 의료 부담과 사회경제적 비용을 초래한다. 현재 DDD 치료(안정, 재활, 약물, 중재치료, 수술)는 증상 완화만 제공할 뿐 추간판(IVD)의 항상성(homeostasis)을 재설정하지 못한다. 건강한 인간 IVD는 중앙의 수핵(nucleus pulposus, NP), 주변의 섬유륜(annulus fibrosus, AF), 그리고 추체에 인접한 연골종판(cartilage endplate, CEP)의 세 가지 구성 요소로 이루어져 있다. IVD의 기원은 이종성(heterologous)으로, NP는 척색(notochord)에서, AF와 CEP는 경절(sclerotome)에서 유래한다. 기존 bulk RNA 시퀀싱은 IVD 세포의 높은 이질성과 복잡한 미세환경으로 인해 퇴행의 분자기전 규명에 한계가 있었다. 본 연구는 건강한 인간 IVD(NP, AF, CEP)의 단일세포 전사체 atlas를 구축하여 세포 이질성을 공간적으로 규명하고, NP 내 전구세포(progenitor) 집단을 동정하며, NP 미세환경의 세포 간 신호전달 네트워크를 분석하고자 하였다.

---

## Key Experiment Methods

**1. 인간 IVD 시료 수집 및 scRNA-seq**

- Pfirrmann grade I 건강한 인간 IVD 5개에서 NP, AF, CEP 분리
- 10X Genomics Chromium droplet-based scRNA-seq으로 128,833개 세포 프로파일링, quality control 후 108,108개 세포 분석
- fastMNN로 batch effect 보정, tSNE로 클러스터링

**2. 세포 유형 동정 및 검증**

- SOX9/ACAN/COL2A1(연골세포), TBXT/KRT8(척색세포), PDGFRA/PRRX1/IGF1(NP 전구세포), ACTA2/TAGLN/MCAM(주위세포), PECAM1/CD34/CDH5(내피세포) 등 marker 유전자로 9개 root cluster 동정
- 면역조직화학으로 SOX9, PDGFRA, ACTA2, PECAM1 공간 분포 검증

**3. 연골세포 아집단 특성화**

- 3개 연골클러스터를 6개 subcluster(C1~C6)로 세분화
- GO 분석, PANTHER, MatrisomeDB로 기능 및 ECM matrisome 유전자 발현 패턴 분석
- 인간 관절연골 OA 단계별 데이터(Ji et al.)와 Pearson 상관분석

**4. NP 전구세포(NPPC) 분석**

- NPPC를 4개 subcluster(NPPC-1~4)로 세분화
- SCENIC으로 transcription factor regulon 분석(HOXA10, SOX4, SMAD3, GLI1 등)
- PDGFRA/PROCR 표면 marker로 NPPC-3 동정, flow cytometry로 분리
- CFU-F colony formation assay로 clonogenicity 평가
- p-SMAD3 면역형광으로 SMAD3 활성화 확인

**5. 분화 궤적 재구성**

- Monocle 3으로 NPPC-3를 starting point로 chondrogenic 및 osteogenic branch 궤적 재구성
- Louvain community analysis로 16개 유전자 모듈 동정
- PROCR+ 세포의 3계통(조골, 연골, 지방) 분화 능력 검증(Alizarin Red, Oil Red O, Alcian Blue, Safranin O/Fast Green 염색)

**6. 세포 간 신호전달 네트워크 분석**

- CellChat으로 NP 내 14개 subcluster 간 ligand-receptor 상호작용 분석
- VEGF, TGFB, PDGF, FGF signaling network 상세 분석
- TGF-β3(10 ng/mL) 및 SB505124(TGF-β 수용체 억제제)로 PROCR+ 세포 연골분화 실험
- PDGF-AA(20 ng/mL) 및 crenolanib(PDGFR α/β 억제제)로 PROCR+ 세포 증식 분석(CCK-8)

**7. 종간 비교**

- 인간과 랫드 IVD scRNA-seq 데이터 비교로 보존된 세포 이질성 확인

---

## Results

**IVD 주요 세포 유형 동정** 108,108개 세포에서 9개 root cluster 동정: SOX9+ 연골세포 3종(Chond1-3), 척색세포, 기질세포, 주위세포, 내피세포, NP 전구세포(NPPC), 혈액세포. 공간적으로 연골세포와 기질세포는 NP, CEP, AF에 풍부하고, 척색세포는 NP에 주로 분포하였다. PDGFRA+ NPPC는 NP에 주로, AF와 CEP에는 드물게 분포하였다.

**연골세포 6개 아집단 특성화** C1은 BMP2/TGFB1/FGF2 등 성장인자 유전자 고발현(regulatory chondrocyte), C3/C4는 ACAN/COL2A1 등 ECM 성분 고발현(homeostatic chondrocyte), C5/C6은 PRG4/CNMD 고발현 및 높은 대사율(effector chondrocyte)을 보였다. C1/C2는 AF와 CEP에 주로, C5는 NP에 주로 위치하였다. Matrisome 분석에서 C1은 secreted factors, C3은 core matrisome(collagens, proteoglycans, ECM glycoproteins), C5는 ECM regulators를 주로 발현하였다.

**NP 전구세포(NPPC) 4개 아집단 및 PROCR+ 세포 동정** NPPC-1(PAX1+), NPPC-2(ANGPT1+), NPPC-3(PRG4+/PROCR+), NPPC-4(SOX9+)로 세분화되었다. NPPC-3은 PROCR을 특이적으로 발현하여 줄기세포 특성(stemness)을 시사하였다. PDGFRA+PROCR+ 세포의 빈도는 NP에서 0.36%였으며, PROCR+ 세포는 CFU-F 형성 능력이 현저히 높았다(25.9±3.3 vs 2.9±1.4 per 1,000 cells, p<0.0001). PROCR+ 세포에서 p-SMAD3 발현이 높아 SMAD3/TGF-β 경로 활성화를 확인하였다.

**PROCR+ 세포의 양계통 분화 궤적** Monocle 3 분석에서 NPPC-3(PROCR+)은 chondrogenic branch(NPPC-3→NPPC-1→Chond2→Chond3)와 osteogenic branch(NPPC-3→NPPC-2→NPPC-4→osteogenic cells→Fib3)로 분기하였다. 체외에서 PROCR+ 세포는 조골, 연골, 지방 3계통 분화 능력을 확인하였다.

**NP 미세환경 신호전달 네트워크** CellChat 분석에서 NPPC 클러스터는 PDGF signaling network에서 핵심 기여자(PDGFA 리간드 분비)로 작용하였다. TGF-β pathway는 연골세포와 NPPC 클러스터 간 TGFB3-TGFBR/ACVR1 신호로 상호작용하였다. TGF-β3는 PROCR+ 세포의 연골분화를 유도하였고, TGF-β 수용체 억제제 SB505124로 차단되었다. PDGF-AA는 PROCR+ 세포 증식을 촉진하였고, PDGFR 억제제 crenolanib로 억제되었다. Fib3는 VEGF, PDGF, FGF 등 거의 모든 pathway에 관여하여 NP 항상성에서 중요한 역할을 하였다.

**종간 보존성** 랫드 IVD scRNA-seq 재분석에서 인간과 동일한 세포 클러스터(NPPC, 내피세포, 주위세포)와 유전자 발현 패턴(PDGFRA, PRRX1, IGF1)이 보존됨을 확인하였다.

---

## Perspective

본 연구는 건강한 인간 IVD의 공간적 단일세포 전사체 atlas를 최초로 구축하여, IVD 연골세포를 regulatory, homeostatic, effector의 세 기능적 아형으로 분류하고, NP 내 PROCR+ 다능성 전구세포 집단을 동정하였다. PROCR+ 세포는 CFU-F 형성 능력과 3계통 분화 능력을 가지며, TGF-β 및 PDGF 신호에 반응하여 NP 항상성 유지에 핵심적인 역할을 한다.

CellChat 기반 신호전달 네트워크 분석은 NP 미세환경에서 PDGF와 TGF-β cascades가 세포 간 crosstalk의 핵심 cue임을 밝혔으며, Fib3가 다중 signaling pathway에 관여하는 hub 세포 유형임을 제시하였다. 이는 퇴행성 추간판 질환(DDD)에서 NP 세포의 항상성 상실 기전을 이해하고, PROCR+ 전구세포를 표적으로 한 세포 기반 재생 치료 전략 개발에 중요한 기초를 제공한다.

향후 연구로는 퇴행성 IVD(Pfirrmann grade III-IV)에서의 단일세포 atlas 비교, PROCR+ 세포의 in vivo 재생 능력 검증, 그리고 PDGF/TGF-β 신호 조절을 통한 DDD 치료 접근이 필요하다. 본 연구에서 확립된 IVD 세포 marker와 신호전달 네트워크는 DDD의 새로운 치료 표적 발굴에 유용한 자원이 될 것이다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*