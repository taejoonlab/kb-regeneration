---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
raw_data:
  - "GEO: GSE137844"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Comparative gene expression profiling between optic nerve and spinal cord injury in Xenopus laevis reveals a core set of genes inherent in successful regeneration of vertebrate central nervous system axons

## Citation (NLM)
Belrose JL, Prasad A, Sammons MA, Gibbs KM, Szaro BG. Comparative gene expression profiling between optic nerve and spinal cord injury in Xenopus laevis reveals a core set of genes inherent in successful regeneration of vertebrate central nervous system axons. BMC Genomics. 2020;21(1):540. doi:10.1186/s12864-020-06954-8

**DOI:** [https://doi.org/10.1186/s12864-020-06954-8](https://doi.org/10.1186/s12864-020-06954-8)

---

## Background

중추신경계(CNS) 축삭 재생 능력은 계통학적으로(무양막류→양막류) 그리고 발생학적으로(배아→성체) 점차 제한된다. 아프리카발톱개구리(*Xenopus laevis*)는 독특한 전환점에 있다: 일부 CNS 뉴런(시신경 압좌 ONC 후 망막신경절세포)은 평생 축삭을 재생하지만, 다른 뉴런(척수 손상 SCI 후 후뇌 뉴런)은 올챙이가 개구리로 변태하면서 갑상선호르몬 급증에 의해 이 능력을 잃는다. 이로써 동일 개체 내에서 재생성 대 비재생성 CNS 손상 반응을 비교할 수 있다.

저자들은 이 특성을 활용하여 축삭이 절단된 CNS 뉴런 집단에 대한 새로운 3방향 RNA-seq 비교를 수행했다. 손상 부위 자체가 아니라 뉴런 세포체가 포함된 조직을 채취하여, 축삭 재생 프로그램을 일반적인 상처/외상 반응과 구별하고자 했다. 목표는 성공적 척추동물 CNS 축삭 재생과 실패를 구별하는 핵심 유전자 발현 프로그램을 규명하는 것이다.

---

## Key Experiment Methods

1. **3방향 조직 비교**: 두 축삭 재생 영역 — 변태 후 어린 개구리 눈(시신경 압좌 ONC 후)과 stage 53 올챙이 후뇌(척수 절단 SCI 후) — 대 하나의 비재생 영역 — 어린 개구리 후뇌(SCI 후).
2. **시점 선정**(기존 조직학·행동 연구 기반): 초기 외상기(3일), 재생성 축삭 성장 최고기(SCI 7일, ONC 11일), 후기 회복기(3주).
3. **RNA-seq 설계**: 표본당 명목 3천만 리드; 각 반복은 후뇌 5개 또는 눈 6개를 풀링; 조건/시점당 생물학적 반복 3개; 17개 조건에 걸쳐 총 51개 표본. 올챙이 SCI는 동일 연령 공동사육 무수술 대조군, ONC는 반대측 무수술 눈을 대조로 사용.
4. **정렬/주석화**: *X. laevis* 유전체(Xenbase v9.1)에 Bowtie2/TopHat, Mayball 유전자 모델 사용; S·L homeolog 분리 처리.
5. **차등발현 분석**: CuffDiff2/CummeRbund(FDR ≤ 0.05), DESeq2로 교차검증; FPKM 임계값 이하 유전자 필터링.
6. **DESR 유전자 규명**("Differentially Expressed in Successful Regeneration") — 두 재생 조직에서 차등발현되지만 비재생 조직에서는 그렇지 않은 유전자.
7. **하류 분석**: 주성분분석(PCA, 고유벡터), GO term(Metascape)과 유전자별 문헌 수기 큐레이션, KEGG 경로 농축, STRING 단백질-단백질 상호작용 네트워크.

---

## Results

- 두 재생 조직(올챙이 SCI 후뇌, 개구리 ONC 눈)은 차등발현 유전자 수가 재생 최고기(7/11일)에 정점을 이루는 유사한 시간 패턴을 공유한 반면, 비재생 개구리 SCI 후뇌는 더 이른 3일에 정점을 보였다.
- **324개의 DESR 유전자**가 규명되었다(253개 상향, 71개 하향). 이는 전체 손상 유도 차등발현 유전자의 약 2.7%로, 대부분의 차등발현은 조직 특이적이었다.
- PCA는 조직 기원이 발현 프로파일에 가장 큰 영향을 미침을 확인했고, SCI 후뇌 내에서는 재생 능력이 그다음으로 강한 요인이었다. 반대측 무수술 눈도 편측 ONC에 반응하여, 이를 축삭 재생 특이적 변화의 필터로 사용한 것이 정당화되었다.
- 다수의 DESR 유전자는 신경 손상과 기존 연관이 있었고(socs3, leptin, fabp7, mapk8/JNK1, sox11, sdcbp/syntenin, prph/peripherin), 비신경 조직 재생과도 연관되었다(도롱뇽 사지: tmsb4x, anxa5, crabp2; 포유류 간: top2A, C9, rrm2). 이는 깊고 계통학적으로 보존된 공통성을 보여준다.
- DESR 유전자는 **11개 기능 범주**로 분류되었으며, 염증반응/상처치유와 세포골격 유전자가 가장 많았다. 11개 범주 모두 최고기에 활성이었고, 세포 신호·세포내 수송·축삭 성장·지질/세포 대사는 최고기에만 국한되었다.
- **KEGG Adipocytokine 신호경로**(leptin을 대사·염증·유전자 조절 경로와 연결)가 핵심 네트워크 허브로 부상했으며, 상향조절된 DESR 유전자 lep, socs3, mapk8, acsbg2를 포함한다(특히 포유류에서 억제적으로 여겨지는 socs3가 여기서는 재생 촉진적이었다).
- 재생 대 비재생 사례에서 상반된 발현을 보인 33개 DESR 유전자 중 55%가 기능적으로 상호연결되었으며(STRING), 히스톤·후성유전 효소·Polycomb Repressive Complex 구성요소(jarid2 등) 등 염색질 접근성 조절자를 중심으로 하는 유전자 조절 네트워크를 이루었다.

---

## Perspective

이 연구는 성공적 CNS 축삭 재생과 다른 조직 재생 사례(사지·간·지느러미) 사이의 깊고 계통학적으로 보존된 공통성을 규명하며, CNS 수복의 분자 기초를 탐구하기 위한 큐레이션된 후보 유전자·네트워크 자원(adipocytokine 허브 및 염색질 접근성 조절 네트워크)을 제공한다. 특히 한 개체 내에서 재생성/비재생성 반응을 대조함으로써, 손상 유도 유전자 발현 변화 중 재생 촉진적인 것과 해로운 것을 구별하는 지침을 제시한다 — 이는 염증이 재생 촉진적이면서 동시에 손상을 주는 포유류 연구의 핵심 난제다.

한계로는 정제된 세포 유형이 아닌 복잡한 전체 조직(뉴런·아교·골수세포 혼합)을 사용한 점, 대부분 포유류 오솔로그에서 추론된 유전자 기능에 의존한 점, X. laevis에 주석화된 유전자로 분석을 제한한 점(신규 유전자·lncRNA·상세 homeolog/paralog 거동 제외), 규명된 네트워크가 상관관계적 성격이라는 점이 있다. 향후 개별 DESR 유전자·네트워크의 기능 검증, 세포 유형별 분석, 이러한 후보 구별의 포유류 CNS 손상으로의 확장이 제안된다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE137844


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
