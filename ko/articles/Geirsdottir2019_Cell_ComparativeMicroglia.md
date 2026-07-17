---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p03.txt
raw_data:
  - "GEO: GSE134707"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Cross-Species Single-Cell Analysis Reveals Divergence of the Primate Microglia Program

## Citation (NLM)
Geirsdottir L, David E, Keren-Shaul H, Weiner A, Bohlen SC, Neuber J, Balic A, Giladi A, Sheban F, Dutertre CA, et al. Cross-Species Single-Cell Analysis Reveals Divergence of the Primate Microglia Program. Cell. 2019;179(7):1609-1622. doi:10.1016/j.cell.2019.11.010

**DOI:** [https://doi.org/10.1016/j.cell.2019.11.010](https://doi.org/10.1016/j.cell.2019.11.010)

---

## Background
미세아교세포(microglia)는 CNS 실질의 주요 상주 면역세포로, 발생 중 중배엽(yolk-sac) 전구세포로부터 유래하며 국소 자가재생으로 유지된다. 시냅스 가지치기 등 뇌 과정을 조절하고 신경퇴행성 질환 병리(예: Trem2-Tyrobp, ApoE 경로를 통한 알츠하이머병)의 핵심 인자이다. 신경퇴행 연구가 형질전환 동물 모델에 크게 의존함에도, 질병 양상은 인간과 동물 모델 간에 크게 다르다. 따라서 진화에 걸친 microglia 경로의 보존성 대 발산을 이해하는 것이 중요하다. 본 연구는 4억 5천만 년 이상의 진화를 아우르는 여러 종에서 microglia 형태와 전사 프로그램을 규명하며, 종간 세포 정제의 항체/에피토프 한계를 우회하기 위해 단일세포 RNA-seq을 사용한다.

---

## Key Experiment Methods
1. 18개 원연관 종에서 Iba1 면역조직화학과 3D-Imaris 형태계측 정량(제브라피시는 mPEG1-GFP, 닭은 CSF1R-mApple pan-myeloid 표지 사용).
2. 고품질 유전체를 가진 8개 종(인간, 마카크, 마모셋, 양, 마우스, 햄스터, 닭, 제브라피시)에서 FACS 분류한 CD45+(Ptprc) 뇌 면역세포의 단일세포(MARS-seq2.0) 및 bulk RNA-seq 결합; ~4,458개 QC 양성 microglia.
3. Metacell 알고리즘으로 견고한 세포 그룹 식별; 단일세포 데이터로 bulk RNA-seq을 deconvolution하여 오염 유전자 제거.
4. "metagene"/ortholog-conjecture 전략으로 종간 상동유전자 정의; quantile 정규화, k-means(17) 클러스터링, PCA 및 계층적 클러스터링.
5. 종내 microglia 이질성 평가를 위한 intra- vs inter-cluster 상관 및 세포간 상관; 랫트와 장수 blind mole rat로 확장.
6. microglia 발현과 인간 신경퇴행 질환 GWAS 감수성 유전자(AD, PD, HD, SCZ) 교차 비교; 마우스 조직 대식세포 compendium(Lavin 등, 2014)과 비교.

---

## Results
- 조사한 모든 동물에서 가지 돌기형(ramified) microglia 유사 형태와 표지를 가진 CNS 실질 세포가 발견되었으나 가지화 정도와 세포 크기는 상당히 다양; 밀도는 거머리 신경절에서 최고, axolotl에서 최저. microglia 밀도는 신경세포 밀도와 상관 없음.
- microglia는 모든 포유류에서 보존된 core 유전자 프로그램(clusters 1–10)을 발현하며, 제브라피시·닭은 outgroup을 형성. 핵심 조절자 Spi1, Irf8, Csf1r, Tgfbr2와 리소좀 가수분해효소(cathepsin류, Hexa), 항상성 유전자(C1qc, P2ry12, Tardbp, Vsir)가 고도로 보존됨.
- 다른 조직 대식세포 대비 microglia에 보존·특이적인 163개 유전자 식별(예: Adgrg1/Gpr56, Apbb1ip), 신경돌기·소뇌 발생 경로에 농축.
- 대부분의 포유류는 단일 우세 microglia 전사 상태를 보이나, 인간 microglia는 성별과 무관하게 6명 전원에서 여러 아형으로 조직된 유의한 이질성을 나타냄.
- 인간 microglia의 한 아집단(~20%)이 노화연관/염증 시그니처(CDKN1, CCL3, CCL4, CCL3L3, CCL4L2, TNF, IL1B)를 공발현하며 이는 젊은 성체 마우스에서는 관찰되지 않음.
- 종간 비교 결과 대사·면역 경로에서 발산; 인간 vs 설치류는 다수의 차등발현 유전자를, 인간 vs 마카크는 주로 대사 유전자(NADK, BCO2) 차이를 보임. 마우스를 제외한 포유류는 DNA 복구, 식균/apoptotic clearance, 보체, ferroptosis 음성조절에 농축.
- 신경퇴행 감수성 유전자(AD, PD)는 설치류 대비 영장류/인간에서 유의한 발현 발산을 보임.

---

## Perspective
본 연구는 보존·발산 microglia 경로에 대한 필수적 범진화 자원을 제공하며, 인간 microglia가 고유하게 이질적이고 주요 신경퇴행 연관 유전자가 설치류와 영장류 사이에서 발산함을 강조한다. 이는 신경퇴행 연구에서 설치류 모델의 한계와 향후 인간 microglia 기반 면역치료 개발에 중요한 함의를 가진다. 데이터는 인터랙티브 웹 도구로 접근 가능하다. 한계로는 종간 유전자 매칭에 ortholog conjecture 의존, 유전체 품질 제약으로 심층 전사체 분석이 8개 종에 국한, 그리고 발산 경로들이 기능적 검증을 기다리는 서술적(자원) 성격이 있다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE134707

**본문에 인용된 기타 accession (외부·재사용 데이터):**
- GEO: GSE63341


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
