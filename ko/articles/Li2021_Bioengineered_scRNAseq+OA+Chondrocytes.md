---
tags: [2026-06, Chondrocyte]
extract: 2026-06-08
log:
  - "2026-06-08 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Combining Bulk and Single-Cell RNA-Sequencing Data to Reveal Gene Expression Pattern of Chondrocytes in the Osteoarthritic Knee

## Citation (NLM)
Li X, Liao Z, Deng Z, Chen N, Zhao L. Combining bulk and single-cell RNA-sequencing data to reveal gene expression pattern of chondrocytes in the osteoarthritic knee. Bioengineered. 2021;12(1):997-1007. doi:10.1080/21655979.2021.1903207

**DOI:** [https://doi.org/10.1080/21655979.2021.1903207](https://doi.org/10.1080/21655979.2021.1903207)

---

## Background
골관절염(OA)은 연골 퇴행을 특징으로 하는 가장 흔한 관절 질환으로, 세계적으로 약 2억 4천만 명이患病되어 있다. Bulk RNA-seq은 조직 전체의 전사체 정보를 제공하지만 개별 세포 간 차이를 모호하게 하며, 단일세포 RNA-seq(scRNA-seq)은 개별 세포의 발현 프로파일을 제공하지만 깊은 전사체 정보를 얻기 어렵다. 슬관절 OA 연골세포에 대한 두 유형의 시퀀싱 데이터가 각각 존재하지만, 이를 통합적으로 분석하여 OA 병인의 분자 기전을 포괄적으로 이해하려는 시도는 부족하였다. 본 연구는 bulk RNA-seq과 scRNA-seq 데이터의 분석 결과를 통합하여 OA 연골세포의 유전자 발현 패턴을 규명하고, 주요 전사인자(TF) 및 긴 비암호화 RNA(lncRNA) 조절 네트워크를 발굴하고자 하였다.

## Key Experiment Methods
1. GEO 데이터베이스에서 bulk RNA-seq 데이터(GSE114007, 38개 시료: 정상 18, OA 20) 및 scRNA-seq 데이터(GSE104782, 10명 OA 환자, 1464개 연골세포) 수집
2. R package DESeq2를 이용한 bulk RNA-seq의 차별 발현 유전자(DEG) 분석 (adjusted p < 0.05, |fold change| > 2)
3. R package WGCNA를 이용한 OA와 가장 강한 상관관계를 가진 유전자 모듈 동정 (signed network, scale-free topology fit index 0.85)
4. R package Monocle 2를 이용한 scRNA-seq 가상시간(pseudotime) 분석 — 병리적 단계(S0-S4)에 따른 연골세포 동적 유전자 발현 변화 추적
5. DEG, WGCNA 모듈 유전자, pseudotime 연관 유전자의 교집합(intersection) 분석을 통한 핵심 유전자 선별
6. HumanTFDB v3.0 및 TRRUST v2 데이터베이스를 이용한 전사인자 및 주요 전사 조절자 동정
7. HGNC BioMart 및 LncTarD 데이터베이스를 이용한 lncRNA 및 표적 유전자 조관계 분석
8. clusterProfiler를 이용한 GO 및 KEGG 경로 농축 분석

## Results
1. Bulk RNA-seq 분석 결과 OA에서 1375개 상향조절 DEG, 1026개 하향조절 DEG가 확인됨 — 주요 상향 경로는 ECM, focal adhesion, CAMs; 하향 경로는 MAPK, FoxO, HIF-1, TNF 신호전달 경로
2. WGCNA에서 OA와 가장 강한 양의 상관관계를 보인 모듈(1240개 유전자)은 ECM 관련 경로에 농축되었고, 가장 강한 음의 상관관계 모듈(731개 유전자)은 FoxO 및 HIF-1 신호전달 경로에 농축됨
3. Pseudotime 분석 결과 병리 단계가 진행될수록 pseudotime 값이 증가하는 경향을 보였으며, 염증 유전자(CCL3, CXCL8, IL1B)는 초기에, ECM 유전자(COL1A1, COL1A2, PRG4)는 후기에 상향조절됨
4. 세 분석법의 교집합을 통해 271개의 핵심 유전자가 선별됨 (183개 상향, 88개 하향)
5. 14개의 전사인자(MAFB, HMGB3, GLI3, SOX11, NR1D1, HMGB2 등)가 동정되었으며, TWIST2, MYBL2, RELA, JUN, KLF4, PTTG1이 271개 유전자의 주요 전사 조절자로 확인됨
6. 8개의 lncRNA(FZD10-AS1, PART1, ISM1-AS1, SILC1, CYTOR, ILF3-DT, HG1, S6-AS1)가 동정됨
7. CYTOR가 miRNA-206을 sponging하여 NRP1을 양성 조절하는 ceRNA 기전이 OA에서도 존재할 가능성 제시 — NRP1은 혈관내피성장인자(VEGF) 및 semaphorin의 공동수용체로, 연골의 혈관신생 및 통증에 기여할 수 있음
8. PTTG1 → S100A4/LGALS1 축의 활성화가 OA 연골에서 염증 및 이화 신호전달을 촉진할 가능성 확인

## Perspective
본 연구는 bulk RNA-seq(DEG + WGCNA)과 scRNA-seq(pseudotime)의 통합 분석을 통해 OA 연골세포의 유전자 발현 패턴을 다차원적으로 규명한 첫 시도이다. 271개의 핵심 유전자, 14개 전사인자, 6개 주요 전사 조절자, 8개 lncRNA를 발굴하여 OA 병리의 분자 네트워크를 체계적으로 제시하였다. 특히 CYTOR-NRP1 축이 OA 연골의 혈관신생과 통증에 관여할 가능성과, PTTG1이 S100A4/LGALS1을 통해 염증 신호를 조절할 가능성은 새로운 치료 표적으로서 가치가 있다. HIF-1 신호전달 경로가 하향조절된 점은 연골세포의 저산소 적응 능력 감소가 OA 진행에 기여함을 시사한다. 한계점으로는 대조군과 OA군 간 연령 차이가 크고(36.6세 vs 66.2세), 순수 생정보학 분석에 기반하여 실험적 검증이 추가로 필요하다는 점이다. 향후 제안된 조절 네트워크와 경로에 대한 기능 검증 연구가 OA의 분자 기전 이해와 치료제 개발에 기여할 것이다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*
