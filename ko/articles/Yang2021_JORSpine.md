---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
---

# Single-cell RNA Seq reveals cellular landscape-specific characteristics and potential etiologies for adolescent idiopathic scoliosis

## Citation (NLM)

Yang Y, Yang M, Shi D, et al. Single-cell RNA Seq reveals cellular landscape-specific characteristics and potential etiologies for adolescent idiopathic scoliosis. JOR Spine. 2021;4(4):e1184. doi:10.1002/jsp2.1184

**DOI:** [https://doi.org/10.1002/jsp2.1184](https://doi.org/10.1002/jsp2.1184)

---

## Background

청소년기 특발성 척추측만증(adolescent idiopathic scoliosis, AIS)은 구조적 측만, 축 회전, 시상면 변형을 특징으로 하는 3차원 척추 변형 질환으로, 청소년의 0.47~5.2%에서 발생한다. 진행 시 삶의 질 저하와 사회경제적 부담을 초래하나, 그 병인은 유전·환경·호르몬·대사·생화학·신경학적 요인 등 다양하게 제시되었을 뿐 명확히 규명되지 않았다. 비대칭적 척추 성장과 낮은 골밀도(low bone density)가 주요 병인 인자로 주목받아 왔으나, 기존 벌크 조직 분석은 세포 이질성을 반영하지 못하는 한계가 있었다. 저자들은 고해상도 단일세포 RNA 시퀀싱(scRNA-seq)을 통해 AIS 환자와 정상 대조군 척추 해면골의 세포 지형을 비교하고, 골 발달 관련 세포 계통의 분화 장애를 규명하고자 하였다.

---

## Key Experiment Methods

**1. 임상 검체 및 단일세포 분리**
- AIS 환자 3명(여성, 12~15세) 및 비AIS 척추 외상 환자 3명(여성, 10~14세)의 척추 해면골(cancellous bone) 조직 수집
- 경골 조직용 해리 프로토콜을 변형한 효소 소화법(DNase II + Collagenase IV)으로 해면골 단일세포 현탁액 제조(본 연구에서 최초 개발)
- Calcein-AM/Draq7 염색으로 65~80% 생존율 확인

**2. scRNA-seq 라이브러리 제작 및 시퀀싱**
- BD Rhapsody 시스템 사용, 200,000개 이상의 마이크로웰 기반 단일세포 포획
- HiSeq X로 150 bp paired-end 시퀀싱
- AIS 환자: 2,226세포, 대조군: 2,241세포 확보(평균 947~767 유전자/세포 검출)

**3. 생정보학 분석**
- Seurat v2.0.1: t-SNE 차원축소, 무감독 클러스터링(11개 주성분, resolution 1.5)
- Monocle 2: 세포 분화 궤적(pseudotime trajectory) 재구성
- GO/KEGG enrichment: Fisher 정확검정 + FDR(BH method) 보정
- Cell-cell communication: ligand-receptor 쌍 데이터베이스 기반 네트워크 구축

---

## Results

**11개 세포 집단 동정**
t-SNE 분석으로 총 11개 주요 세포 집단이 확인되었다: B림프구(BLC), T림프구(TLC), 중간엽줄기세포(MSC), 연골전구세포(CPC), 중성구(NP), 조골세포(OB), 단핵구(MC), 연골세포(CC), 수지상세포(DC), 파골세포(OC), 조혈줄기세포(HSC). GO 분석으로 각 집단의 기능적 정체성이 검증되었다.

**면역세포 증가**
AIS 환자에서 전체 면역세포 수가 대조군 대비 유의하게 증가하여, 면역 미세환경이 AIS 병인에 관여할 가능성이 시사되었다.

**조골세포 계통 분화 장애**
MSC는 3개 아형(MSC-LOXL2, MSC-IGFBP5, MSC-GJA1)으로 분류되었다. MSC-LOXL2(423세포)와 MSC-GJA1(182세포)은 대조군에서만 검출되었고, MSC-IGFBP5는 AIS에서만 발견되었으며(181/220세포, 82%), AIS MSC 집단의 대부분을 차지하였다. Pseudotime 분석 결과 대조군에서는 MSC-LOXL2 → MSC-GJA1 → OB-DPT/OB-OLFML2B 순서로 정상적인 조골세포 분화가 진행되었으나, AIS에서는 MSC-IGFBP5가 조골세포로 분화하지 못하고 세포 증식 억제 및 세포사 증가가 관찰되었다. 결과적으로 AIS 조골세포 수(OB-DPT: 2, OB-OLFML2B: 9)가 대조군(각각 303, 259)에 비해 현저히 적어, 낮은 골밀도의 세포적 근거가 제시되었다.

**연골세포 계통 분화 장애**
CPC는 CPC-SLC2A1과 CPC-PCNA 두 아형으로 나뉘었다. CPC-PCNA(PCNA, CCNE1 등 비정상 세포주기·DNA 손상 관련 유전자 고발현)는 AIS 환자에서만 특이적으로 관찰되었다(42세포). CPC-SLC2A1은 AIS에서 크게 증가하였다(350 vs 114). 두 연골세포 아형(CC-MPP13, CC-MT1G)은 모두 AIS에서는 검출되지 않았고 대조군에서만 존재하여(각각 254, 189세포), AIS에서 CPC가 연골세포로 분화하지 못하는 장애가 확인되었다. 이는 연골내골화(endochondral ossification) 이상을 통해 척추 성장 장애를 유발할 가능성을 시사한다.

**파골세포 계통**
AIS 단핵구(MC) 수는 증가(45 vs 8)하였으나, OC-BIRC3는 AIS에서 감소하였다. Pseudotime 분석에서 AIS MC는 주로 OC-CRISP3로 편향된 분화 양상을 보였다.

**면역세포-골발달 세포 간 상호작용**
MSC-IGFBP5는 LTβR 상호작용(LTβ-LTβR: B-IGHM, TNF-LTβR: T-GNLY)과 HLAE-NKG2A 면역관용 회피 신호를 통해 림프구 매개 염증 및 면역 감시 회피 기전이 확인되었다. CPC-PCNA에서는 IDE-CCL3, NECTIN1-CD96 등 면역관여 리간드-수용체 쌍이 농축되었다. 경로 분석에서 AIS MSC의 NF-κB 신호 상향조절과 TGF-β 신호 하향조절이 조골세포 분화 장애의 분자적 기전으로 확인되었다. CPC에서는 HIF-1α 신호 경로의 지속적 활성화가 해당과정-산화적 인산화 불균형을 통해 연골세포 분화 장애를 유발하는 것으로 추정되었다.

---

## Perspective

본 연구는 AIS 환자 척추 해면골의 단일세포 수준 세포 지형을 최초로 제시한 연구로서 다음과 같은 핵심 의의를 갖는다.

첫째, 경골 조직에 적합하지 않았던 기존 연조직 해리 프로토콜을 해면골에 맞게 변형·최적화하여, 경조직 단일세포 분석의 기술적 토대를 마련하였다. 이 방법은 향후 다양한 골 질환 연구에 활용될 수 있다.

둘째, AIS 특이적 MSC 아형(MSC-IGFBP5)과 CPC 아형(CPC-PCNA)을 발견하고, 이들이 각각 조골세포와 연골세포로 정상 분화하지 못하는 분화 장애를 단일세포 수준에서 증명하였다. 이는 AIS의 낮은 골밀도와 척추 비대칭 성장의 세포적·분자적 기전을 설명하는 핵심 발견이다.

셋째, 면역세포-골발달 세포 간의 세포 간 대화(cell-cell communication) 분석을 통해 림프구 매개 MSC 염증 반응, HIF-1α 경로 항상성 장애, NF-κB/TGF-β 경로 불균형 등 AIS의 잠재적 면역병인 면역병리 기전을 제시하였다. 이는 AIS를 단순한 골격 변형 질환이 아닌 면역-골격 상호작용 질환으로 재개념화할 가능성을 열어준다.

향후 과제로는 MSC-IGFBP5와 CPC-PCNA의 생체 내(in vivo) 존재 확인 및 계통 추적, 제안된 면역 병인 기전의 기능적 검증, 더 넓은 코호트를 통한 결과의 일반화, 그리고 이 연구가 제시한 분화 장애 표적에 기반한 새로운 치료 전략 개발이 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
