---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
raw_data:
  - "GEO: GSE106292, GSE107592, GSE11849, GSE11850"
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Mapping molecular landmarks of human skeletal ontogeny and pluripotent stem cell-derived articular chondrocytes

## Citation (NLM)

Ferguson GB, Van Handel B, Bay M, Fiziev P, Org T, Lee S, Shkhyan R, Banks NW, Scheinberg M, Wu L, Saitta B, Elphingstone J, Larson AN, Riester SM, Pyle AD, Bernthal NM, Mikkola HK, Ernst J, van Wijnen AJ, Bonaguidi M, Evseenko D. Mapping molecular landmarks of human skeletal ontogeny and pluripotent stem cell-derived articular chondrocytes. _Nat Commun._ 2018 Sep 7;9(1):3634. doi: [10.1038/s41467-018-05573-y](https://doi.org/10.1038/s41467-018-05573-y).

---

## Background

조직 특이적 유전자 발현은 세포 정체성과 기능을 정의하지만, 인간 초기 발생에 대한 분자 수준 지식은 제한적이며, 이는 세포 기반 치료 적용을 저해한다. 마우스 모델에서 Sox9+ 골격전구세포는 연골, 골, 인대, 건으로 분화할 수 있음이 보고되었으나, 인간 근골격계 발생은 해부학적 기술과 핵심 조절 유전자 분석을 넘어서는 정보가 부족하다. 인간과 마우스는 성장판 발달, 조직 두께, 기계적 힘, 재생 잠재력에서 큰 차이가 있으며, 종간 전사체 및 조절 네트워크의 차이를 이해하는 것이 재생 의학 발전에 필수적이다. 본 연구는 17주 태아(fetal)의 5개 근골격계 세포 유형(연골세포, 조골세포, 근아세포, 건세포, 인대세포)을 전사체 분석하고, WGCNA를 통해 조직 특이적 유전자 모듈을 정의하였다. 또한 인간 연골 발생의 4개 단계(배아 5-6주, 태아 17주, 청소년, 성인)와 만능줄기세포(PSC) 유래 연골세포의 2개 단계(d14, d60)를 비교하여, 연골 지정과 성숙 과정의 전사체·후성유전체적 특징을 규명하고, 성인 관절 연골 내 기능적으로 다른 연골세포 아집단을 동정하고자 하였다.

---

## Key Experiment Methods

**1. 태아 근골격계 세포 분리 및 RNA 시퀀싱**

- 17 WPC 인간 태아 무릎 연골세포, 대퇴골 골아세포, 대퇴사두근 근아세포, 전/후방 십자인대 인대세포, 아킬레스건 건세포 분리
- 유세포 분류: LIN−(CD45−CD235a−CD31−) gating
- 연골세포: LIN−CD34−BMPR1B+, 골아세포: LIN−ALP+, 근아세포: LIN−CD146+CD56+, 인대/건세포: LIN−
- RNA-seq 수행

**2. WGCNA(Weighted Gene Co-expression Network Analysis)**

- 17 WPC 5개 조직 전사체로 조직 특이적 유전자 모듈 정의
- 인간 연골 발생 4개 단계 전사체로 발생 단계별 모듈 정의
- GO 분석, OPOSSUM 전사인자 결합 모티프 분석

**3. 인간-마우스 연골 발생 비교**

- E16.5 마우스 배아 및 2개월 성체 연골세포(LIN−ALP−BMPR1B+) 분리 및 RNA-seq
- 인간-마우스 종간 차등발현 분석, mean enrichment plot, volcano plot

**4. PSC 유래 연골세포 분석**

- PSC에서 중배엽 유도 후 14일(d14) 및 60일(d60) 연골세포 전사체 분석
- In vivo 연골세포 발생 단계와의 hierarchical clustering, Spearman 상관분석, GO 비교

**5. ITGA4 기반 연골세포 아집단 분석**

- 성인 돼지 관절 연골에서 ITGA4와 BMPR1B 발현에 따른 4개 집단 분류: ITGA4+BMPR1B+, ITGA4+BMPR1B−, ITGA4−BMPR1B+, ITGA4−BMPR1B−
- Western blotting: SOX9, GLI1, pSTAT3, RUNX2 단백질 정량
- RNA-seq 및 pairwise 차등발현 분석
- In vitro 연골/조골 분화 평가

**6. Chromatin state 분석(ChIP-Seq)**

- 태아 연골세포, 성인 관절 연골세포, PSC 유래 d14/d60 연골세포, H1-hESC에서 H3K27ac, H3K27me3, H3K4me1, H3K4me3 ChIP-Seq
- ChromHMM으로 12개 chromatin state 정의
- WGCNA 모듈 유전자의 promoter proximal region에서 chromatin state 분포 분석

**7. In vivo 이식 실험**

- 5-6 WPC 일차 전연골세포 및 PSC 유래 d14/d60 세포를 nude rat flank에 이식
- d60 PSC 유래 연골세포 응집체를 rat 원위 대퇴골 골연골 결손에 이식

---

## Results

**5개 태아 근골격계 조직의 전사체 프로파일링**

5000개 고발현 유전자의 hierarchical clustering에서 연골세포와 인대세포 간 넓은 유사성이 관찰되었으며, Spearman 상관분석에서도 관절 내 인대세포가 연골세포와 가장 높은 상관관계를 보였다. 이는 마우스 Sox9-CreERT2 lineage tracing에서 연골, 인대, 건이 Sox9+ 간엽전구세포에서 기원한다는 보고와 일치한다.

**WGCNA로 조직 특이적 유전자 모듈 정의**

17 WPC 5개 조직에서 13개 유전자 모듈이 정의되었다: brown(조골세포), yellow(연골세포), turquoise(근아세포) 등 각 조직에 대응하는 모듈이 확인되었다. SOX9, RUNX2, MYOD1 등 핵심 조절 인자가 각각 올바른 모듈에 할당됨이 검증되었다. 각 모듈에서 GO term 및 전사인자 결합 모티프가 동정되었다.

**인간 연골 발생의 전사체 역동성**

4개 인간 연골 발생 단계(배아 5-6주, 태아 17주, 청소년, 성인) 분석에서:
- **태아 vs 성인**: 태아 연골세포는 ECM organization, cell adhesion, collagen metabolism 유전자가 풍부하여 활발한 기질 침착을 보였다. 성인 연골세포는 metabolism, cell death, interferon signaling 유전자가 풍부하였다.
- **태아 vs 배아**: 태아 연골세포는 연골형성 특성이 풍부하였으나, 배아 전연골세포는 근육, 신경, 골 계통 관련 전사체가 남아 있어 전사체 가소성(transcriptional plasticity)이 높았다. 배아 유전자 프로모터에는 신경(SOX2) 및 연골(SOX5/9) SOX 가족과 심장(NKX2.5) 전사인자 모티프가 풍부하였다.
- **청소년 vs 성인**: 청소년 연골세포는 더 증식적이며, 성인은 후성유전 및 전사후 조절이 증가하였다.

**인간-마우스 연골 발생 비교**

Hierarchical clustering과 PCA에서 인간과 마우스 간 상당한 전사체 차이가 확인되었다. 핵심 연골형성 유전자(COL2A1, SOX9, ACAN 등)는 종간 보존도가 높았으나(Col10a1 제외), 마우스 연골세포는 WNT, AKT, MAPK 신호 및 세포주기 유전자가 풍부하여 증식이 더 활발함을 시사하였다. 인간 연골세포는 산화 대사 및 리보솜 생합성 유전자가 상향조절되었다. 이는 핵심 연골형성 프로그램은 보존되나, 신호전달 및 증식 차이가 인간과 마우스 관절 연골 재생 잠재력 차이의 기반이 될 수 있음을 시사한다.

**PSC 유래 연골세포의 in vitro 성숙**

d14와 d60 PSC 유래 연골세포 비교에서, d60 세포는 in vivo 유래 세포(fetal, adult)와 더 유사하였다. d60에서 풍부해진 유전자는 태아 vs 배아 및 성인 vs 태아 비교에서 풍부해진 유전자와 유의하게 중복되었다. d14 세포는 세포주기, 심혈관 발달, 신경 발달 등 넓은 발생 잠재력 관련 유전자가 풍부하였다. 이는 PSC 유래 연골세포의 성숙이 in vivo 연골 지정과 광범위하게 유사함을 보여준다.

**ITGA4가 성인 관절 연골의 독특한 연골세포 아집단을 정의**

배아 연골세포와 PSC d14 세포에서 풍부하고 태아/성인에서 감소하는 CAMs 중 ITGA4가 유일하게 배아 모듈에 포함되었다. IHC에서 ITGA4는 성인 경골 플랫폼 관절 연골의 표층에서 소수 세포에 발현되었으며, BMPR1B는 표층과 이행층에서 더 넓게 발현되었다.

성인 돼지 연골에서 ITGA4와 BMPR1B 발현에 따른 4개 집단을 분석한 결과:
- **ITGA4+BMPR1B+ 세포**: SOX9, GLI1, RUNX2, pSTAT3 단백질이 풍부하여 골연골 전구세포 마커가 enrichment됨. RNA-seq에서 이 집단 특이적 38개 유전자가 동정되었으며, GO 분석에서 세포주기, 유사분열, 증식 관련 term이 풍부하였다. In vitro에서 강력한 조골 분화 능력을 보였으며, 연골 분화도 가능하였다. 섬유아세포 유사 형태를 보였다.
- **ITGA4−BMPR1B+ 세포**: 주로 이행층에 위치, 가장 강력한 연골 기질 생성 능력을 보였다. 조골 분화 능력은 낮았다.
- **ITGA4+BMPR1B− 세포**: 표층 PRG4/lubricin 발현이 풍부하였다.
- **ITGA4−BMPR1B− 세포**: 심층에 위치, 최소한의 조골/연골 분화 능력으로 말단 분화 상태를 반영하였다.

**In vivo 및 in vitro 연골형성의 후성유전체 조절**

ChromHMM으로 12개 chromatin state를 정의한 결과, 태아 연골세포에서 연골 및 인대 모듈 유전자의 promoter proximal region은 active promoter(AP) 및 promoter proximal(PP) state가 풍부하였고, 조골/근아세포/건 모듈 유전자는 polycomb repressed(PR) state가 풍부하였다. SOX9, COL2A1, ACAN locus에서는 H3K4me3 및 H3K27ac 활성 마커가 풍부하였고 H3K27me3 억제 마커는 absent하였다. NANOG와 DPPA4는 PR state로 H3K27me3이 풍부하였다. H1-hESC에서 SOX9 locus는 bivalent signature를 가지다가 연골 지정으로 활성 상태로 해소되었다.

**In vivo 이식: 성숙도가 기능적 연골형성에 필요**

5-6 WPC 일차 전연골세포와 PSC d14 세포는 nude rat flank에서 연골 anlagen을 형성하지 못하였으나, 17 WPC 일차 연골세포와 PSC d60 세포는 연골 anlagen을 형성하였다. d60 PSC 유래 연골세포 응집체를 rat 골연골 결손에 이식한 결과, COL2+ 인간 연골이 robust하게 재생되었으며, 표층에 PRG4, ITGA4+, BMPR1B+ 세포가 정상 성인 관절 연골과 유사한 영역 구조로 배열되었다.

---

## Perspective

본 연구는 인간 근골격계 발생의 포괄적 전사체·후성유전체 자원을 최초로 제공하여, 연골 지정과 성숙 과정의 분자 랜드마크를 체계적으로 규명하였다. 배아 전연골세포가 근육, 신경, 골 계통 유전자를 점진적으로 침묵시키는 "progressive silencing" 과정을 거치며 연골 정체성을 확립함이 밝혀졌다. 인간과 마우스의 핵심 연골형성 유전자는 높게 보존되나, 증식 및 신호전달 차이가 재생 잠재력 차이의 기반이 될 수 있다. PSC 유래 연골세포의 전사체 가소성은 in vivo 연골 지정의 자연적 과정을 반영하며, d60 세포는 태아와 성인 사이의 발달 단계를 대표한다. ITGA4는 성인 관절 연골 내 기능적으로 다른 연골세포 아집단을 정의하는 핵심 마커로, ITGA4+BMPR1B+ 세포는 골연골 전구세포 특성과 증식 잠재력을 가져 연골 재생 및 조직 공학에 중요한 표적이 될 수 있다. Chromatin state 분석은 연골 유전자의 활성 히스톤 변형 축적과 타 계통 유전자의 억제 상태 획득이 연골 성숙과 동기화됨을 보여주어, 후성유전체 조절이 연골 세포 정체성 유지에 필수적임을 강조한다. 본 연구에서 생성된 유전자 모듈, chromatin state 맵, ITGA4 기반 연골세포 아집단 정보는 질환 모델링, 재생 의학, 조직 공학에 필수적인 비교 자원으로 활용될 수 있다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE106292, GSE107592, GSE11849, GSE11850


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
