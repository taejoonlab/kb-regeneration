---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Single cell transcriptomic analysis of human pluripotent stem cell chondrogenesis

## Citation

Wu CL, Dicks A, Steward N, Tang R, Katz DB, Choi YR, Guilak F. Single cell transcriptomic analysis of human pluripotent stem cell chondrogenesis. _Nat Commun._ 2021 Jan 14;12(1):362. doi: [10.1038/s41467-020-20598-y](https://doi.org/10.1038/s41467-020-20598-y). PMID: 33446649.

---

## Background

골관절염(OA)은 연골 퇴행을 특징으로 하는 질환으로, 연골의 자가재생 능력이 제한적이어서 줄기세포 기반 재생치료에 대한 관심이 높다. Human induced pluripotent stem cells(hiPSC)은 연골 재생 치료 및 OA 약물 발굴을 위한 in vitro 질환 모델링의 핵심 자원으로 주목받아왔다. 그러나 hiPSC를 연골세포로 일관되게 분화시키는 것은 여전히 어려운 과제로, 분화 과정에서 신경세포·멜라노사이트 등의 **비표적(off-target) 세포 집단**이 예측 불가능하게 생성되어 연골세포의 수율과 균질성을 저하시킨다는 문제가 있었다. 이러한 비표적 분화를 유도하는 유전자 조절 네트워크(GRN)와 비표적 세포가 chondrogenesis에 미치는 이종세포 신호전달(heterocellular signaling) 기전은 단일세포 수준에서 규명되지 않은 상태였다.

---

## Key Experiment Methods

**1. Stepwise hiPSC chondrogenic differentiation protocol**

- 3가지 독립 hiPSC 라인(STAN, ATCC, BJFF)을 사용
- 단계적 중배엽 분화: Activin A/CHIR99021/FGF-2(anterior primitive streak) → SB-505124/CHIR/FGF-2/dorsomorphin(paraxial mesoderm) → sclerotome → chondroprogenitor(Cp, BMP4 처리) 순서로 유도
- Cp 단계 이후 3D pellet culture에서 TGF-β3 처리로 최대 42일간 연골 분화 유도

**2. Bulk RNA sequencing (bulk RNA-seq)**

- 3개 hiPSC 라인의 중배엽 6단계 + 연골 분화 5단계(총 33개 샘플) 수집
- DESeq2를 이용한 단계별 차등발현유전자(DEG) 분석
- GAGE 패키지를 이용한 GO enrichment 분석

**3. Single cell RNA sequencing (scRNA-seq)**

- 10× Chromium 플랫폼 사용; hiPSC~d42까지 9개 시점(총 >19,000 세포 quality control 통과)
- Seurat(CCA alignment, unsupervised clustering, tSNE visualization), Monocle2(pseudotime trajectory) 분석
- WNT 억제(C59) 처리 pellet 대상 scRNA-seq 추가 수행(총 14,683 세포)

**4. Weighted Gene Co-expression Network Analysis (WGCNA)**

- d14 pellet scRNA-seq 데이터(2,148 cells, 3,784 genes)를 대상으로 GRN 재구성
- Cytoscape를 이용해 신경발생 및 멜라닌 생합성 서브네트워크 시각화; hub gene은 degree, weight, betweenness centrality(BC)로 결정

**5. WNT 억제 및 MITF 억제 실험**

- Pan-WNT inhibitor Wnt-C59(C59, 1 µM)와 MITF antagonist ML329(ML, 1 µM)를 단독 또는 병용으로 pellet culture에 처리
- Flow cytometry로 Cp 단계의 CD146+/CD166+/CD45− 전구세포 비율 측정

**6. 개별 WNT 리간드 처리 실험**

- WNT2B, WNT3A, WNT4, WNT5B, WNT7B(각 100 ng/mL)를 pellet culture에 처리
- RT-qPCR(SOX9, ACAN, COL2A1, COL1A1), GAG/DNA ratio, IHC로 연골 표현형 평가

**7. 이종세포 신호전달 모델(Heterocellular signaling model)**

- 2,557개 인간 ligand-receptor 쌍 데이터베이스를 활용, scRNA-seq 데이터에서 WNT-FZD 수용체 발현 세포 비율 정량
- Circlize R 패키지로 다세포 신호전달 방향 시각화

**8. In vivo 실험**

- 면역결핍 NSG 마우스의 피하 및 슬관절 골연골 결손 모델에 d14 pellet 이식(14~28일 후 조직학 평가)

---

## Results

**Off-target 세포 정체 규명** scRNA-seq 및 Monocle2 trajectory 분석을 통해 hiPSC 분화 과정에서 연골 계통 외에 신경세포(NES, OTX2, SOX2, WNT3A 발현) 및 MITF+ 멜라노사이트로의 계통 분기(lineage bifurcation)가 확인되었다. 특히 Cp 단계에서 neural crest cell 마커(PAX3, FOXD3)를 발현하는 세포군이 처음 출현하였으며, pellet 표면의 흑색 색소 침착은 멜라노사이트에 의한 것임이 IHC로 확인되었다.

**WGCNA를 통한 Hub gene 동정** d14 pellet의 WGCNA 분석에서 신경발생 GRN의 핵심 hub gene으로 **WNT4**, 멜라노사이트 발생 GRN의 hub gene으로 **WNT2B**가 동정되었다. WNT2B는 MITF 및 ETV1과 높은 연관성을 보였다.

**WNT 억제가 연골 분화 균질성 향상** Pellet culture 중 C59 처리 시 비표적 세포가 현저히 감소하고 Saf-O 염색 및 GAG/DNA ratio가 유의하게 증가하였다(p=0.00001, d28). Cp 단계에서 C59 처리 시에는 오히려 분화가 저해되었다. RNA-FISH에서 C59 처리 pellet은 WNT3A/WNT4 발현 감소와 COL2A1의 균질한 분포를 보였다.

**WNT 이종세포 신호전달 모델** WNT3A, WNT4, WNT7B는 주로 신경세포에서, WNT2B는 멜라노사이트(30%)에서 분비되는 반면, WNT 수용체 FZD2는 연골세포의 31.6%에서 발현되어, 비표적 세포가 분비한 WNT이 연골세포의 비대(hypertrophy)를 유도하는 이종세포 신호전달 경로가 존재함을 시사하였다. 개별 WNT 처리 실험에서 WNT3A는 GAG/DNA ratio를 유의하게 감소시켰고, 여러 WNT는 COL10A1 발현 및 COL1A1 염색을 증가시켰다.

**Chondrocyte 아집단 특성화** C59 처리 pellet의 scRNA-seq에서 4가지 보존된 연골세포 아집단이 확인되었다: (1) HMGB2/CDK1+ 증식 연골세포, (2) IGFBP5+ 초기 분화 연골세포, (3) LECT1/EPYC/FRZB+ 조기 성숙 연골세포(COL2A1/ACAN 최고 발현), (4) ISG15/IFI6/MX1+ 성숙-비대 연골세포. 성숙-비대 연골세포 서브셋에서는 IGFBP3가 STAT-1을 활성화하고 FOS 발현을 억제하는 기전이 연골세포 비대를 완화하는 것으로 시사되었다.

**In vivo 연골 재생 확인** NSG 마우스 슬관절 골연골 결손 모델에 d14 pellet 이식 시 28일째 proteoglycan 및 COL2A1이 풍부한 연골 기질로 결손 부위 수복이 확인되었다. 미이식 대조군에서는 섬유성 조직만 관찰되었다.

---

## Perspective

본 연구는 hiPSC chondrogenesis 과정의 세포 불균질성과 이를 유발하는 분자 기전을 단일세포 수준에서 체계적으로 규명한 최초의 종합적 연구로서 다음과 같은 의의를 갖는다.

첫째, WNT 신호 억제(C59)와 MITF 억제(ML329)를 병용하면 **세포 분류(cell sorting) 없이** 비표적 세포를 제거하고 균질한 연골세포를 고수율로 생산하는 향상된 분화 프로토콜이 가능함을 보였다. 이는 hiPSC 기반 연골 재생 치료의 임상적용 가능성을 높이는 실용적 접근이다.

둘째, 비표적 세포(신경세포, 멜라노사이트)가 단순한 '오염원'이 아니라 WNT 리간드를 분비함으로써 연골세포의 비대 분화를 능동적으로 촉진하는 이종세포 신호 원천임을 밝혔다. 이는 분화 효율 개선을 위해 세포 조성과 세포 간 신호를 함께 고려해야 함을 시사한다.

셋째, ISG15/IFI6/MX1+ 성숙-비대 연골세포 서브집단 및 LECT1/EPYC/FRZB+ 성숙 연골세포 등 새로운 연골세포 아집단의 존재와 기능적 의의가 제시되었으며, 이들의 완전한 기능적 특성 규명은 향후 연구 과제로 남아있다.

넷째, 이 연구에서 개발된 단일세포 전사체 기반 GRN 분석 접근법은 연골 외 다른 세포 분화 과정의 최적화에도 광범위하게 적용 가능한 로드맵을 제시한다.

향후 과제로는 CD146/CD166+ 전구세포의 다능성 여부 확인, C59 처리와 BMP/GDF 신호의 상호작용 기전 심층 연구, 그리고 장기 이식 후 연골 표현형 유지 및 안전성 검증이 필요하다.
---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
