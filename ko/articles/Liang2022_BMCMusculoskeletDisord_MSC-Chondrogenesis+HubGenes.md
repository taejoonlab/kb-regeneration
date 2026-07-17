---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Identifying the key genes regulating mesenchymal stem cells chondrogenic differentiation: an in vitro study

## Citation (NLM)
Liang T, Li P, Liang A, Zhu Y, Qiu X, Qiu J, Peng Y, Huang D, Gao W, Gao B. Identifying the key genes regulating mesenchymal stem cells chondrogenic differentiation: an in vitro study. BMC Musculoskelet Disord. 2022;23:985. doi:10.1186/s12891-022-05958-7

**DOI:** [https://doi.org/10.1186/s12891-022-05958-7](https://doi.org/10.1186/s12891-022-05958-7)

---

## Background

관절 연골은 제한된 재생 능력을 가지며, 연골 결손은 적절히 치료되지 않으면 골관절염(OA)으로 진행될 수 있다. 중간엽 줄기세포(MSC)는 연골 결손 치료를 위한 세포 기반 스캐폴드의 핵심 요소이며, MSC의 연골형성 분화(chondrogenesis)는 이 과정의 핵심이다. 그러나 MSC 연골형성을 조절하는 유전자 네트워크는 아직 완전히 이해되지 않았다. SOX9, BMP 신호 등 주요 조절 인자가 알려져 있으나, emerging evidence는 non-coding RNA, growth factor 등 다양한参与者가 복잡한 네트워크를 형성함을 시사한다. 본 연구는 고밀도 미세배양(micromass culture) 시스템을 사용하여 MSC 연골형성 과정의 시간별 유전자 발현 프로파일을 분석하고, 핵심 조절 유전자와 전사인자(transcription factor, TF)를 발굴하고자 하였다.

---

## Key Experiment Methods

- **MSC 분리 및 배양**: 건강한 남성 공여자(평균 37.6±4.2세, n=3)의 장골능(iliac crest) 골수 흡인물에서 MSC 분리. 3-5계대 사용.
- **연골형성 분화**: 고밀도 micromass 배양법. TGF-β3(10 μg/ml) 함유 연골형성 배지로 7, 14, 21일간 분화 유도. CHO군은 TKA 수술 환자의 연골세포.
- **RNA-seq**: Illumina HiSeq X Ten. DESeq으로 차등 발현 유전자(DEG) 분석. 기준: log2FC>1 또는 <-1, P<0.05.
- **PPI 네트워크 분석**: STRING 데이터베이스, Cytoscape(cytoHubba, MCODE)로 hub 유전자 발굴.
- **전사인자 분석**: DEG 중 TF 식별 및 상위 5개 TF 선별. RORA 기능 검증.

---

## Results

### DEG 분석
- **Day 7 vs D0**: 6,247개 DEG(3,333 상향, 2,914 하향). 가장 많은 변화가 초기에 발생.
- **Day 14 vs D0**: 85개 DEG로 급감.
- **Day 21 vs D0**: 유의미한 DEG 없음 → 후기 단계에서는 전사체 안정화.

### Day 7 상위 DEG
- COL9A3, COL10A1, CILP2, COL2A1, COL11A2, COL5A1, FN1 등 → 세포외기질(ECM) 조직화 관련.
- 상위 30개 DEG는 주로 ECM, 콜라겐, 연골 발달 관련 유전자.
- GO enrichment: ECM 조직, 콜라겐 삼중나선 중합, 단백질 가수분해, 연골 발달, 세포 부착 등.

### Day 14 상위 DEG
- CXCL8, TLR2, CCL20, MMP3 등 → 염증 반응 관련 유전자 풍부.
- 7일차 ECM 단계 → 14일차 염증/리모델링 단계로 전이됨을 시사.
- KEGG: IL-17 신호, TNF 신호, NOD样 수용체 신호, 류마티스 관절염 경로.

### PPI 네트워크 hub 유전자
- Day 7: 세포외기질 관련 네트워크.
- Day 14: CXCL8, TLR2, CCL20, MMP3 등 염증/면역 관련 hub 유전자.

### 전사인자 분석
- 상위 5개 TF: **LEF1, FOXO1, RORA, BHLHE41, SOX5**.
- 이 중 **RORA**를 초기 MSC 연골형성 촉진 인자로 기능 검증: RORA 발현 증가가 연골형성 유전자 발현 촉진.

---

## Perspective

- 본 연구는 MSC 연골형성의 시간적 전사체 변화를 체계적으로 분석하여, 초기(7일) ECM 형성 단계와 후기(14일) 염증/리모델링 단계로 구분되는 두 단계 분화 과정을 규명하였다.
- CXCL8, TLR2, CCL20, MMP3 등 염증 관련 유전자가 MSC 연골형성 후기에 중요한 역할을 할 가능성을 제시한다.
- RORA를 초기 연골형성 촉진 전사인자로 발굴하여, 연골 재생 치료를 위한 새로운 분자 표적을 제시하였다.
- 한계점: (1) 비교적 작은 샘플 크기, (2) RORA 외 다른 TF의 기능 검증 필요, (3) 생체 내(in vivo) 검증 부재.
- 향후 과제: 발굴된 TF(LEF1, FOXO1, BHLHE41, SOX5)의 기능 검증 및 연골 재생 치료 응용 가능성 탐색.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
