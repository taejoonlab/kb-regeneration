---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
raw_data:
  - "GEO: GSE214987"
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Differential chondrogenic differentiation between iPSC derived from healthy and OA cartilage is associated with changes in epigenetic regulation and metabolic transcriptomic signatures

## Citation (NLM)
Khan NM, Diaz-Hernandez ME, Chihab S, Priyadarshani P, Bhattaram P, Mortensen LJ, Guzzo RM, Drissi H. Differential chondrogenic differentiation between iPSC derived from healthy and OA cartilage is associated with changes in epigenetic regulation and metabolic transcriptomic signatures. eLife. 2023;12:e83138. doi:10.7554/eLife.83138

**DOI:** [https://doi.org/10.7554/eLife.83138](https://doi.org/10.7554/eLife.83138)

---

## Background

유도만능줄기세포(iPSC)는 재생의학에서 유망한 세포 공급원이지만, iPSC는 공여 세포 유형에 따라 분화 능력에 차이를 보이는 것으로 알려져 있다(epigenetic memory). 그러나 건강한 연골과 골관절염(OA) 연골에서 유래한 iPSC의 연골형성 분화 능력 차이와 그 분자 기전은 밝혀지지 않았다. 본 연구는 건강 관절 연골세포(AC-iPSC)와 OA 연골세포(OA-iPSC)에서 유래한 iPSC의 연골형성 분화 잠재력을 비교하고, OA 질환 상태가 iPSC의 분화 능력에 미치는 영향을 규명하고자 하였다.

---

## Key Experiment Methods

- **iPSC 생성**: 건강 관절 연골 및 OA 관절 연골에서 분리한 연골세체에 viral reprogramming(Oct4, Sox2, Klf4, c-Myc)으로 iPSC 생성. AC-iPSC(클론 #7, #14, #15), OA-iPSC(클론 #2, #5, #8).
- **중간엽 줄기세포(MSC) 분화**: 직접 도말법(direct plating)으로 iPSC→iMSC 유도. 성상세포 형태, stemness gene 하향 조절 확인.
- **연골형성 분화**: iMSC를 micromass pellet 배양, TGF-β3 처리. 21일간 연골형성 유도.
- **전사체 분석(pans-transcriptome)**: AC-iMSC vs OA-iMSC 연골형성 분화 전후 RNA-seq. 차등 발현 유전자(DEG), GO enrichment, KEGG pathway 분석.
- **후성유전체 분석**: H3K4me3, H3K27ac, H3K27me3 등 히스톤 변형 및 DNA 메틸화 분석.
- **대사체 분석**: 세포 에너지 대사 경로(해당, TCA 회로, 산화적 인산화) 관련 유전자 발현 비교.
- **조직화학**: Safranin O(GAG), collagen type II 면역염색, ALP 염색(줄기세포 마커).

---

## Results

### iPSC 특성 확인
- AC-iPSC와 OA-iPSC 모두 ALP 양성, SOX2/OCT4/NANOG/KLF4 발현, TRA-1-60/SSEA-4 표면 항원 발현 → 정상적인 줄기세포 특성 확인.
- 두 iPSC 유형에서 줄기세포 마커 발현 수준 유사.

### iMSC 특성
- AC-iMSC와 OA-iMSC 모두 방추형 형태, SOX2/OCT4 하향 조절, MSC 마커(CD44, CD73, CD90, CD105) 발현. 두 그룹 간 형태 및 표현형 차이 없음.

### 연골형성 분화 능력 차이
- **AC-iPSC 유래 연골세포**: OA-iPSC 유래 연골세포에 비해 유의하게 높은 연골형성 능력.
  - AC-iMSC: COL2A1, ACAN, SOX9 등 연골 유전자 발현 증가.
  - Safranin O 염색 강도 및 GAG 함량: AC-iMSC > OA-iMSC.
- **OA-iPSC 유래 연골세포**: COL10A1(비대형 마커), MMP13, ADAMTS5 등 이형성 및 분해 관련 유전자 발현 증가 → OA 유사 표현형.

### Pan-transcriptome 분석
- AC-iMSC 유래 연골세포에서 증가된 경로: 에너지 대사(해당, TCA 회로, 산화적 인산화), 후성유전적 조절(히스톤 변형, DNA 메틸화), 콜라겐 형성.
- OA-iMSC 유래 연골세포에서 증가된 경로: ECM 분해, 염증 반응, 세포자멸사.
- 차등 발현 유전자 중 AC-iMSC에서 상향된 유전자들은 에너지 대사 및 후성유전학 관련 유전자들.

### 후성유전체 및 대사 기억
- OA 연골세포에서 관찰되는 후성유전적 변화(DNA 메틸화 패턴, 히스톤 변형)가 재프로그래밍 후에도 iMSC 단계에서 유지됨.
- OA-iMSC에서 미토콘드리아 기능 및 산화적 인산화 관련 유전자 발현 저하 → 대사 기억(metabolic memory) 존재.
- 이러한 후성유전적·대사적 기억이 OA-iPSC의 연골형성 분화 능력 저하의 원인임을 시사.

---

## Perspective

- 본 연구는 iPSC가 건강 상태 또는 OA 질환 상태의 공여 세포 기원에 따른 분자적·후성유전적 기억을 유지하며, 이는 iPSC의 연골형성 분화 능력에 직접적 영향을 미침을 처음으로 규명하였다.
- 건강 연골 유래 iPSC(AC-iPSC)가 OA 유래 iPSC(OA-iPSC)보다 현저히 높은 연골형성 잠재력을 가지며, 이는 에너지 대사 및 후성유전적 조절 경로의 차이와 연관된다.
- OA-iPSC는 OA 연골세포의 분자적 특성을 유지하여 OA 모델링에 유용하나, 연골 재생 치료에는 AC-iPSC가 더 적합함을 시사한다.
- 후성유전적 조절자 및 에너지 대사 경로를 표적으로 하는 전략이 iPSC의 연골형성 분화 능력 향상에 효과적일 수 있다.
- 향후 과제: (1) iPSC의 후성유전적 기억을 제거하는 방법 개발, (2) AC-iPSC의 연골 재생 치료 적용을 위한 대규모 전임상 연구, (3) OA-iPSC를 활용한 OA 질환 모델링 및 약물 스크리닝 플랫폼 구축.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE214987

**본문에 인용된 기타 accession (외부·재사용 데이터):**
- GEO: GSE114007


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
