---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
---

# Sorafenib inhibits ossification of the posterior longitudinal ligament by blocking LOXL2-mediated vascularization

## Citation (NLM)

Wang L, Jiang W, Zhao S, Xie D, Chen Q, Zhao Q, Wu H, Luo J, Yang L. Sorafenib inhibits ossification of the posterior longitudinal ligament by blocking LOXL2-mediated vascularization. _Bone Res._ 2024 Mar 26;12(1):24. doi: [10.1038/s41413-024-00327-7](https://doi.org/10.1038/s41413-024-00327-7).

---

## Background

후종인대 골화증(OPLL)은 척추의 퇴행성 과골형성 질환으로, 부드럽고 탄력 있는 후종인대(PLL)가 뼈로 변환되어 척추 가동성 제한 및 신경 압박을 유발한다. OPLL은 경추에 주로 발생하며 동아시아에서 유병률이 높다(일본 1.9~4.3%). 조직학적으로 OPLL은 연골내 골화(endochondral ossification) 과정을 통해 진행되며, 무혈관 인대 조직이 고도로 혈관화된 뼈 조직으로 대체된다. 혈관 침윤은 OPLL 진행에서 골분화 이상의 중요한 생물학적 과정으로 작용한다. Lysyl oxidase family의 LOXL2는 콜라겐 scaffolding을 통한 혈관 형성 조절, 종양 혈관모방, 섬유화 질환 등에 관여함이 알려져 있으나, OPLL에서의 역할은 규명되지 않았다. 본 연구는 bulk 및 단일세포 RNA 시퀀싱을 통해 OPLL 과정의 분자 특성, 세포 구성 및 그 진화를 단일세포 해상도로 규명하고, LOXL2가 인대세포의 내피세포 유사 분화에서 수행하는 역할과 sorafenib의 OPLL 억제 효과를 검증하고자 하였다.

---

## Key Experiment Methods

**1. 임상 검체 분석**

- OPLL 환자의 lateral X-ray, 3D CT, MRI로 ossification 평가
- Modified JOA 및 NDI scale로 질병 중증도 측정, spinal canal occupancy ratio와 상관관계 분석
- H&E, SOFG 염색, COLII/COLX/SP7/BGLAP/RUNX2/MMP1 면역염색으로 연골내 골화 특징 확인

**2. Bulk RNA-seq**

- 동일 OPLL 환자 4명에서 ossified(OPLL) vs non-ossified(non-OPLL) 인대 쌍으로 비교
- HISAT2 alignment, edgeR로 DEG 분석(paired design)
- GO, KEGG, GSEA(Hallmark gene sets), STRING PPI network 분석
- 5가지 centrality 방법(MCC, DMNC, EPC, MNC, ClusteringCoefficient)으로 hub gene 동정

**3. 단일세포 RNA 시퀀싱(scRNA-seq)**

- OPLL 3명, non-OPLL 2명의 후종인대에서 51,245개 세포(30,628 non-OPLL, 20,617 OPLL) 프로파일링
- UMAP으로 13개 클러스터 동정: 인대세포(ligament_1-4), 내피세포(EC_1-2), 주위세포, 단구-대식세포, T세포, B세포, 형질세포
- 인대세포, 주위세포, 내피세포 추출하여 9개 subcluster로 재클러스터링

**4. RNA velocity 및 분화 궤적 분석**

- UMAP embedding of RNA velocity로 동적 trajectory 확인
- CytoTRACE로 미분화 정도 평가
- Monocle3으로 C6(progenitor)를 starting point로 ligament-to-vascular differentiation trajectory 재구성
- Louvain community analysis로 10개 유전자 모듈 동정, ReactomePA로 pathway enrichment

**5. 체외 모세관 형성 assay(Matrigel)**

- HUVECs(양성 대조), hUC-MSCs, 인대세포를 Matrigel에서 tube formation 평가
- VEGFA(100 ng/mL), PDGF-BB(100 ng/mL) 자극 효과 분석
- Bevacizumab(VEGFA 항체), imatinib(PDGFR 억제제)로 억제 실험
- Matrigel 상 인대세포에서 CD31, EMCN, LOXL2, VEGFA, PDGFB 발현 분석(qPCR)

**6. In vivo 혈관망 형성 assay**

- Nude 마우스 피하에 인대세포+Matrigel gel sphere 주입
- Left ventricle를 통한 ink perfusion으로 functional blood vessel 확인
- 인간 특이적 CD31 면역조직화학, UEA I(인간 내피 특이적), GS-B4(마우스 내피 특이적) lectin staining

**7. LOXL2 기능 연구**

- LOXL2 overexpression(OE)으로 tube formation 영향 평가
- BAPN(pan-Lox(L) 억제제, 2 mmol/L) 처리로 효소활성 의존성 확인
- HIF1A pathway 분석

**8. Sorafenib 치료 실험**

- BMP 유도 및 enpp1 결손 유도 동물 모델에서 sorafenib의 OPLL 진행 억제 효과 평가
- 정상 골량에 대한 영향 확인

---

## Results

**OPLL은 연골내 골화 특징** OPLL 환자의 ossified 조직은 성숙한 뼈, Haversian canal, 소주 및 골수 구조를 보였다. 접합부에서 proteoglycan 풍부 연골 및 비대 연골세포가 관찰되었고, COLII/COLX가 접합부 연골에서 높게 발현되었다. SP7, BGLAP, RUNX2 등 조골 marker는 골화 부위에서 증가하였다. MMP1은 접합부 및 골화 부위 모두에서 높았다. Spinal canal occupancy ratio는 JOA score와 음의 상관(r=-0.66), NDI score와 양의 상관(r=0.56)을 보였다.

**OPLL에서 신혈관 형성 pathway 상승** Bulk RNA-seq에서 OPLL vs non-OPLL 간 677개 DEG(371 상승, 306 하조절)가 동정되었다. GO 분석에서 extracellular matrix organization, angiogenesis, skeletal system development, cartilage development가 풍부하였다. GSEA에서 angiogenesis pathway가 주요 생물학적 과정으로 확인되었다(NES=1.89, adj P<0.001). PPI network에서 LOXL2, TGFBI, PCOLCE가 top hub gene으로 동정되었다. 비대 인대 microarray(GSE113212)에서도 LOXL2 상승 및 angiogenesis/hypoxia pathway 활성화가 확인되었다.

**OPLL에서 LOXL2 및 H-type 혈관 증가** OPLL 조직 및 인대세포에서 LOXL2 발현이 상승하였다. LOXL2+ 세포는 골화와 비골화 접합부에 주로 국재되었다. CD31+EMCN+ type H vessel이 골화 부위 및 접합부 골수강 내에서 증가하였다. 인대세포는 3계통 분화 능력을 가지며 MSC 표면 marker(CD73+, CD90+, CD105+, CD45−)를 발현하였다.

**단일세포 분석: 인대세포의 내피 분화 궤적** 9개 subcluster 중 C6(progenitor, PRG4+)을 starting point로 RNA velocity와 CytoTRACE 분석에서 C6→C4/C9(endothelial), C2/C5(chondrocytes), C8(osteoblasts)로 분화함을 확인하였다. Module 4(PECAM1, EMCN 등 내피 marker, VEGF signaling)와 Module 5(LOXL2, HIF1A, RNA splicing, heat shock response)가 내피 분화 과정에서 점진적으로 증가하였다. LOXL2와 HIF1A는 내피 분화 과정에서 초기 증가 후 감소 패턴을 보였다.

**인대세포의 내피세포 유사 분화 능력** Matrigel assay에서 인대세포는 HUVECs과 유사하게 자발적으로 모세관 구조를 형성하였으나, hUC-MSCs는 세포 응집만 보였다. Tube formation 과정에서 인대세포는 LOXL2, VEGFA, PDGFB 발현이 증가하였고, 조골 marker SP7도 상승하여 혈관형성과 골화의 coupling을 시사하였다. In vivo에서 인대세포+Matrigel gel sphere는 ink particle 침착을 보였고, 인간 특이적 CD31 양성 부위 내에 ink가 위치하였다. UEA I(인간) 양성, GS-B4(마우스) 음성으로 인대세포 유래 functional blood vessel 형성을 확인하였다. VEGFA 및 PDGF-BB는 모세관 형성을 촉진하였고, Bevacizumab 및 imatinib으로 억제되었다.

**LOXL2가 HIF1A 경로를 통해 내피 분화 조절** LOXL2 OE는 모세관 형성을 증가시켰으나, BAPN(효소활성 억제제) 처리는 영향을 미치지 않아 LOXL2의 혈관형성 조절이 효소활성과 무관함을 보였다.

**Sorafenib의 OPLL 억제 효과** Sorafenib은 LOXL2 매개 혈관 형태형성을 효과적으로 억제하였다. BMP 유도 및 enpp1 결손 유도 동물 모델에서 sorafenib은 혈관화와 골화의 coupling을 차단하여 OPLL 진행을 유의하게 억제하였고, 정상 골량에는 영향을 미치지 않았다.

---

## Perspective

본 연구는 OPLL의 발병 기전에서 LOXL2-HIF1A-VEGFA/PDGF-BB 축이 인대세포의 내피세포 유사 분화와 혈관형성을 매개하며, 이 과정이 골화와 밀접하게 coupling되어 있음을 단일세포 해상도로 규명하였다. LOXL2의 혈관형성 조절 기능이 그 효소활성과 무관하다는 점은 LOXL2의 비전통적(non-canonical) 기능을 시사하며, 새로운 치료 표적 개발에 중요한 통찰을 제공한다.

Sorafenib은 광범위 tyrosine kinase inhibitor로 LOXL2 매개 혈관 형태형성을 억제함으로써 OPLL 진행을 효과적으로 차단하면서도 정상 골량에는 영향을 미치지 않아, OPLL 특이적 치료제로서의 잠재력을 보였다. 이는 혈관화와 골화의 coupling을 표적으로 한 치료 전략이 OPLL뿐만 아니라 다른 이소성 골화 질환에도 적용 가능함을 시사한다.

본 연구의 의의는 다음과 같다: (1) OPLL의 단일세포 atlas 최초로 구축, (2) 인대세포의 내피세포 유사 분화 능력 및 LOXL2의 조절 기전 규명, (3) Sorafenib의 OPLL 치료제로서의 preclinical 검증. 향후 연구로는 LOXL2-HIF1A 상호작용의 분자기전 심층 분석, Sorafenib의 장기 안전성 및 임상 시험, 그리고 LOXL2 특이적 억제제 개발이 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*