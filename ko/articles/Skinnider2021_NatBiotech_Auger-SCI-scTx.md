---
tags: [2026-07]
extract: 2026-07-16
---

# Cell type prioritization in single-cell data

## Citation (NLM)
Skinnider MA, Squair JW, Kathe C, Anderson MA, Gautier M, Matson KJE, Milano M, Hutson TH, Barraud Q, Phillips AA, Foster LJ, La Manno G, Levine AJ, Courtine G. Cell type prioritization in single-cell data. Nat Biotechnol. 2021;39(1):30-34. doi:10.1038/s41587-020-0605-1

**DOI:** [https://doi.org/10.1038/s41587-020-0605-1](https://doi.org/10.1038/s41587-020-0605-1)

---

## Background

단일세포 기술은 건강한 조직의 지도화(atlasing)에서 질병·실험적 교란에 대한 세포 유형 특이적 반응 규명으로 발전해왔다. 이 전환은 세포 유형 *간* 차이의 목록화가 아니라, 세포 유형 *내부*의 미묘한 표현형 변화 해석을 요구한다. 기존 도구들은 개별 차등발현(differentially expressed, DE) 유전자/단백질 식별에 초점을 맞추는데, 이는 "고차원 단일세포 공간에서 어떤 세포 유형이 교란에 가장 반응적인가"라는 더 넓은 질문에는 부적합하다.

저자들은 생물학적 교란에 가장 반응적인 세포 유형의 우선순위를 매기는 기계학습 방법 Augur를 소개한다. 대표적 생물학 응용으로, 척수 손상(SCI) 후 보행을 회복시키는 것으로 알려진 표적 경막외 척수 자극(targeted epidural spinal stimulation, TESS)에 의해 동원되는 척수 뉴런 아형을 Augur로 규명한다. 이 치료가 관여하는 신경 회로는 그동안 밝혀지지 않았으며, 이를 위해 손상된 요수(lumbar spinal cord)의 단일핵 전사체 분석을 수행했다.

---

## Key Experiment Methods

1. **Augur 알고리즘**: 각 세포 유형별로 random forest 분류기를 학습시켜 단일세포 측정값으로부터 실험 조건(예: 처리 vs 대조)을 예측; 교차검증 ROC 곡선 하 면적(AUC)으로 분리도(separability)를 정량화. AUC로 세포 유형 순위 결정. 반복적 서브샘플링(기본값: 조건당 20세포의 50개 서브샘플)으로 세포 유형 존재비 불균형의 교란을 제거.
2. **검증**: 모의 scRNA-seq(Splatter), 22개 공개 scRNA-seq 데이터셋, 염색질 접근성(scATAC-seq), 이미징 전사체(STARmap, MERFISH)에서 검증; 6개 DE 기반 우선순위 방법(t-검정, Wilcoxon, 우도비, 로지스틱 회귀, MAST, 음이항)과 비교. LPS 용량-반응 및 FACS 정제 마이크로어레이/bulk RNA-seq 골드 스탠다드로 벤치마크.
3. **RNA velocity 모드**: 전사체 동역학에 Augur를 적용하여 급성 전사 반응을 겪는 세포 유형 우선순위 결정.
4. **SCI/TESS 실험**: 마우스에 심한 T8 타박상(contusion)으로 영구적 양측 다리 마비 유발. 세로토닌성(5HT) 및 D1 작용제와 함께 요수 TESS로 즉각적 보행 가능. 손상 6주 후 TESS로 30분 보행한 마우스(n=3) vs 마비 대조군(n=3)에서 18,514개 핵의 단일핵 RNA-seq 수행.
5. **회로 식별**: 6,035개 뉴런을 38개 뉴런 아형으로 하위 클러스터링; RNA velocity에 Augur 적용하여 급성 관여 아형 우선순위 결정. 즉시초기유전자(Fos) 발현, RNAscope in situ hybridization, Vsx2-Cre 마우스의 단일시냅스 순행성 바이러스 추적으로 검증.

---

## Results

- 서브샘플링은 AUC가 세포 수에 의존하는 현상을 제거한 반면, DE 기반 방법은 존재비가 높은 세포 유형으로 강하게 편향되었다(예: DE 방법은 존재비 때문에 알츠하이머병에서 oligodendrocyte를 가장 교란된 세포로 잘못 지목).
- Augur의 AUC는 모의 DE의 비율과 크기 모두에 단조 증가했고, 세포 유형 분포와 무관하게 정확도를 유지(r ≥ 0.95)한 반면, DE 방법은 불균형 분포에서 급격히 성능이 저하되었다.
- Augur는 골드 스탠다드 벤치마크와 일치했다: 4종의 LPS 용량-반응, 인터페론 FACS 골드 스탠다드(r=0.98), 두 알츠하이머 연구 간 재현성(neuron과 내피세포 우선순위화), 모달리티 간 일관성(scRNA-seq vs STARmap; scATAC-seq vs bulk RNA-seq).
- SCI/TESS 실험에서 단일핵 RNA-seq은 요수의 6개 주요 세포 유형과 38개 뉴런 아형을 분해했다.
- Augur(RNA velocity 적용)는 V2a 및 V1/V2b 인터뉴런 — 고유수용성 구심섬유 시냅스를 받고 좌우(V2a) 및 굴근-신근(V2b) 교대를 조절하는 것으로 알려진 아형 — 과 운동뉴런과 연관된 Spp1 양성 뉴런을 강력하게 우선순위화했다.
- V2a 및 V1/V2b 인터뉴런에서 즉시초기유전자(Fos) 유도가 RNAscope로 확인되어 TESS 유발 보행 중 이들의 활성화를 입증했고, 우선순위화되지 않은 인터뉴런은 Fos가 최소였다. 바이러스 추적은 우선순위화된 인터뉴런이 운동뉴런으로 조밀하게 투사함을 보였다.
- Augur는 계산 효율적이며(22개 데이터셋에 ~49.7분, 2.3 GB RAM), 수백만 세포로 확장 가능하고, 시퀀싱 깊이·배치 효과·하이퍼파라미터에 강건하며, 3' 및 full-length 프로토콜과 호환된다. R 패키지로 제공(github.com/neurorestore/Augur).

---

## Perspective

Augur는 DE 유전자 개수 계산 방식에 내재된 존재비 편향을 극복하고, 교란에 대한 분자적 반응성으로 세포 유형 순위를 매기는 원칙적이고 모달리티 비의존적인 방법을 제공한다. 손상된 척수에의 적용은 SCI 회복과 직접 관련된다: 마비 후 TESS 유발 보행을 매개하는 특정 인터뉴런 아형(V2a, V1/V2b)을 식별하여 단일세포 전사체 상태를 기능적 회로 동원과 연결했다. 명시된 한계는 세포 유형 수준의 추론이 세포 집단 내부의 연속적 반응 강도 구배를 집약한다는 점이다. Augur는 개체 수준 표현형의 기저 세포 유형을 정확히 지목함으로써 하류 인과 실험(예: Cre 계통 또는 FACS gate 선택)을 안내할 수 있으며, SCI 맥락에서는 신경자극 기반 회복의 치료 표적 정의에 기여할 수 있다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
