---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
raw_data:
  - "GEO: GSE114007"
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Identification of transcription factors responsible for dysregulated networks in human osteoarthritis cartilage by global gene expression analysis

## Citation (NLM)
Fisch KM, Gamini R, Alvarez-Garcia O, Akagi R, Saito M, Muramatsu Y, Sasho T, Koziol JA, Su AI, Lotz MK. Identification of transcription factors responsible for dysregulated networks in human osteoarthritis cartilage by global gene expression analysis. Osteoarthritis Cartilage. 2018;26(11):1531-1538. doi:10.1016/j.joca.2018.07.012

**DOI:** [https://doi.org/10.1016/j.joca.2018.07.012](https://doi.org/10.1016/j.joca.2018.07.012)

---

## Background

골관절염(osteoarthritis, OA)은 가장 흔한 관절 질환으로 노인에서 주요 장애 원인이지만, 질환 수정 치료제(disease-modifying therapy)는 아직 개발되지 않았다. OA 관절 내 모든 조직이 영향을 받지만, 관절 연골이 외상 및 노화 관련 변화에 가장 취약하다. 유전체 연관 연구(GWAS)는 OA 병리 이해에 기여했으나, 확인된 후보 유전자의 수가 적고 오즈비가 낮아 새로운 치료 표적 발굴에는 한계가 있었다. 전사체 분석(RNA-seq)은 새로운 기전과 치료 표적 발견의 잠재력을 제공한다. 본 연구는 정상 및 OA 인간 무릎 연골에 대한 RNA-seq 데이터를 통합 분석하여, OA에서 이상발현(differentially expressed, DE)된 유전자와 조절 네트워크를 규명하고, 특히 전사인자(transcription factor, TF)를 중심으로 한 새로운 치료 표적을 발굴하고자 하였다.

---

## Key Experiment Methods

- **임상 샘플**: 정상 무릎 연골 18예(사체, 여5/남13, 평균 38세), OA 연골 20예(무릎 치환술, 여12/남8, 평균 66세). BMI는 두 군 간 유의한 차이 없음.
- **RNA-seq**: Illumina HiSeq 2000, 100bp paired-end, 샘플당 19-24M reads. STAR aligner로 hg19 정렬.
- **발현 분석**: limma-voom으로 DE 유전자 분석 (adjusted P<0.05, |log2FC|>1). 배경 유전자: 12,463개(발현 검출된 Entrez ID 매핑 유전자).
- **GO enrichment 분석**: topGO (weight01 method, Fisher's exact test, BH correction). KEGG pathway overrepresentation (WebGestalt).
- **TF enrichment 분석**: GO:0003700(TF 활성) 기반 TF 선별. oPOSSUM single site analysis(Fisher's test)로 DE 유전자 프로모터(전사개시점 상류 1 kb) 내 JASPAR PWMs 과대표성 평가. BH adjusted P<0.1 유의.
- **네트워크 분석**: HumanBase 연골 특이적 유전자 상호작용 네트워크 사용. 14개 DE enriched TF를 seed로 하여 subnetwork 구축(최대 50 genes, 최소 상호작용 신뢰도 0.17). Cytoscape v3.6.0 시각화.
- **데이터 공개**: GEO accession GSE114007.

---

## Results

### OA 전사체 프로파일링
- 13,102개 전사체 발현 검출, 12,463개 Entrez ID 매핑.
- MDS plot에서 OA와 정상 샘플의 뚜렷한 분리 확인.
- 1,332개 DE 유전자 동정(630上调, 702下调; log2FC 범위 −4.8~6.8).

### 이상 발현 경로
- **상향 조절**: ECM 유전자(COL10A1, COL13A1, COL15A1, COL1A2), 단백질분해효소(MMP13, ADAMTS5), 보체 활성화 경로.
- **KEGG pathway 분석**으로 15개 유의하게 교란된 경로 확인:
  - ECM-receptor interaction
  - **PI3K-Akt 신호**: 연골 ECM 분해, 자가포식 조절 관련.
  - **FoxO 신호**: PI3K-Akt 음성 조절자; OA 및 노화 연골에서 감소.
  - **HIF-1 신호**: 저산소 반응 중앙 조절자; 연골세포 분화 및 생존 촉진.
  - **Circadian rhythm**: OA 연골에서 교란 확인, TGFβ 경로 조절.
- TGF-β/WNT, 염증, 혈관신생 경로는 유의한 교란 없음 (이전 보고와 차이).

### 전사인자 네트워크 분석
- 연골 발현 TF: 1,090개. 이 중 OA에서 DE TF: 93개(대부분 하향 조절).
- TF 결합 부위 분석: 44개 TF가 DE 유전자 프로모터에 결합 부위 과대표성.
- 93개 DE TF ∩ 44개 enriched TF → **14개 DE enriched TF** 선별:
  - **JUN, EGR1, JUND, FOSL2, MYC, KLF4, RELA, FOS** 등 8개 TF가 특히 중요.
  - 이 8개 TF는 OA에서 모두 **하향 조절**.
  - 이들 TF는 많은 수의 DE 유전자를 표적으로 하며, 그 자체도 OA에서 억제됨.

### 네트워크 기반 TF 우선순위 분석
- 14개 seed TF로 구축한 62개 유전자 subnetwork 분석.
- Degree (연결 수) 기준 상위 유전자: JUN, MYC, EGR1, FOS, HIF1A, RELA, JUND, FOSL2 등.
- Subnetwork 내 주요 경로: 암 관련 경로, FoxO, HIF-1 신호.

---

## Perspective

- 본 연구는 인간 OA 연골의 포괄적 전사체 프로파일을 구축하고, 네트워크 분석을 통해 OA 병인의 핵심 조절자로서 8개 하향 조절된 TF(JUN, EGR1, JUND, FOSL2, MYC, KLF4, RELA, FOS)로 구성된 새로운 조절 네트워크를 규명하였다.
- 이 TF 네트워크는 OA에서 이상 유전자 발현 패턴의 주요 매개자이며, 이들의 발현 회복이 OA 치료 전략이 될 수 있음을 시사한다.
- PI3K-Akt, FoxO, HIF-1, circadian rhythm 경로의 교란은 연골 항상성 유지에 필수적인 기전의 붕괴를 의미하며, OA 진행의 분자적 기반을 제공한다.
- 한계점: (1) 전장 유전체 프로모터 영역 분석으로 인핸서 및 기타 조절 영역 미포함, (2) 상대적으로 작은 샘플 크기, (3) TF와 표적 유전자의 인과관계는 추가 검증 필요.
- 향후 과제: (1) 확인된 TF의 OA 연골세포에서 기능적 검증, (2) TF 네트워크를 표적으로 하는 약물 개발, (3) 더 큰 코호트를 통한 검증 연구.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE114007


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
