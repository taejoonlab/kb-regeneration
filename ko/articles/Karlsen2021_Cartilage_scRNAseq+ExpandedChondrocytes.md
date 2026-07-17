---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
---

# Single-Cell RNA Sequencing of In Vitro Expanded Chondrocytes: MSC-Like Cells With No Evidence of Distinct Subpopulations

## Citation (NLM)
Karlsen TA, Sundaram AYM, Brinchmann JE. Single-cell RNA sequencing of in vitro expanded chondrocytes: MSC-like cells with no evidence of distinct subpopulations. Cartilage. 2021;13(Suppl 2):774S-784S. doi:10.1177/1947603519847746

**DOI:** [https://doi.org/10.1177/1947603519847746](https://doi.org/10.1177/1947603519847746)

---

## Background

자가 연골세포 이식술(autologous chondrocyte implantation, ACI)은 관절 연골의 국소 결손 치료에 사용되는 표준 세포치료법이다. ACI 시술 시 환자의 관절 연골에서 소량의 조직을 채취하여 연골세체를 분리, in vitro에서 증폭한 후 결손 부위에 이식한다. 그러나 in vitro 배양 과정에서 연골세포는 탈분화(dedifferentiation)되어 섬유연골(fibrocartilage) 특이적 ECM 분자(COL1, versican)를 합성하게 되며, 이는 정상 유리연골(hyaline cartilage)에 비해 기계적 특성이 떨어진다. 일부 연구는 인간 연골 내에 줄기세포 또는 전구세포가 존재한다고 제안하지만, 배양된 연골세포 집단이 균일한 세포 집단인지, 아니면 서로 다른 재생 잠재력을 가진 여러 하위 집단(subpopulation)으로 구성되어 있는지는 명확하지 않다. 본 연구는 단일세포 RNA 시퀀싱(scRNA-seq)을 사용하여 in vitro에서 증폭된 인간 관절 연골세포의 이질성을 조사하고자 하였다.

---

## Key Experiment Methods

- **세포 배양**: 골관절염(OA) 환자의 대퇴부 연골에서 분리한 연골세포, 14일간 배양(Passage 3). 1명의 공여자 사용.
- **단일세포 분리**: FACS로 96-well plate에 1 cell/well로 86개 단일세포 분리.
- **scRNA-seq**: Smart-Seq2 프로토콜, Illumina NextSeq500, paired-end 2×25 bp. Tophat v2.0.10 정렬, Cufflinks v2.2.1 정량. NCBI SRA: PRJNA522964.
- **분석**: PCA, t-SNE, Cross R² hierarchical clustering(Pearson correlation, average linkage), LIMMA 차등 발현 분석, MEV v4.9.0.
- **검증**: flow cytometry(CD44, CD90, CD73, CD105, CD34, CD45, CD19, HLA-DR 등), 단일세포 RT-qPCR(COL1A1, COL3A1, B2M).
- **다분화능 확인**: 동일 공여자의 polyclonal 연골세포 집단을 지방세포(Oil Red O) 및 골모세포(Alizarin Red S)로 분화 유도.

---

## Results

### 단일세포 전사체 분석
- PCA 분석: 86개 단일세포가 하나의 세포 집단으로 클러스터링. 별도의 하위 집단(subpopulation) 증거 없음.
- t-SNE 분석: 별도의 클러스터 관찰되지 않음.
- 계층적 클러스터링: 히트맵 상단의 덴드로그램은 클러스터를 표시하지만, 시각화에서 뚜렷한 하위 집단 패턴 미발견.
- 가장 분리된 두 클러스터 간 차등 발현 분석: 유의미한 DE 유전자 없음 → 체계적인 차이가 없음을 확인.

### 유전자 발현의 이질성
- GAPDH, B2M, ACTB 등 housekeeping 유전자도 세포 간 발현 변동 폭 큼: GAPDH 최고/최저 2.9배, B2M 4.9배, ACTB 30배 차이.
- 개별 유전자의 FPKM 값은 세포 간 상당한 변동성을 보이나, 이는 하위 집단의 존재보다는 연속적인 발현 차이로 설명 가능.

### 연골세포의 MSC 특성
- 배양된 연골세포의 대부분은 MSC 정의 마커(CD44, CD90, CD73, CD105)를 발현하고, 조혈 마커(CD34, CD45, CD19, HLA-DR)는不发현.
- 동일 공여자의 polyclonal 연골세포 집단은 지방세포 및 골모세포로 분화 가능 → International Society for Cellular Therapy(ISCT) 기준을 충족하는 MSC임을 입증.

---

## Perspective

- 본 연구는 in vitro에서 증폭된 인간 관절 연골세포가 별도의 하위 집단으로 나뉘지 않는 균일한 단일 세포 집단임을 단일세포 RNA 시퀀싱으로 처음으로 규명하였다.
- 개별 세포 간 유전자 발현의 상당한 변동성은 하위 집단의 존재보다는 세포 주기, 국소 환경, 또는 stochasic 발현 차이에 기인할 가능성이 크다.
- 배양된 연골세포는 ISCT 기준의 MSC 정의를 충족하므로, ACI에 사용되는 탈분화 연골세포는 사실상 MSC와 동등한 세포임을 시사한다.
- 연골세포의 MSC 특성은 ACI 후 재생 조직의 질이 제한적인 이유 중 하나일 수 있으며, 연골세포의 재분화(redifferentiation)를 유도하는 배양 조건 개발의 중요성을 강조한다.
- 한계점: 단일 공여자만 사용, 비교적 적은 수의 세포(86개) 분석. 향후 다양한 공여자와 더 많은 세포를 포함한 연구가 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
