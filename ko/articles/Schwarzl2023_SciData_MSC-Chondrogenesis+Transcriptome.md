---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
---

# Transcriptional profiling of early differentiation of primary human mesenchymal stem cells into chondrocytes

## Citation (NLM)
Schwarzl T, Keogh A, Shaw G, Krstic A, Clayton E, Higgins DG, Kolch W, Barry F. Transcriptional profiling of early differentiation of primary human mesenchymal stem cells into chondrocytes. Sci Data. 2023;10:758. doi:10.1038/s41597-023-02686-y

**DOI:** [https://doi.org/10.1038/s41597-023-02686-y](https://doi.org/10.1038/s41597-023-02686-y)

---

## Background

관절 연골은 재생 능력이 매우 제한적인 조직으로, 외상이나 퇴행성 질환으로 인한 손상 시 효과적인 재생 치료가 필요하다. 중간엽 줄기세포(MSC)는 연골 재생을 위한 유망한 세포 공급원으로, MSC의 연골형성 분화(chondrogenesis)를 이해하는 것은 치료 효능 향상에 중요하다. 특히 분화 신호에 대한 조기 반응(early response)과 세포 운명 결정(commitment) 단계는 치료적 개입을 통해 분화 효율을 높일 수 있는 핵심 시점이다. 그러나 MSC의 초기 연골형성 분화 단계(15분-16시간)의 전사체 변화는 체계적으로 연구되지 않았다. 본 연구는 인간 골수 유래 MSC 클론을 이용하여 연골형성 분화 유도 후 초기 시간대의 전사체 프로파일링을 최초로 수행하였다.

---

## Key Experiment Methods

- **MSC 클론 분리**: 인간 골수 흡인물(건강한 23세 남성)에서 limiting dilution으로 단일 콜로니 분리. 21개 클론 중 3계통 분화능(tri-lineage) 보유한 1F3 클론 선별. 표면 마커(CD73+/CD90+/CD105+, CD45−/CD34−/CD19−/CD14−/CD3−/HLA-DR−) 확인.
- **연골형성 분화**: Pellet 배양법. TGF-β3(10 ng/ml) 함유 배지. 시간점: monolayer, 3D pellet(0 h), 15분, 30분, 1시간, 2시간, 4시간, 8시간, 16시간, 그리고 21일(완전 분화 연골세포).
- **RNA-seq**: Illumina GAIIx, 35 nt single-read, 3회 기술적 반복. STAR 정렬, featureCounts 정량. 총 30개 샘플(3 반복 × 10 조건).
- **분석**: PCA, 계층적 클러스터링, t-SNE, DESeq2 차등 발현, edgeR, Mfuzz 시계열 클러스터링, Ingenuity Pathway Analysis, Cluster Profiler. BioStudies: E-MTAB-10476.

---

## Results

### MSC 클론 검증
- 21개 클론 중 11개가 3계통 분화능 보유.
- 선별된 1F3 클론은 3계통 분화능(연골, 지방, 골) 완전 보유 및 MSC 표면 마커 발현 확인.

### 시퀀싱 품질
- 중간 라이브러리 크기 21.52M reads.
- 3회 기술적 반복 간 높은 재현성(PCA, t-SNE, 계층적 클러스터링으로 확인).

### 전사체 분석
- 초기 시간대(15분~16시간)의 유전자 발현 변화를 최초로 상세히 프로파일링.
- 분화 초기 단계에서 TGF-β 신호, 세포 부착, ECM 재구성 관련 유전자들이 빠르게 변화.
- 21일 분화 연골세포는 초기 시간대와 뚜렷이 다른 전사체 프로파일.

### 데이터 활용
- 시간 경과 클러스터링, 기능 주석, upstream regulator 예측 워크플로우를 Zenodo에 공개.
- 연구자들이 GRN(gene regulatory network) 분석 및 추가 데이터 마이닝 가능.

---

## Perspective

- 본 연구는 MSC 연골형성 분화의 가장 초기 단계(15분~16시간)의 전사체 변화를 최초로 규명한 데이터셋을 제공한다.
- 이 데이터는 MSC가 분화 신호(TGF-β3)에 노출된 후 수분 이내에 시작되는 유전자 발현 변화를 포착하여, 연골형성 분화의 commitment 메커니즘 이해에 중요한 기반을 제공한다.
- 클론 MSC를 사용함으로써 이질성을 최소화하여 조기 분화 신호의 해석을 용이하게 하였다.
- 공개된 데이터와 분석 워크플로우는 MSC 연골형성 분화 연구자들에게 귀중한 리소스가 될 것이다.
- 한계점: 단일 공여자, 단일 클론 사용으로 일반화에 주의 필요. 기술적 반복(technical replicate)으로 생물학적 다양성 반영 제한.
- 추후 연구: 다양한 공여자 및 MSC 클론을 포함한 검증, 단일세포 수준에서의 초기 분화 반응 분석.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
