---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
raw_data:
  - "ArrayExpress: E-MTAB-14385"
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# A multi-omic atlas of human embryonic skeletal development

## Citation (NLM)

To K, Fei L, Pett JP, et al. A multi-omic atlas of human embryonic skeletal development. Nature. 2024;635:657-667. doi:10.1038/s41586-024-08189-z

**DOI:** [https://doi.org/10.1038/s41586-024-08189-z](https://doi.org/10.1038/s41586-024-08189-z)

---

## Background

인간 배아의 골격 발생은 수정 후 5~11주(post-conception weeks, PCW) 사이에 시작되며, 두개관(calvaria)의 막내골화(intramembranous ossification)와 사지 및 두개저(skull base)의 연골내골화(endochondral ossification)라는 두 가지 주요 골화 방식을 통해 진행된다. 활막관절(synovial joint)은 5~6 PCW에 interzone 응축(condensation)으로 형성되기 시작하여 7~8 PCW에 관절강(cavity)이 생긴다. 지금까지 인간 배아 골격 발생을 단일세포 및 후생유전체 수준에서 종합적으로 기술한 연구는 부재하였으며, 특히 골·연골 전구세포의 지역 특이적 운명 결정과 조절 네트워크는 거의 알려져 있지 않았다. 저자들은 snRNA-seq, snATAC-seq(10X Multiome), 공간 전사체 분석을 결합한 멀티오믹 접근법을 통해 인간 배아 골격 발생의 세포 지형과 조절 원리를 규명하고자 하였다.

---

## Key Experiment Methods

**1. Multiome (snRNA-seq + snATAC-seq)**
- 5~11 PCW의 12명 기증자로부터 고관절, 슬관절, 견관절 및 두개부(전방·후방 calvaria, 두개저) 샘플 수집
- 10X Genomics Multiome 플랫폼으로 336,162개 핵 적격 droplet 포착
- MultiVI를 활용한 snRNA·snATAC 통합 분석 및 SCENIC+ 전사인자 조절 네트워크 추론

**2. 고해상도 공간 전사체 분석**
- 155-plex in situ sequencing(ISS)으로 배아 전·후지 슬관절 및 견관절(5.7~7.3 PCW) 고해상도 공간 지도화
- 10X Visium CytAssist로 9 PCW 관상봉합(coronal suture) 및 전두골 공간 전사체 분석
- ISS-Patcher(신규 도구): 저차원 ISS 데이터에 고차원 droplet 데이터의 세포 레이블을 KNN 기반으로 할당하는 방법론 개발

**3. OrganAxis 공간 궤적 분석**
- 봉합(suture)에서 골 전면(bone front)까지의 연속적 성숙 축을 정의하는 새로운 공간 주석 도구
- 전두골 전후축을 따라 suture zone → osteogenic front → osteogenic zone 순서로 구역화

**4. SNP2Cell 도구 개발**
- 세포 유형 특이적 유전자 조절 네트워크(GRN)와 다유전자 형질(GWAS)을 연결하는 도구
- 골관절염(OA) 및 두개골조기유합증(craniosynostosis) 관련 유전자 변이의 세포 유형 특이적 농축 분석

**5. 슈반세포-연골세포 계통 분석**
- RNA velocity 및 pseudotime trajectory 분석으로 슈반세포 전구체(SCP) → SOX9+ enSC → 연골세포로의 비정규적 분화 경로 예측
- RNA-ISH(RNAscope)를 통한 MPZ+SOX9+ 세포의 고관절 내 공동위치 확인

**6. Craniosynostosis in silico 모의실험**
- CellOracle을 이용한 전사인자 결손(knockout) 시뮬레이션으로 TWIST1, MSX2, LMX1B 결손 시 골화 영향 예측

---

## Results

**관절 형성의 Interzone 구역화**
InterzoneChon(GDF5+PITX2+) 집단에서 7개의 아집단(Early IZ, Articular IZ, Fibro IZ, GDF5hi IZ, Hypertrophic IZ1/2, Dermal IZ)이 확인되었다. 공간 분석 결과 interzone의 중심부에서 연골형성 전사인자가 농축되고, RUNX2 농축은 주변 연골 원기둥(cartilage scaffold)에서 관찰되어, 관절 형성 초기부터 골화 억제와 연골형성 간의 영역적 구획화(zonation)가 확립됨을 보여주었다. 관절강 형성(cavitation)은 이 구획화 이후 7~8 PCW에 발생한다.

**Fibroblast 계통 지도**
HIC1+Mes를 초기 섬유모세포 전구체로 규명하고, 이로부터 건세포(tenocyte), 윤활막 섬유모세포(synovial fibroblast), 진피 섬유모세포(dermal fibroblast), 근섬유모세포(myofibroblast)로 분화하는 경로를 RNA velocity로 예측하였다. 8 PCW 이후 FibroPRO2(PI16+DPT+)가 출현하여 성체 전조직 외막 관련 섬유모세포와 연결되었다.

**막내골화 및 연골내골화의 조절 네트워크**
두개부에서 CranialMes → SutureMes1/2 → HHIP+PreOB → 조골세포 → 골세포의 막내골화 궤적과, 사지에서 LimbMes → Preosteoblast → 조골세포의 연골내골화 궤적이 구축되었다. SCENIC+ 분석으로 봉합(suture) 영역에서 TWIST1, LMX1B, ALX4의 항골화(anti-osteogenic) 활성이 RUNX2와 HHIP의 발현을 간접적으로 억제하는 이중 음성 조절 네트워크가 확인되었다(Fig. 2h). RUNX2와 HHIP 유전자좌의 ATAC coverage와 예측된 enhancer-loop가 이 조절 구조를 뒷받침하였다.

**혈관신생과 골화의 연계**
봉합 전구세포(SutureMes)와 HHIP+PreOB가 VEGFA/VEGFB를 분비하고 tip cell이 NOTCH 신호를 통해 조골세포 분화를 촉진하는 공간적 신호전달 네트워크가 확인되었다. 내피세포의 FGF2와 RSPO3 신호가 조골세포 분화 및 골세포 광물화를 조력하는 것으로 예측되었다.

**연골세포 다양성 및 비정규적 기원**
12개의 연골세포 아집단이 지역 특이적 풍부도를 보였다(ArticularChon1/2, RestingChon, CyclingChon, DLK1+Chon, HyperChon, ChondroPro1/2, FacialChon, MandibularChon, PAX7+Chon, InterzoneChon). 특히 SOX9+ enSC(SOX9+ endoneurial Schwann cells) 집단이 MPZ, SOX10 등 고전적 슈반세포 마커와 COL2A1, ACAN 등 연골 마커를 동시 발현하며, RNA-ISH에서 고관절 연골 내에서 MPZ+SOX9+ 공동위치가 검증되었다. 이는 인간 배아에서 슈반세포가 연골세포의 비정규적 기원(non-canonical origin)이 될 수 있음을 시사한다.

**GWAS와 연결: 골관절염 및 두개골조기유합증**
슬관절 OA 신호는 연골형성 세포(ArticularChon)에서, 고관절 OA 신호는 조골 형성 세포(Preosteoblast)에서 각각 농축되었다. SNP2Cell을 통해 고관절 OA-관련 GRN에서 RUNX2, NFATC1/2/4, TEAD1 등이 핵심 조절자로 발굴되었다. 22개 두개골조기유합증 유전자 중 13개가 막내골화 전구세포(SutureMes, HHIP+PreOB)에서 농축되었으며, TWIST1, MSX2, LMX1B knockout in silico 시뮬레이션에서 SutureMes2의 강한 분화 속도 변화가 예측되었다.

---

## Perspective

본 연구는 인간 배아 골격 발생의 가장 포괄적인 멀티오믹 지도를 제공하며, 다음과 같은 혁신적 의의를 갖는다.

첫째, 336,162개 핵의 paired snRNA+snATAC 데이터를 기반으로 100개 이상의 미세 클러스터를 정의하고, 막내골화와 연골내골화 두 경로를 가로지르는 통합적 조절 네트워크를 제시하였다. HHIP+PreOB와 TWIST1-LMX1B의 항골화 네트워크는 개방 봉합 유지의 핵심 기전이다.

둘째, 슈반세포 계통이 인간 배아 연골의 비정규적 세포 기원이 될 수 있다는 최초의 증거를 RNA-ISS 및 RNA-ISH를 통해 제시하였다. 이는 발생생물학의 패러다임 확장에 기여한다.

셋째, ISS-Patcher, OrganAxis, SNP2Cell 등 새로운 전산 도구를 개발하여 공간 전사체와 GWAS 데이터를 통합함으로써 발생-질병 연결고리를 규명하는 프레임워크를 확립하였다. 특히 두개골조기유합증에 대한 in silico 유전자 결손 모의실험은 질환 발병 세포 상태의 예측을 가능하게 한다.

넷째, OA GWAS 신호가 배아 관절 특이적 GRN과 연결됨을 보여주어, 성인 질병의 배아 발생 기원 가설을 지지한다. 슬관절과 고관절 OA가 서로 다른 발생 세포 유형과 연관된다는 발견은 정밀 치료 표적 발굴에 중요하다.

향후 과제로는 SOX9+ enSC의 연골세포 기여도 정량을 위한 계통 추적 실험, 배아 골격의 신경 분포 연구, 그리고 in silico 질환 예측 결과의 기능적 검증이 필요하다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- ArrayExpress: E-MTAB-14385


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
