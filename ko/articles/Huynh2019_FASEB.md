---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
---

# High-depth transcriptomic profiling reveals the temporal gene signature of human mesenchymal stem cells during chondrogenesis

## Citation (NLM)
Huynh NPT, Zhang B, Guilak F. High-depth transcriptomic profiling reveals the temporal gene signature of human mesenchymal stem cells during chondrogenesis. FASEB J. 2019;33(1):358-372. doi:10.1096/fj.201800534R

**DOI:** [https://doi.org/10.1096/fj.201800534R](https://doi.org/10.1096/fj.201800534R)

---

## Background

관절 연골은 손상이나 질병 후 자가 재생 능력이 거의 없어, 생체재료와 줄기세포를 결합한 조직공학적 접근이 활발히 연구되고 있다. 중간엽 줄기세포(MSC)는 골수 등에서 쉽게 얻을 수 있고 여러 골격 계통으로 분화 가능하여 연골 재생의 유망한 세포 공급원이다. MSC의 연골형성 분화(chondrogenesis)는 복잡한 분자 경로의 상호작용에 의해 조절되지만, 그 시간적 전사체 변화에 대한 포괄적 이해는 아직 부족하다. 기존 연구는 특정 유전자나 제한된 시간점에 초점을 맞추었으나, 본 연구는 고심도 RNA-seq을 통해 MSC 연골형성 과정의 6개 시간점에서 전사체 지도를 구축하고, 차등 발현 유전자, 유전자 온톨로지, 가중 유전자 상관관계 네트워크 분석(WGCNA)을 통해 연골형성의 핵심 유전자 시그니처와 조절 네트워크를 규명하고자 하였다.

---

## Key Experiment Methods

- **MSC 분리 및 배양**: 인간 골수 유래 MSC, 3명의 개별 공여자(donor). CD44+/CD73+/CD90+/CD105+/CD45− 표현형 확인.
- **연골형성 분화**: Pellet 배양법(2.5×10⁵ cells/pellet), TGF-β3 함유 연골형성 배지, 21일 배양. 0, 1, 3, 7, 14, 21일 총 6개 시간점에서 샘플링.
- **RNA-seq**: TruSeq Stranded Total RNA with Ribo-Zero Gold, HiSeq 2500, paired-end 100 bp, 샘플당 100M reads. 18개 라이브러리(3 donors × 6 time points). GEO: GSE109503.
- **분석**: DESeq 차등 발현 분석, DAVID GO enrichment, WGCNA(soft thresholding 7, height cutoff 0.25), K-means clustering, JASPAR TF 데이터베이스, Cytoscape 네트워크 시각화.
- **조직화학**: Safranin O/Fast Green(GAG), type I/II/X collagen 면역조직화학.
- **생화학**: PicoGreen(DNA), DMB assay(GAG).
- **웹 도구 개발**: Shiny R 패키지 기반 온라인 검색 가능 백과사전 구축.

---

## Results

### MSC 연골형성의 전사체 역학
- PCA: 시간 경과에 따른 점진적 전사체 변화 확인. d0→d1 초기 급격한 변화, 이후 d3→d21 점진적 변화.
- 6개 시간점 간 연속적 비교: d0→d1에서 5,788개, d1→d3에서 438개, d3→d7에서 1,018개, d7→d14에서 125개, d14→d21에서 55개의 DE 유전자 확인.
- 초기(0-1일)에 가장 많은 전사체 변화 발생, 후기로 갈수록 DE 유전자 수 감소.

### 주요 생물학적 경로의 시간적 변화
- **d0→d1 (초기)**: ECM 조직, 콜라겐 대사, 세포 부착, 골격계 발달, 세포 증식, 세포자멸사 경로 활성화.
- **d1→d3 (초기~중기)**: 세포자멸사 및 세포 운동성 경로 지속적 변화.
- **d3→d7 (중기)**: 콜라겐 대사, 연골 발달, 세포 분화, 단당류 대사 경로 활성화. TGF-β 신호 관련 유전자 상향.
- **d7→d14 (후기)**: 세포자멸사 억제, 세포 부착, I-kB kinase/NF-kB 신호 경로 활성화.
- **d14→d21 (말기)**: 가장 적은 변화. 연골 항상성 유지 관련 경로.

### WGCNA를 통한 유전자 모듈 식별
- 9개의 공동 발현(co-expression) 모듈 식별.
- **Turquoise 모듈**: 연골형성과 가장 높은 상관관계. ECM, 연골 발달, 콜라겐 관련 유전자 풍부. 주요 허브 유전자: COL2A1, COL11A1, COL9A1, ACAN, MATN3.
- **Brown 모듈**: 콜라겐 대사, 단백질 소화/흡수 관련.
- **Yellow 모듈**: 세포 부착, 혈관 발달 관련.
- **Blue 모듈**: 세포 주기, DNA 복제 관련 (초기 증식 단계).
- **TF 분석**: 각 모듈에서 핵심 전사인자 발굴 (예: turquoise 모듈의 SOX9, RUNX2 등).

### 비암호화 RNA 발굴
- 연골형성 중 발현이 변화하는 405개 lncRNA 및 170개 miRNA 동정.
- 이들 중 다수는 이전에 연골형성과 연관성이 보고되지 않은 새로운 후보.

### MSC 연골 vs 인간 관절 연골 전사체 비교
- MSC 유래 연골과 인간 관절 연골 간 전사체 유사성 및 차이점 분석.
- ECM 유전자 발현 패턴은 유사하나, specific marker에서 차이 확인.

### 온라인 백과사전 구축
- Shiny 기반 대화형 웹 도구: 유전자 및 시간별 발현 패턴 검색 가능. 데이터 마이닝 및 경로 분석을 위한 오픈 리소스.

---

## Perspective

- 본 연구는 MSC 연골형성의 6개 시간점에 걸친 고심도 RNA-seq 데이터를 통해 연골 분화의 시간적 전사체 지도를 최초로 포괄적으로 제시하였다.
- 연골형성 과정에서 초기(d0-1)에 가장 큰 전사체 변화가 발생하며, 이후 점진적으로 안정화됨을 규명하였다.
- WGCNA를 통해 연골형성 핵심 모듈(turquoise module)과 허브 유전자(COL2A1, COL9A1, ACAN 등)를 발굴하고, 이를 조절하는 TF 네트워크를 제시하였다.
- 새로운 lncRNA 및 miRNA 후보들의 연골형성 조절 가능성을 제시하여, 향후 기능 검증의 기반을 마련하였다.
- 구축된 온라인 백과사전은 MSC 연골형성 연구자들에게 귀중한 공개 자원이 될 것이다.
- 추후 연구 과제: (1) 발굴된 lncRNA/miRNA의 기능적 검증, (2) MSC 유래 연골과 자연 연골의 차이를 극복하기 위한 배양 조건 최적화, (3) 단일세포 수준에서의 이질성 분석.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
