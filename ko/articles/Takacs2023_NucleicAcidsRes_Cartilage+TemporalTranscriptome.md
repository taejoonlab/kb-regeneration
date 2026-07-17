---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
raw_data:
  - "SRA: PRJNA817177, PRJNA938813"
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# The temporal transcriptomic signature of cartilage formation

## Citation (NLM)
Takács R, Vágó J, Póliska S, Pushparaj PN, Ducza L, Kovács P, Jin EJ, Barrett-Jolley R, Zákány R, Matta C. The temporal transcriptomic signature of cartilage formation. Nucleic Acids Res. 2023;51(8):3590-3617. doi:10.1093/nar/gkad210

**DOI:** [https://doi.org/10.1093/nar/gkad210](https://doi.org/10.1093/nar/gkad210)

---

## Background

연골형성(chondrogenesis)은 연골 전구세포가 독특한 구조적·기능적 특성을 가진 조직을 생성하는 다단계 과정이다. 연골 재생을 위한 여러 접근법이 이식된 전구세포의 분화에 의존하지만, in vitro 연골형성 과정의 시간적 전사체 지형(temporal transcriptomic landscape)은 다양한 모델에서 보고된 바 없다. 연골 세포외기질(ECM)의 주요 구성 요소인 콜라겐은 조직의 인장 강도와 전단 강도를 제공하며, 초자연골 ECM의 90% 이상을 제2형 콜라겐이 차지한다. 그러나 연골형성 과정에서 분화하는 연골세포에 의해 합성되는 다양한 콜라겐 유형에 대해서는 알려진 바가 적다. 중간엽 줄기세포(MSC)는 연골 조직공학에 유망한 세포 공급원이지만, MSC 유래 연골세포의 표현형이 불안정하고 비대형(hypertrophic) 표현형으로 진행되는 경향이 있어 한계가 있다. 배아 사지 유래 간엽 전구세포(LMP)를 사용한 계(chicken) micromass 모델은 초자연골의 연골형성을 더 일관되게 재현한다. 본 연구는 LMP 기반 micromass 배양에서 연골형성 과정의 시간적 전사체 프로파일을 RNA-seq으로 포괄적으로 분석하고, 새로운 연골형성 관련 전사인자와 콜라겐 유형을 발굴하고자 하였다.

---

## Key Experiment Methods

- **Micromass 배양**: 계(Hamburger-Hamilton stage 22-24) 배아 사지에서 LMP 분리, 1.5×10⁷ cells/ml 고밀도 배양. 8개 시점(day 0, 1, 2, 3, 4, 6, 10, 15)에서 샘플링. 성체 계 슬관절 연골세포도 비교 분석.
- **ECM 분석**: Alcian blue, Safranin-O, DMMB 염색으로 연골 기질 생성 평가. Collagen type I/II 면역조직화학 (DAB 발색).
- **RNA-seq**: Illumina 플랫폼, 계 참조 유전체 GRCg6a 정렬. Benjamini-Hochberg adjusted P<0.05, LFC ±2.0 기준 DEG 선정.
- **생물정보학 분석**: PCA, UMAP 차원 축소, Monocle 3 pseudotime 분석, GO enrichment, IPA network 분석, Cytoscape + STRING plugin 단백질 상호작용 네트워크.
- **유전자 발현 검증**: RT-qPCR (RPS7 참조 유전자로 정규화).
- **일시적 유전자 침묵(siRNA)**: ATOH8 및 EBF1 표적 siRNA, nucleofector 전기천공법으로 LMP에 도입. Day 6에서 DMMB 염색 및 MTT assay로 연골형성 평가. RT-qPCR로 골/연골 마커 유전자 발현 분석.

---

## Results

### 연골형성 과정의 글로벌 전사체 변화
- PCA: 샘플이 배양 시간에 따라 점진적으로 분리됨. PC1이 분산의 52.46% 설명. Day 10까지 미분화→분화 방향으로 이동, day 15는 역행.
- 성체 연골세포는 micromass와 별도 클러스터링 → 유사하지만 구별되는 전사체.
- Monocle 3 pseudotime 분석: 약 day 6부터 발달적 포화(developmental saturation) 발생.
- 계층적 클러스터링: 초기(days 0-2), 중기(days 3-6), 후기(days 10-15) 및 성체 연골세포로 구분.

### 시기별 DEG 프로파일
- 총 3,470개 DEG 확인. 초기 단계(days 0→1): 590개 DEG (458 상향, 132 하향).
- 분화 중기(days 3→4): 단 14개 DEG로 가장 적음 → 전사체 안정화.
- 후기(days 10→15): 408개 DEG (84 상향, 324 하향) → 대부분 하향 조절.
- 연골발생 관련 유전자(GO:0051216) 비율이 day 10까지 증가 후 감소.
- 주요 DEG: GDF5, MATN1, COMP, SPP1, MMP13, COL10A1 등 연골발생 관련 유전자 다수 포함.

### 주요 콜라겐 유전자 발현 동역학
- COL2A1, COL9A1, COL11A1: 분화 초기부터 발현 증가 → day 10까지 유지.
- COL1A1, COL1A2: 초기에 높은 발현 → 분화 진행에 따라 감소 (섬유아세포→연골세포 전환 반영).
- 기타 콜라겐 유형(COL14A1 등) 발현 동역학 최초 보고.
- Collagen type II 단백질: day 4부터 ECM 내 축적 증가; type I은 초기 높았다가 감소.

### 새로운 연골형성 관련 전사인자 발굴
- 차세대 시퀀싱 데이터 분석으로 ATOH8 (atonal homolog 8) 및 EBF1 (early B-cell factor 1) 동정.
- **ATOH8 siRNA**: 연골 ECM 생성 감소 (DMMB 염색 ↓), MTT viability 감소. Col2a1, Acan, Sox9 발현 하향 조절.
- **EBF1 siRNA**: 유사하게 연골형성 억제. 연골 마커 유전자 발현 감소.

### 단백질 상호작용 네트워크
- Day 0: 가장 많은 상호작용 (6,099 interactions) → 분화 초기 복잡한 네트워크.
- 분화 진행 중 상호작용 감소 → 성숙 micromass/day 15에서 다시 증가.
- 중심 허브 유전자: 샤페론(CCT2, HSP90AA1), 리보솜 단백질(RPLP0, RPS27A), 해당 효소(GAPDH) 등.

---

## Perspective

- 본 연구는 계 LMP 기반 micromass 배양에서 연골형성의 8개 시점에 걸친 최초의 포괄적 시간적 전사체 지도를 제공한다.
- 연골형성 과정이 초기 활발한 유전자 발현 변화 → 중기 안정화 → 후기 하향 조절의 3단계로 진행됨을 규명하였다.
- ATOH8과 EBF1을 새로운 연골형성 조절 전사인자로 처음 보고하였으며, 이들의 일시적 침묵이 연골형성을 손상시킴을 확인하였다.
- 성체 연골세포와 micromass 유래 연골세포의 전사체 차이는 in vitro 모델의 한계를 보여주며, 특히 day 15 이후의 역행 현상은 추가 최적화가 필요함을 시사한다.
- 본 데이터셋은 연골 조직공학 및 재생의학 연구를 위한 분자 플랫폼으로 활용될 수 있다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- SRA: PRJNA817177, PRJNA938813

**본문에 인용된 기타 accession (외부·재사용 데이터):**
- GEO: GSE109503


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
